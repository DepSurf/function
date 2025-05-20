# Function: <code>rtnl_kfree_skbs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817935b0)
Location: net/core/rtnetlink.c:75
Inline: False
Direct callers:
  - net/sched/sch_generic.c:pfifo_fast_reset
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff817935b0-ffffffff817935d6: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c0e80)
Location: net/core/rtnetlink.c:75
Inline: False
Direct callers:
  - net/sched/sch_generic.c:pfifo_fast_reset
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff817c0e80-ffffffff817c0ea6: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817df650)
Location: net/core/rtnetlink.c:77
Inline: False
Direct callers:
  - net/sched/sch_generic.c:pfifo_fast_reset
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff817df650-ffffffff817df676: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81859f20)
Location: net/core/rtnetlink.c:77
Inline: False
Direct callers:
  - net/sched/sch_generic.c:pfifo_fast_reset
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff81859f20-ffffffff81859f46: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a57a0)
Location: net/core/rtnetlink.c:88
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff818a57a0-ffffffff818a57c6: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818c8d30)
Location: net/core/rtnetlink.c:88
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff818c8d30-ffffffff818c8d56: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81915970)
Location: net/core/rtnetlink.c:83
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff81915970-ffffffff81915996: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81947f30)
Location: net/core/rtnetlink.c:83
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff81947f30-ffffffff81947f56: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a180e0)
Location: net/core/rtnetlink.c:83
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff81a180e0-ffffffff81a18106: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a182e0)
Location: net/core/rtnetlink.c:83
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff81a182e0-ffffffff81a18306: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819ff240)
Location: net/core/rtnetlink.c:83
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff819ff240-ffffffff819ff266: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab1430)
Location: net/core/rtnetlink.c:83
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff81ab1430-ffffffff81ab1456: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2a5c0)
Location: net/core/rtnetlink.c:85
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff81c2a5c0-ffffffff81c2a5f0: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ddd2f0)
Location: net/core/rtnetlink.c:86
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff81ddd2f0-ffffffff81ddd320: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e4e040)
Location: net/core/rtnetlink.c:89
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff81e4e040-ffffffff81e4e070: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f0cda0)
Location: net/core/rtnetlink.c:90
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff81f0cda0-ffffffff81f0cdd0: rtnl_kfree_skbs (STB_GLOBAL)
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
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010be9ac8)
Location: net/core/rtnetlink.c:83
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffff800010be9ac8-ffff800010be9b0c: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d0243c)
Location: net/core/rtnetlink.c:83
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
c0d0243c-c0d02470: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000ccbc60)
Location: net/core/rtnetlink.c:83
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
c000000000ccbc60-c000000000ccbc94: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076d4e8)
Location: net/core/rtnetlink.c:83
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffe00076d4e8-ffffffe00076d524: rtnl_kfree_skbs (STB_GLOBAL)
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
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818e7f00)
Location: net/core/rtnetlink.c:83
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff818e7f00-ffffffff818e7f26: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a1d40)
Location: net/core/rtnetlink.c:83
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff818a1d40-ffffffff818a1d66: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81938f30)
Location: net/core/rtnetlink.c:83
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff81938f30-ffffffff81938f56: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rtnl_kfree_skbs(struct sk_buff *head, struct sk_buff *tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195a740)
Location: net/core/rtnetlink.c:83
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
**Symbols:**

```
ffffffff8195a740-ffffffff8195a766: rtnl_kfree_skbs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
