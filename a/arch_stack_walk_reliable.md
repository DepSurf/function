# Function: <code>arch_stack_walk_reliable</code>

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
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81043a60)
Location: arch/x86/kernel/stacktrace.c:38
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
```
**Symbols:**

```
ffffffff81043a60-ffffffff81043b3c: arch_stack_walk_reliable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff810441b0)
Location: arch/x86/kernel/stacktrace.c:38
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
```
**Symbols:**

```
ffffffff810441b0-ffffffff8104428c: arch_stack_walk_reliable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81047ed0)
Location: arch/x86/kernel/stacktrace.c:38
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
```
**Symbols:**

```
ffffffff81047ed0-ffffffff81047f9b: arch_stack_walk_reliable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81047380)
Location: arch/x86/kernel/stacktrace.c:38
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
```
**Symbols:**

```
ffffffff81047380-ffffffff81047449: arch_stack_walk_reliable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81048c80)
Location: arch/x86/kernel/stacktrace.c:32
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
```
**Symbols:**

```
ffffffff81048c80-ffffffff81048d49: arch_stack_walk_reliable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/kernel/stacktrace.c:32
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
```
**Symbols:**

```
ffffffff81c9a87f-ffffffff81c9a8a7: arch_stack_walk_reliable.cold (STB_LOCAL)
ffffffff8104f650-ffffffff8104f739: arch_stack_walk_reliable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/kernel/stacktrace.c:32
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
```
**Symbols:**

```
ffffffff81e49cff-ffffffff81e49d28: arch_stack_walk_reliable.cold (STB_LOCAL)
ffffffff8105a940-ffffffff8105aa55: arch_stack_walk_reliable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/kernel/stacktrace.c:32
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
```
**Symbols:**

```
ffffffff8205272e-ffffffff82052757: arch_stack_walk_reliable.cold (STB_LOCAL)
ffffffff81068700-ffffffff81068815: arch_stack_walk_reliable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/kernel/stacktrace.c:32
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
```
**Symbols:**

```
ffffffff820d0bfb-ffffffff820d0c24: arch_stack_walk_reliable.cold (STB_LOCAL)
ffffffff8106a020-ffffffff8106a135: arch_stack_walk_reliable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/stacktrace.c (0)
Location: arch/x86/kernel/stacktrace.c:32
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
```
**Symbols:**

```
ffffffff821ab724-ffffffff821ab74d: arch_stack_walk_reliable.cold (STB_LOCAL)
ffffffff810714f0-ffffffff81071605: arch_stack_walk_reliable (STB_GLOBAL)
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
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81044330)
Location: arch/x86/kernel/stacktrace.c:38
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
```
**Symbols:**

```
ffffffff81044330-ffffffff8104440c: arch_stack_walk_reliable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81033950)
Location: arch/x86/kernel/stacktrace.c:38
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
```
**Symbols:**

```
ffffffff81033950-ffffffff81033a2c: arch_stack_walk_reliable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81044170)
Location: arch/x86/kernel/stacktrace.c:38
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
```
**Symbols:**

```
ffffffff81044170-ffffffff8104424c: arch_stack_walk_reliable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int arch_stack_walk_reliable(stack_trace_consume_fn consume_entry, void *cookie, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81045570)
Location: arch/x86/kernel/stacktrace.c:38
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
```
**Symbols:**

```
ffffffff81045570-ffffffff8104564c: arch_stack_walk_reliable (STB_GLOBAL)
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
