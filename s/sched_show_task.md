# Function: <code>sched_show_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae420)
Location: kernel/sched/core.c:4900
Inline: False
Direct callers:
  - kernel/sched/core.c:show_state_filter
  - kernel/sched/core.c:dump_cpu_task
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff810ae420-ffffffff810ae524: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0dd0)
Location: kernel/sched/core.c:5151
Inline: False
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff810b0dd0-ffffffff810b0ed4: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b7030)
Location: kernel/sched/core.c:5190
Inline: False
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff810b7030-ffffffff810b7162: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3360)
Location: kernel/sched/core.c:5108
Inline: True
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff810b3360-ffffffff810b3473: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3a40)
Location: kernel/sched/core.c:5174
Inline: True
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff810b3a40-ffffffff810b3b62: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810c2e0a)
Location: kernel/sched/core.c:5299
Inline: True
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff810c2e0a-ffffffff810c2ee5: sched_show_task.part.62 (STB_LOCAL)
ffffffff810c2ee5-ffffffff810c2eef: sched_show_task.cold.83 (STB_LOCAL)
ffffffff810bac90-ffffffff810bacd4: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810cc0bc)
Location: kernel/sched/core.c:5282
Inline: True
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff810cc0bc-ffffffff810cc197: sched_show_task.part.64 (STB_LOCAL)
ffffffff810cc197-ffffffff810cc1a1: sched_show_task.cold.83 (STB_LOCAL)
ffffffff810c4110-ffffffff810c4154: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810d44a2)
Location: kernel/sched/core.c:5734
Inline: True
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff810d44a2-ffffffff810d4561: sched_show_task.cold (STB_LOCAL)
ffffffff810c9ee0-ffffffff810c9f55: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810deab2)
Location: kernel/sched/core.c:5925
Inline: True
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff810deab2-ffffffff810deb69: sched_show_task.cold (STB_LOCAL)
ffffffff810d30f0-ffffffff810d3165: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810e6d19)
Location: kernel/sched/core.c:6158
Inline: True
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/update.c:check_all_holdout_tasks
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/hung_task.c:check_hung_task
  - mm/oom_kill.c:oom_reaper
```
**Symbols:**

```
ffffffff810e6d19-ffffffff810e6dde: sched_show_task.part.0 (STB_LOCAL)
ffffffff810e6df0-ffffffff810e6dfd: sched_show_task.cold (STB_LOCAL)
ffffffff810dcda0-ffffffff810dcdf3: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff81bdc532)
Location: kernel/sched/core.c:6978
Inline: True
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/hung_task.c:check_hung_task
  - mm/oom_kill.c:oom_reaper
```
**Symbols:**

```
ffffffff81bdc532-ffffffff81bdc614: sched_show_task.part.0 (STB_LOCAL)
ffffffff81bdc626-ffffffff81bdc633: sched_show_task.cold (STB_LOCAL)
ffffffff810d9620-ffffffff810d9673: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff81bce6de)
Location: kernel/sched/core.c:7329
Inline: True
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/hung_task.c:check_hung_task
  - mm/oom_kill.c:oom_reaper
```
**Symbols:**

```
ffffffff81bce6de-ffffffff81bce7b5: sched_show_task.cold (STB_LOCAL)
ffffffff810daee0-ffffffff810daf31: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810eec1f)
Location: kernel/sched/core.c:8527
Inline: True
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/hung_task.c:check_hung_task
  - mm/oom_kill.c:oom_reaper
```
**Symbols:**

```
ffffffff81ca5b91-ffffffff81ca5ba2: sched_show_task.cold (STB_LOCAL)
ffffffff810eebd0-ffffffff810eed13: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff8110ba9d)
Location: kernel/sched/core.c:8818
Inline: True
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/update.c:check_all_holdout_tasks
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/hung_task.c:check_hung_task
  - mm/oom_kill.c:oom_reaper
```
**Symbols:**

```
ffffffff81e554cd-ffffffff81e554de: sched_show_task.cold (STB_LOCAL)
ffffffff8110ba40-ffffffff8110bba3: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81131e10)
Location: kernel/sched/core.c:9002
Inline: True
Direct callers:
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:check_all_holdout_tasks
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/hung_task.c:check_hung_task
  - mm/oom_kill.c:oom_reaper
```
**Symbols:**

```
ffffffff81131e10-ffffffff81131f88: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81140090)
Location: kernel/sched/core.c:9159
Inline: True
Direct callers:
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:check_all_holdout_tasks
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/hung_task.c:check_hung_task
  - mm/oom_kill.c:oom_reaper
```
**Symbols:**

```
ffffffff81140090-ffffffff81140200: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114aff0)
Location: kernel/sched/core.c:9146
Inline: True
Direct callers:
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/update.c:check_holdout_task
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/hung_task.c:check_hung_task
  - mm/oom_kill.c:oom_reaper
```
**Symbols:**

```
ffffffff8114aff0-ffffffff8114b16b: sched_show_task (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffff80001013e4d8)
Location: kernel/sched/core.c:5925
Inline: True
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffff80001013e4d8-ffff80001013e5e8: sched_show_task.part.0 (STB_LOCAL)
ffff8000101334a8-ffff8000101334f0: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (c038e6d0)
Location: kernel/sched/core.c:5925
Inline: True
Inline callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
c038e4b0-c038e5bc: sched_show_task.part.0 (STB_LOCAL)
c0382a3c-c0382a64: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000017e430)
Location: kernel/sched/core.c:5925
Inline: True
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
c00000000017e430-c00000000017e5b8: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e6196)
Location: kernel/sched/core.c:5925
Inline: True
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffe0000e6196-ffffffe0000e62d2: sched_show_task (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8ca2)
Location: kernel/sched/core.c:5925
Inline: True
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff810d8ca2-ffffffff810d8d59: sched_show_task.cold (STB_LOCAL)
ffffffff810cd410-ffffffff810cd485: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810c76ad)
Location: kernel/sched/core.c:5925
Inline: True
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff810c76ad-ffffffff810c7764: sched_show_task.cold (STB_LOCAL)
ffffffff810bbc70-ffffffff810bbce5: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4fe2)
Location: kernel/sched/core.c:5925
Inline: True
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff810d4fe2-ffffffff810d5099: sched_show_task.cold (STB_LOCAL)
ffffffff810cc8f0-ffffffff810cc965: sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_show_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810e0882)
Location: kernel/sched/core.c:5925
Inline: True
Direct callers:
  - kernel/sched/core.c:dump_cpu_task
  - kernel/sched/core.c:show_state_filter
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/hung_task.c:watchdog
```
**Symbols:**

```
ffffffff810e0882-ffffffff810e0948: sched_show_task.cold (STB_LOCAL)
ffffffff810d5280-ffffffff810d52f9: sched_show_task (STB_GLOBAL)
```
</details>
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
