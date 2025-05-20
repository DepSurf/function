# Function: <code>__save_stack_trace</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void __save_stack_trace(struct stack_trace *trace, struct task_struct *task, struct pt_regs *regs, bool nosched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103dc60)
Location: arch/x86/kernel/stacktrace.c:31
Inline: False
Direct callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
  - arch/x86/kernel/stacktrace.c:save_stack_trace_regs
  - arch/x86/kernel/stacktrace.c:save_stack_trace
```
**Symbols:**

```
ffffffff8103dc60-ffffffff8103dd52: __save_stack_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __save_stack_trace(struct stack_trace *trace, struct task_struct *task, struct pt_regs *regs, bool nosched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103bcf0)
Location: arch/x86/kernel/stacktrace.c:33
Inline: False
Direct callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_regs
  - arch/x86/kernel/stacktrace.c:save_stack_trace
```
**Symbols:**

```
ffffffff8103bcf0-ffffffff8103bde1: __save_stack_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __save_stack_trace(struct stack_trace *trace, struct task_struct *task, struct pt_regs *regs, bool nosched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103e710)
Location: arch/x86/kernel/stacktrace.c:33
Inline: False
Direct callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
  - arch/x86/kernel/stacktrace.c:save_stack_trace_regs
  - arch/x86/kernel/stacktrace.c:save_stack_trace
```
**Symbols:**

```
ffffffff8103e710-ffffffff8103e801: __save_stack_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __save_stack_trace(struct stack_trace *trace, struct task_struct *task, struct pt_regs *regs, bool nosched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103fcd0)
Location: arch/x86/kernel/stacktrace.c:33
Inline: False
Direct callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
  - arch/x86/kernel/stacktrace.c:save_stack_trace_regs
  - arch/x86/kernel/stacktrace.c:save_stack_trace
```
**Symbols:**

```
ffffffff8103fcd0-ffffffff8103fdc2: __save_stack_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __save_stack_trace(struct stack_trace *trace, struct task_struct *task, struct pt_regs *regs, bool nosched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff810412f0)
Location: arch/x86/kernel/stacktrace.c:33
Inline: False
Direct callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
  - arch/x86/kernel/stacktrace.c:save_stack_trace_regs
  - arch/x86/kernel/stacktrace.c:save_stack_trace
```
**Symbols:**

```
ffffffff810412f0-ffffffff810413f1: __save_stack_trace (STB_LOCAL)
```
</details>
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
void __save_stack_trace(struct task_struct *tsk, struct stack_trace *trace, unsigned int nosched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/stacktrace.c (ffff800010093ba0)
Location: arch/arm64/kernel/stacktrace.c:171
Inline: False
Direct callers:
  - arch/arm64/kernel/stacktrace.c:save_stack_trace
  - arch/arm64/kernel/stacktrace.c:save_stack_trace_tsk
```
**Symbols:**

```
ffff800010093ba0-ffff800010093c84: __save_stack_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __save_stack_trace(struct task_struct *tsk, struct stack_trace *trace, unsigned int nosched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/stacktrace.c (c030eeb4)
Location: arch/arm/kernel/stacktrace.c:102
Inline: False
Direct callers:
  - arch/arm/kernel/stacktrace.c:save_stack_trace
  - arch/arm/kernel/stacktrace.c:save_stack_trace_tsk
```
**Symbols:**

```
c030eeb4-c030ef60: __save_stack_trace (STB_LOCAL)
```
</details>
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
