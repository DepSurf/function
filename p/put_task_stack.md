# Function: <code>put_task_stack</code>

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
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810847e0)
Location: kernel/fork.c:336
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
  - kernel/sched/core.c:sched_show_task
  - kernel/sched/core.c:finish_task_switch
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff810847e0-ffffffff810848f5: put_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81081700)
Location: kernel/fork.c:360
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:get_wchan
  - kernel/sched/core.c:finish_task_switch
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff81081700-ffffffff810817d2: put_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81087fe0)
Location: kernel/fork.c:366
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
  - kernel/sched/core.c:finish_task_switch
  - fs/proc/array.c:do_task_stat
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff81087fe0-ffffffff810880b7: put_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108bd30)
Location: kernel/fork.c:392
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
  - kernel/sched/core.c:finish_task_switch
  - fs/proc/array.c:do_task_stat
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff8108bd30-ffffffff8108be09: put_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810935b0)
Location: kernel/fork.c:435
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:get_wchan
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
  - kernel/sched/core.c:finish_task_switch
  - fs/proc/array.c:do_task_stat
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff810935b0-ffffffff81093725: put_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:441
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:get_wchan
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:finish_task_switch
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
  - fs/proc/array.c:do_task_stat
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff8109abb5-ffffffff8109abc8: put_task_stack.cold (STB_LOCAL)
ffffffff81097cd0-ffffffff81097e15: put_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109e390)
Location: kernel/fork.c:450
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:get_wchan
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:finish_task_switch
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
  - fs/proc/array.c:do_task_stat
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff8109e390-ffffffff8109e4d9: put_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a5980)
Location: kernel/fork.c:455
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:get_wchan
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:finish_task_switch
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
  - fs/proc/array.c:do_task_stat
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff810a5980-ffffffff810a59fb: put_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1170)
Location: kernel/fork.c:441
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:get_wchan
  - kernel/fork.c:copy_process
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
  - fs/proc/array.c:do_task_stat
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff810a1170-ffffffff810a12a6: put_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1ee0)
Location: kernel/fork.c:445
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:get_wchan
  - kernel/fork.c:copy_process
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/bpf/stackmap.c:bpf_get_task_stack
  - fs/proc/array.c:do_task_stat
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff810a1ee0-ffffffff810a2017: put_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b2cc0)
Location: kernel/fork.c:445
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:get_wchan
  - kernel/fork.c:copy_process
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/bpf/stackmap.c:bpf_get_task_stack
  - fs/proc/array.c:do_task_stat
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff810b2cc0-ffffffff810b2dfd: put_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c9020)
Location: kernel/fork.c:536
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:__get_wchan
  - kernel/fork.c:copy_process
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/bpf/stackmap.c:bpf_get_task_stack
  - fs/proc/array.c:do_task_stat
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff810c9020-ffffffff810c9104: put_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e64f0)
Location: kernel/fork.c:534
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:__get_wchan
  - kernel/fork.c:copy_process
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/bpf/stackmap.c:bpf_get_task_stack
  - fs/proc/array.c:do_task_stat
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff810e64f0-ffffffff810e65d4: put_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f1e60)
Location: kernel/fork.c:598
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:__get_wchan
  - kernel/fork.c:copy_process
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/bpf/stackmap.c:bpf_get_task_stack
  - fs/proc/array.c:do_task_stat
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff810f1e60-ffffffff810f1f44: put_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fbac0)
Location: kernel/fork.c:578
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:__get_wchan
  - kernel/fork.c:copy_process
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
  - kernel/bpf/stackmap.c:bpf_get_task_stack
  - fs/proc/array.c:do_task_stat
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff810fbac0-ffffffff810fbba4: put_task_stack (STB_GLOBAL)
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
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f2f38)
Location: kernel/fork.c:450
Inline: False
Direct callers:
  - arch/arm64/kernel/process.c:get_wchan
  - arch/arm64/kernel/stacktrace.c:__save_stack_trace
  - arch/arm64/kernel/traps.c:dump_backtrace
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:finish_task_switch
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffff8000100f2f38-ffff8000100f2fac: put_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (0)
Location: include/linux/sched/task_stack.h:75
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched/task_stack.h:75
Inline: True
```
```
In fs/proc/array.c (c060ae08)
Location: include/linux/sched/task_stack.h:75
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In lib/syscall.c (0)
Location: include/linux/sched/task_stack.h:75
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000138ca0)
Location: kernel/fork.c:450
Inline: False
Direct callers:
  - arch/powerpc/kernel/process.c:show_stack
  - arch/powerpc/kernel/process.c:get_wchan
  - arch/powerpc/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:finish_task_switch
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
c000000000138ca0-c000000000138d5c: put_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c0112)
Location: kernel/fork.c:450
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
Direct callers:
  - kernel/sched/core.c:finish_task_switch
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffe0000bfb2a-ffffffe0000bfb74: put_task_stack (STB_GLOBAL)
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
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097cb0)
Location: kernel/fork.c:450
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:get_wchan
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:finish_task_switch
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
  - fs/proc/array.c:do_task_stat
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff81097cb0-ffffffff81097df9: put_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81086720)
Location: kernel/fork.c:450
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:get_wchan
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:finish_task_switch
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
  - fs/proc/array.c:do_task_stat
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff81086720-ffffffff81086855: put_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097c60)
Location: kernel/fork.c:450
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:get_wchan
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:finish_task_switch
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
  - fs/proc/array.c:do_task_stat
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff81097c60-ffffffff81097da9: put_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void put_task_stack(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109f860)
Location: kernel/fork.c:450
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:get_wchan
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:finish_task_switch
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
  - fs/proc/array.c:do_task_stat
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
  - lib/syscall.c:collect_syscall
```
**Symbols:**

```
ffffffff8109f860-ffffffff8109f9a9: put_task_stack (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
