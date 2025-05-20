# Function: <code>attach_one_default_qdisc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81741ad0)
Location: net/sched/sch_generic.c:726
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817ae980)
Location: net/sched/sch_generic.c:753
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817de000)
Location: net/sched/sch_generic.c:757
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817fd640)
Location: net/sched/sch_generic.c:757
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8187b230)
Location: net/sched/sch_generic.c:777
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818cd6f3)
Location: net/sched/sch_generic.c:1003
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818f88d3)
Location: net/sched/sch_generic.c:1042
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819580ae)
Location: net/sched/sch_generic.c:1037
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8198e54d)
Location: net/sched/sch_generic.c:1032
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void attach_one_default_qdisc(struct net_device *dev, struct netdev_queue *dev_queue, void *_unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a661ce)
Location: net/sched/sch_generic.c:1029
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
```
**Symbols:**

```
ffffffff81a660f0-ffffffff81a66157: attach_one_default_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void attach_one_default_qdisc(struct net_device *dev, struct netdev_queue *dev_queue, void *_unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a6e29e)
Location: net/sched/sch_generic.c:1016
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
```
**Symbols:**

```
ffffffff81a6e1c0-ffffffff81a6e227: attach_one_default_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void attach_one_default_qdisc(struct net_device *dev, struct netdev_queue *dev_queue, void *_unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a56b6d)
Location: net/sched/sch_generic.c:1060
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
```
**Symbols:**

```
ffffffff81a56a50-ffffffff81a56abc: attach_one_default_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void attach_one_default_qdisc(struct net_device *dev, struct netdev_queue *dev_queue, void *_unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81b0f99d)
Location: net/sched/sch_generic.c:1086
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
```
**Symbols:**

```
ffffffff81b0f880-ffffffff81b0f8ec: attach_one_default_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void attach_one_default_qdisc(struct net_device *dev, struct netdev_queue *dev_queue, void *_unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81c96b63)
Location: net/sched/sch_generic.c:1128
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
```
**Symbols:**

```
ffffffff81c96a30-ffffffff81c96aaa: attach_one_default_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void attach_one_default_qdisc(struct net_device *dev, struct netdev_queue *dev_queue, void *_unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81e527af)
Location: net/sched/sch_generic.c:1139
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
Direct callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
```
**Symbols:**

```
ffffffff81e52670-ffffffff81e526ea: attach_one_default_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void attach_one_default_qdisc(struct net_device *dev, struct netdev_queue *dev_queue, void *_unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81eae01c)
Location: net/sched/sch_generic.c:1147
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
Direct callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
```
**Symbols:**

```
ffffffff81eadee0-ffffffff81eadf5a: attach_one_default_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void attach_one_default_qdisc(struct net_device *dev, struct netdev_queue *dev_queue, void *_unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81f70a9e)
Location: net/sched/sch_generic.c:1151
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
Direct callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
```
**Symbols:**

```
ffffffff81f70970-ffffffff81f709ea: attach_one_default_qdisc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffff800010c39dbc)
Location: net/sched/sch_generic.c:1032
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c0d4c0c0)
Location: net/sched/sch_generic.c:1032
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c000000000d32d58)
Location: net/sched/sch_generic.c:1032
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffe0007ab050)
Location: net/sched/sch_generic.c:1032
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8192e3bd)
Location: net/sched/sch_generic.c:1032
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818e7ebd)
Location: net/sched/sch_generic.c:1032
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8197f54d)
Location: net/sched/sch_generic.c:1032
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819a1aad)
Location: net/sched/sch_generic.c:1032
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
