# Function: <code>tracing_gen_ctx_irq_test</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int tracing_gen_ctx_irq_test(unsigned int irqs_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811be410)
Location: kernel/trace/trace.c:2598
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811be410-ffffffff811be466: tracing_gen_ctx_irq_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int tracing_gen_ctx_irq_test(unsigned int irqs_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e8c70)
Location: kernel/trace/trace.c:2621
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
  - kernel/trace/trace_events_trigger.c:stacktrace_trigger
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811e8c70-ffffffff811e8ce1: tracing_gen_ctx_irq_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int tracing_gen_ctx_irq_test(unsigned int irqs_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81220930)
Location: kernel/trace/trace.c:2612
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_puts
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
ffffffff81220930-ffffffff812209b8: tracing_gen_ctx_irq_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int tracing_gen_ctx_irq_test(unsigned int irqs_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126b790)
Location: kernel/trace/trace.c:2636
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_puts
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
ffffffff8126b790-ffffffff8126b818: tracing_gen_ctx_irq_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int tracing_gen_ctx_irq_test(unsigned int irqs_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81282900)
Location: kernel/trace/trace.c:2707
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_array_puts
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_osnoise.c:__timerlat_dump_stack
  - kernel/trace/trace_osnoise.c:trace_timerlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
ffffffff81282900-ffffffff8128298f: tracing_gen_ctx_irq_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int tracing_gen_ctx_irq_test(unsigned int irqs_status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129d9f0)
Location: kernel/trace/trace.c:2702
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_array_puts
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_stack_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_osnoise.c:__timerlat_dump_stack
  - kernel/trace/trace_osnoise.c:trace_timerlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:trace_graph_return
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
ffffffff8129d9f0-ffffffff8129da7f: tracing_gen_ctx_irq_test (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
