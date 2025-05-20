# Function: <code>save_stack_trace_tsk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void save_stack_trace_tsk(struct task_struct *tsk, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103e560)
Location: arch/x86/kernel/stacktrace.c:76
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff8103e560-ffffffff8103e59d: save_stack_trace_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void save_stack_trace_tsk(struct task_struct *tsk, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103e3a0)
Location: arch/x86/kernel/stacktrace.c:80
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff8103e3a0-ffffffff8103e3dd: save_stack_trace_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void save_stack_trace_tsk(struct task_struct *tsk, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103dd80)
Location: arch/x86/kernel/stacktrace.c:66
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff8103dd80-ffffffff8103ddf2: save_stack_trace_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void save_stack_trace_tsk(struct task_struct *tsk, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103be10)
Location: arch/x86/kernel/stacktrace.c:68
Inline: True
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff8103be10-ffffffff8103be77: save_stack_trace_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void save_stack_trace_tsk(struct task_struct *tsk, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103e840)
Location: arch/x86/kernel/stacktrace.c:69
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff8103e840-ffffffff8103e8b4: save_stack_trace_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void save_stack_trace_tsk(struct task_struct *tsk, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103fe00)
Location: arch/x86/kernel/stacktrace.c:69
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff8103fe00-ffffffff8103fe75: save_stack_trace_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void save_stack_trace_tsk(struct task_struct *tsk, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81041430)
Location: arch/x86/kernel/stacktrace.c:69
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff81041430-ffffffff810414a5: save_stack_trace_tsk (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void save_stack_trace_tsk(struct task_struct *tsk, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/stacktrace.c (ffff800010093c88)
Location: arch/arm64/kernel/stacktrace.c:201
Inline: True
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_tsk
```
**Symbols:**

```
ffff800010093c88-ffff800010093cc0: save_stack_trace_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void save_stack_trace_tsk(struct task_struct *tsk, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/stacktrace.c (c030ef60)
Location: arch/arm/kernel/stacktrace.c:155
Inline: True
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_tsk
```
**Symbols:**

```
c030ef60-c030ef80: save_stack_trace_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void save_stack_trace_tsk(struct task_struct *tsk, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/stacktrace.c (c000000000069390)
Location: arch/powerpc/kernel/stacktrace.c:66
Inline: True
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_tsk
```
**Symbols:**

```
c000000000069390-c000000000069460: save_stack_trace_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void save_stack_trace_tsk(struct task_struct *tsk, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/stacktrace.c (ffffffe0000b72ae)
Location: arch/riscv/kernel/stacktrace.c:157
Inline: True
Inline callers:
  - arch/riscv/kernel/stacktrace.c:save_stack_trace
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_tsk
```
**Symbols:**

```
ffffffe0000b725c-ffffffe0000b7298: save_stack_trace_tsk (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
