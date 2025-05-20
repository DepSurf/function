# Function: <code>bpf_get_perf_event_info</code>

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
int bpf_get_perf_event_info(const struct perf_event *event, u32 *prog_id, u32 *fd_type, const char **buf, u64 *probe_offset, u64 *probe_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a5f50)
Location: kernel/trace/bpf_trace.c:1180
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
**Symbols:**

```
ffffffff811a5f50-ffffffff811a6069: bpf_get_perf_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_get_perf_event_info(const struct perf_event *event, u32 *prog_id, u32 *fd_type, const char **buf, u64 *probe_offset, u64 *probe_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b4300)
Location: kernel/trace/bpf_trace.c:1215
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811b4300-ffffffff811b4419: bpf_get_perf_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_get_perf_event_info(const struct perf_event *event, u32 *prog_id, u32 *fd_type, const char **buf, u64 *probe_offset, u64 *probe_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c3310)
Location: kernel/trace/bpf_trace.c:1387
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811c3310-ffffffff811c342b: bpf_get_perf_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_get_perf_event_info(const struct perf_event *event, u32 *prog_id, u32 *fd_type, const char **buf, u64 *probe_offset, u64 *probe_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811ceac0)
Location: kernel/trace/bpf_trace.c:1411
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811ceac0-ffffffff811cebdb: bpf_get_perf_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_get_perf_event_info(const struct perf_event *event, u32 *prog_id, u32 *fd_type, const char **buf, u64 *probe_offset, u64 *probe_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811eafe0)
Location: kernel/trace/bpf_trace.c:1905
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
**Symbols:**

```
ffffffff811eafe0-ffffffff811eb0fb: bpf_get_perf_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_get_perf_event_info(const struct perf_event *event, u32 *prog_id, u32 *fd_type, const char **buf, u64 *probe_offset, u64 *probe_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e9180)
Location: kernel/trace/bpf_trace.c:2161
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
**Symbols:**

```
ffffffff811e9180-ffffffff811e929b: bpf_get_perf_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_get_perf_event_info(const struct perf_event *event, u32 *prog_id, u32 *fd_type, const char **buf, u64 *probe_offset, u64 *probe_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811ea070)
Location: kernel/trace/bpf_trace.c:1858
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
**Symbols:**

```
ffffffff811ea070-ffffffff811ea18d: bpf_get_perf_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_get_perf_event_info(const struct perf_event *event, u32 *prog_id, u32 *fd_type, const char **buf, u64 *probe_offset, u64 *probe_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8121aea0)
Location: kernel/trace/bpf_trace.c:1942
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
**Symbols:**

```
ffffffff8121aea0-ffffffff8121afc3: bpf_get_perf_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_get_perf_event_info(const struct perf_event *event, u32 *prog_id, u32 *fd_type, const char **buf, u64 *probe_offset, u64 *probe_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81259bf0)
Location: kernel/trace/bpf_trace.c:2123
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
**Symbols:**

```
ffffffff81259bf0-ffffffff81259d60: bpf_get_perf_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_get_perf_event_info(const struct perf_event *event, u32 *prog_id, u32 *fd_type, const char **buf, u64 *probe_offset, u64 *probe_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a9e90)
Location: kernel/trace/bpf_trace.c:2346
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
**Symbols:**

```
ffffffff812a9e90-ffffffff812aa000: bpf_get_perf_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_get_perf_event_info(const struct perf_event *event, u32 *prog_id, u32 *fd_type, const char **buf, u64 *probe_offset, u64 *probe_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812cc700)
Location: kernel/trace/bpf_trace.c:2355
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
**Symbols:**

```
ffffffff812cc700-ffffffff812cc875: bpf_get_perf_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_get_perf_event_info(const struct perf_event *event, u32 *prog_id, u32 *fd_type, const char **buf, u64 *probe_offset, u64 *probe_addr, long unsigned int *missed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e9b80)
Location: kernel/trace/bpf_trace.c:2460
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - kernel/bpf/syscall.c:bpf_perf_link_fill_common
```
**Symbols:**

```
ffffffff812e9b80-ffffffff812e9d01: bpf_get_perf_event_info (STB_GLOBAL)
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
int bpf_get_perf_event_info(const struct perf_event *event, u32 *prog_id, u32 *fd_type, const char **buf, u64 *probe_offset, u64 *probe_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024ed90)
Location: kernel/trace/bpf_trace.c:1411
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffff80001024ed90-ffff80001024eee0: bpf_get_perf_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_get_perf_event_info(const struct perf_event *event, u32 *prog_id, u32 *fd_type, const char **buf, u64 *probe_offset, u64 *probe_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0481ce0)
Location: kernel/trace/bpf_trace.c:1411
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
**Symbols:**

```
c0481ce0-c0481e24: bpf_get_perf_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_get_perf_event_info(const struct perf_event *event, u32 *prog_id, u32 *fd_type, const char **buf, u64 *probe_offset, u64 *probe_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002eb3e0)
Location: kernel/trace/bpf_trace.c:1411
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
c0000000002eb3e0-c0000000002eb5b4: bpf_get_perf_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: include/linux/trace_events.h:522
Inline: True
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
int bpf_get_perf_event_info(const struct perf_event *event, u32 *prog_id, u32 *fd_type, const char **buf, u64 *probe_offset, u64 *probe_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c70e0)
Location: kernel/trace/bpf_trace.c:1411
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811c70e0-ffffffff811c71fb: bpf_get_perf_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_get_perf_event_info(const struct perf_event *event, u32 *prog_id, u32 *fd_type, const char **buf, u64 *probe_offset, u64 *probe_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b9ec0)
Location: kernel/trace/bpf_trace.c:1411
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811b9ec0-ffffffff811b9fdb: bpf_get_perf_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_get_perf_event_info(const struct perf_event *event, u32 *prog_id, u32 *fd_type, const char **buf, u64 *probe_offset, u64 *probe_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c4eb0)
Location: kernel/trace/bpf_trace.c:1411
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811c4eb0-ffffffff811c4fcb: bpf_get_perf_event_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_get_perf_event_info(const struct perf_event *event, u32 *prog_id, u32 *fd_type, const char **buf, u64 *probe_offset, u64 *probe_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d3110)
Location: kernel/trace/bpf_trace.c:1411
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811d3110-ffffffff811d322b: bpf_get_perf_event_info (STB_GLOBAL)
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
