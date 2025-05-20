# Function: <code>dump_trace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dump_trace(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, long unsigned int bp, const struct stacktrace_ops *ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff81031170)
Location: arch/x86/kernel/dumpstack_64.c:151
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace
  - arch/x86/kernel/stacktrace.c:save_stack_trace
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
  - arch/x86/kernel/stacktrace.c:save_stack_trace_regs
```
**Symbols:**

```
ffffffff81031170-ffffffff81031480: dump_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dump_trace(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, long unsigned int bp, const struct stacktrace_ops *ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff81030230)
Location: arch/x86/kernel/dumpstack_64.c:151
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
  - arch/x86/kernel/stacktrace.c:save_stack_trace_regs
  - arch/x86/kernel/stacktrace.c:save_stack_trace
```
**Symbols:**

```
ffffffff81030230-ffffffff81030546: dump_trace (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
