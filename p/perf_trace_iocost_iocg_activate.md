# Function: <code>perf_trace_iocost_iocg_activate</code>

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
void perf_trace_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81511920)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffff81511920-ffffffff81511bc5: perf_trace_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_trace_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81572b30)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffff81572b30-ffffffff81572dd5: perf_trace_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void perf_trace_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff800010614fe8)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffff800010614fe8-ffff800010615244: perf_trace_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_trace_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07c0fc0)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
c07c0fc0-c07c1258: perf_trace_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_trace_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b5310)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
c0000000007b5310-c0000000007b5638: perf_trace_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_trace_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044c29e)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffe00044c29e-ffffffe00044c488: perf_trace_iocost_iocg_activate (STB_LOCAL)
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
void perf_trace_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81509f00)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffff81509f00-ffffffff8150a1a5: perf_trace_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_trace_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814fa6a0)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffff814fa6a0-ffffffff814fa945: perf_trace_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_trace_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81505f90)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffff81505f90-ffffffff81506235: perf_trace_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_trace_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81521830)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffff81521830-ffffffff81521ad5: perf_trace_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
