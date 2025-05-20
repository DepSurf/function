# Function: <code>sched_core_enabled</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fde5a)
Location: kernel/sched/sched.h:1158
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:queue_core_balance
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:raw_spin_rq_unlock
```
```
In kernel/sched/fair.c (ffffffff811077ab)
Location: kernel/sched/sched.h:1158
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
```
```
In kernel/sched/core_sched.c (ffffffff8112c21f)
Location: kernel/sched/sched.h:1158
Inline: True
Inline callers:
  - kernel/sched/core_sched.c:sched_core_update_cookie
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8111a8d4)
Location: kernel/sched/sched.h:1155
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:raw_spin_rq_unlock
```
```
In kernel/sched/fair.c (ffffffff811249f6)
Location: kernel/sched/sched.h:1155
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
```
```
In kernel/sched/build_utility.c (ffffffff81144ac7)
Location: kernel/sched/sched.h:1155
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sched_core_set
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114225c)
Location: kernel/sched/sched.h:1209
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:raw_spin_rq_unlock
```
```
In kernel/sched/fair.c (ffffffff8114ca2e)
Location: kernel/sched/sched.h:1209
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:find_idlest_group_cpu
```
```
In kernel/sched/build_utility.c (ffffffff81170df0)
Location: kernel/sched/sched.h:1209
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sched_core_set
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81152482)
Location: kernel/sched/sched.h:1216
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:task_call_func
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff8115aedb)
Location: kernel/sched/sched.h:1216
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:find_idlest_group_cpu
```
```
In kernel/sched/build_utility.c (ffffffff811810bc)
Location: kernel/sched/sched.h:1216
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sched_core_set
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8115e347)
Location: kernel/sched/sched.h:1234
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_core_idle_cpu
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:sched_tick_remote
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:task_call_func
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff8116c19d)
Location: kernel/sched/sched.h:1234
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:find_idlest_group_cpu
```
```
In kernel/sched/build_utility.c (ffffffff8118f42c)
Location: kernel/sched/sched.h:1234
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sched_core_set
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
