# Function: <code>interrupt_context_level</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8109508b)
Location: include/linux/preempt.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8109a9ee)
Location: include/linux/preempt.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff81182d27)
Location: include/linux/preempt.h:89
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff812098c8)
Location: include/linux/preempt.h:89
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff81216c71)
Location: include/linux/preempt.h:89
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace_functions.c (ffffffff8122e069)
Location: include/linux/preempt.h:89
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff8123eeef)
Location: include/linux/preempt.h:89
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/fprobe.c (ffffffff81268584)
Location: include/linux/preempt.h:89
Inline: True
```
```
In kernel/events/core.c (ffffffff812e0fc2)
Location: include/linux/preempt.h:89
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_event
```
```
In kernel/events/callchain.c (ffffffff812e3ee1)
Location: include/linux/preempt.h:89
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_entry
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
In arch/x86/kernel/ftrace.c (ffffffff810aab6b)
Location: include/linux/preempt.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b142e)
Location: include/linux/preempt.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff811bdd77)
Location: include/linux/preempt.h:89
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff81252078)
Location: include/linux/preempt.h:89
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff81261de1)
Location: include/linux/preempt.h:89
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace_functions.c (ffffffff81279f29)
Location: include/linux/preempt.h:89
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128c95f)
Location: include/linux/preempt.h:89
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/fprobe.c (ffffffff812ba7c4)
Location: include/linux/preempt.h:89
Inline: True
```
```
In kernel/events/core.c (ffffffff813494c2)
Location: include/linux/preempt.h:89
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_pending_irq
```
```
In kernel/events/callchain.c (ffffffff8134c611)
Location: include/linux/preempt.h:89
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_entry
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
In arch/x86/kernel/ftrace.c (ffffffff810adf20)
Location: include/linux/preempt.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b43dc)
Location: include/linux/preempt.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff811d0767)
Location: include/linux/preempt.h:90
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff81269b1b)
Location: include/linux/preempt.h:90
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff81278e51)
Location: include/linux/preempt.h:90
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace_functions.c (ffffffff81291967)
Location: include/linux/preempt.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff812a9896)
Location: include/linux/preempt.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/fprobe.c (ffffffff812ddd13)
Location: include/linux/preempt.h:90
Inline: True
```
```
In kernel/events/core.c (ffffffff8137a4d2)
Location: include/linux/preempt.h:90
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_pending_irq
```
```
In kernel/events/callchain.c (ffffffff8137d661)
Location: include/linux/preempt.h:90
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_entry
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
In arch/x86/kernel/ftrace.c (ffffffff810b4aa0)
Location: include/linux/preempt.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810bb83c)
Location: include/linux/preempt.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff811e53b7)
Location: include/linux/preempt.h:90
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff81283c8b)
Location: include/linux/preempt.h:90
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
```
```
In kernel/trace/ring_buffer.c (ffffffff81293a43)
Location: include/linux/preempt.h:90
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
```
In kernel/trace/trace_functions.c (ffffffff812acf77)
Location: include/linux/preempt.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c55a6)
Location: include/linux/preempt.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/fprobe.c (ffffffff812fbe03)
Location: include/linux/preempt.h:90
Inline: True
```
```
In kernel/events/core.c (ffffffff813a36d2)
Location: include/linux/preempt.h:90
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_pending_irq
```
```
In kernel/events/callchain.c (ffffffff813a68c1)
Location: include/linux/preempt.h:90
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_callchain_entry
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
