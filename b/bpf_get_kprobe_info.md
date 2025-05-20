# Function: <code>bpf_get_kprobe_info</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_get_kprobe_info(const struct perf_event *event, u32 *fd_type, const char **symbol, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811a89f0)
Location: kernel/trace/trace_kprobe.c:1302
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811a89f0-ffffffff811a8aac: bpf_get_kprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_get_kprobe_info(const struct perf_event *event, u32 *fd_type, const char **symbol, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811b6db0)
Location: kernel/trace/trace_kprobe.c:1218
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811b6db0-ffffffff811b6e6c: bpf_get_kprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_get_kprobe_info(const struct perf_event *event, u32 *fd_type, const char **symbol, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c5e60)
Location: kernel/trace/trace_kprobe.c:1253
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811c5e60-ffffffff811c5f10: bpf_get_kprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_get_kprobe_info(const struct perf_event *event, u32 *fd_type, const char **symbol, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811d1bc0)
Location: kernel/trace/trace_kprobe.c:1454
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811d1bc0-ffffffff811d1c70: bpf_get_kprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_get_kprobe_info(const struct perf_event *event, u32 *fd_type, const char **symbol, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ee530)
Location: kernel/trace/trace_kprobe.c:1635
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811ee530-ffffffff811ee5f8: bpf_get_kprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_get_kprobe_info(const struct perf_event *event, u32 *fd_type, const char **symbol, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ec780)
Location: kernel/trace/trace_kprobe.c:1655
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811ec780-ffffffff811ec848: bpf_get_kprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_get_kprobe_info(const struct perf_event *event, u32 *fd_type, const char **symbol, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ed510)
Location: kernel/trace/trace_kprobe.c:1658
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811ed510-ffffffff811ed5d8: bpf_get_kprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_get_kprobe_info(const struct perf_event *event, u32 *fd_type, const char **symbol, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8121e580)
Location: kernel/trace/trace_kprobe.c:1653
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff8121e580-ffffffff8121e648: bpf_get_kprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_get_kprobe_info(const struct perf_event *event, u32 *fd_type, const char **symbol, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8125db90)
Location: kernel/trace/trace_kprobe.c:1638
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff8125db90-ffffffff8125dc74: bpf_get_kprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_get_kprobe_info(const struct perf_event *event, u32 *fd_type, const char **symbol, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812ae600)
Location: kernel/trace/trace_kprobe.c:1590
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff812ae600-ffffffff812ae6e4: bpf_get_kprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_get_kprobe_info(const struct perf_event *event, u32 *fd_type, const char **symbol, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812d0af0)
Location: kernel/trace/trace_kprobe.c:1547
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff812d0af0-ffffffff812d0bfc: bpf_get_kprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_get_kprobe_info(const struct perf_event *event, u32 *fd_type, const char **symbol, u64 *probe_offset, u64 *probe_addr, long unsigned int *missed, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812ee550)
Location: kernel/trace/trace_kprobe.c:1613
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff812ee550-ffffffff812ee69a: bpf_get_kprobe_info (STB_GLOBAL)
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
int bpf_get_kprobe_info(const struct perf_event *event, u32 *fd_type, const char **symbol, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffff800010251d48)
Location: kernel/trace/trace_kprobe.c:1454
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffff800010251d48-ffff800010251e10: bpf_get_kprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_get_kprobe_info(const struct perf_event *event, u32 *fd_type, const char **symbol, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0484c48)
Location: kernel/trace/trace_kprobe.c:1454
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
c0484c48-c0484d18: bpf_get_kprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_get_kprobe_info(const struct perf_event *event, u32 *fd_type, const char **symbol, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0000000002f0190)
Location: kernel/trace/trace_kprobe.c:1454
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
c0000000002f0190-c0000000002f02a0: bpf_get_kprobe_info (STB_GLOBAL)
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
int bpf_get_kprobe_info(const struct perf_event *event, u32 *fd_type, const char **symbol, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ca1e0)
Location: kernel/trace/trace_kprobe.c:1454
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811ca1e0-ffffffff811ca290: bpf_get_kprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_get_kprobe_info(const struct perf_event *event, u32 *fd_type, const char **symbol, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811bcfb0)
Location: kernel/trace/trace_kprobe.c:1454
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811bcfb0-ffffffff811bd060: bpf_get_kprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_get_kprobe_info(const struct perf_event *event, u32 *fd_type, const char **symbol, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c7fb0)
Location: kernel/trace/trace_kprobe.c:1454
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811c7fb0-ffffffff811c8060: bpf_get_kprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_get_kprobe_info(const struct perf_event *event, u32 *fd_type, const char **symbol, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811d6210)
Location: kernel/trace/trace_kprobe.c:1454
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811d6210-ffffffff811d62c0: bpf_get_kprobe_info (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int *missed</code>
</li>
<li>
<b>Param reordered. </b>
<code>event, fd_type, symbol, probe_offset, probe_addr, perf_type_tracepoint</code> ➡️ <code>event, fd_type, symbol, probe_offset, probe_addr, missed, perf_type_tracepoint</code>
</li>
</ul>
</details>
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
