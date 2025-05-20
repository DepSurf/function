# Function: <code>task_rq_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a969b)
Location: kernel/sched/sched.h:1455
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_move_task
```
```
In kernel/sched/deadline.c (ffffffff810c27f3)
Location: kernel/sched/sched.h:1455
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ac050)
Location: kernel/sched/core.c:201
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810ac050-ffffffff810ac0fc: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2130)
Location: kernel/sched/core.c:201
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810b2130-ffffffff810b21d4: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae110)
Location: kernel/sched/core.c:116
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810ae110-ffffffff810ae1d6: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b52a0)
Location: kernel/sched/core.c:118
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/livepatch/transition.c:klp_try_switch_task
```
**Symbols:**

```
ffffffff810b52a0-ffffffff810b5366: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bcca0)
Location: kernel/sched/core.c:96
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/livepatch/transition.c:klp_try_switch_task
```
**Symbols:**

```
ffffffff810bcca0-ffffffff810bcd59: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c5ec0)
Location: kernel/sched/core.c:90
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/livepatch/transition.c:klp_try_switch_task
```
**Symbols:**

```
ffffffff810c5ec0-ffffffff810c5f77: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cbad0)
Location: kernel/sched/core.c:102
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/psi.c:cgroup_move_task
```
**Symbols:**

```
ffffffff810cbad0-ffffffff810cbb80: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4da0)
Location: kernel/sched/core.c:102
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/psi.c:cgroup_move_task
```
**Symbols:**

```
ffffffff810d4da0-ffffffff810d4e50: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df710)
Location: kernel/sched/core.c:105
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/psi.c:cgroup_move_task
```
**Symbols:**

```
ffffffff810df710-ffffffff810df7c0: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc9c0)
Location: kernel/sched/core.c:204
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_sync_util_min_rt_default
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/psi.c:cgroup_move_task
  - fs/io-wq.c:io_wq_worker_affinity
```
**Symbols:**

```
ffffffff810dc9c0-ffffffff810dcaa9: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de590)
Location: kernel/sched/core.c:214
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/psi.c:cgroup_move_task
```
**Symbols:**

```
ffffffff810de590-ffffffff810de679: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:567
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:migrate_enable
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/core_sched.c:sched_core_update_cookie
```
**Symbols:**

```
ffffffff81ca5cd2-ffffffff81ca5ce6: task_rq_lock.cold (STB_LOCAL)
ffffffff810f33c0-ffffffff810f350f: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:637
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:migrate_enable
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_utility.c:cgroup_move_task
  - kernel/sched/build_utility.c:__sched_core_set
  - kernel/sched/build_utility.c:__sched_core_set
```
**Symbols:**

```
ffffffff81e555f6-ffffffff81e5560b: task_rq_lock.cold (STB_LOCAL)
ffffffff8110f3d0-ffffffff8110f52c: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:630
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_utility.c:cgroup_move_task
  - kernel/sched/build_utility.c:__sched_core_set
  - kernel/sched/build_utility.c:__sched_core_set
```
**Symbols:**

```
ffffffff82056a3f-ffffffff82056a54: task_rq_lock.cold (STB_LOCAL)
ffffffff81136220-ffffffff8113637c: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:651
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_utility.c:cgroup_move_task
  - kernel/sched/build_utility.c:__sched_core_set
  - kernel/sched/build_utility.c:__sched_core_set
```
**Symbols:**

```
ffffffff820d510f-ffffffff820d5124: task_rq_lock.cold (STB_LOCAL)
ffffffff81145230-ffffffff811453a1: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:652
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_utility.c:cgroup_move_task
  - kernel/sched/build_utility.c:__sched_core_set
  - kernel/sched/build_utility.c:__sched_core_set
```
**Symbols:**

```
ffffffff821b0032-ffffffff821b0047: task_rq_lock.cold (STB_LOCAL)
ffffffff81150750-ffffffff811508c1: task_rq_lock (STB_GLOBAL)
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
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff8000101358f0)
Location: kernel/sched/core.c:102
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/psi.c:cgroup_move_task
```
**Symbols:**

```
ffff8000101358f0-ffff800010135a24: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038488c)
Location: kernel/sched/core.c:102
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/cputime.c:thread_group_cputime
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/psi.c:cgroup_move_task
```
**Symbols:**

```
c038488c-c0384990: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0000000001806b0)
Location: kernel/sched/core.c:102
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/psi.c:cgroup_move_task
```
**Symbols:**

```
c0000000001806b0-c00000000018081c: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e7282)
Location: kernel/sched/core.c:102
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:__se_sys_sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/psi.c:cgroup_move_task
```
**Symbols:**

```
ffffffe0000e7282-ffffffe0000e7388: task_rq_lock (STB_GLOBAL)
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
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf090)
Location: kernel/sched/core.c:102
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/psi.c:cgroup_move_task
```
**Symbols:**

```
ffffffff810cf090-ffffffff810cf140: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bd960)
Location: kernel/sched/core.c:102
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/psi.c:cgroup_move_task
```
**Symbols:**

```
ffffffff810bd960-ffffffff810bda10: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ce4c0)
Location: kernel/sched/core.c:102
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/psi.c:cgroup_move_task
```
**Symbols:**

```
ffffffff810ce4c0-ffffffff810ce570: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rq *task_rq_lock(struct task_struct *p, struct rq_flags *rf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d6c20)
Location: kernel/sched/core.c:102
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/psi.c:cgroup_move_task
```
**Symbols:**

```
ffffffff810d6c20-ffffffff810d6cce: task_rq_lock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
