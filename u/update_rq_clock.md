# Function: <code>update_rq_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810a65c0)
Location: kernel/sched/core.c:98
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_call
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
Direct callers:
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migration_call
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810a65c0-ffffffff810a65f5: update_rq_clock.part.79 (STB_LOCAL)
ffffffff810aa1d0-ffffffff810aa1ea: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3289)
Location: kernel/sched/core.c:99
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:hrtick
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810aa580-ffffffff810aa5b5: update_rq_clock.part.82 (STB_LOCAL)
ffffffff810abfb0-ffffffff810abfca: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810b986b)
Location: kernel/sched/core.c:99
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:hrtick
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810b0670-ffffffff810b06a5: update_rq_clock.part.80 (STB_LOCAL)
ffffffff810b2090-ffffffff810b20aa: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae1e0)
Location: kernel/sched/core.c:212
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810ae1e0-ffffffff810ae259: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b5490)
Location: kernel/sched/core.c:214
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810b5490-ffffffff810b5509: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bcff0)
Location: kernel/sched/core.c:192
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810bcff0-ffffffff810bd068: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c6210)
Location: kernel/sched/core.c:185
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810c6210-ffffffff810c6288: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cbe20)
Location: kernel/sched/core.c:199
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810cbe20-ffffffff810cbeee: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d5980)
Location: kernel/sched/core.c:199
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810d5980-ffffffff810d5a4e: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dff50)
Location: kernel/sched/core.c:202
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:migrate_tasks
  - kernel/sched/core.c:migrate_tasks
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810dff50-ffffffff810e0054: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dd3b0)
Location: kernel/sched/core.c:301
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810dd3b0-ffffffff810dd4b4: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dee20)
Location: kernel/sched/core.c:311
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810dee20-ffffffff810def24: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:664
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff81ca5ce6-ffffffff81ca5d10: update_rq_clock.cold (STB_LOCAL)
ffffffff810f3d40-ffffffff810f3e9c: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:734
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:yield_task_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_utility.c:__sched_core_tick
```
**Symbols:**

```
ffffffff81e5560b-ffffffff81e55635: update_rq_clock.cold (STB_LOCAL)
ffffffff811101e0-ffffffff81110358: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:728
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:yield_task_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_utility.c:__sched_core_tick
```
**Symbols:**

```
ffffffff82056a54-ffffffff82056aa8: update_rq_clock.cold (STB_LOCAL)
ffffffff811370f0-ffffffff81137317: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:750
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:__cfsb_csd_unthrottle
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:yield_task_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_utility.c:__sched_core_tick
```
**Symbols:**

```
ffffffff820d5124-ffffffff820d5178: update_rq_clock.cold (STB_LOCAL)
ffffffff81146160-ffffffff81146399: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:751
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:sched_tick_remote
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:__cfsb_csd_unthrottle
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:yield_task_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_utility.c:__sched_core_tick
```
**Symbols:**

```
ffffffff821b0047-ffffffff821b009b: update_rq_clock.cold (STB_LOCAL)
ffffffff81151730-ffffffff81151969: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010136428)
Location: kernel/sched/core.c:199
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:dequeue_task
  - kernel/sched/core.c:enqueue_task
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffff800010136428-ffff80001013652c: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0385288)
Location: kernel/sched/core.c:199
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
c0385288-c0385438: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000181610)
Location: kernel/sched/core.c:199
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
c000000000181610-c000000000181718: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e7388)
Location: kernel/sched/core.c:199
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffe0000e7388-ffffffe0000e742c: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cfc80)
Location: kernel/sched/core.c:199
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810cfc80-ffffffff810cfd4e: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810be540)
Location: kernel/sched/core.c:199
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_tick_remote
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810be540-ffffffff810be60e: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ce810)
Location: kernel/sched/core.c:199
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810ce810-ffffffff810ce8de: update_rq_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void update_rq_clock(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d77f0)
Location: kernel/sched/core.c:199
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:hrtick
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/deadline.c:yield_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810d77f0-ffffffff810d78be: update_rq_clock (STB_GLOBAL)
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
