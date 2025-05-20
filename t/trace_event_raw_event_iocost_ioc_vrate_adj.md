# Function: <code>trace_event_raw_event_iocost_ioc_vrate_adj</code>

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
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81510fc0)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffff81510fc0-ffffffff815111ab: trace_event_raw_event_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815721d0)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffff815721d0-ffffffff815723b1: trace_event_raw_event_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158de10)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff8158de10-ffffffff8158dfe7: trace_event_raw_event_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81594b70)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff81594b70-ffffffff81594d47: trace_event_raw_event_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815fc4e0)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff815fc4e0-ffffffff815fc6b7: trace_event_raw_event_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff816b0200)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff816b0200-ffffffff816b03e1: trace_event_raw_event_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8176f090)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff8176f090-ffffffff8176f309: trace_event_raw_event_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817aec10)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff817aec10-ffffffff817aeeb4: trace_event_raw_event_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817f2a20)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff817f2a20-ffffffff817f2cc4: trace_event_raw_event_iocost_ioc_vrate_adj (STB_LOCAL)
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
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff800010614468)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffff800010614468-ffff800010614624: trace_event_raw_event_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07c09ac)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
c07c09ac-c07c0b70: trace_event_raw_event_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b3fc0)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
c0000000007b3fc0-c0000000007b4208: trace_event_raw_event_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044c132)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffe00044c132-ffffffe00044c29e: trace_event_raw_event_iocost_ioc_vrate_adj (STB_LOCAL)
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
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815095a0)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffff815095a0-ffffffff8150978b: trace_event_raw_event_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814f9a50)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffff814f9a50-ffffffff814f9c3b: trace_event_raw_event_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81505630)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffff81505630-ffffffff8150581b: trace_event_raw_event_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void trace_event_raw_event_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81520120)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffff81520120-ffffffff8152030b: trace_event_raw_event_iocost_ioc_vrate_adj (STB_LOCAL)
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
