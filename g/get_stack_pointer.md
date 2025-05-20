# Function: <code>get_stack_pointer</code>

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
In arch/x86/events/core.c (ffffffff810077e8)
Location: arch/x86/include/asm/stacktrace.h:72
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81030db9)
Location: arch/x86/include/asm/stacktrace.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103dca8)
Location: arch/x86/include/asm/stacktrace.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
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
In arch/x86/events/core.c (ffffffff8100756b)
Location: arch/x86/include/asm/stacktrace.h:72
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8102f0c2)
Location: arch/x86/include/asm/stacktrace.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103bd38)
Location: arch/x86/include/asm/stacktrace.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
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
In arch/x86/events/core.c (ffffffff810079a1)
Location: arch/x86/include/asm/stacktrace.h:76
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810310c2)
Location: arch/x86/include/asm/stacktrace.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103e948)
Location: arch/x86/include/asm/stacktrace.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
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
In arch/x86/events/core.c (ffffffff81007fd1)
Location: arch/x86/include/asm/stacktrace.h:76
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810322dd)
Location: arch/x86/include/asm/stacktrace.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103ff08)
Location: arch/x86/include/asm/stacktrace.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
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
In arch/x86/events/core.c (ffffffff81007eb1)
Location: arch/x86/include/asm/stacktrace.h:76
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810335a2)
Location: arch/x86/include/asm/stacktrace.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81041536)
Location: arch/x86/include/asm/stacktrace.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
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
In arch/x86/events/core.c (ffffffff81008201)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81034f14)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81043a8d)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
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
In arch/x86/events/core.c (ffffffff81008421)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81035744)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810441dd)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100948f)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81037d30)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81047efb)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff8103789b-ffffffff810378ba: get_stack_pointer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100853f)
Location: arch/x86/include/asm/stacktrace.h:80
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81bd38f5)
Location: arch/x86/include/asm/stacktrace.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810473ab)
Location: arch/x86/include/asm/stacktrace.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff81bd3477-ffffffff81bd3496: get_stack_pointer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008f0f)
Location: arch/x86/include/asm/stacktrace.h:80
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81bc5d67)
Location: arch/x86/include/asm/stacktrace.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81048cab)
Location: arch/x86/include/asm/stacktrace.h:80
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff81bc58ea-ffffffff81bc5909: get_stack_pointer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81009dc7)
Location: arch/x86/include/asm/stacktrace.h:90
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81c98ab1)
Location: arch/x86/include/asm/stacktrace.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8104f67d)
Location: arch/x86/include/asm/stacktrace.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff81c98634-ffffffff81c98653: get_stack_pointer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100949a)
Location: arch/x86/include/asm/stacktrace.h:90
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81e4804d)
Location: arch/x86/include/asm/stacktrace.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff81051fa1)
Location: arch/x86/include/asm/stacktrace.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8105a97e)
Location: arch/x86/include/asm/stacktrace.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff81e47b57-ffffffff81e47b82: get_stack_pointer.part.0 (STB_LOCAL)
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
In arch/x86/events/core.c (ffffffff8100a92a)
Location: arch/x86/include/asm/stacktrace.h:90
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81051b7a)
Location: arch/x86/include/asm/stacktrace.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff8105f7d1)
Location: arch/x86/include/asm/stacktrace.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8106873e)
Location: arch/x86/include/asm/stacktrace.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
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
In arch/x86/events/core.c (ffffffff8100a17a)
Location: arch/x86/include/asm/stacktrace.h:90
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810528ba)
Location: arch/x86/include/asm/stacktrace.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff81060f29)
Location: arch/x86/include/asm/stacktrace.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8106a05e)
Location: arch/x86/include/asm/stacktrace.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
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
In arch/x86/events/core.c (ffffffff8100f89a)
Location: arch/x86/include/asm/stacktrace.h:90
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81059ada)
Location: arch/x86/include/asm/stacktrace.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff81067fd9)
Location: arch/x86/include/asm/stacktrace.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8107152e)
Location: arch/x86/include/asm/stacktrace.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008421)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810358a4)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8104435d)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
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
In arch/x86/events/core.c (ffffffff81006c11)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810251f4)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103397d)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
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
In arch/x86/events/core.c (ffffffff810083e1)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81035704)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8104419d)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
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
In arch/x86/events/core.c (ffffffff81008541)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810366e4)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8104559d)
Location: arch/x86/include/asm/stacktrace.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
</details>
</li>
</ul>

## Differences
