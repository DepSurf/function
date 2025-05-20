# Function: <code>rq_unpin_lock</code>

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
In kernel/sched/core.c (ffffffff810ae310)
Location: kernel/sched/sched.h:928
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
```
```
In kernel/sched/fair.c (ffffffff810c0ffd)
Location: kernel/sched/sched.h:928
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810c4ba5)
Location: kernel/sched/sched.h:928
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810c81e4)
Location: kernel/sched/sched.h:928
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/livepatch/transition.c (0)
Location: kernel/sched/sched.h:928
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
In kernel/sched/core.c (ffffffff810b55d0)
Location: kernel/sched/sched.h:942
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
```
```
In kernel/sched/fair.c (ffffffff810c8751)
Location: kernel/sched/sched.h:942
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810cc255)
Location: kernel/sched/sched.h:942
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810cf9ca)
Location: kernel/sched/sched.h:942
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/livepatch/transition.c (ffffffff8110373b)
Location: kernel/sched/sched.h:942
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
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
In kernel/sched/core.c (ffffffff810bd280)
Location: kernel/sched/sched.h:1025
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
```
```
In kernel/sched/fair.c (ffffffff810d0cb5)
Location: kernel/sched/sched.h:1025
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810d3f8b)
Location: kernel/sched/sched.h:1025
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810d7573)
Location: kernel/sched/sched.h:1025
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/livepatch/transition.c (ffffffff8110bb7f)
Location: kernel/sched/sched.h:1025
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
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
In kernel/sched/core.c (ffffffff810c7100)
Location: kernel/sched/sched.h:1083
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
```
```
In kernel/sched/fair.c (ffffffff810da4fa)
Location: kernel/sched/sched.h:1083
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810ddc2b)
Location: kernel/sched/sched.h:1083
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810e1b6d)
Location: kernel/sched/sched.h:1083
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff810ef9e1)
Location: kernel/sched/sched.h:1083
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff8111736f)
Location: kernel/sched/sched.h:1083
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
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
In kernel/sched/core.c (ffffffff810cc560)
Location: kernel/sched/sched.h:1141
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
```
```
In kernel/sched/fair.c (ffffffff810e1829)
Location: kernel/sched/sched.h:1141
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
```
```
In kernel/sched/rt.c (ffffffff810e4c2b)
Location: kernel/sched/sched.h:1141
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810e8655)
Location: kernel/sched/sched.h:1141
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff810f6ea1)
Location: kernel/sched/sched.h:1141
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff81121705)
Location: kernel/sched/sched.h:1141
Inline: True
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
In kernel/sched/core.c (ffffffff810d7140)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/fair.c (ffffffff810ec0a0)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (ffffffff810efe38)
Location: kernel/sched/sched.h:1149
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f460b)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff81102c31)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff8112dd25)
Location: kernel/sched/sched.h:1149
Inline: True
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
In kernel/sched/core.c (ffffffff810e1aa0)
Location: kernel/sched/sched.h:1197
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migrate_tasks
  - kernel/sched/core.c:migrate_tasks
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_invoke_on_locked_down_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:ttwu_do_wakeup
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/fair.c (ffffffff810f5d4c)
Location: kernel/sched/sched.h:1197
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/rt.c (ffffffff810f9788)
Location: kernel/sched/sched.h:1197
Inline: True
Inline callers:
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff810fddfb)
Location: kernel/sched/sched.h:1197
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff8110dc11)
Location: kernel/sched/sched.h:1197
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff8113c388)
Location: kernel/sched/sched.h:1197
Inline: True
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
In kernel/sched/core.c (ffffffff810dee40)
Location: kernel/sched/sched.h:1255
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:try_invoke_on_locked_down_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:ttwu_do_wakeup
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/sched/core.c:uclamp_sync_util_min_rt_default
```
```
In kernel/sched/fair.c (ffffffff810f3e9c)
Location: kernel/sched/sched.h:1255
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/rt.c (ffffffff810f7b42)
Location: kernel/sched/sched.h:1255
Inline: True
Inline callers:
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff810fc3cb)
Location: kernel/sched/sched.h:1255
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff8110af65)
Location: kernel/sched/sched.h:1255
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff81136a98)
Location: kernel/sched/sched.h:1255
Inline: True
```
```
In fs/io-wq.c (ffffffff8139b406)
Location: kernel/sched/sched.h:1255
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_worker_affinity
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
In kernel/sched/core.c (ffffffff810e0a30)
Location: kernel/sched/sched.h:1268
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:try_invoke_on_locked_down_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_wakeup
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/fair.c (ffffffff810f5760)
Location: kernel/sched/sched.h:1268
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:distribute_cfs_runtime
```
```
In kernel/sched/rt.c (ffffffff810f9932)
Location: kernel/sched/sched.h:1268
Inline: True
Inline callers:
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff810fe7ad)
Location: kernel/sched/sched.h:1268
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff8110cb82)
Location: kernel/sched/sched.h:1268
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff81137831)
Location: kernel/sched/sched.h:1268
Inline: True
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
In kernel/sched/core.c (ffffffff810f5b40)
Location: kernel/sched/sched.h:1555
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:try_invoke_on_locked_down_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:ttwu_do_wakeup
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/fair.c (ffffffff8110f441)
Location: kernel/sched/sched.h:1555
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (ffffffff81113192)
Location: kernel/sched/sched.h:1555
Inline: True
Inline callers:
  - kernel/sched/rt.c:balance_rt
```
```
In kernel/sched/deadline.c (ffffffff8111a0da)
Location: kernel/sched/sched.h:1555
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff8112bbdf)
Location: kernel/sched/sched.h:1555
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/sched/core_sched.c (ffffffff8112c19a)
Location: kernel/sched/sched.h:1555
Inline: True
Inline callers:
  - kernel/sched/core_sched.c:sched_core_update_cookie
```
```
In kernel/livepatch/transition.c (ffffffff8115a588)
Location: kernel/sched/sched.h:1555
Inline: True
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
In kernel/sched/core.c (ffffffff81111458)
Location: kernel/sched/sched.h:1536
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:ttwu_do_wakeup
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
```
```
In kernel/sched/fair.c (ffffffff8112b415)
Location: kernel/sched/sched.h:1536
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/build_policy.c (ffffffff81139e22)
Location: kernel/sched/sched.h:1536
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:balance_rt
```
```
In kernel/sched/build_utility.c (ffffffff8114c3a6)
Location: kernel/sched/sched.h:1536
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cgroup_move_task
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
In kernel/sched/core.c (ffffffff81138418)
Location: kernel/sched/sched.h:1582
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:ttwu_do_wakeup
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
```
```
In kernel/sched/fair.c (ffffffff81154de5)
Location: kernel/sched/sched.h:1582
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/build_policy.c (ffffffff8116468c)
Location: kernel/sched/sched.h:1582
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:balance_rt
```
```
In kernel/sched/build_utility.c (ffffffff8117af0a)
Location: kernel/sched/sched.h:1582
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cgroup_move_task
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
In kernel/sched/core.c (ffffffff8114750f)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:wait_task_inactive
```
```
In kernel/sched/fair.c (ffffffff81164f95)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/build_policy.c (ffffffff81174e2c)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:balance_rt
```
```
In kernel/sched/build_utility.c (ffffffff8118ba6a)
Location: kernel/sched/sched.h:1609
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cgroup_move_task
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
In kernel/sched/core.c (ffffffff81152d3f)
Location: kernel/sched/sched.h:1628
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:wait_task_inactive
```
```
In kernel/sched/fair.c (ffffffff81171ce5)
Location: kernel/sched/sched.h:1628
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/build_policy.c (ffffffff8118312c)
Location: kernel/sched/sched.h:1628
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:balance_rt
```
```
In kernel/sched/build_utility.c (ffffffff8119a3ca)
Location: kernel/sched/sched.h:1628
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cgroup_move_task
  - kernel/sched/build_utility.c:__sched_core_set
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
In kernel/sched/core.c (ffff800010137c1c)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/fair.c (ffff80001014c578)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (ffff8000101513e8)
Location: kernel/sched/sched.h:1149
Inline: True
```
```
In kernel/sched/deadline.c (ffff800010156aa4)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffff800010167a4c)
Location: kernel/sched/sched.h:1149
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
In kernel/sched/core.c (c0384b64)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
```
```
In kernel/sched/cputime.c (c038f200)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/cputime.c:thread_group_cputime
```
```
In kernel/sched/fair.c (c039a168)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (c039c634)
Location: kernel/sched/sched.h:1149
Inline: True
```
```
In kernel/sched/deadline.c (c03a4760)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (c03b48b8)
Location: kernel/sched/sched.h:1149
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
In kernel/sched/core.c (c000000000181880)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/fair.c (c00000000019ef1c)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (c0000000001a22a8)
Location: kernel/sched/sched.h:1149
Inline: True
```
```
In kernel/sched/deadline.c (c0000000001ab4e0)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (c0000000001bf890)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (c0000000001f2c20)
Location: kernel/sched/sched.h:1149
Inline: True
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
In kernel/sched/core.c (ffffffe0000e7e40)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:__se_sys_sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
```
```
In kernel/sched/fair.c (ffffffe0000f5a9c)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (ffffffe0000f96e4)
Location: kernel/sched/sched.h:1149
Inline: True
```
```
In kernel/sched/deadline.c (ffffffe0000fdac0)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffe000109f90)
Location: kernel/sched/sched.h:1149
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
In kernel/sched/core.c (ffffffff810d0490)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/fair.c (ffffffff810e6200)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (ffffffff810e9728)
Location: kernel/sched/sched.h:1149
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810eda0b)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff810fbf41)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff81126305)
Location: kernel/sched/sched.h:1149
Inline: True
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
In kernel/sched/core.c (ffffffff810bfbd0)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/fair.c (ffffffff810d53a0)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (ffffffff810d91f8)
Location: kernel/sched/sched.h:1149
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810dda9b)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff810ec151)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff81118d65)
Location: kernel/sched/sched.h:1149
Inline: True
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
In kernel/sched/core.c (ffffffff810cf7d0)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
```
```
In kernel/sched/fair.c (ffffffff810e25d0)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (ffffffff810e6368)
Location: kernel/sched/sched.h:1149
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810eab3b)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff810f9101)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff811241f5)
Location: kernel/sched/sched.h:1149
Inline: True
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
In kernel/sched/core.c (ffffffff810d7970)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_rr_get_interval
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:uclamp_update_active_tasks
```
```
In kernel/sched/fair.c (ffffffff810ee182)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
```
In kernel/sched/rt.c (ffffffff810f0088)
Location: kernel/sched/sched.h:1149
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f5aeb)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/psi.c (ffffffff81104241)
Location: kernel/sched/sched.h:1149
Inline: True
Inline callers:
  - kernel/sched/psi.c:cgroup_move_task
```
```
In kernel/livepatch/transition.c (ffffffff81130835)
Location: kernel/sched/sched.h:1149
Inline: True
```
</details>
</li>
</ul>

## Differences
