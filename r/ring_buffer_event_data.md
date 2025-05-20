# Function: <code>ring_buffer_event_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811470d0)
Location: kernel/trace/ring_buffer.c:265
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:trace_buffer_lock_reserve
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
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811470d0-ffffffff811470db: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8114f8e0)
Location: kernel/trace/ring_buffer.c:265
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8114f8e0-ffffffff8114f8eb: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811598d0)
Location: kernel/trace/ring_buffer.c:265
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811598d0-ffffffff81159904: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115c6d0)
Location: kernel/trace/ring_buffer.c:266
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8115c6d0-ffffffff8115c701: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81169680)
Location: kernel/trace/ring_buffer.c:265
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_process_export
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff81169680-ffffffff811696b0: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811785f0)
Location: kernel/trace/ring_buffer.c:271
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_process_export
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811785f0-ffffffff8117861f: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81185ab0)
Location: kernel/trace/ring_buffer.c:272
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff81185ab0-ffffffff81185adf: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81192df0)
Location: kernel/trace/ring_buffer.c:263
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff81192df0-ffffffff81192e1b: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119ea70)
Location: kernel/trace/ring_buffer.c:264
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8119ea70-ffffffff8119ea9b: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b4b30)
Location: kernel/trace/ring_buffer.c:264
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:ftrace_trace_userstack
  - kernel/trace/trace.c:ftrace_trace_userstack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff811b4b30-ffffffff811b4b6b: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b23e0)
Location: kernel/trace/ring_buffer.c:274
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace.c:ftrace_exports
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff811b23e0-ffffffff811b241b: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b2ee0)
Location: kernel/trace/ring_buffer.c:274
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace.c:ftrace_exports
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff811b2ee0-ffffffff811b2f1b: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811dce10)
Location: kernel/trace/ring_buffer.c:274
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace.c:ftrace_exports
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff811dce10-ffffffff811dce4b: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81213330)
Location: kernel/trace/ring_buffer.c:282
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace.c:__trace_puts
  - kernel/trace/trace.c:__trace_puts
  - kernel/trace/trace.c:ftrace_exports
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff81213330-ffffffff8121337b: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125cbb0)
Location: kernel/trace/ring_buffer.c:282
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace.c:__trace_puts
  - kernel/trace/trace.c:__trace_puts
  - kernel/trace/trace.c:ftrace_exports
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
```
**Symbols:**

```
ffffffff8125cbb0-ffffffff8125cbfb: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81273b00)
Location: kernel/trace/ring_buffer.c:282
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace.c:__trace_array_puts
  - kernel/trace/trace.c:__trace_array_puts
  - kernel/trace/trace.c:ftrace_exports
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_osnoise.c:__timerlat_dump_stack
  - kernel/trace/trace_osnoise.c:trace_timerlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
  - kernel/trace/trace_fprobe.c:fexit_trace_func
  - kernel/trace/trace_fprobe.c:fentry_trace_func
```
**Symbols:**

```
ffffffff81273b00-ffffffff81273b4b: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8128e100)
Location: kernel/trace/ring_buffer.c:283
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace.c:__trace_array_puts
  - kernel/trace/trace.c:__trace_array_puts
  - kernel/trace/trace.c:ftrace_exports
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_osnoise.c:__timerlat_dump_stack
  - kernel/trace/trace_osnoise.c:trace_timerlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
  - kernel/trace/trace_fprobe.c:fexit_trace_func
  - kernel/trace/trace_fprobe.c:fentry_trace_func
```
**Symbols:**

```
ffffffff8128e100-ffffffff8128e14b: ring_buffer_event_data (STB_GLOBAL)
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
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff800010217370)
Location: kernel/trace/ring_buffer.c:264
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffff800010217370-ffff8000102173ac: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0456c6c)
Location: kernel/trace/ring_buffer.c:264
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
c0456c6c-c0456cb0: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c000000000299670)
Location: kernel/trace/ring_buffer.c:264
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
c000000000299670-c0000000002996b4: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe00017729a)
Location: kernel/trace/ring_buffer.c:264
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffe00017729a-ffffffe0001772d4: ring_buffer_event_data (STB_GLOBAL)
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
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81197090)
Location: kernel/trace/ring_buffer.c:264
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff81197090-ffffffff811970bb: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118a370)
Location: kernel/trace/ring_buffer.c:264
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8118a370-ffffffff8118a39b: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81194e60)
Location: kernel/trace/ring_buffer.c:264
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff81194e60-ffffffff81194e8b: ring_buffer_event_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_event_data(struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a2a70)
Location: kernel/trace/ring_buffer.c:264
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:print_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811a2a70-ffffffff811a2a9b: ring_buffer_event_data (STB_GLOBAL)
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
