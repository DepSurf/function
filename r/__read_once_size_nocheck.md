# Function: <code>__read_once_size_nocheck</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81039846)
Location: include/linux/compiler.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
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
In arch/x86/kernel/process.c (ffffffff81038836)
Location: include/linux/compiler.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/sched/core.c (ffffffff810b0e24)
Location: include/linux/compiler.h:237
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_show_task
```
```
In kernel/trace/trace_stack.c (ffffffff81162c10)
Location: include/linux/compiler.h:237
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/kernel/dumpstack.c (ffffffff81030b34)
Location: include/linux/compiler.h:260
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff81038275)
Location: include/linux/compiler.h:260
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:thread_saved_pc
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff81069b47)
Location: include/linux/compiler.h:260
Inline: True
```
```
In kernel/trace/trace_stack.c (ffffffff8116df40)
Location: include/linux/compiler.h:260
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/kernel/dumpstack.c (ffffffff8102ee44)
Location: include/linux/compiler.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff810363e0)
Location: include/linux/compiler.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff81068d39)
Location: include/linux/compiler.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
```
In kernel/trace/trace_stack.c (ffffffff8117126d)
Location: include/linux/compiler.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/kernel/dumpstack.c (ffffffff81030e5a)
Location: include/linux/compiler.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff81038770)
Location: include/linux/compiler.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8106d5be)
Location: include/linux/compiler.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
```
In kernel/trace/trace_stack.c (ffffffff8117e41f)
Location: include/linux/compiler.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/kernel/dumpstack.c (ffffffff8103216d)
Location: include/linux/compiler.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff81039c20)
Location: include/linux/compiler.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8107094d)
Location: include/linux/compiler.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
```
In kernel/trace/trace_stack.c (ffffffff8118d4c0)
Location: include/linux/compiler.h:204
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/kernel/dumpstack.c (ffffffff81033432)
Location: include/linux/compiler.h:209
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff8103b17b)
Location: include/linux/compiler.h:209
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8107695c)
Location: include/linux/compiler.h:209
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
```
In kernel/trace/trace_stack.c (ffffffff8119ae3e)
Location: include/linux/compiler.h:209
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/kernel/dumpstack.c (ffffffff810352bc)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff8103d764)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a4f2)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
```
In kernel/trace/trace_stack.c (ffffffff811a89b1)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
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
In arch/x86/kernel/dumpstack.c (ffffffff81035aec)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff8103df24)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8107b5e4)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
```
In kernel/trace/trace_stack.c (ffffffff811b41d1)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In arch/arm64/kernel/stacktrace.c (ffff80001009393c)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - arch/arm64/kernel/stacktrace.c:unwind_frame
  - arch/arm64/kernel/stacktrace.c:unwind_frame
```
```
In kernel/trace/trace_stack.c (ffff8000102325c8)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (c046e280)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_stack.c (c0000000002bced0)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
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
In kernel/trace/trace_stack.c (ffffffe000189cea)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
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
In arch/x86/kernel/dumpstack.c (ffffffff81035c4c)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff8103e0a4)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a5e4)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
```
In kernel/trace/trace_stack.c (ffffffff811ac7f1)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
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
In arch/x86/kernel/dumpstack.c (ffffffff8102559c)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff8102d8b4)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff81069d14)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
```
In kernel/trace/trace_stack.c (ffffffff8119f529)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
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
In arch/x86/kernel/dumpstack.c (ffffffff81035aac)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff8103dee4)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a594)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
```
In kernel/trace/trace_stack.c (ffffffff811aa5c1)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
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
In arch/x86/kernel/dumpstack.c (ffffffff81036a8c)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff8103f044)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff8107c694)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_dump
```
```
In kernel/trace/trace_stack.c (ffffffff811b8419)
Location: include/linux/compiler.h:215
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
</details>
</li>
</ul>

## Differences
