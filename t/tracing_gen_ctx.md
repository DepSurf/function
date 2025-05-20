# Function: <code>tracing_gen_ctx</code>

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
In kernel/trace/trace.c (ffffffff811be7bf)
Location: include/linux/trace_events.h:184
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811c8eb9)
Location: include/linux/trace_events.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c992b)
Location: include/linux/trace_events.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_hwlat.c (ffffffff811ca717)
Location: include/linux/trace_events.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_events.c (ffffffff811d3727)
Location: include/linux/trace_events.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff811d68fa)
Location: include/linux/trace_events.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d6b3d)
Location: include/linux/trace_events.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_inject.c (ffffffff811dbd40)
Location: include/linux/trace_events.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:parse_entry
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ec10e)
Location: include/linux/trace_events.h:184
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
In kernel/trace/trace.c (ffffffff811e9070)
Location: include/linux/trace_events.h:184
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
```
```
In kernel/trace/trace_functions.c (ffffffff811f4889)
Location: include/linux/trace_events.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f53fb)
Location: include/linux/trace_events.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_hwlat.c (ffffffff811f6487)
Location: include/linux/trace_events.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_events.c (ffffffff81200668)
Location: include/linux/trace_events.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_syscalls.c (ffffffff812037a3)
Location: include/linux/trace_events.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_event_perf.c (ffffffff8120398d)
Location: include/linux/trace_events.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8120788e)
Location: include/linux/trace_events.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:stacktrace_trigger
```
```
In kernel/trace/trace_eprobe.c (ffffffff81209f51)
Location: include/linux/trace_events.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
```
```
In kernel/trace/trace_events_inject.c (ffffffff8120b470)
Location: include/linux/trace_events.h:184
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:parse_entry
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121d0de)
Location: include/linux/trace_events.h:184
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
In kernel/trace/trace.c (ffffffff81220d3c)
Location: include/linux/trace_events.h:186
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_puts
```
```
In kernel/trace/trace_functions.c (ffffffff8122e5a8)
Location: include/linux/trace_events.h:186
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122ec56)
Location: include/linux/trace_events.h:186
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_hwlat.c (ffffffff8122fe87)
Location: include/linux/trace_events.h:186
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_events.c (ffffffff8123bf88)
Location: include/linux/trace_events.h:186
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_event_perf.c (ffffffff8123ecfd)
Location: include/linux/trace_events.h:186
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8124372e)
Location: include/linux/trace_events.h:186
Inline: True
```
```
In kernel/trace/trace_events_inject.c (ffffffff8124755f)
Location: include/linux/trace_events.h:186
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
In kernel/trace/trace.c (ffffffff8126bbdc)
Location: include/linux/trace_events.h:186
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_puts
```
```
In kernel/trace/trace_functions.c (ffffffff8127a4d8)
Location: include/linux/trace_events.h:186
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127ac76)
Location: include/linux/trace_events.h:186
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_hwlat.c (ffffffff8127c087)
Location: include/linux/trace_events.h:186
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_events.c (ffffffff81288738)
Location: include/linux/trace_events.h:186
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128c74d)
Location: include/linux/trace_events.h:186
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812912ae)
Location: include/linux/trace_events.h:186
Inline: True
```
```
In kernel/trace/trace_events_inject.c (ffffffff81295bcf)
Location: include/linux/trace_events.h:186
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
In kernel/trace/trace.c (ffffffff81282f3c)
Location: include/linux/trace_events.h:197
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_array_puts
```
```
In kernel/trace/trace_functions.c (ffffffff81291f88)
Location: include/linux/trace_events.h:197
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81292796)
Location: include/linux/trace_events.h:197
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_hwlat.c (ffffffff81293ba7)
Location: include/linux/trace_events.h:197
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_osnoise.c (ffffffff812963e0)
Location: include/linux/trace_events.h:197
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:__timerlat_dump_stack
  - kernel/trace/trace_osnoise.c:trace_timerlat_sample
```
```
In kernel/trace/trace_events.c (ffffffff812a5468)
Location: include/linux/trace_events.h:197
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_event_perf.c (ffffffff812a964d)
Location: include/linux/trace_events.h:197
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812ae51e)
Location: include/linux/trace_events.h:197
Inline: True
```
```
In kernel/trace/trace_events_inject.c (ffffffff812b2adf)
Location: include/linux/trace_events.h:197
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
In kernel/trace/trace.c (ffffffff8129e2cc)
Location: include/linux/trace_events.h:197
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_array_puts
```
```
In kernel/trace/trace_functions.c (ffffffff812ad598)
Location: include/linux/trace_events.h:197
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_stacktrace
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ade7c)
Location: include/linux/trace_events.h:197
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_hwlat.c (ffffffff812af207)
Location: include/linux/trace_events.h:197
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b1a50)
Location: include/linux/trace_events.h:197
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:__timerlat_dump_stack
  - kernel/trace/trace_osnoise.c:trace_timerlat_sample
```
```
In kernel/trace/trace_events.c (ffffffff812c0e88)
Location: include/linux/trace_events.h:197
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c535d)
Location: include/linux/trace_events.h:197
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812caa3e)
Location: include/linux/trace_events.h:197
Inline: True
```
```
In kernel/trace/trace_events_inject.c (ffffffff812cf08f)
Location: include/linux/trace_events.h:197
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
