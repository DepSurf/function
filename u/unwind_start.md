# Function: <code>unwind_start</code>

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
Location: arch/x86/include/asm/unwind.h:35
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81030aac)
Location: arch/x86/include/asm/unwind.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103dca8)
Location: arch/x86/include/asm/unwind.h:35
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
Location: arch/x86/include/asm/unwind.h:38
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8102ed7c)
Location: arch/x86/include/asm/unwind.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103bd38)
Location: arch/x86/include/asm/unwind.h:38
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
Location: arch/x86/include/asm/unwind.h:49
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81030d5c)
Location: arch/x86/include/asm/unwind.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103e948)
Location: arch/x86/include/asm/unwind.h:49
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
Location: arch/x86/include/asm/unwind.h:49
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81032020)
Location: arch/x86/include/asm/unwind.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103ff08)
Location: arch/x86/include/asm/unwind.h:49
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
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810332e5)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81041536)
Location: arch/x86/include/asm/unwind.h:55
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
In arch/x86/events/core.c (ffffffff81008188)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103515e)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81043a8d)
Location: arch/x86/include/asm/unwind.h:55
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
In arch/x86/events/core.c (ffffffff810083a8)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103598e)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810441dd)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
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
In arch/x86/events/core.c (ffffffff81009416)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81037a25)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81047efb)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
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
In arch/x86/events/core.c (ffffffff810084c6)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81bd35e4)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff810473ab)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
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
In arch/x86/events/core.c (ffffffff81008e96)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81bc5a56)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81048cab)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
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
In arch/x86/events/core.c (ffffffff81009d3a)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81c987a0)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8104f67d)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
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
In arch/x86/events/core.c (ffffffff8100949a)
Location: arch/x86/include/asm/unwind.h:59
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81e47d03)
Location: arch/x86/include/asm/unwind.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff81051fa1)
Location: arch/x86/include/asm/unwind.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8105a97e)
Location: arch/x86/include/asm/unwind.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
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
Location: arch/x86/include/asm/unwind.h:59
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810516d1)
Location: arch/x86/include/asm/unwind.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff8105f7d1)
Location: arch/x86/include/asm/unwind.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8106873e)
Location: arch/x86/include/asm/unwind.h:59
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
Location: arch/x86/include/asm/unwind.h:59
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8105242e)
Location: arch/x86/include/asm/unwind.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff81060f29)
Location: arch/x86/include/asm/unwind.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8106a05e)
Location: arch/x86/include/asm/unwind.h:59
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
Location: arch/x86/include/asm/unwind.h:59
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8105964e)
Location: arch/x86/include/asm/unwind.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/process.c (ffffffff81067fd9)
Location: arch/x86/include/asm/unwind.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8107152e)
Location: arch/x86/include/asm/unwind.h:59
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
In arch/x86/events/core.c (ffffffff810083a8)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81035aee)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8104435d)
Location: arch/x86/include/asm/unwind.h:55
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
In arch/x86/events/core.c (ffffffff81006b98)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8102543e)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103397d)
Location: arch/x86/include/asm/unwind.h:55
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
In arch/x86/events/core.c (ffffffff81008368)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103594e)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8104419d)
Location: arch/x86/include/asm/unwind.h:55
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
In arch/x86/events/core.c (ffffffff810084c8)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/kernel/dumpstack.c (ffffffff8103692e)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8104559d)
Location: arch/x86/include/asm/unwind.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
</details>
</li>
</ul>

## Differences
