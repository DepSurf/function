# Function: <code>walk_stackframe</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
void walk_stackframe(struct task_struct *tsk, struct stackframe *frame, int (*fn)(struct stackframe *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/stacktrace.c (ffff800010093ab8)
Location: arch/arm64/kernel/stacktrace.c:117
Inline: False
Direct callers:
  - arch/arm64/kernel/stacktrace.c:__save_stack_trace
  - arch/arm64/kernel/stacktrace.c:save_stack_trace_regs
  - arch/arm64/kernel/return_address.c:return_address
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_kernel
```
**Symbols:**

```
ffff800010093ab8-ffff800010093b0c: walk_stackframe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void walk_stackframe(struct stackframe *frame, int (*fn)(struct stackframe *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/stacktrace.c (c030ed58)
Location: arch/arm/kernel/stacktrace.c:50
Inline: False
Direct callers:
  - arch/arm/kernel/return_address.c:return_address
  - arch/arm/kernel/stacktrace.c:save_stack_trace_regs
  - arch/arm/kernel/stacktrace.c:__save_stack_trace
  - arch/arm/kernel/perf_callchain.c:perf_callchain_kernel
```
**Symbols:**

```
c030ed58-c030edd0: walk_stackframe (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void walk_stackframe(struct task_struct *task, struct pt_regs *regs, bool (*fn)(long unsigned int, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/stacktrace.c (ffffffe0000b7190)
Location: arch/riscv/kernel/stacktrace.c:22
Inline: False
Direct callers:
  - arch/riscv/kernel/stacktrace.c:save_stack_trace
  - arch/riscv/kernel/stacktrace.c:get_wchan
  - arch/riscv/kernel/stacktrace.c:show_stack
  - arch/riscv/kernel/perf_callchain.c:perf_callchain_kernel
```
**Symbols:**

```
ffffffe0000b7190-ffffffe0000b725c: walk_stackframe (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
