# Function: <code>arch_stack_walk</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void arch_stack_walk(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81043970)
Location: arch/x86/kernel/stacktrace.c:15
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_regs
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/stacktrace.c:stack_trace_save
```
**Symbols:**

```
ffffffff81043970-ffffffff81043a5d: arch_stack_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_stack_walk(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff810440c0)
Location: arch/x86/kernel/stacktrace.c:15
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_regs
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/stacktrace.c:stack_trace_save
```
**Symbols:**

```
ffffffff810440c0-ffffffff810441ad: arch_stack_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void arch_stack_walk(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81047de0)
Location: arch/x86/kernel/stacktrace.c:15
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_regs
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/stacktrace.c:stack_trace_save
```
**Symbols:**

```
ffffffff81047de0-ffffffff81047ecd: arch_stack_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void arch_stack_walk(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81047290)
Location: arch/x86/kernel/stacktrace.c:15
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_regs
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/stacktrace.c:stack_trace_save
```
**Symbols:**

```
ffffffff81047290-ffffffff81047379: arch_stack_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void arch_stack_walk(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81048b90)
Location: arch/x86/kernel/stacktrace.c:15
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_regs
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/stacktrace.c:stack_trace_save
```
**Symbols:**

```
ffffffff81048b90-ffffffff81048c79: arch_stack_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void arch_stack_walk(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8104f560)
Location: arch/x86/kernel/stacktrace.c:15
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_regs
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/stacktrace.c:stack_trace_save
```
**Symbols:**

```
ffffffff8104f560-ffffffff8104f649: arch_stack_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_stack_walk(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8105a830)
Location: arch/x86/kernel/stacktrace.c:15
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_regs
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/stacktrace.c:stack_trace_save
```
**Symbols:**

```
ffffffff8105a830-ffffffff8105a933: arch_stack_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_stack_walk(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff810685e0)
Location: arch/x86/kernel/stacktrace.c:15
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_regs
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/stacktrace.c:stack_trace_save
```
**Symbols:**

```
ffffffff810685e0-ffffffff810686e3: arch_stack_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_stack_walk(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81069f00)
Location: arch/x86/kernel/stacktrace.c:15
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_regs
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/stacktrace.c:stack_trace_save
```
**Symbols:**

```
ffffffff81069f00-ffffffff8106a003: arch_stack_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_stack_walk(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff810713d0)
Location: arch/x86/kernel/stacktrace.c:15
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_regs
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/stacktrace.c:stack_trace_save
```
**Symbols:**

```
ffffffff810713d0-ffffffff810714d3: arch_stack_walk (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void arch_stack_walk(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81044240)
Location: arch/x86/kernel/stacktrace.c:15
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_regs
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/stacktrace.c:stack_trace_save
```
**Symbols:**

```
ffffffff81044240-ffffffff8104432d: arch_stack_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_stack_walk(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81033860)
Location: arch/x86/kernel/stacktrace.c:15
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_regs
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/stacktrace.c:stack_trace_save
```
**Symbols:**

```
ffffffff81033860-ffffffff8103394d: arch_stack_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_stack_walk(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81044080)
Location: arch/x86/kernel/stacktrace.c:15
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_regs
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/stacktrace.c:stack_trace_save
```
**Symbols:**

```
ffffffff81044080-ffffffff8104416d: arch_stack_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_stack_walk(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81045480)
Location: arch/x86/kernel/stacktrace.c:15
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_regs
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/stacktrace.c:stack_trace_save
```
**Symbols:**

```
ffffffff81045480-ffffffff8104556d: arch_stack_walk (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
