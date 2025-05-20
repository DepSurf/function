# Function: <code>bpf_get_uprobe_info</code>

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
int bpf_get_uprobe_info(const struct perf_event *event, u32 *fd_type, const char **filename, u64 *probe_offset, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811afd30)
Location: kernel/trace/trace_uprobe.c:1165
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811afd30-ffffffff811afda8: bpf_get_uprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event *event, u32 *fd_type, const char **filename, u64 *probe_offset, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811be3a0)
Location: kernel/trace/trace_uprobe.c:1167
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811be3a0-ffffffff811be418: bpf_get_uprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event *event, u32 *fd_type, const char **filename, u64 *probe_offset, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811cdfa0)
Location: kernel/trace/trace_uprobe.c:1189
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811cdfa0-ffffffff811ce017: bpf_get_uprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event *event, u32 *fd_type, const char **filename, u64 *probe_offset, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811da600)
Location: kernel/trace/trace_uprobe.c:1397
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811da600-ffffffff811da677: bpf_get_uprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event *event, u32 *fd_type, const char **filename, u64 *probe_offset, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f7090)
Location: kernel/trace/trace_uprobe.c:1404
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811f7090-ffffffff811f711c: bpf_get_uprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event *event, u32 *fd_type, const char **filename, u64 *probe_offset, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f5c40)
Location: kernel/trace/trace_uprobe.c:1417
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811f5c40-ffffffff811f5ccc: bpf_get_uprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event *event, u32 *fd_type, const char **filename, u64 *probe_offset, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f6b30)
Location: kernel/trace/trace_uprobe.c:1422
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811f6b30-ffffffff811f6bbc: bpf_get_uprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event *event, u32 *fd_type, const char **filename, u64 *probe_offset, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81228100)
Location: kernel/trace/trace_uprobe.c:1423
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff81228100-ffffffff8122818c: bpf_get_uprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event *event, u32 *fd_type, const char **filename, u64 *probe_offset, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812681e0)
Location: kernel/trace/trace_uprobe.c:1413
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff812681e0-ffffffff8126828b: bpf_get_uprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event *event, u32 *fd_type, const char **filename, u64 *probe_offset, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812ba3a0)
Location: kernel/trace/trace_uprobe.c:1419
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff812ba3a0-ffffffff812ba44b: bpf_get_uprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event *event, u32 *fd_type, const char **filename, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812dd990)
Location: kernel/trace/trace_uprobe.c:1419
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff812dd990-ffffffff812dda5b: bpf_get_uprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event *event, u32 *fd_type, const char **filename, u64 *probe_offset, u64 *probe_addr, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812fba80)
Location: kernel/trace/trace_uprobe.c:1415
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff812fba80-ffffffff812fbb4b: bpf_get_uprobe_info (STB_GLOBAL)
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
int bpf_get_uprobe_info(const struct perf_event *event, u32 *fd_type, const char **filename, u64 *probe_offset, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffff80001025ace8)
Location: kernel/trace/trace_uprobe.c:1397
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffff80001025ace8-ffff80001025ad80: bpf_get_uprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event *event, u32 *fd_type, const char **filename, u64 *probe_offset, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (c048dddc)
Location: kernel/trace/trace_uprobe.c:1397
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
c048dddc-c048de74: bpf_get_uprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event *event, u32 *fd_type, const char **filename, u64 *probe_offset, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (c0000000002fe820)
Location: kernel/trace/trace_uprobe.c:1397
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
c0000000002fe820-c0000000002fe8ec: bpf_get_uprobe_info (STB_GLOBAL)
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
int bpf_get_uprobe_info(const struct perf_event *event, u32 *fd_type, const char **filename, u64 *probe_offset, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811d2c20)
Location: kernel/trace/trace_uprobe.c:1397
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811d2c20-ffffffff811d2c97: bpf_get_uprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event *event, u32 *fd_type, const char **filename, u64 *probe_offset, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811c59f0)
Location: kernel/trace/trace_uprobe.c:1397
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811c59f0-ffffffff811c5a67: bpf_get_uprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event *event, u32 *fd_type, const char **filename, u64 *probe_offset, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811d09f0)
Location: kernel/trace/trace_uprobe.c:1397
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811d09f0-ffffffff811d0a67: bpf_get_uprobe_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_get_uprobe_info(const struct perf_event *event, u32 *fd_type, const char **filename, u64 *probe_offset, bool perf_type_tracepoint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811decb0)
Location: kernel/trace/trace_uprobe.c:1397
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_perf_event_info
```
**Symbols:**

```
ffffffff811decb0-ffffffff811ded27: bpf_get_uprobe_info (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 *probe_addr</code>
</li>
<li>
<b>Param reordered. </b>
<code>event, fd_type, filename, probe_offset, perf_type_tracepoint</code> ➡️ <code>event, fd_type, filename, probe_offset, probe_addr, perf_type_tracepoint</code>
</li>
</ul>
</details>
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
