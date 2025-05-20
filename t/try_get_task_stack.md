# Function: <code>try_get_task_stack</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103821e)
Location: include/linux/sched.h:3234
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103dd85)
Location: include/linux/sched.h:3234
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
```
```
In kernel/sched/core.c (ffffffff810b7039)
Location: include/linux/sched.h:3234
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_show_task
```
```
In lib/syscall.c (ffffffff81479f70)
Location: include/linux/sched.h:3234
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/process.c (ffffffff81036397)
Location: include/linux/sched/task_stack.h:61
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103be15)
Location: include/linux/sched/task_stack.h:61
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b3369)
Location: include/linux/sched/task_stack.h:61
Inline: True
```
```
In lib/syscall.c (ffffffff81483280)
Location: include/linux/sched/task_stack.h:61
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/process.c (ffffffff81038727)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103e911)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
```
```
In kernel/sched/core.c (ffffffff810b3a5d)
Location: include/linux/sched/task_stack.h:62
Inline: True
```
```
In fs/proc/array.c (ffffffff812f4924)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (ffffffff814bf2c0)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/process.c (ffffffff81039bd7)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103fed1)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
```
```
In kernel/sched/core.c (ffffffff810bac95)
Location: include/linux/sched/task_stack.h:62
Inline: True
```
```
In fs/proc/array.c (ffffffff81321f8d)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (ffffffff814f0320)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/process.c (ffffffff8103b132)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810414ff)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
```
```
In kernel/sched/core.c (ffffffff810c4115)
Location: include/linux/sched/task_stack.h:62
Inline: True
```
```
In fs/proc/array.c (ffffffff8133909d)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (ffffffff81504240)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/process.c (ffffffff8103d715)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/sched/core.c (ffffffff810c9f08)
Location: include/linux/sched/task_stack.h:62
Inline: True
```
```
In kernel/stacktrace.c (ffffffff81126060)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In fs/proc/array.c (ffffffff81361743)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (ffffffff815323a0)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/process.c (ffffffff8103ded5)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/sched/core.c (ffffffff810d3118)
Location: include/linux/sched/task_stack.h:62
Inline: True
```
```
In kernel/stacktrace.c (ffffffff81132030)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In fs/proc/array.c (ffffffff813799a3)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (ffffffff815531e0)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/process.c (ffffffff81040f95)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/sched/core.c (ffffffff810dcda5)
Location: include/linux/sched/task_stack.h:62
Inline: True
```
```
In kernel/stacktrace.c (ffffffff81141468)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In fs/proc/array.c (ffffffff813c2a54)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (ffffffff815dc5b0)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/process.c (ffffffff81040ef5)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/sched/core.c (ffffffff810d9625)
Location: include/linux/sched/task_stack.h:62
Inline: True
```
```
In kernel/stacktrace.c (ffffffff8113d708)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In fs/proc/array.c (ffffffff813d4be2)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (ffffffff815fa230)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/process.c (ffffffff810428f5)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/sched/core.c (ffffffff810daee5)
Location: include/linux/sched/task_stack.h:62
Inline: True
```
```
In kernel/stacktrace.c (ffffffff8113e958)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/bpf/stackmap.c (ffffffff81237c81)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In fs/proc/array.c (ffffffff813dba1e)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (ffffffff815dce10)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/process.c (ffffffff81048c63)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/sched/core.c (ffffffff810eebd5)
Location: include/linux/sched/task_stack.h:66
Inline: True
```
```
In kernel/stacktrace.c (ffffffff81161de8)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/bpf/stackmap.c (ffffffff81272255)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In fs/proc/array.c (ffffffff8142d0b8)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (ffffffff81648770)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/process.c (ffffffff81051f6c)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In kernel/sched/core.c (ffffffff8110ba45)
Location: include/linux/sched/task_stack.h:66
Inline: True
```
```
In kernel/stacktrace.c (ffffffff81194cef)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/bpf/stackmap.c (ffffffff812c157a)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In fs/proc/array.c (ffffffff814a6a6d)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (ffffffff8175eba0)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/process.c (ffffffff8105f79c)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In kernel/sched/core.c (ffffffff81131e15)
Location: include/linux/sched/task_stack.h:66
Inline: True
```
```
In kernel/stacktrace.c (ffffffff811d29ef)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/bpf/stackmap.c (ffffffff81324e7a)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In fs/proc/array.c (ffffffff8153c0ad)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (ffffffff8188c4c0)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/process.c (ffffffff81060efc)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In kernel/sched/core.c (ffffffff81140095)
Location: include/linux/sched/task_stack.h:66
Inline: True
```
```
In kernel/stacktrace.c (ffffffff811e6cdf)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/bpf/stackmap.c (ffffffff813550da)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In fs/proc/array.c (ffffffff815743d8)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (ffffffff818ce930)
Location: include/linux/sched/task_stack.h:66
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/process.c (ffffffff81067fac)
Location: include/linux/sched/task_stack.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In kernel/sched/core.c (ffffffff8114aff5)
Location: include/linux/sched/task_stack.h:67
Inline: True
```
```
In kernel/stacktrace.c (ffffffff811fca2f)
Location: include/linux/sched/task_stack.h:67
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/bpf/stackmap.c (ffffffff8137daaa)
Location: include/linux/sched/task_stack.h:67
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In fs/proc/array.c (ffffffff815ace64)
Location: include/linux/sched/task_stack.h:67
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (ffffffff81920710)
Location: include/linux/sched/task_stack.h:67
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/arm64/kernel/process.c (ffff800010089634)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:get_wchan
```
```
In arch/arm64/kernel/stacktrace.c (ffff800010093bd4)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/arm64/kernel/stacktrace.c:__save_stack_trace
```
```
In arch/arm64/kernel/traps.c (ffff800010094244)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:dump_backtrace
```
```
In kernel/sched/core.c (ffff8000101334c0)
Location: include/linux/sched/task_stack.h:62
Inline: True
```
```
In fs/proc/array.c (ffff800010445ca0)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (ffff80001065f518)
Location: include/linux/sched/task_stack.h:62
Inline: True
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
In kernel/sched/core.c (c038e6d0)
Location: include/linux/sched/task_stack.h:70
Inline: True
Inline callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
```
```
In fs/proc/array.c (c060adfc)
Location: include/linux/sched/task_stack.h:70
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (c080863c)
Location: include/linux/sched/task_stack.h:70
Inline: True
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
In arch/powerpc/kernel/process.c (c000000000022ab4)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:show_stack
  - arch/powerpc/kernel/process.c:get_wchan
```
```
In arch/powerpc/kernel/stacktrace.c (c00000000006971c)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/powerpc/kernel/stacktrace.c:save_stack_trace_tsk_reliable
```
```
In kernel/sched/core.c (c00000000017e458)
Location: include/linux/sched/task_stack.h:62
Inline: True
```
```
In fs/proc/array.c (c00000000055adb4)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (c0000000008120b4)
Location: include/linux/sched/task_stack.h:62
Inline: True
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
In kernel/sched/core.c (ffffffe0000e61ac)
Location: include/linux/sched/task_stack.h:62
Inline: True
```
```
In fs/proc/array.c (ffffffe0002db38a)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (ffffffe00048c546)
Location: include/linux/sched/task_stack.h:62
Inline: True
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
In arch/x86/kernel/process.c (ffffffff8103e055)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/sched/core.c (ffffffff810cd438)
Location: include/linux/sched/task_stack.h:62
Inline: True
```
```
In kernel/stacktrace.c (ffffffff8112a7e0)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In fs/proc/array.c (ffffffff81371f83)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (ffffffff8154b7c0)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/process.c (ffffffff8102d865)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/sched/core.c (ffffffff810bbc98)
Location: include/linux/sched/task_stack.h:62
Inline: True
```
```
In kernel/stacktrace.c (ffffffff8111d050)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In fs/proc/array.c (ffffffff81362a5c)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (ffffffff8153baa0)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/process.c (ffffffff8103de95)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/sched/core.c (ffffffff810cc918)
Location: include/linux/sched/task_stack.h:62
Inline: True
```
```
In kernel/stacktrace.c (ffffffff81128500)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In fs/proc/array.c (ffffffff8136fa53)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (ffffffff81547500)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
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
In arch/x86/kernel/process.c (ffffffff8103eff5)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/sched/core.c (ffffffff810d52aa)
Location: include/linux/sched/task_stack.h:62
Inline: True
```
```
In kernel/stacktrace.c (ffffffff81134b90)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In fs/proc/array.c (ffffffff813833e3)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (ffffffff81561350)
Location: include/linux/sched/task_stack.h:62
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
</details>
</li>
</ul>

## Differences
