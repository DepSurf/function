# Function: <code>rcu_read_unlock_trace_special</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_read_unlock_trace_special(struct task_struct *t, int nesting);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81130150)
Location: kernel/rcu/tasks.h:757
Inline: True
Direct callers:
  - kernel/rcu/update.c:exit_tasks_rcu_finish
```
**Symbols:**

```
ffffffff81130150-ffffffff8113018e: rcu_read_unlock_trace_special (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rcu_read_unlock_trace_special(struct task_struct *t, int nesting);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112bf90)
Location: kernel/rcu/tasks.h:767
Inline: True
Direct callers:
  - kernel/rcu/update.c:exit_tasks_rcu_finish
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
```
**Symbols:**

```
ffffffff8112bf90-ffffffff8112bfce: rcu_read_unlock_trace_special (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rcu_read_unlock_trace_special(struct task_struct *t, int nesting);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112c4c0)
Location: kernel/rcu/tasks.h:803
Inline: True
Direct callers:
  - kernel/rcu/update.c:exit_tasks_rcu_finish
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
```
**Symbols:**

```
ffffffff8112c4c0-ffffffff8112c4fe: rcu_read_unlock_trace_special (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rcu_read_unlock_trace_special(struct task_struct *t, int nesting);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8114d1c0)
Location: kernel/rcu/tasks.h:850
Inline: True
Direct callers:
  - kernel/rcu/update.c:exit_tasks_rcu_finish
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
```
**Symbols:**

```
ffffffff8114d1c0-ffffffff8114d200: rcu_read_unlock_trace_special (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rcu_read_unlock_trace_special(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81173d50)
Location: kernel/rcu/tasks.h:1195
Inline: True
Direct callers:
  - kernel/rcu/update.c:exit_tasks_rcu_finish
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
```
**Symbols:**

```
ffffffff81173d50-ffffffff81173db0: rcu_read_unlock_trace_special (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rcu_read_unlock_trace_special(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1273
Inline: False
Direct callers:
  - kernel/rcu/update.c:exit_tasks_rcu_finish
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
```
**Symbols:**

```
ffffffff82059e8f-ffffffff82059eb1: rcu_read_unlock_trace_special.cold (STB_LOCAL)
ffffffff811abea0-ffffffff811abfe5: rcu_read_unlock_trace_special (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rcu_read_unlock_trace_special(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1310
Inline: False
Direct callers:
  - kernel/rcu/update.c:exit_tasks_rcu_finish
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
```
**Symbols:**

```
ffffffff820d8686-ffffffff820d86a8: rcu_read_unlock_trace_special.cold (STB_LOCAL)
ffffffff811bddc0-ffffffff811bdf05: rcu_read_unlock_trace_special (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rcu_read_unlock_trace_special(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1426
Inline: False
Direct callers:
  - kernel/rcu/update.c:exit_tasks_rcu_finish
  - kernel/trace/bpf_trace.c:uprobe_prog_run
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/bpf/bpf_iter.c:bpf_iter_run_prog
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
```
**Symbols:**

```
ffffffff821b3950-ffffffff821b3972: rcu_read_unlock_trace_special.cold (STB_LOCAL)
ffffffff811ce2e0-ffffffff811ce425: rcu_read_unlock_trace_special (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nesting</code>
</li>
</ul>
</details>
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
