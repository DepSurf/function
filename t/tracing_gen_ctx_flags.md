# Function: <code>tracing_gen_ctx_flags</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811be7c9)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811c8ec3)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c9935)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_hwlat.c (ffffffff811ca721)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811cbd80)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811cca27)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff811cfff2)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_events.c (ffffffff811d3731)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d6904)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d6b47)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_inject.c (ffffffff811dbd4a)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:parse_entry
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ec118)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e907a)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811f4893)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f5405)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_hwlat.c (ffffffff811f6491)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811f8362)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811f9176)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff811fcac8)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_events.c (ffffffff81200672)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff812037ad)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff81203997)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81207898)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_trigger
```
```
In kernel/trace/trace_eprobe.c (ffffffff81209f5b)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
```
```
In kernel/trace/trace_events_inject.c (ffffffff8120b47a)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:parse_entry
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121d0e8)
Location: include/linux/trace_events.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81220d45)
Location: include/linux/trace_events.h:180
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_puts
```
```
In kernel/trace/trace_functions.c (ffffffff8122e5b1)
Location: include/linux/trace_events.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122ec5f)
Location: include/linux/trace_events.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_hwlat.c (ffffffff8122fe90)
Location: include/linux/trace_events.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff81232059)
Location: include/linux/trace_events.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81232ff6)
Location: include/linux/trace_events.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff81236a16)
Location: include/linux/trace_events.h:180
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_events.c (ffffffff8123bf91)
Location: include/linux/trace_events.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_event_perf.c (ffffffff8123ed06)
Location: include/linux/trace_events.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81243737)
Location: include/linux/trace_events.h:180
Inline: True
```
```
In kernel/trace/trace_events_inject.c (ffffffff81247568)
Location: include/linux/trace_events.h:180
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126bbe2)
Location: include/linux/trace_events.h:180
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_puts
```
```
In kernel/trace/trace_functions.c (ffffffff8127a4de)
Location: include/linux/trace_events.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127ac7c)
Location: include/linux/trace_events.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_hwlat.c (ffffffff8127c08d)
Location: include/linux/trace_events.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8127e6a9)
Location: include/linux/trace_events.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8127f786)
Location: include/linux/trace_events.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff812836fc)
Location: include/linux/trace_events.h:180
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_events.c (ffffffff8128873e)
Location: include/linux/trace_events.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128c753)
Location: include/linux/trace_events.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812912b4)
Location: include/linux/trace_events.h:180
Inline: True
```
```
In kernel/trace/trace_events_inject.c (ffffffff81295bd5)
Location: include/linux/trace_events.h:180
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81282f42)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_array_puts
```
```
In kernel/trace/trace_functions.c (ffffffff81291f8e)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8129279c)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_hwlat.c (ffffffff81293bad)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_osnoise.c (ffffffff812963ff)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:__timerlat_dump_stack
  - kernel/trace/trace_osnoise.c:trace_timerlat_sample
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8129b129)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8129c316)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff812a03a8)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_events.c (ffffffff812a546e)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_event_perf.c (ffffffff812a9653)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812ae524)
Location: include/linux/trace_events.h:191
Inline: True
```
```
In kernel/trace/trace_events_inject.c (ffffffff812b2ae5)
Location: include/linux/trace_events.h:191
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129e2d2)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_array_puts
```
```
In kernel/trace/trace_functions.c (ffffffff812ad59e)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ade82)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_hwlat.c (ffffffff812af20d)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b1a6b)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:__timerlat_dump_stack
  - kernel/trace/trace_osnoise.c:trace_timerlat_sample
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff812b67d9)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
```
```
In kernel/trace/trace_functions_graph.c (ffffffff812b79f6)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff812bbad8)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_events.c (ffffffff812c0e8e)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c5363)
Location: include/linux/trace_events.h:191
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812caa44)
Location: include/linux/trace_events.h:191
Inline: True
```
```
In kernel/trace/trace_events_inject.c (ffffffff812cf095)
Location: include/linux/trace_events.h:191
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
