# Function: <code>task_on_rq_queued</code>

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
In kernel/sched/core.c (ffffffff810a97e7)
Location: kernel/sched/sched.h:1039
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1039
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1039
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1039
Inline: True
```
```
In kernel/sched/stop_task.c (0)
Location: kernel/sched/sched.h:1039
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b321f)
Location: kernel/sched/sched.h:1077
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:do_set_cpus_allowed
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1077
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1077
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1077
Inline: True
```
```
In kernel/sched/stop_task.c (0)
Location: kernel/sched/sched.h:1077
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b23df)
Location: kernel/sched/sched.h:1111
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1111
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1111
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1111
Inline: True
```
```
In kernel/sched/stop_task.c (0)
Location: kernel/sched/sched.h:1111
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae529)
Location: kernel/sched/sched.h:1279
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1279
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1279
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1279
Inline: True
```
```
In kernel/sched/stop_task.c (0)
Location: kernel/sched/sched.h:1279
Inline: True
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
In kernel/sched/core.c (ffffffff810b57f5)
Location: kernel/sched/sched.h:1316
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1316
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:1316
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1316
Inline: True
```
```
In kernel/sched/stop_task.c (0)
Location: kernel/sched/sched.h:1316
Inline: True
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
In kernel/sched/core.c (ffffffff810c2b64)
Location: kernel/sched/sched.h:1405
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810c56e5)
Location: kernel/sched/sched.h:1405
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810d430b)
Location: kernel/sched/sched.h:1405
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810d7a05)
Location: kernel/sched/sched.h:1405
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff810dd0d8)
Location: kernel/sched/sched.h:1405
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff810cbe64)
Location: kernel/sched/sched.h:1559
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810cfa71)
Location: kernel/sched/sched.h:1559
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/rt.c (ffffffff810dd81b)
Location: kernel/sched/sched.h:1559
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810e0635)
Location: kernel/sched/sched.h:1559
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff810e6d38)
Location: kernel/sched/sched.h:1559
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
```
```
In kernel/sched/psi.c (ffffffff810ef95a)
Location: kernel/sched/sched.h:1559
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
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
In kernel/sched/core.c (ffffffff810d3f08)
Location: kernel/sched/sched.h:1617
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810d6f78)
Location: kernel/sched/sched.h:1617
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (ffffffff810e4b10)
Location: kernel/sched/sched.h:1617
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810e7315)
Location: kernel/sched/sched.h:1617
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff810ed9c8)
Location: kernel/sched/sched.h:1617
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
```
```
In kernel/sched/psi.c (ffffffff810f6e35)
Location: kernel/sched/sched.h:1617
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
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
In kernel/sched/core.c (ffffffff810de428)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810e7997)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (ffffffff810efce3)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/sched/deadline.c (ffffffff810f2935)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff810f95a2)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
```
```
In kernel/sched/psi.c (ffffffff81102bc5)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
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
In kernel/sched/core.c (ffffffff810e69e4)
Location: kernel/sched/sched.h:1671
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:migrate_tasks
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810f2b27)
Location: kernel/sched/sched.h:1671
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
```
```
In kernel/sched/rt.c (ffffffff810f77e5)
Location: kernel/sched/sched.h:1671
Inline: True
Inline callers:
  - kernel/sched/rt.c:switched_from_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lock_lowest_rq
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff810fbf85)
Location: kernel/sched/sched.h:1671
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff811036b1)
Location: kernel/sched/sched.h:1671
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
```
```
In kernel/sched/psi.c (ffffffff8110dbf5)
Location: kernel/sched/sched.h:1671
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
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
In kernel/sched/core.c (ffffffff810e48e4)
Location: kernel/sched/sched.h:1736
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810f0cf7)
Location: kernel/sched/sched.h:1736
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
```
```
In kernel/sched/rt.c (ffffffff810f59b5)
Location: kernel/sched/sched.h:1736
Inline: True
Inline callers:
  - kernel/sched/rt.c:switched_from_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lock_lowest_rq
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff810fa4e5)
Location: kernel/sched/sched.h:1736
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff81101dd1)
Location: kernel/sched/sched.h:1736
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
```
```
In kernel/sched/psi.c (ffffffff8110af45)
Location: kernel/sched/sched.h:1736
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
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
In kernel/sched/core.c (ffffffff810e68a4)
Location: kernel/sched/sched.h:1747
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810f0827)
Location: kernel/sched/sched.h:1747
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
```
```
In kernel/sched/rt.c (ffffffff810f7a85)
Location: kernel/sched/sched.h:1747
Inline: True
Inline callers:
  - kernel/sched/rt.c:switched_from_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lock_lowest_rq
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff810fc415)
Location: kernel/sched/sched.h:1747
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff81104141)
Location: kernel/sched/sched.h:1747
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
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
In kernel/sched/core.c (ffffffff810fddf6)
Location: kernel/sched/sched.h:2035
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:sched_task_on_rq
```
```
In kernel/sched/fair.c (ffffffff811092b7)
Location: kernel/sched/sched.h:2035
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
```
```
In kernel/sched/rt.c (ffffffff81112185)
Location: kernel/sched/sched.h:2035
Inline: True
Inline callers:
  - kernel/sched/rt.c:switched_from_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lock_lowest_rq
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff8111a999)
Location: kernel/sched/sched.h:2035
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/stop_task.c (ffffffff81121241)
Location: kernel/sched/sched.h:2035
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
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
In kernel/sched/core.c (ffffffff8111a876)
Location: kernel/sched/sched.h:2030
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:sched_task_on_rq
```
```
In kernel/sched/fair.c (ffffffff81124f47)
Location: kernel/sched/sched.h:2030
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:cpu_util_next
```
```
In kernel/sched/build_policy.c (ffffffff8113a93a)
Location: kernel/sched/sched.h:2030
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:switched_from_rt
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:balance_rt
```
```
In kernel/sched/build_utility.c (ffffffff811443c1)
Location: kernel/sched/sched.h:2030
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:pick_next_task_stop
  - kernel/sched/build_utility.c:balance_stop
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
In kernel/sched/core.c (ffffffff81142168)
Location: kernel/sched/sched.h:2080
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:sched_task_on_rq
```
```
In kernel/sched/fair.c (ffffffff8114d307)
Location: kernel/sched/sched.h:2080
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:cpu_util_next
```
```
In kernel/sched/build_policy.c (ffffffff81165134)
Location: kernel/sched/sched.h:2080
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:switched_from_rt
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:balance_rt
```
```
In kernel/sched/build_utility.c (ffffffff81170e2a)
Location: kernel/sched/sched.h:2080
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sched_core_set
  - kernel/sched/build_utility.c:pick_next_task_stop
  - kernel/sched/build_utility.c:balance_stop
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
In kernel/sched/core.c (ffffffff8114de5a)
Location: kernel/sched/sched.h:2123
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:check_preempt_curr
  - kernel/sched/core.c:sched_task_on_rq
```
```
In kernel/sched/fair.c (ffffffff8115ca57)
Location: kernel/sched/sched.h:2123
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
```
```
In kernel/sched/build_policy.c (ffffffff811758d4)
Location: kernel/sched/sched.h:2123
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:switched_from_rt
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:balance_rt
```
```
In kernel/sched/build_utility.c (ffffffff811810fd)
Location: kernel/sched/sched.h:2123
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sched_core_set
  - kernel/sched/build_utility.c:pick_next_task_stop
  - kernel/sched/build_utility.c:balance_stop
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
In kernel/sched/core.c (ffffffff81159c81)
Location: kernel/sched/sched.h:2165
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wakeup_preempt
  - kernel/sched/core.c:sched_task_on_rq
  - kernel/sched/core.c:sched_can_stop_tick
```
```
In kernel/sched/fair.c (ffffffff81167eb7)
Location: kernel/sched/sched.h:2165
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
```
```
In kernel/sched/build_policy.c (ffffffff81183beb)
Location: kernel/sched/sched.h:2165
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:switched_from_rt
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:balance_rt
```
```
In kernel/sched/build_utility.c (ffffffff8118f46d)
Location: kernel/sched/sched.h:2165
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sched_core_set
  - kernel/sched/build_utility.c:pick_next_task_stop
  - kernel/sched/build_utility.c:balance_stop
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
In kernel/sched/core.c (ffff80001013dfc0)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffff80001014617c)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (ffff800010151100)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/sched/deadline.c (ffff800010154b80)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffff80001015dec4)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
```
```
In kernel/sched/psi.c (ffff800010167a24)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
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
In kernel/sched/core.c (c038de78)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (c0393ef8)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (c039c3c0)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/sched/deadline.c (c03a1ca4)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (c03a9cb4)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
```
```
In kernel/sched/psi.c (c03b4858)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
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
In kernel/sched/core.c (c00000000018cfa4)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (c0000000001972e0)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (c0000000001a201c)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/sched/deadline.c (c0000000001aa0bc)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (c0000000001b2a68)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
```
```
In kernel/sched/psi.c (c0000000001bf860)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
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
In kernel/sched/core.c (ffffffe0000eccfc)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffe0000f11c2)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (ffffffe0000f93aa)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/sched/deadline.c (ffffffe0000fb928)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffe000102390)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
```
```
In kernel/sched/psi.c (ffffffe000109f6e)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
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
In kernel/sched/core.c (ffffffff810d8618)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810e1b47)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (ffffffff810e95d3)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/sched/deadline.c (ffffffff810ebd35)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff810f29a2)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
```
```
In kernel/sched/psi.c (ffffffff810fbed5)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
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
In kernel/sched/core.c (ffffffff810c7028)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810d0c27)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (ffffffff810d909e)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/sched/deadline.c (ffffffff810dbd55)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff810e2ab2)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
```
```
In kernel/sched/psi.c (ffffffff810ec0e5)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
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
In kernel/sched/core.c (ffffffff810d4dc4)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810ddec7)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (ffffffff810e6213)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/sched/deadline.c (ffffffff810e8e65)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff810efad2)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
```
```
In kernel/sched/psi.c (ffffffff810f9095)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
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
In kernel/sched/core.c (ffffffff810e01f8)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:check_preempt_curr
```
```
In kernel/sched/fair.c (ffffffff810e99b7)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:find_idlest_cpu
```
```
In kernel/sched/rt.c (ffffffff810eff0a)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
```
```
In kernel/sched/deadline.c (ffffffff810f3e15)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff810fab22)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
  - kernel/sched/stop_task.c:balance_stop
```
```
In kernel/sched/psi.c (ffffffff811041d5)
Location: kernel/sched/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
</details>
</li>
</ul>

## Differences
