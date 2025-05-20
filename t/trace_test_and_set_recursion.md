# Function: <code>trace_test_and_set_recursion</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81140101)
Location: kernel/trace/trace.h:515
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_recurs_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff811567b0)
Location: kernel/trace/trace.h:515
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81149648)
Location: kernel/trace/trace.h:524
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff81161020)
Location: kernel/trace/trace.h:524
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811534f8)
Location: kernel/trace/trace.h:531
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff8116ba80)
Location: kernel/trace/trace.h:531
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81154f18)
Location: kernel/trace/trace.h:537
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff8116ebd0)
Location: kernel/trace/trace.h:537
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811617d5)
Location: kernel/trace/trace.h:541
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff8117bcc0)
Location: kernel/trace/trace.h:541
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81170705)
Location: kernel/trace/trace.h:549
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff8118ae10)
Location: kernel/trace/trace.h:549
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8117e1a5)
Location: kernel/trace/trace.h:589
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff81198770)
Location: kernel/trace/trace.h:589
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118b24f)
Location: kernel/trace/trace.h:638
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff811a6305)
Location: kernel/trace/trace.h:638
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119714f)
Location: kernel/trace/trace.h:639
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff811b1af5)
Location: kernel/trace/trace.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ac450)
Location: kernel/trace/trace.h:683
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff811ca692)
Location: kernel/trace/trace.h:683
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
</details>
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
Location: include/linux/trace_recursion.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff81135cdd)
Location: include/linux/trace_recursion.h:162
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff811a9d57)
Location: include/linux/trace_recursion.h:162
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff811c7cf9)
Location: include/linux/trace_recursion.h:162
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d56c6)
Location: include/linux/trace_recursion.h:162
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
Location: include/linux/trace_recursion.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff81136b03)
Location: include/linux/trace_recursion.h:162
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff811aa917)
Location: include/linux/trace_recursion.h:162
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff811c9457)
Location: include/linux/trace_recursion.h:162
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d6be6)
Location: include/linux/trace_recursion.h:162
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
Location: include/linux/trace_recursion.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff81159744)
Location: include/linux/trace_recursion.h:142
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff811d4580)
Location: include/linux/trace_recursion.h:142
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff811f4eba)
Location: include/linux/trace_recursion.h:142
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff81203b05)
Location: include/linux/trace_recursion.h:142
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
Location: include/linux/trace_recursion.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8109a9cf)
Location: include/linux/trace_recursion.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff81182d04)
Location: include/linux/trace_recursion.h:141
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff812098b7)
Location: include/linux/trace_recursion.h:141
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff8122e05f)
Location: include/linux/trace_recursion.h:141
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff8123eed0)
Location: include/linux/trace_recursion.h:141
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/fprobe.c (ffffffff81268584)
Location: include/linux/trace_recursion.h:141
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
Location: include/linux/trace_recursion.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b140f)
Location: include/linux/trace_recursion.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff811bdd54)
Location: include/linux/trace_recursion.h:141
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff81252067)
Location: include/linux/trace_recursion.h:141
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff81279f1f)
Location: include/linux/trace_recursion.h:141
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128c940)
Location: include/linux/trace_recursion.h:141
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/fprobe.c (ffffffff812ba7c4)
Location: include/linux/trace_recursion.h:141
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
Location: include/linux/trace_recursion.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b43bf)
Location: include/linux/trace_recursion.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff811d0742)
Location: include/linux/trace_recursion.h:156
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff81269af6)
Location: include/linux/trace_recursion.h:156
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff8129195a)
Location: include/linux/trace_recursion.h:156
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff812a9872)
Location: include/linux/trace_recursion.h:156
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/fprobe.c (ffffffff812ddd06)
Location: include/linux/trace_recursion.h:156
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
Location: include/linux/trace_recursion.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810bb81f)
Location: include/linux/trace_recursion.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/livepatch/patch.c (ffffffff811e5392)
Location: include/linux/trace_recursion.h:156
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/trace/ftrace.c (ffffffff81283c66)
Location: include/linux/trace_recursion.h:156
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff812acf6a)
Location: include/linux/trace_recursion.h:156
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c5582)
Location: include/linux/trace_recursion.h:156
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/fprobe.c (ffffffff812fbdf6)
Location: include/linux/trace_recursion.h:156
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff80001020f588)
Location: kernel/trace/trace.h:639
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_no_ops
```
```
In kernel/trace/trace_functions.c (ffff8000102301fc)
Location: kernel/trace/trace.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c044e950)
Location: kernel/trace/trace.h:639
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (c046b544)
Location: kernel/trace/trace.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c00000000028e418)
Location: kernel/trace/trace.h:639
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (c0000000002b933c)
Location: kernel/trace/trace.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe0001702d8)
Location: kernel/trace/trace.h:639
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffe000187900)
Location: kernel/trace/trace.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118f76f)
Location: kernel/trace/trace.h:639
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff811aa115)
Location: kernel/trace/trace.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811828af)
Location: kernel/trace/trace.h:639
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff8119d095)
Location: kernel/trace/trace.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118d53f)
Location: kernel/trace/trace.h:639
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff811a7ee5)
Location: kernel/trace/trace.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119b0bd)
Location: kernel/trace/trace.h:639
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
```
In kernel/trace/trace_functions.c (ffffffff811b5c8c)
Location: kernel/trace/trace.h:639
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
```
</details>
</li>
</ul>

## Differences
