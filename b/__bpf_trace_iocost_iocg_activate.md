# Function: <code>__bpf_trace_iocost_iocg_activate</code>

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
void __bpf_trace_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8150faf0)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffff8150faf0-ffffffff8150faff: __bpf_trace_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81570bf0)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffff81570bf0-ffffffff81570bff: __bpf_trace_iocost_iocg_activate (STB_LOCAL)
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
void __bpf_trace_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff800010613850)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffff800010613850-ffff800010613864: __bpf_trace_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07be098)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
c07be098-c07be0e4: __bpf_trace_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b20a0)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
c0000000007b20a0-c0000000007b20cc: __bpf_trace_iocost_iocg_activate (STB_LOCAL)
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
void __bpf_trace_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815080d0)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffff815080d0-ffffffff815080df: __bpf_trace_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814f8580)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffff814f8580-ffffffff814f858f: __bpf_trace_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81504160)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffff81504160-ffffffff8150416f: __bpf_trace_iocost_iocg_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_iocost_iocg_activate(void *__data, struct ioc_gq *iocg, const char *path, struct ioc_now *now, u64 last_period, u64 cur_period, u64 vtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151d710)
Location: include/trace/events/iocost.h:14
Inline: False
```
**Symbols:**

```
ffffffff8151d710-ffffffff8151d71f: __bpf_trace_iocost_iocg_activate (STB_LOCAL)
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
