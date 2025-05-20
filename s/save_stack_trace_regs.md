# Function: <code>save_stack_trace_regs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void save_stack_trace_regs(struct pt_regs *regs, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103e630)
Location: arch/x86/kernel/stacktrace.c:69
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
ffffffff8103e630-ffffffff8103e67a: save_stack_trace_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void save_stack_trace_regs(struct pt_regs *regs, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103e480)
Location: arch/x86/kernel/stacktrace.c:73
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
ffffffff8103e480-ffffffff8103e4ca: save_stack_trace_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void save_stack_trace_regs(struct pt_regs *regs, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103de00)
Location: arch/x86/kernel/stacktrace.c:61
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
ffffffff8103de00-ffffffff8103de21: save_stack_trace_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void save_stack_trace_regs(struct pt_regs *regs, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103be80)
Location: arch/x86/kernel/stacktrace.c:63
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
ffffffff8103be80-ffffffff8103bea1: save_stack_trace_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void save_stack_trace_regs(struct pt_regs *regs, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103e8c0)
Location: arch/x86/kernel/stacktrace.c:64
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
ffffffff8103e8c0-ffffffff8103e8e1: save_stack_trace_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void save_stack_trace_regs(struct pt_regs *regs, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103fe80)
Location: arch/x86/kernel/stacktrace.c:64
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
ffffffff8103fe80-ffffffff8103fea1: save_stack_trace_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void save_stack_trace_regs(struct pt_regs *regs, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff810414b0)
Location: arch/x86/kernel/stacktrace.c:64
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
ffffffff810414b0-ffffffff810414d1: save_stack_trace_regs (STB_GLOBAL)
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
void save_stack_trace_regs(struct pt_regs *regs, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/stacktrace.c (ffff800010093b10)
Location: arch/arm64/kernel/stacktrace.c:157
Inline: True
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_regs
```
**Symbols:**

```
ffff800010093b10-ffff800010093b9c: save_stack_trace_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void save_stack_trace_regs(struct pt_regs *regs, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/stacktrace.c (c030f01c)
Location: arch/arm/kernel/stacktrace.c:138
Inline: True
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_regs
```
**Symbols:**

```
c030f01c-c030f0b8: save_stack_trace_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void save_stack_trace_regs(struct pt_regs *regs, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/stacktrace.c (c000000000069320)
Location: arch/powerpc/kernel/stacktrace.c:85
Inline: True
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_regs
```
**Symbols:**

```
c000000000069320-c000000000069348: save_stack_trace_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void save_stack_trace_regs(struct pt_regs *regs, struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffe000129f70)
Location: kernel/stacktrace.c:259
Inline: True
Direct callers:
  - kernel/stacktrace.c:stack_trace_save_regs
```
**Symbols:**

```
ffffffe000129f70-ffffffe000129fb8: save_stack_trace_regs (STB_WEAK)
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
