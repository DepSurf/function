# Function: <code>trace_buffer_lock_reserve</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct ring_buffer *buffer, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114ea80)
Location: kernel/trace/trace.c:1670
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_current_buffer_lock_reserve
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffff8114ea80-ffffffff8114eacd: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct ring_buffer *buffer, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81157750)
Location: kernel/trace/trace.c:1926
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffff81157750-ffffffff8115779d: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct ring_buffer *buffer, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81162a70)
Location: kernel/trace/trace.c:1960
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffff81162a70-ffffffff81162abd: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct ring_buffer *buffer, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81165f60)
Location: kernel/trace/trace.c:2137
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffff81165f60-ffffffff81165fad: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct ring_buffer *buffer, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81172ef0)
Location: kernel/trace/trace.c:2140
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffff81172ef0-ffffffff81172f3d: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct ring_buffer *buffer, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81181ed0)
Location: kernel/trace/trace.c:2152
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffff81181ed0-ffffffff81181f1d: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct ring_buffer *buffer, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118f890)
Location: kernel/trace/trace.c:2153
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffff8118f890-ffffffff8118f8dd: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct ring_buffer *buffer, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119d2c0)
Location: kernel/trace/trace.c:2337
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffff8119d2c0-ffffffff8119d308: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct ring_buffer *buffer, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a8c70)
Location: kernel/trace/trace.c:2363
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffff811a8c70-ffffffff811a8cb8: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct trace_buffer *buffer, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c0f50)
Location: kernel/trace/trace.c:2467
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffff811c0f50-ffffffff811c0f98: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct trace_buffer *buffer, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811beb80)
Location: kernel/trace/trace.c:2611
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffff811beb80-ffffffff811bebc8: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct trace_buffer *buffer, int type, long unsigned int len, unsigned int trace_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bf450)
Location: kernel/trace/trace.c:2620
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffff811bf450-ffffffff811bf49f: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct trace_buffer *buffer, int type, long unsigned int len, unsigned int trace_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e9ce0)
Location: kernel/trace/trace.c:2644
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
**Symbols:**

```
ffffffff811e9ce0-ffffffff811e9d2f: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct trace_buffer *buffer, int type, long unsigned int len, unsigned int trace_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81221aa0)
Location: kernel/trace/trace.c:2637
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
**Symbols:**

```
ffffffff81221aa0-ffffffff81221aff: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct trace_buffer *buffer, int type, long unsigned int len, unsigned int trace_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126ca00)
Location: kernel/trace/trace.c:2661
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
**Symbols:**

```
ffffffff8126ca00-ffffffff8126ca5f: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct trace_buffer *buffer, int type, long unsigned int len, unsigned int trace_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81283b90)
Location: kernel/trace/trace.c:2732
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_osnoise.c:__timerlat_dump_stack
  - kernel/trace/trace_osnoise.c:trace_timerlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
**Symbols:**

```
ffffffff81283b90-ffffffff81283bef: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct trace_buffer *buffer, int type, long unsigned int len, unsigned int trace_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129ecb0)
Location: kernel/trace/trace.c:2727
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_osnoise.c:__timerlat_dump_stack
  - kernel/trace/trace_osnoise.c:trace_timerlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
**Symbols:**

```
ffffffff8129ecb0-ffffffff8129ed0f: trace_buffer_lock_reserve (STB_GLOBAL)
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
struct ring_buffer_event *trace_buffer_lock_reserve(struct ring_buffer *buffer, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010225950)
Location: kernel/trace/trace.c:2363
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffff800010225950-ffff8000102259a4: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct ring_buffer *buffer, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0462d74)
Location: kernel/trace/trace.c:2363
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
c0462d74-c0462db4: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct ring_buffer *buffer, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002ab030)
Location: kernel/trace/trace.c:2363
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
c0000000002ab030-c0000000002ab0b0: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct ring_buffer *buffer, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe0001807a0)
Location: kernel/trace/trace.c:2363
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffe0001807a0-ffffffe0001807f0: trace_buffer_lock_reserve (STB_GLOBAL)
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
struct ring_buffer_event *trace_buffer_lock_reserve(struct ring_buffer *buffer, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a1290)
Location: kernel/trace/trace.c:2363
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffff811a1290-ffffffff811a12d8: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct ring_buffer *buffer, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81194260)
Location: kernel/trace/trace.c:2363
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffff81194260-ffffffff811942a8: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct ring_buffer *buffer, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119f060)
Location: kernel/trace/trace.c:2363
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffff8119f060-ffffffff8119f0a8: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ring_buffer_event *trace_buffer_lock_reserve(struct ring_buffer *buffer, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811acd60)
Location: kernel/trace/trace.c:2363
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffff811acd60-ffffffff811acda8: trace_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ring_buffer *buffer</code> ➡️ <code>struct trace_buffer *buffer</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int trace_ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int pc</code>
</li>
</ul>
</details>
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
