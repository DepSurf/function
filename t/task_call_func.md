# Function: <code>task_call_func</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int task_call_func(struct task_struct *p, task_call_f func, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81116ab0)
Location: kernel/sched/core.c:4229
Inline: False
Direct callers:
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/tree.c:rcu_print_task_stall
  - kernel/livepatch/transition.c:klp_try_switch_task
```
**Symbols:**

```
ffffffff81116ab0-ffffffff81116b87: task_call_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int task_call_func(struct task_struct *p, task_call_f func, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113e000)
Location: kernel/sched/core.c:4327
Inline: False
Direct callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/tree.c:rcu_print_task_stall
  - kernel/livepatch/transition.c:klp_try_switch_task
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
**Symbols:**

```
ffffffff8113e000-ffffffff8113e0e7: task_call_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int task_call_func(struct task_struct *p, task_call_f func, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114ab20)
Location: kernel/sched/core.c:4404
Inline: False
Direct callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/tree.c:rcu_print_task_stall
  - kernel/livepatch/transition.c:klp_try_switch_task
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
**Symbols:**

```
ffffffff8114ab20-ffffffff8114ac1d: task_call_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int task_call_func(struct task_struct *p, task_call_f func, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81156720)
Location: kernel/sched/core.c:4426
Inline: False
Direct callers:
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/tree.c:rcu_print_task_stall
  - kernel/livepatch/transition.c:klp_try_switch_task
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
```
**Symbols:**

```
ffffffff81156720-ffffffff8115681d: task_call_func (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
