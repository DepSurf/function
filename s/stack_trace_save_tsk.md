# Function: <code>stack_trace_save_tsk</code>

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
unsigned int stack_trace_save_tsk(struct task_struct *tsk, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81125f00)
Location: kernel/stacktrace.c:137
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff81125f00-ffffffff81125faa: stack_trace_save_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int stack_trace_save_tsk(struct task_struct *tsk, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81131ec0)
Location: kernel/stacktrace.c:137
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff81131ec0-ffffffff81131f7e: stack_trace_save_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int stack_trace_save_tsk(struct task_struct *tsk, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811412f0)
Location: kernel/stacktrace.c:137
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff811412f0-ffffffff811413b0: stack_trace_save_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int stack_trace_save_tsk(struct task_struct *tsk, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8113d590)
Location: kernel/stacktrace.c:135
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff8113d590-ffffffff8113d650: stack_trace_save_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int stack_trace_save_tsk(struct task_struct *tsk, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8113e7e0)
Location: kernel/stacktrace.c:135
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff8113e7e0-ffffffff8113e89c: stack_trace_save_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int stack_trace_save_tsk(struct task_struct *tsk, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81161c70)
Location: kernel/stacktrace.c:135
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff81161c70-ffffffff81161d2c: stack_trace_save_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int stack_trace_save_tsk(struct task_struct *tsk, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81194b70)
Location: kernel/stacktrace.c:136
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff81194b70-ffffffff81194c38: stack_trace_save_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int stack_trace_save_tsk(struct task_struct *tsk, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811d2850)
Location: kernel/stacktrace.c:136
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff811d2850-ffffffff811d2918: stack_trace_save_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int stack_trace_save_tsk(struct task_struct *tsk, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811e6b40)
Location: kernel/stacktrace.c:136
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff811e6b40-ffffffff811e6c04: stack_trace_save_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int stack_trace_save_tsk(struct task_struct *tsk, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811fc800)
Location: kernel/stacktrace.c:136
Inline: False
Direct callers:
  - kernel/latencytop.c:__account_scheduler_latency
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff811fc800-ffffffff811fc8c4: stack_trace_save_tsk (STB_GLOBAL)
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
unsigned int stack_trace_save_tsk(struct task_struct *task, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffff800010199a18)
Location: kernel/stacktrace.c:295
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffff800010199a18-ffff800010199aa8: stack_trace_save_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int stack_trace_save_tsk(struct task_struct *task, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (c03e443c)
Location: kernel/stacktrace.c:295
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
c03e443c-c03e44c4: stack_trace_save_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int stack_trace_save_tsk(struct task_struct *task, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (c0000000001f9ca0)
Location: kernel/stacktrace.c:295
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
c0000000001f9ca0-c0000000001f9d34: stack_trace_save_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int stack_trace_save_tsk(struct task_struct *task, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffe000129fb8)
Location: kernel/stacktrace.c:295
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffe000129fb8-ffffffe00012a01c: stack_trace_save_tsk (STB_GLOBAL)
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
unsigned int stack_trace_save_tsk(struct task_struct *tsk, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8112a670)
Location: kernel/stacktrace.c:137
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff8112a670-ffffffff8112a72e: stack_trace_save_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int stack_trace_save_tsk(struct task_struct *tsk, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8111cee0)
Location: kernel/stacktrace.c:137
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff8111cee0-ffffffff8111cf9e: stack_trace_save_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int stack_trace_save_tsk(struct task_struct *tsk, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81128390)
Location: kernel/stacktrace.c:137
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff81128390-ffffffff8112844e: stack_trace_save_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int stack_trace_save_tsk(struct task_struct *tsk, long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81134a20)
Location: kernel/stacktrace.c:137
Inline: False
Direct callers:
  - kernel/latencytop.c:__account_scheduler_latency
  - fs/proc/base.c:proc_pid_stack
```
**Symbols:**

```
ffffffff81134a20-ffffffff81134ade: stack_trace_save_tsk (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *task</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *task</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *task</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *task</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
</ul>
</details>
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
