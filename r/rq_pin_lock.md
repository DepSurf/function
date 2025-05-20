# Function: <code>rq_pin_lock</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810af744)
Location: kernel/sched/sched.h:918
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sys_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810c2393)
Location: kernel/sched/sched.h:918
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:distribute_cfs_runtime
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b6a1a)
Location: kernel/sched/sched.h:932
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sys_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810c9a3b)
Location: kernel/sched/sched.h:932
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:distribute_cfs_runtime
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bc617)
Location: kernel/sched/sched.h:1015
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810d1ba3)
Location: kernel/sched/sched.h:1015
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:distribute_cfs_runtime
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c4df7)
Location: kernel/sched/sched.h:1073
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810db4e3)
Location: kernel/sched/sched.h:1073
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/psi.c (ffffffff810ef846)
Location: kernel/sched/sched.h:1073
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ce4ab)
Location: kernel/sched/sched.h:1131
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810e2966)
Location: kernel/sched/sched.h:1131
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/psi.c (ffffffff810f6ce6)
Location: kernel/sched/sched.h:1131
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d80ab)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810ed016)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/psi.c (ffffffff81102a76)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df3f7)
Location: kernel/sched/sched.h:1187
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810f6f26)
Location: kernel/sched/sched.h:1187
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/psi.c (ffffffff8110da95)
Location: kernel/sched/sched.h:1187
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc090)
Location: kernel/sched/sched.h:1242
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810f5108)
Location: kernel/sched/sched.h:1242
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/psi.c (ffffffff8110adb5)
Location: kernel/sched/sched.h:1242
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de0b0)
Location: kernel/sched/sched.h:1255
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810f71f2)
Location: kernel/sched/sched.h:1255
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/psi.c (ffffffff8110c9e5)
Location: kernel/sched/sched.h:1255
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f2d80)
Location: kernel/sched/sched.h:1542
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff8111161b)
Location: kernel/sched/sched.h:1542
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/psi.c (ffffffff8112ba29)
Location: kernel/sched/sched.h:1542
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff8110eb3a)
Location: kernel/sched/sched.h:1523
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff8112d838)
Location: kernel/sched/sched.h:1523
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/build_policy.c (ffffffff81132056)
Location: kernel/sched/sched.h:1523
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
```
```
In kernel/sched/build_utility.c (ffffffff8114c1bd)
Location: kernel/sched/sched.h:1523
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_memstall_leave
  - kernel/sched/build_utility.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff81135900)
Location: kernel/sched/sched.h:1569
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff8115761d)
Location: kernel/sched/sched.h:1569
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/build_policy.c (ffffffff8115c326)
Location: kernel/sched/sched.h:1569
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
```
```
In kernel/sched/build_utility.c (ffffffff8117b030)
Location: kernel/sched/sched.h:1569
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_memstall_enter
  - kernel/sched/build_utility.c:psi_memstall_enter
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
In kernel/sched/core.c (ffffffff8115241d)
Location: kernel/sched/sched.h:1596
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff81167667)
Location: kernel/sched/sched.h:1596
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:__cfsb_csd_unthrottle
  - kernel/sched/fair.c:__cfsb_csd_unthrottle
```
```
In kernel/sched/build_policy.c (ffffffff8116c6e6)
Location: kernel/sched/sched.h:1596
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
```
```
In kernel/sched/build_utility.c (ffffffff8118bb6e)
Location: kernel/sched/sched.h:1596
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_memstall_enter
  - kernel/sched/build_utility.c:psi_memstall_enter
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:rq_attach_root
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
In kernel/sched/core.c (ffffffff8115e2dd)
Location: kernel/sched/sched.h:1615
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_tick_remote
  - kernel/sched/core.c:sched_tick_remote
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff81174457)
Location: kernel/sched/sched.h:1615
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:__cfsb_csd_unthrottle
  - kernel/sched/fair.c:__cfsb_csd_unthrottle
```
```
In kernel/sched/build_policy.c (ffffffff81179f76)
Location: kernel/sched/sched.h:1615
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
```
```
In kernel/sched/build_utility.c (ffffffff8119a4ce)
Location: kernel/sched/sched.h:1615
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_memstall_enter
  - kernel/sched/build_utility.c:psi_memstall_enter
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:rq_attach_root
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff8000101387d4)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffff80001014d64c)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/psi.c (ffff80001016788c)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
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
In kernel/sched/core.c (c0387550)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (c039b224)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/psi.c (c03b4694)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018451c)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (c0000000001a054c)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/psi.c (c0000000001bf628)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e86d0)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffe0000f68e2)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/psi.c (ffffffe000109dde)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d257b)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810e7176)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/psi.c (ffffffff810fbd86)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c0baf)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_tick_remote
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810d6316)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/psi.c (ffffffff810ebf90)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d032b)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810e3546)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/psi.c (ffffffff810f8f46)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d9c80)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810ef126)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/psi.c (ffffffff81104086)
Location: kernel/sched/sched.h:1139
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
</details>
</li>
</ul>

## Differences
