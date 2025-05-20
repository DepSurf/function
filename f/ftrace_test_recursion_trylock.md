# Function: <code>ftrace_test_recursion_trylock</code>

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
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107b122)
Location: include/linux/trace_recursion.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff81135cdd)
Location: include/linux/trace_recursion.h:214
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/trace_functions.c (ffffffff811c7cf9)
Location: include/linux/trace_recursion.h:214
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d56c6)
Location: include/linux/trace_recursion.h:214
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
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107c32f)
Location: include/linux/trace_recursion.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff81136b03)
Location: include/linux/trace_recursion.h:214
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/trace_functions.c (ffffffff811c9457)
Location: include/linux/trace_recursion.h:214
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d6be6)
Location: include/linux/trace_recursion.h:214
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
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8108a47f)
Location: include/linux/trace_recursion.h:183
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff81159744)
Location: include/linux/trace_recursion.h:183
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/trace_functions.c (ffffffff811f4eba)
Location: include/linux/trace_recursion.h:183
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff81203b05)
Location: include/linux/trace_recursion.h:183
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
In arch/x86/kernel/ftrace.c (ffffffff81095084)
Location: include/linux/trace_recursion.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8109a9cf)
Location: include/linux/trace_recursion.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff81182d04)
Location: include/linux/trace_recursion.h:192
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/trace_functions.c (ffffffff8122e05f)
Location: include/linux/trace_recursion.h:192
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff8123eed0)
Location: include/linux/trace_recursion.h:192
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/fprobe.c (ffffffff81268584)
Location: include/linux/trace_recursion.h:192
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
In arch/x86/kernel/ftrace.c (ffffffff810aab64)
Location: include/linux/trace_recursion.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b140f)
Location: include/linux/trace_recursion.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff811bdd54)
Location: include/linux/trace_recursion.h:192
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/trace_functions.c (ffffffff81279f1f)
Location: include/linux/trace_recursion.h:192
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128c940)
Location: include/linux/trace_recursion.h:192
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/fprobe.c (ffffffff812ba7c4)
Location: include/linux/trace_recursion.h:192
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
In arch/x86/kernel/ftrace.c (ffffffff810adf13)
Location: include/linux/trace_recursion.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b43bf)
Location: include/linux/trace_recursion.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff811d0742)
Location: include/linux/trace_recursion.h:210
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/trace_functions.c (ffffffff8129195a)
Location: include/linux/trace_recursion.h:210
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff812a9872)
Location: include/linux/trace_recursion.h:210
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/fprobe.c (ffffffff812ddd06)
Location: include/linux/trace_recursion.h:210
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
In arch/x86/kernel/ftrace.c (ffffffff810b4a93)
Location: include/linux/trace_recursion.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810bb81f)
Location: include/linux/trace_recursion.h:210
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff811e5392)
Location: include/linux/trace_recursion.h:210
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/trace_functions.c (ffffffff812acf6a)
Location: include/linux/trace_recursion.h:210
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c5582)
Location: include/linux/trace_recursion.h:210
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/fprobe.c (ffffffff812fbdf6)
Location: include/linux/trace_recursion.h:210
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
