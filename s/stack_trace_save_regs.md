# Function: <code>stack_trace_save_regs</code>

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
unsigned int stack_trace_save_regs(struct pt_regs *regs, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81125fb0)
Location: kernel/stacktrace.c:164
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
ffffffff81125fb0-ffffffff81126013: stack_trace_save_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int stack_trace_save_regs(struct pt_regs *regs, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81131f80)
Location: kernel/stacktrace.c:165
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
ffffffff81131f80-ffffffff81131fe3: stack_trace_save_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int stack_trace_save_regs(struct pt_regs *regs, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811413b0)
Location: kernel/stacktrace.c:165
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
ffffffff811413b0-ffffffff81141413: stack_trace_save_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int stack_trace_save_regs(struct pt_regs *regs, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8113d650)
Location: kernel/stacktrace.c:163
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
ffffffff8113d650-ffffffff8113d6b3: stack_trace_save_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int stack_trace_save_regs(struct pt_regs *regs, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8113e8a0)
Location: kernel/stacktrace.c:163
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
ffffffff8113e8a0-ffffffff8113e903: stack_trace_save_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int stack_trace_save_regs(struct pt_regs *regs, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81161d30)
Location: kernel/stacktrace.c:163
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - mm/kfence/report.c:kfence_report_error
```
**Symbols:**

```
ffffffff81161d30-ffffffff81161d93: stack_trace_save_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int stack_trace_save_regs(struct pt_regs *regs, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81194c40)
Location: kernel/stacktrace.c:164
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - mm/kfence/report.c:kfence_report_error
```
**Symbols:**

```
ffffffff81194c40-ffffffff81194caf: stack_trace_save_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int stack_trace_save_regs(struct pt_regs *regs, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811d2930)
Location: kernel/stacktrace.c:164
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - mm/kfence/report.c:kfence_report_error
```
**Symbols:**

```
ffffffff811d2930-ffffffff811d299f: stack_trace_save_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int stack_trace_save_regs(struct pt_regs *regs, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811e6c20)
Location: kernel/stacktrace.c:164
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - mm/kfence/report.c:kfence_report_error
```
**Symbols:**

```
ffffffff811e6c20-ffffffff811e6c8f: stack_trace_save_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int stack_trace_save_regs(struct pt_regs *regs, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811fc970)
Location: kernel/stacktrace.c:165
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - mm/kfence/report.c:kfence_report_error
```
**Symbols:**

```
ffffffff811fc970-ffffffff811fc9df: stack_trace_save_regs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
unsigned int stack_trace_save_regs(struct pt_regs *regs, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffff800010199aa8)
Location: kernel/stacktrace.c:319
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
ffff800010199aa8-ffff800010199b2c: stack_trace_save_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int stack_trace_save_regs(struct pt_regs *regs, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (c03e44c4)
Location: kernel/stacktrace.c:319
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
c03e44c4-c03e4538: stack_trace_save_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int stack_trace_save_regs(struct pt_regs *regs, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (c0000000001f9d40)
Location: kernel/stacktrace.c:319
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
c0000000001f9d40-c0000000001f9dc0: stack_trace_save_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int stack_trace_save_regs(struct pt_regs *regs, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffe00012a01c)
Location: kernel/stacktrace.c:319
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
ffffffe00012a01c-ffffffe00012a074: stack_trace_save_regs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
unsigned int stack_trace_save_regs(struct pt_regs *regs, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8112a730)
Location: kernel/stacktrace.c:165
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
ffffffff8112a730-ffffffff8112a793: stack_trace_save_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int stack_trace_save_regs(struct pt_regs *regs, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8111cfa0)
Location: kernel/stacktrace.c:165
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
ffffffff8111cfa0-ffffffff8111d003: stack_trace_save_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int stack_trace_save_regs(struct pt_regs *regs, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81128450)
Location: kernel/stacktrace.c:165
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
ffffffff81128450-ffffffff811284b3: stack_trace_save_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int stack_trace_save_regs(struct pt_regs *regs, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81134ae0)
Location: kernel/stacktrace.c:165
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
```
**Symbols:**

```
ffffffff81134ae0-ffffffff81134b43: stack_trace_save_regs (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
