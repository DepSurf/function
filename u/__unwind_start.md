# Function: <code>__unwind_start</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __unwind_start(struct unwind_state *state, struct task_struct *task, struct pt_regs *regs, long unsigned int *first_frame);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81069dd0)
Location: arch/x86/kernel/unwind_frame.c:279
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
```
**Symbols:**

```
ffffffff81069dd0-ffffffff81069eed: __unwind_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __unwind_start(struct unwind_state *state, struct task_struct *task, struct pt_regs *regs, long unsigned int *first_frame);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81069160)
Location: arch/x86/kernel/unwind_frame.c:359
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
```
**Symbols:**

```
ffffffff81069160-ffffffff81069242: __unwind_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __unwind_start(struct unwind_state *state, struct task_struct *task, struct pt_regs *regs, long unsigned int *first_frame);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8106d9e0)
Location: arch/x86/kernel/unwind_frame.c:384
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
```
**Symbols:**

```
ffffffff8106d9e0-ffffffff8106dac2: __unwind_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __unwind_start(struct unwind_state *state, struct task_struct *task, struct pt_regs *regs, long unsigned int *first_frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810707d0)
Location: arch/x86/kernel/unwind_frame.c:384
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
```
**Symbols:**

```
ffffffff810707d0-ffffffff810708b3: __unwind_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __unwind_start(struct unwind_state *state, struct task_struct *task, struct pt_regs *regs, long unsigned int *first_frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810767b0)
Location: arch/x86/kernel/unwind_frame.c:388
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
```
**Symbols:**

```
ffffffff810767b0-ffffffff810768ca: __unwind_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __unwind_start(struct unwind_state *state, struct task_struct *task, struct pt_regs *regs, long unsigned int *first_frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a350)
Location: arch/x86/kernel/unwind_frame.c:366
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff8107a350-ffffffff8107a46a: __unwind_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __unwind_start(struct unwind_state *state, struct task_struct *task, struct pt_regs *regs, long unsigned int *first_frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107b440)
Location: arch/x86/kernel/unwind_frame.c:366
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff8107b440-ffffffff8107b55a: __unwind_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __unwind_start(struct unwind_state *state, struct task_struct *task, struct pt_regs *regs, long unsigned int *first_frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81082870)
Location: arch/x86/kernel/unwind_frame.c:363
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff81082870-ffffffff81082979: __unwind_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __unwind_start(struct unwind_state *state, struct task_struct *task, struct pt_regs *regs, long unsigned int *first_frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81082320)
Location: arch/x86/kernel/unwind_frame.c:363
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff81082320-ffffffff81082429: __unwind_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __unwind_start(struct unwind_state *state, struct task_struct *task, struct pt_regs *regs, long unsigned int *first_frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81083140)
Location: arch/x86/kernel/unwind_frame.c:363
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff81083140-ffffffff81083249: __unwind_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __unwind_start(struct unwind_state *state, struct task_struct *task, struct pt_regs *regs, long unsigned int *first_frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81092240)
Location: arch/x86/kernel/unwind_frame.c:363
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff81092240-ffffffff81092349: __unwind_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __unwind_start(struct unwind_state *state, struct task_struct *task, struct pt_regs *regs, long unsigned int *first_frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810a34c0)
Location: arch/x86/kernel/unwind_frame.c:362
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/process.c:__get_wchan
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff810a34c0-ffffffff810a35db: __unwind_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __unwind_start(struct unwind_state *state, struct task_struct *task, struct pt_regs *regs, long unsigned int *first_frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810bb8e0)
Location: arch/x86/kernel/unwind_frame.c:373
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/process.c:__get_wchan
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff810bb8e0-ffffffff810bb9fb: __unwind_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __unwind_start(struct unwind_state *state, struct task_struct *task, struct pt_regs *regs, long unsigned int *first_frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810bea20)
Location: arch/x86/kernel/unwind_frame.c:373
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/process.c:__get_wchan
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff810bea20-ffffffff810beb3b: __unwind_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __unwind_start(struct unwind_state *state, struct task_struct *task, struct pt_regs *regs, long unsigned int *first_frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810c5ba0)
Location: arch/x86/kernel/unwind_frame.c:373
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/process.c:__get_wchan
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff810c5ba0-ffffffff810c5cbb: __unwind_start (STB_GLOBAL)
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
void __unwind_start(struct unwind_state *state, struct task_struct *task, struct pt_regs *regs, long unsigned int *first_frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a440)
Location: arch/x86/kernel/unwind_frame.c:366
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff8107a440-ffffffff8107a55a: __unwind_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __unwind_start(struct unwind_state *state, struct task_struct *task, struct pt_regs *regs, long unsigned int *first_frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81069b70)
Location: arch/x86/kernel/unwind_frame.c:366
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff81069b70-ffffffff81069c8a: __unwind_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __unwind_start(struct unwind_state *state, struct task_struct *task, struct pt_regs *regs, long unsigned int *first_frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a3f0)
Location: arch/x86/kernel/unwind_frame.c:366
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff8107a3f0-ffffffff8107a50a: __unwind_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __unwind_start(struct unwind_state *state, struct task_struct *task, struct pt_regs *regs, long unsigned int *first_frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107c4f0)
Location: arch/x86/kernel/unwind_frame.c:366
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff8107c4f0-ffffffff8107c60a: __unwind_start (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
