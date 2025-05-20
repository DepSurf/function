# Function: <code>end_of_stack</code>

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
In arch/x86/mm/fault.c (0)
Location: include/linux/sched.h:2815
Inline: True
```
```
In kernel/fork.c (ffffffff8107e335)
Location: include/linux/sched.h:2815
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:2815
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/sched.h:2815
Inline: True
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
In arch/x86/mm/fault.c (0)
Location: include/linux/sched.h:3084
Inline: True
```
```
In kernel/fork.c (ffffffff8107ffd5)
Location: include/linux/sched.h:3084
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:3084
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/sched.h:3084
Inline: True
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
In arch/x86/mm/fault.c (0)
Location: include/linux/sched.h:3197
Inline: True
```
```
In kernel/fork.c (ffffffff81084925)
Location: include/linux/sched.h:3197
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched.h:3197
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/sched.h:3197
Inline: True
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
In arch/x86/mm/fault.c (0)
Location: include/linux/sched/task_stack.h:25
Inline: True
```
```
In kernel/fork.c (ffffffff81081805)
Location: include/linux/sched/task_stack.h:25
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched/task_stack.h:25
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/sched/task_stack.h:25
Inline: True
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
In arch/x86/mm/fault.c (0)
Location: include/linux/sched/task_stack.h:26
Inline: True
```
```
In kernel/fork.c (ffffffff810880e5)
Location: include/linux/sched/task_stack.h:26
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched/task_stack.h:26
Inline: True
```
```
In kernel/trace/trace_stack.c (0)
Location: include/linux/sched/task_stack.h:26
Inline: True
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
In arch/x86/mm/fault.c (ffffffff81075856)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/fork.c (ffffffff8108be35)
Location: include/linux/sched/task_stack.h:26
Inline: True
```
```
In kernel/sched/core.c (ffffffff819ec40f)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_stack.c (ffffffff8118d572)
Location: include/linux/sched/task_stack.h:26
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
In arch/x86/mm/fault.c (ffffffff8107b660)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/fork.c (ffffffff81093755)
Location: include/linux/sched/task_stack.h:26
Inline: True
```
```
In kernel/sched/core.c (ffffffff81a2765f)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_stack.c (ffffffff8119aef0)
Location: include/linux/sched/task_stack.h:26
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
In arch/x86/mm/fault.c (ffffffff8107f183)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/fork.c (ffffffff81098447)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (ffffffff81a97f24)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_stack.c (ffffffff811a8a47)
Location: include/linux/sched/task_stack.h:26
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
In arch/x86/mm/fault.c (ffffffff81080213)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/fork.c (ffffffff8109ea21)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (ffffffff81acf7f8)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_stack.c (ffffffff811b4267)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
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
In arch/x86/mm/fault.c (ffffffff810873bd)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/fork.c (ffffffff810a5ad3)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/sched/core.c (ffffffff81bc82b4)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_stack.c (ffffffff811cca7b)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/mm/fault.c (ffffffff81087a61)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/fork.c (ffffffff810a13bf)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/sched/core.c (ffffffff81c40fea)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_stack.c (ffffffff811c9fbb)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/mm/fault.c (ffffffff810885ba)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
```
In kernel/fork.c (ffffffff810a212e)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/sched/core.c (ffffffff81c32f4a)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_stack.c (ffffffff811cb37a)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/mm/fault.c (ffffffff810979c4)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
```
In kernel/fork.c (ffffffff810b2f1e)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/sched/core.c (ffffffff81d51975)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_stack.c (ffffffff811f76dc)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/mm/fault.c (ffffffff810aa531)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
```
In kernel/fork.c (ffffffff810c91eb)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/sched/core.c (ffffffff81f21e94)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_stack.c (ffffffff8123122b)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/mm/fault.c (ffffffff810c3f2a)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
```
In kernel/fork.c (ffffffff810e66db)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/sched/core.c (ffffffff820cc6e4)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_stack.c (ffffffff8127d69b)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/mm/fault.c (ffffffff810c776a)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
```
In kernel/fork.c (ffffffff810f204b)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/sched/core.c (ffffffff82150994)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_stack.c (ffffffff8129a12b)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In arch/x86/mm/fault.c (ffffffff810cfc3a)
Location: include/linux/sched/task_stack.h:27
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
```
In kernel/fork.c (ffffffff810fbc8e)
Location: include/linux/sched/task_stack.h:27
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/sched/core.c (ffffffff8114b180)
Location: include/linux/sched/task_stack.h:27
Inline: True
```
```
In kernel/trace/trace_stack.c (ffffffff812b57ab)
Location: include/linux/sched/task_stack.h:27
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:check_stack
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
In kernel/fork.c (ffff8000100f3118)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/sched/core.c (ffff800010da1488)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_stack.c (ffff8000102326a4)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
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
In arch/arm/kernel/traps.c (c030f538)
Location: include/linux/sched/task_stack.h:50
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:die
  - arch/arm/kernel/traps.c:dump_backtrace
```
```
In kernel/fork.c (c0351dc8)
Location: include/linux/sched/task_stack.h:50
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (c0e994a0)
Location: include/linux/sched/task_stack.h:50
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_stack.c (c046e330)
Location: include/linux/sched/task_stack.h:50
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
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
In arch/powerpc/kernel/process.c (0)
Location: include/linux/sched/task_stack.h:26
Inline: True
```
```
In arch/powerpc/kernel/setup-common.c (c00000000134a9a0)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:setup_arch
```
```
In arch/powerpc/mm/fault.c (c000000000086fb0)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - arch/powerpc/mm/fault.c:bad_page_fault
```
```
In kernel/fork.c (c0000000001393f4)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (c000000000ee24d8)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_stack.c (c0000000002bcfd0)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
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
In kernel/fork.c (ffffffe0000bfdf0)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (ffffffe0008c4d3e)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_stack.c (ffffffe000189d26)
Location: include/linux/sched/task_stack.h:26
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
In arch/x86/mm/fault.c (ffffffff8107f213)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/fork.c (ffffffff81098341)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (ffffffff81a6e668)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_stack.c (ffffffff811ac887)
Location: include/linux/sched/task_stack.h:26
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
In arch/x86/mm/fault.c (ffffffff8106e1f6)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/fork.c (ffffffff81086d87)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (ffffffff81a2aa6b)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_stack.c (ffffffff8119f5be)
Location: include/linux/sched/task_stack.h:26
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
In arch/x86/mm/fault.c (ffffffff8107f1c3)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/fork.c (ffffffff810982f1)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (ffffffff81adaa78)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_stack.c (ffffffff811aa657)
Location: include/linux/sched/task_stack.h:26
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
In arch/x86/mm/fault.c (ffffffff810812b3)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In kernel/fork.c (ffffffff8109fee8)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (ffffffff81ae6f27)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_stack.c (ffffffff811b84b9)
Location: include/linux/sched/task_stack.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
</details>
</li>
</ul>

## Differences
