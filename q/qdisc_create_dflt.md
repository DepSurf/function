# Function: <code>qdisc_create_dflt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81741950)
Location: net/sched/sch_generic.c:617
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff81741950-ffffffff817419c3: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817ae7f0)
Location: net/sched/sch_generic.c:639
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff817ae7f0-ffffffff817ae86d: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817dde70)
Location: net/sched/sch_generic.c:643
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff817dde70-ffffffff817ddeed: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817fd490)
Location: net/sched/sch_generic.c:643
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff817fd490-ffffffff817fd513: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8187b080)
Location: net/sched/sch_generic.c:672
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff8187b080-ffffffff8187b106: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818cd4f0)
Location: net/sched/sch_generic.c:882
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff818cd4f0-ffffffff818cd5a2: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818f86d0)
Location: net/sched/sch_generic.c:893
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff818f86d0-ffffffff818f8782: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81957ea0)
Location: net/sched/sch_generic.c:885
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff81957ea0-ffffffff81957f53: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8198e340)
Location: net/sched/sch_generic.c:880
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff8198e340-ffffffff8198e3f3: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a65fd0)
Location: net/sched/sch_generic.c:881
Inline: False
Direct callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff81a65fd0-ffffffff81a660ee: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a6e0b0)
Location: net/sched/sch_generic.c:868
Inline: False
Direct callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff81a6e0b0-ffffffff81a6e1b5: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a56930)
Location: net/sched/sch_generic.c:912
Inline: False
Direct callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff81a56930-ffffffff81a56a45: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81b0f760)
Location: net/sched/sch_generic.c:938
Inline: False
Direct callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff81b0f760-ffffffff81b0f872: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81c96910)
Location: net/sched/sch_generic.c:988
Inline: False
Direct callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff81c96910-ffffffff81c96a22: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81e52540)
Location: net/sched/sch_generic.c:984
Inline: False
Direct callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff81e52540-ffffffff81e52652: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81eaddb0)
Location: net/sched/sch_generic.c:984
Inline: False
Direct callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff81eaddb0-ffffffff81eadec2: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81f70840)
Location: net/sched/sch_generic.c:986
Inline: False
Direct callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff81f70840-ffffffff81f70952: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffff800010c39b60)
Location: net/sched/sch_generic.c:880
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffff800010c39b60-ffff800010c39c40: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c0d4bebc)
Location: net/sched/sch_generic.c:880
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
c0d4bebc-c0d4bf7c: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c000000000d32a20)
Location: net/sched/sch_generic.c:880
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
c000000000d32a20-c000000000d32b74: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffe0007aaeb2)
Location: net/sched/sch_generic.c:880
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffe0007aaeb2-ffffffe0007aaf48: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8192e1b0)
Location: net/sched/sch_generic.c:880
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff8192e1b0-ffffffff8192e263: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818e7cb0)
Location: net/sched/sch_generic.c:880
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff818e7cb0-ffffffff818e7d63: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8197f340)
Location: net/sched/sch_generic.c:880
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff8197f340-ffffffff8197f3f3: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct Qdisc *qdisc_create_dflt(struct netdev_queue *dev_queue, const struct Qdisc_ops *ops, unsigned int parentid, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819a18a0)
Location: net/sched/sch_generic.c:880
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_fifo.c:fifo_create_dflt
```
**Symbols:**

```
ffffffff819a18a0-ffffffff819a1953: qdisc_create_dflt (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
