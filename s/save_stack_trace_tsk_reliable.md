# Function: <code>save_stack_trace_tsk_reliable</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int save_stack_trace_tsk_reliable(struct task_struct *tsk, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff810fa9a0)
Location: kernel/stacktrace.c:74
Inline: False
```
**Symbols:**

```
ffffffff810fa9a0-ffffffff810fa9d4: save_stack_trace_tsk_reliable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int save_stack_trace_tsk_reliable(struct task_struct *tsk, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103e8f0)
Location: arch/x86/kernel/stacktrace.c:162
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
```
**Symbols:**

```
ffffffff8103e8f0-ffffffff8103eaa5: save_stack_trace_tsk_reliable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int save_stack_trace_tsk_reliable(struct task_struct *tsk, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103feb0)
Location: arch/x86/kernel/stacktrace.c:162
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
```
**Symbols:**

```
ffffffff8103feb0-ffffffff81040079: save_stack_trace_tsk_reliable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int save_stack_trace_tsk_reliable(struct task_struct *tsk, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff810414e0)
Location: arch/x86/kernel/stacktrace.c:148
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
```
**Symbols:**

```
ffffffff810414e0-ffffffff81041636: save_stack_trace_tsk_reliable (STB_GLOBAL)
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int save_stack_trace_tsk_reliable(struct task_struct *tsk, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/stacktrace.c (c0000000000696f0)
Location: arch/powerpc/kernel/stacktrace.c:205
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
```
**Symbols:**

```
c0000000000696f0-c0000000000699c8: save_stack_trace_tsk_reliable (STB_GLOBAL)
```
</details>
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
