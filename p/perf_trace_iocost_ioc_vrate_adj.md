# Function: <code>perf_trace_iocost_ioc_vrate_adj</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81511480)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffff81511480-ffffffff815116b0: perf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81571fa0)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffff81571fa0-ffffffff815721ca: perf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158d550)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff8158d550-ffffffff8158d772: perf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81594940)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff81594940-ffffffff81594b62: perf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815fbe30)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff815fbe30-ffffffff815fc052: perf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff816adc10)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff816adc10-ffffffff816ade30: perf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8176c450)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff8176c450-ffffffff8176c712: perf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817ab380)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff817ab380-ffffffff817ab662: perf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817ef130)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff817ef130-ffffffff817ef412: perf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
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
void perf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff800010614a38)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffff800010614a38-ffff800010614c2c: perf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07c07a8)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
c07c07a8-c07c09ac: perf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b44d0)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
c0000000007b44d0-c0000000007b4778: perf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044bdec)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffe00044bdec-ffffffe00044bf6c: perf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
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
void perf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81509a60)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffff81509a60-ffffffff81509c90: perf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814f9f10)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffff814f9f10-ffffffff814fa140: perf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81505af0)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffff81505af0-ffffffff81505d20: perf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81521390)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffff81521390-ffffffff815215c0: perf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32[2] *missed_ppm</code> ➡️ <code>u32 *missed_ppm</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nr_surpluses</code>
</li>
</ul>
</details>
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
