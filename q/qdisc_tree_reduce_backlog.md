# Function: <code>qdisc_tree_reduce_backlog</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, unsigned int n, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817b1770)
Location: net/sched/sch_api.c:744
Inline: True
```
**Symbols:**

```
ffffffff817b1770-ffffffff817b1882: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, unsigned int n, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817e0ea0)
Location: net/sched/sch_api.c:750
Inline: True
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffff817e0ea0-ffffffff817e0fb2: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, unsigned int n, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818003e0)
Location: net/sched/sch_api.c:746
Inline: True
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffff818003e0-ffffffff818004d4: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, unsigned int n, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8187e190)
Location: net/sched/sch_api.c:727
Inline: True
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffff8187e190-ffffffff8187e2c2: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, unsigned int n, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818d0c20)
Location: net/sched/sch_api.c:739
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffff818d0c20-ffffffff818d0d5f: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, unsigned int n, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818fbf70)
Location: net/sched/sch_api.c:761
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffff818fbf70-ffffffff818fc0af: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, int n, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8195b920)
Location: net/sched/sch_api.c:753
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffff8195b920-ffffffff8195ba3d: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, int n, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81991dd0)
Location: net/sched/sch_api.c:753
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffff81991dd0-ffffffff81991eed: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, int n, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a69c70)
Location: net/sched/sch_api.c:762
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffff81a69c70-ffffffff81a69dae: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, int n, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a723b0)
Location: net/sched/sch_api.c:764
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffff81a723b0-ffffffff81a724f3: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, int n, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a5ac30)
Location: net/sched/sch_api.c:764
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffff81a5ac30-ffffffff81a5ad70: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, int n, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81b13de0)
Location: net/sched/sch_api.c:770
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffff81b13de0-ffffffff81b13f20: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, int n, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81c9b210)
Location: net/sched/sch_api.c:771
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffff81c9b210-ffffffff81c9b384: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, int n, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81e576f0)
Location: net/sched/sch_api.c:773
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffff81e576f0-ffffffff81e57864: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, int n, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81eb1a30)
Location: net/sched/sch_api.c:781
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffff81eb1a30-ffffffff81eb1ba4: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, int n, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81f744e0)
Location: net/sched/sch_api.c:781
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffff81f744e0-ffffffff81f74654: qdisc_tree_reduce_backlog (STB_GLOBAL)
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
void qdisc_tree_reduce_backlog(struct Qdisc *sch, int n, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffff800010c3e398)
Location: net/sched/sch_api.c:753
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffff800010c3e398-ffff800010c3e4c8: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, int n, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c0d4fd9c)
Location: net/sched/sch_api.c:753
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
c0d4fd9c-c0d4ff40: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, int n, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c000000000d38450)
Location: net/sched/sch_api.c:753
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
c000000000d38450-c000000000d38618: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, int n, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffe0007ae454)
Location: net/sched/sch_api.c:753
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffe0007ae454-ffffffe0007ae552: qdisc_tree_reduce_backlog (STB_GLOBAL)
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
void qdisc_tree_reduce_backlog(struct Qdisc *sch, int n, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81931c40)
Location: net/sched/sch_api.c:753
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffff81931c40-ffffffff81931d5d: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, int n, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818eb740)
Location: net/sched/sch_api.c:753
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffff818eb740-ffffffff818eb85d: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, int n, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81982dd0)
Location: net/sched/sch_api.c:753
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffff81982dd0-ffffffff81982eed: qdisc_tree_reduce_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc *sch, int n, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff819a5310)
Location: net/sched/sch_api.c:753
Inline: False
Direct callers:
  - net/sched/sch_fifo.c:pfifo_tail_enqueue
```
**Symbols:**

```
ffffffff819a5310-ffffffff819a5433: qdisc_tree_reduce_backlog (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int n</code> ➡️ <code>int n</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int len</code> ➡️ <code>int len</code>
</li>
</ul>
</details>
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
