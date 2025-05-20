# Function: <code>set_task_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ab2b0)
Location: kernel/sched/core.c:1267
Inline: False
Direct callers:
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:pull_dl_task
```
**Symbols:**

```
ffffffff810ab2b0-ffffffff810ab3d4: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810adef0)
Location: kernel/sched/core.c:1203
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810adef0-ffffffff810ae07c: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b4060)
Location: kernel/sched/core.c:1214
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810b4060-ffffffff810b41e7: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810afff0)
Location: kernel/sched/core.c:1138
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810afff0-ffffffff810b0140: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b73f0)
Location: kernel/sched/core.c:1153
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810b73f0-ffffffff810b755e: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bef90)
Location: kernel/sched/core.c:1150
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810bef90-ffffffff810bf0fd: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c8220)
Location: kernel/sched/core.c:1145
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810c8220-ffffffff810c8390: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf880)
Location: kernel/sched/core.c:1587
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810cf880-ffffffff810cfa01: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d9720)
Location: kernel/sched/core.c:1707
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff810d9720-ffffffff810d98c3: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e2980)
Location: kernel/sched/core.c:1777
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_one_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff810e2980-ffffffff810e2b01: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dfb20)
Location: kernel/sched/core.c:2401
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_one_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff810dfb20-ffffffff810dfcb4: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1900)
Location: kernel/sched/core.c:2422
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff810e1900-ffffffff810e1a94: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f7b30)
Location: kernel/sched/core.c:2989
Inline: False
Direct callers:
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff810f7b30-ffffffff810f7cbf: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81113dc0)
Location: kernel/sched/core.c:3088
Inline: False
Direct callers:
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
**Symbols:**

```
ffffffff81113dc0-ffffffff81113f74: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113b0c0)
Location: kernel/sched/core.c:3144
Inline: False
Direct callers:
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
**Symbols:**

```
ffffffff8113b0c0-ffffffff8113b292: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114a410)
Location: kernel/sched/core.c:3320
Inline: False
Direct callers:
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
**Symbols:**

```
ffffffff8114a410-ffffffff8114a5e8: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81155f80)
Location: kernel/sched/core.c:3350
Inline: False
Direct callers:
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
**Symbols:**

```
ffffffff81155f80-ffffffff8115615b: set_task_cpu (STB_GLOBAL)
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
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010139618)
Location: kernel/sched/core.c:1707
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffff800010139618-ffff8000101397fc: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0388dd4)
Location: kernel/sched/core.c:1707
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
c0388dd4-c038906c: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000186340)
Location: kernel/sched/core.c:1707
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
c000000000186340-c0000000001865cc: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e912a)
Location: kernel/sched/core.c:1707
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffe0000e912a-ffffffe0000e92be: set_task_cpu (STB_GLOBAL)
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
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3bf0)
Location: kernel/sched/core.c:1707
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff810d3bf0-ffffffff810d3d71: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c2220)
Location: kernel/sched/core.c:1707
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff810c2220-ffffffff810c23c3: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d0e50)
Location: kernel/sched/core.c:1707
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff810d0e50-ffffffff810d0ff3: set_task_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_task_cpu(struct task_struct *p, unsigned int new_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810db390)
Location: kernel/sched/core.c:1707
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff810db390-ffffffff810db52a: set_task_cpu (STB_GLOBAL)
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
