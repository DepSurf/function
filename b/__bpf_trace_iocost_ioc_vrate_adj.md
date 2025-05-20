# Function: <code>__bpf_trace_iocost_ioc_vrate_adj</code>

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
void __bpf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8150fb20)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffff8150fb20-ffffffff8150fb3b: __bpf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81570c20)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffff81570c20-ffffffff81570c3b: __bpf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158c0b0)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff8158c0b0-ffffffff8158c0c6: __bpf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81592f70)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff81592f70-ffffffff81592f86: __bpf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815fa320)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff815fa320-ffffffff815fa336: __bpf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff816ac730)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff816ac730-ffffffff816ac75a: __bpf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8176af90)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff8176af90-ffffffff8176afba: __bpf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817aa070)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff817aa070-ffffffff817aa09a: __bpf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32 *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817ede30)
Location: include/trace/events/iocost.h:142
Inline: False
```
**Symbols:**

```
ffffffff817ede30-ffffffff817ede5a: __bpf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
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
void __bpf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff800010613888)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffff800010613888-ffff8000106138ac: __bpf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07be140)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
c07be140-c07be1b0: __bpf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b2100)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
c0000000007b2100-c0000000007b2138: __bpf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81508100)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffff81508100-ffffffff8150811b: __bpf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814f85b0)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffff814f85b0-ffffffff814f85cb: __bpf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81504190)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffff81504190-ffffffff815041ab: __bpf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_iocost_ioc_vrate_adj(void *__data, struct ioc *ioc, u64 new_vrate, u32[2] *missed_ppm, u32 rq_wait_pct, int nr_lagging, int nr_shortages, int nr_surpluses);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151d740)
Location: include/trace/events/iocost.h:131
Inline: False
```
**Symbols:**

```
ffffffff8151d740-ffffffff8151d75b: __bpf_trace_iocost_ioc_vrate_adj (STB_LOCAL)
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
