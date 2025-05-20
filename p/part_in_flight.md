# Function: <code>part_in_flight</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b45d5)
Location: include/linux/genhd.h:410
Inline: True
Inline callers:
  - block/blk-core.c:part_round_stats_single
```
```
In block/genhd.c (ffffffff813ca482)
Location: include/linux/genhd.h:410
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
```
```
In block/partition-generic.c (ffffffff813ccc87)
Location: include/linux/genhd.h:410
Inline: True
Inline callers:
  - block/partition-generic.c:part_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813f82c5)
Location: include/linux/genhd.h:394
Inline: True
Inline callers:
  - block/blk-core.c:part_round_stats_single
```
```
In block/genhd.c (ffffffff8140e732)
Location: include/linux/genhd.h:394
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
```
```
In block/partition-generic.c (ffffffff81410ff2)
Location: include/linux/genhd.h:394
Inline: True
Inline callers:
  - block/partition-generic.c:part_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81411ce5)
Location: include/linux/genhd.h:385
Inline: True
Inline callers:
  - block/blk-core.c:part_round_stats_single
```
```
In block/genhd.c (ffffffff81429acc)
Location: include/linux/genhd.h:385
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
```
```
In block/partition-generic.c (ffffffff8142c38c)
Location: include/linux/genhd.h:385
Inline: True
Inline callers:
  - block/partition-generic.c:part_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8141fb25)
Location: include/linux/genhd.h:379
Inline: True
Inline callers:
  - block/blk-core.c:part_round_stats_single
```
```
In block/genhd.c (ffffffff81437e12)
Location: include/linux/genhd.h:379
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
```
```
In block/partition-generic.c (ffffffff81439708)
Location: include/linux/genhd.h:379
Inline: True
Inline callers:
  - block/partition-generic.c:part_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void part_in_flight(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81464290)
Location: block/genhd.c:68
Inline: True
Direct callers:
  - block/blk-core.c:part_round_stats
  - block/blk-core.c:part_round_stats
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
```
**Symbols:**

```
ffffffff81464290-ffffffff814642e9: part_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void part_in_flight(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81497bb0)
Location: block/genhd.c:68
Inline: True
Direct callers:
  - block/blk-core.c:part_round_stats
  - block/blk-core.c:part_round_stats
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
```
**Symbols:**

```
ffffffff81497bb0-ffffffff81497c08: part_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int part_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b1b10)
Location: block/genhd.c:68
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
```
**Symbols:**

```
ffffffff814b1b10-ffffffff814b1b93: part_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int part_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814dff30)
Location: block/genhd.c:69
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
```
**Symbols:**

```
ffffffff814dff30-ffffffff814dffb3: part_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int part_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f9360)
Location: block/genhd.c:69
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
```
**Symbols:**

```
ffffffff814f9360-ffffffff814f93e3: part_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff81559840)
Location: block/genhd.c:115
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff81559840-ffffffff815598a6: part_in_flight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int part_in_flight(struct block_device *part);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81575990)
Location: block/genhd.c:133
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff81575990-ffffffff815759f6: part_in_flight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int part_in_flight(struct block_device *part);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8157d7c0)
Location: block/genhd.c:130
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff8157d7c0-ffffffff8157d82b: part_in_flight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int part_in_flight(struct block_device *part);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815e29a0)
Location: block/genhd.c:144
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff815e29a0-ffffffff815e2a69: part_in_flight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int part_in_flight(struct block_device *part);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81691b10)
Location: block/genhd.c:148
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff81691b10-ffffffff81691bf7: part_in_flight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int part_in_flight(struct block_device *part);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817510a0)
Location: block/genhd.c:125
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff817510a0-ffffffff8175118d: part_in_flight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int part_in_flight(struct block_device *part);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8178d670)
Location: block/genhd.c:121
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff8178d670-ffffffff8178d75c: part_in_flight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int part_in_flight(struct block_device *part);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817cfed0)
Location: block/genhd.c:121
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff817cfed0-ffffffff817cffbc: part_in_flight (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
unsigned int part_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105fac48)
Location: block/genhd.c:69
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
```
**Symbols:**

```
ffff8000105fac48-ffff8000105fad08: part_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
unsigned int part_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a5db0)
Location: block/genhd.c:69
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
```
**Symbols:**

```
c07a5db0-c07a5e40: part_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
unsigned int part_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (c000000000793bd0)
Location: block/genhd.c:69
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
```
**Symbols:**

```
c000000000793bd0-c000000000793cd4: part_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
unsigned int part_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe000436f24)
Location: block/genhd.c:69
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
```
**Symbols:**

```
ffffffe000436f24-ffffffe000436fc6: part_in_flight (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
unsigned int part_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f1940)
Location: block/genhd.c:69
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
```
**Symbols:**

```
ffffffff814f1940-ffffffff814f19c3: part_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int part_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e1e70)
Location: block/genhd.c:69
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
```
**Symbols:**

```
ffffffff814e1e70-ffffffff814e1ef3: part_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int part_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814ed9d0)
Location: block/genhd.c:69
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
```
**Symbols:**

```
ffffffff814ed9d0-ffffffff814eda53: part_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int part_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81506a50)
Location: block/genhd.c:69
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
```
**Symbols:**

```
ffffffff81506a50-ffffffff81506ad3: part_in_flight (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int *inflight</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
