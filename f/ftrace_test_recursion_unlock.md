# Function: <code>ftrace_test_recursion_unlock</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107b222)
Location: include/linux/trace_recursion.h:226
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff81135d93)
Location: include/linux/trace_recursion.h:226
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/trace_functions.c (ffffffff811c7da5)
Location: include/linux/trace_recursion.h:226
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d57ba)
Location: include/linux/trace_recursion.h:226
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107c42e)
Location: include/linux/trace_recursion.h:226
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff81136baf)
Location: include/linux/trace_recursion.h:226
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/trace_functions.c (ffffffff811c9537)
Location: include/linux/trace_recursion.h:226
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d6cda)
Location: include/linux/trace_recursion.h:226
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
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
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8108a55a)
Location: include/linux/trace_recursion.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff81159806)
Location: include/linux/trace_recursion.h:195
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/trace_functions.c (ffffffff811f4f86)
Location: include/linux/trace_recursion.h:195
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff81203b6e)
Location: include/linux/trace_recursion.h:195
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
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
In arch/x86/kernel/ftrace.c (ffffffff810950ed)
Location: include/linux/trace_recursion.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8109aae7)
Location: include/linux/trace_recursion.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff81182de0)
Location: include/linux/trace_recursion.h:204
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/trace_functions.c (ffffffff8122e0e6)
Location: include/linux/trace_recursion.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff8123ef4f)
Location: include/linux/trace_recursion.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/fprobe.c (ffffffff81268653)
Location: include/linux/trace_recursion.h:204
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
In arch/x86/kernel/ftrace.c (ffffffff810aabcd)
Location: include/linux/trace_recursion.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b1527)
Location: include/linux/trace_recursion.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff811bde30)
Location: include/linux/trace_recursion.h:204
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/trace_functions.c (ffffffff81279fa6)
Location: include/linux/trace_recursion.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128c9bf)
Location: include/linux/trace_recursion.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/fprobe.c (ffffffff812ba893)
Location: include/linux/trace_recursion.h:204
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
In arch/x86/kernel/ftrace.c (ffffffff810adf9d)
Location: include/linux/trace_recursion.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b44e9)
Location: include/linux/trace_recursion.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff811d0831)
Location: include/linux/trace_recursion.h:222
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/trace_functions.c (ffffffff812919f9)
Location: include/linux/trace_recursion.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff812a990f)
Location: include/linux/trace_recursion.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/fprobe.c (ffffffff812ddd99)
Location: include/linux/trace_recursion.h:222
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
In arch/x86/kernel/ftrace.c (ffffffff810b4b1d)
Location: include/linux/trace_recursion.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810bb949)
Location: include/linux/trace_recursion.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff811e5481)
Location: include/linux/trace_recursion.h:222
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/trace_functions.c (ffffffff812ad009)
Location: include/linux/trace_recursion.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c561f)
Location: include/linux/trace_recursion.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/fprobe.c (ffffffff812fbe89)
Location: include/linux/trace_recursion.h:222
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
