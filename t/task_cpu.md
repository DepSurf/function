# Function: <code>task_cpu</code>

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
In kernel/cpu.c (ffffffff81081758)
Location: include/linux/sched.h:3088
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/core.c (ffffffff810a4975)
Location: include/linux/sched.h:3088
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_call
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
```
In kernel/sched/idle_task.c (ffffffff810b1c45)
Location: include/linux/sched.h:3088
Inline: True
Inline callers:
  - kernel/sched/idle_task.c:select_task_rq_idle
```
```
In kernel/sched/fair.c (ffffffff810b321c)
Location: include/linux/sched.h:3088
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_move_group_fair
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/rt.c (ffffffff810bef5c)
Location: include/linux/sched.h:3088
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/sched/deadline.c (ffffffff810c1200)
Location: include/linux/sched.h:3088
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_dead_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/sched/stop_task.c (ffffffff810c3015)
Location: include/linux/sched.h:3088
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:select_task_rq_stop
```
```
In kernel/sched/debug.c (ffffffff810c6b50)
Location: include/linux/sched.h:3088
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/sched/cpuacct.c (ffffffff810c99b5)
Location: include/linux/sched.h:3088
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_charge
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811573cf)
Location: include/linux/sched.h:3088
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff811789b7)
Location: include/linux/sched.h:3088
Inline: True
Inline callers:
  - kernel/events/core.c:task_function_call
```
```
In fs/proc/array.c (ffffffff8128036a)
Location: include/linux/sched.h:3088
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/cpu.c (ffffffff81083f6a)
Location: include/linux/sched.h:3365
Inline: True
Inline callers:
  - kernel/cpu.c:notify_dead
```
```
In kernel/sched/core.c (ffffffff810b2ca2)
Location: include/linux/sched.h:3365
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/idle_task.c (ffffffff810b4765)
Location: include/linux/sched.h:3365
Inline: True
Inline callers:
  - kernel/sched/idle_task.c:select_task_rq_idle
```
```
In kernel/sched/fair.c (ffffffff810bf2c4)
Location: include/linux/sched.h:3365
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/rt.c (ffffffff810c3cdd)
Location: include/linux/sched.h:3365
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c518e)
Location: include/linux/sched.h:3365
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:task_dead_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810c69a5)
Location: include/linux/sched.h:3365
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:select_task_rq_stop
```
```
In kernel/sched/debug.c (ffffffff810cc9f7)
Location: include/linux/sched.h:3365
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/rcu/update.c (ffffffff810e961a)
Location: include/linux/sched.h:3365
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8113f00b)
Location: include/linux/sched.h:3365
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81140786)
Location: include/linux/sched.h:3365
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81161c4f)
Location: include/linux/sched.h:3365
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff8118fc15)
Location: include/linux/sched.h:3365
Inline: True
Inline callers:
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:task_function_call
```
```
In fs/proc/array.c (ffffffff812ad3c9)
Location: include/linux/sched.h:3365
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: include/linux/sched.h:3534
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b75c4)
Location: include/linux/sched.h:3534
Inline: True
Inline callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap
```
```
In kernel/sched/idle_task.c (0)
Location: include/linux/sched.h:3534
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810bf636)
Location: include/linux/sched.h:3534
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/rt.c (ffffffff810c8a36)
Location: include/linux/sched.h:3534
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810caf05)
Location: include/linux/sched.h:3534
Inline: True
Inline callers:
  - kernel/sched/deadline.c:find_later_rq
```
```
In kernel/sched/stop_task.c (0)
Location: include/linux/sched.h:3534
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/sched.h:3534
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:3534
Inline: True
```
```
In kernel/locking/rwsem-xadd.c (0)
Location: include/linux/sched.h:3534
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:3534
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81148ddb)
Location: include/linux/sched.h:3534
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8114a576)
Location: include/linux/sched.h:3534
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116c89b)
Location: include/linux/sched.h:3534
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (0)
Location: include/linux/sched.h:3534
Inline: True
```
```
In fs/proc/array.c (0)
Location: include/linux/sched.h:3534
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: include/linux/sched.h:1587
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b37a4)
Location: include/linux/sched.h:1587
Inline: True
Inline callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap
```
```
In kernel/sched/idle_task.c (0)
Location: include/linux/sched.h:1587
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810b9d8b)
Location: include/linux/sched.h:1587
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/rt.c (ffffffff810c2b76)
Location: include/linux/sched.h:1587
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810c5325)
Location: include/linux/sched.h:1587
Inline: True
Inline callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
```
```
In kernel/sched/stop_task.c (0)
Location: include/linux/sched.h:1587
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/sched.h:1587
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1587
Inline: True
```
```
In kernel/locking/rwsem-xadd.c (0)
Location: include/linux/sched.h:1587
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1587
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff810f5e6a)
Location: include/linux/sched.h:1587
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8114abeb)
Location: include/linux/sched.h:1587
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8114c477)
Location: include/linux/sched.h:1587
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116fc4b)
Location: include/linux/sched.h:1587
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (0)
Location: include/linux/sched.h:1587
Inline: True
```
```
In fs/proc/array.c (0)
Location: include/linux/sched.h:1587
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: include/linux/sched.h:1621
Inline: True
```
```
In kernel/sched/core.c (ffffffff810baa14)
Location: include/linux/sched.h:1621
Inline: True
Inline callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap
```
```
In kernel/sched/idle_task.c (0)
Location: include/linux/sched.h:1621
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810c1e5b)
Location: include/linux/sched.h:1621
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/rt.c (ffffffff810ca3c6)
Location: include/linux/sched.h:1621
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810cca36)
Location: include/linux/sched.h:1621
Inline: True
Inline callers:
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:inactive_task_timer
```
```
In kernel/sched/stop_task.c (0)
Location: include/linux/sched.h:1621
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/sched.h:1621
Inline: True
```
```
In kernel/locking/mutex.c (0)
Location: include/linux/sched.h:1621
Inline: True
```
```
In kernel/locking/rwsem-xadd.c (0)
Location: include/linux/sched.h:1621
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:1621
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff81100e36)
Location: include/linux/sched.h:1621
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81157b6b)
Location: include/linux/sched.h:1621
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81158d17)
Location: include/linux/sched.h:1621
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8117cda3)
Location: include/linux/sched.h:1621
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (0)
Location: include/linux/sched.h:1621
Inline: True
```
```
In fs/proc/array.c (0)
Location: include/linux/sched.h:1621
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81047fd9)
Location: include/linux/sched.h:1735
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c2533)
Location: include/linux/sched.h:1735
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/idle.c (ffffffff810c3fe5)
Location: include/linux/sched.h:1735
Inline: True
Inline callers:
  - kernel/sched/idle.c:select_task_rq_idle
```
```
In kernel/sched/fair.c (ffffffff810c730a)
Location: include/linux/sched.h:1735
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/rt.c (ffffffff810d37b1)
Location: include/linux/sched.h:1735
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810d88f5)
Location: include/linux/sched.h:1735
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff810dcfa5)
Location: include/linux/sched.h:1735
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:select_task_rq_stop
```
```
In kernel/sched/debug.c (ffffffff810e0718)
Location: include/linux/sched.h:1735
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/locking/mutex.c (ffffffff810e4755)
Location: include/linux/sched.h:1735
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem-xadd.c (ffffffff819efe1a)
Location: include/linux/sched.h:1735
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
```
```
In kernel/rcu/update.c (ffffffff811029bc)
Location: include/linux/sched.h:1735
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff8110802a)
Location: include/linux/sched.h:1735
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8116675b)
Location: include/linux/sched.h:1735
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81167927)
Location: include/linux/sched.h:1735
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118bcda)
Location: include/linux/sched.h:1735
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff811d2ff7)
Location: include/linux/sched.h:1735
Inline: True
Inline callers:
  - kernel/events/core.c:task_function_call
```
```
In fs/proc/array.c (ffffffff81321b84)
Location: include/linux/sched.h:1735
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81057b49)
Location: include/linux/sched.h:1748
Inline: True
```
```
In kernel/sched/core.c (ffffffff810cb823)
Location: include/linux/sched.h:1748
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/idle.c (ffffffff810cd2a5)
Location: include/linux/sched.h:1748
Inline: True
Inline callers:
  - kernel/sched/idle.c:select_task_rq_idle
```
```
In kernel/sched/fair.c (ffffffff810d762c)
Location: include/linux/sched.h:1748
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/rt.c (ffffffff810dcb56)
Location: include/linux/sched.h:1748
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e23f5)
Location: include/linux/sched.h:1748
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff810e6c05)
Location: include/linux/sched.h:1748
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:select_task_rq_stop
```
```
In kernel/sched/debug.c (ffffffff810eaece)
Location: include/linux/sched.h:1748
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/sched/psi.c (ffffffff810ef4d5)
Location: include/linux/sched.h:1748
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/locking/mutex.c (ffffffff810efd45)
Location: include/linux/sched.h:1748
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem-xadd.c (ffffffff81a2b84c)
Location: include/linux/sched.h:1748
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_spin_on_owner
```
```
In kernel/rcu/update.c (ffffffff8110e37d)
Location: include/linux/sched.h:1748
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff8111439c)
Location: include/linux/sched.h:1748
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811734bb)
Location: include/linux/sched.h:1748
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81174757)
Location: include/linux/sched.h:1748
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811996f8)
Location: include/linux/sched.h:1748
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff811e32e7)
Location: include/linux/sched.h:1748
Inline: True
Inline callers:
  - kernel/events/core.c:task_function_call
```
```
In fs/proc/array.c (ffffffff81338c94)
Location: include/linux/sched.h:1748
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ad95)
Location: include/linux/sched.h:1821
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d3839)
Location: include/linux/sched.h:1821
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/idle.c (ffffffff810d5695)
Location: include/linux/sched.h:1821
Inline: True
Inline callers:
  - kernel/sched/idle.c:select_task_rq_idle
```
```
In kernel/sched/fair.c (ffffffff810dc7f3)
Location: include/linux/sched.h:1821
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/rt.c (ffffffff810e3b01)
Location: include/linux/sched.h:1821
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e8ef5)
Location: include/linux/sched.h:1821
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff810ed895)
Location: include/linux/sched.h:1821
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:select_task_rq_stop
```
```
In kernel/sched/debug.c (ffffffff810f1d02)
Location: include/linux/sched.h:1821
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/sched/psi.c (ffffffff810f6865)
Location: include/linux/sched.h:1821
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/locking/mutex.c (ffffffff810f77a3)
Location: include/linux/sched.h:1821
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff810f85f9)
Location: include/linux/sched.h:1821
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/rcu/update.c (ffffffff81117a50)
Location: include/linux/sched.h:1821
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff8111e0bd)
Location: include/linux/sched.h:1821
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118028b)
Location: include/linux/sched.h:1821
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811814e7)
Location: include/linux/sched.h:1821
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a731e)
Location: include/linux/sched.h:1821
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff811fa4be)
Location: include/linux/sched.h:1821
Inline: True
Inline callers:
  - kernel/events/core.c:task_function_call
```
```
In fs/proc/array.c (ffffffff81361338)
Location: include/linux/sched.h:1821
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b685)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/sched/core.c (ffffffff810ddd82)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/idle.c (ffffffff810dfc55)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/idle.c:select_task_rq_idle
```
```
In kernel/sched/fair.c (ffffffff810e6c33)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/rt.c (ffffffff810ef9a2)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810f49d5)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff810f9435)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:select_task_rq_stop
```
```
In kernel/sched/debug.c (ffffffff810fd9c2)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/sched/psi.c (ffffffff811025f5)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/locking/mutex.c (ffffffff81103563)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff81104441)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/rcu/update.c (ffffffff81123e1d)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff8112a68b)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118c0fb)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8118d357)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2b07)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff8120758e)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/events/core.c:task_function_call
```
```
In fs/proc/array.c (ffffffff81379598)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810604f6)
Location: include/linux/sched.h:1864
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
```
```
In kernel/sched/core.c (ffffffff810e3069)
Location: include/linux/sched.h:1864
Inline: True
Inline callers:
  - kernel/sched/core.c:migrate_tasks
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_invoke_on_locked_down_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/idle.c (ffffffff810e7fa5)
Location: include/linux/sched.h:1864
Inline: True
Inline callers:
  - kernel/sched/idle.c:select_task_rq_idle
```
```
In kernel/sched/fair.c (ffffffff810eddbd)
Location: include/linux/sched.h:1864
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/rt.c (ffffffff810f7240)
Location: include/linux/sched.h:1864
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lock_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fe0e5)
Location: include/linux/sched.h:1864
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff81103555)
Location: include/linux/sched.h:1864
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:select_task_rq_stop
```
```
In kernel/sched/debug.c (ffffffff81105afb)
Location: include/linux/sched.h:1864
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/sched/psi.c (ffffffff8110d7c5)
Location: include/linux/sched.h:1864
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_flags_change
```
```
In kernel/locking/mutex.c (ffffffff8110e082)
Location: include/linux/sched.h:1864
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8110f0c0)
Location: include/linux/sched.h:1864
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/rcu/update.c (ffffffff81131473)
Location: include/linux/sched.h:1864
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/rcu/tree.c (ffffffff811389ea)
Location: include/linux/sched.h:1864
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119e673)
Location: include/linux/sched.h:1864
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_pid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811a14b5)
Location: include/linux/sched.h:1864
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811a2a71)
Location: include/linux/sched.h:1864
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811caff8)
Location: include/linux/sched.h:1864
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
```
```
In kernel/events/core.c (ffffffff812329ac)
Location: include/linux/sched.h:1864
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
```
In fs/proc/array.c (ffffffff813c2643)
Location: include/linux/sched.h:1864
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ed56)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
```
```
In kernel/sched/core.c (ffffffff81bdc6dc)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_invoke_on_locked_down_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/idle.c (ffffffff810e5bd5)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/sched/idle.c:select_task_rq_idle
```
```
In kernel/sched/fair.c (ffffffff810ebbdd)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/rt.c (ffffffff810f53d0)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lock_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fc7ce)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/cpudeadline.c (ffffffff810fea7e)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/stop_task.c (ffffffff81101c45)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:select_task_rq_stop
```
```
In kernel/sched/debug.c (ffffffff8110414b)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/sched/psi.c (ffffffff8110aab5)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_flags_change
```
```
In kernel/locking/mutex.c (ffffffff8110b344)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8110c292)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/rcu/update.c (ffffffff81be1e47)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/update.c:trc_inspect_reader
```
```
In kernel/rcu/tree.c (ffffffff81be22cc)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/stop_machine.c (ffffffff81182e10)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/stop_machine.c:print_stop_info
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119b393)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_pid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119e605)
Location: include/linux/sched.h:1925
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8119fbc1)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c86d8)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
```
```
In kernel/events/core.c (ffffffff8123c62c)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
```
In fs/io_uring.c (ffffffff8138df8d)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
```
```
In fs/proc/array.c (ffffffff813d47d1)
Location: include/linux/sched.h:1925
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ec39)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/core.c (ffffffff81bce85f)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_invoke_on_locked_down_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/idle.c (ffffffff810e7b95)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/sched/idle.c:select_task_rq_idle
```
```
In kernel/sched/fair.c (ffffffff810ed73d)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/rt.c (ffffffff810f74a0)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lock_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810feb1f)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/cpudeadline.c (ffffffff81100e4d)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/stop_task.c (ffffffff81103fb5)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:select_task_rq_stop
```
```
In kernel/sched/debug.c (ffffffff81106e6b)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/sched/psi.c (ffffffff8110c6a5)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_flags_change
```
```
In kernel/locking/mutex.c (ffffffff8110d1d4)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8110e0d7)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/rcu/update.c (ffffffff81bd3ed3)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/update.c:trc_inspect_reader
```
```
In kernel/rcu/tree.c (ffffffff81bd4138)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_expired_fqs_timer
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/stop_machine.c (ffffffff81183def)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/stop_machine.c:print_stop_info
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119be22)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_pid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119fd57)
Location: include/linux/sched.h:1997
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811a0821)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c9992)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff81240cdc)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
```
In fs/io_uring.c (ffffffff81397e66)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
```
```
In fs/proc/array.c (ffffffff813db60d)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81068326)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/core.c (ffffffff81ca606e)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_invoke_on_locked_down_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/idle.c (ffffffff810ff225)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - kernel/sched/idle.c:select_task_rq_idle
```
```
In kernel/sched/fair.c (ffffffff8110644d)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/rt.c (ffffffff81111a10)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lock_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff8111a53f)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/sched/cpudeadline.c (ffffffff8111cfc9)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/stop_task.c (ffffffff81121075)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:select_task_rq_stop
```
```
In kernel/sched/debug.c (ffffffff81124a4d)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/sched/psi.c (ffffffff8112b72f)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_flags_change
```
```
In kernel/locking/mutex.c (ffffffff8112ca14)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8112d794)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/rtmutex_api.c (ffffffff81d549c9)
Location: include/linux/sched.h:2114
Inline: True
```
```
In kernel/rcu/update.c (ffffffff8114cf9c)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/update.c:trc_inspect_reader
```
```
In kernel/rcu/tree.c (ffffffff81cae345)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_expired_fqs_timer
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/stop_machine.c (ffffffff811ac181)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - kernel/stop_machine.c:print_stop_info
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811c5d82)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_pid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811c9ce9)
Location: include/linux/sched.h:2114
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811c9f41)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f5470)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff8127b6cc)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
```
In fs/io_uring.c (ffffffff813e39c7)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
```
```
In fs/proc/array.c (ffffffff8142cca1)
Location: include/linux/sched.h:2114
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81074e31)
Location: include/linux/sched.h:2204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/core.c (ffffffff81e559c6)
Location: include/linux/sched.h:2204
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/fair.c (ffffffff81122b0e)
Location: include/linux/sched.h:2204
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/build_policy.c (ffffffff8113a4df)
Location: include/linux/sched.h:2204
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:__dequeue_dl_entity
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/sched/build_policy.c:yield_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:select_task_rq_idle
```
```
In kernel/sched/build_utility.c (ffffffff8114be6e)
Location: include/linux/sched.h:2204
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
  - kernel/sched/build_utility.c:psi_flags_change
  - kernel/sched/build_utility.c:put_prev_task_stop
  - kernel/sched/build_utility.c:select_task_rq_stop
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:print_cpu
```
```
In kernel/locking/mutex.c (ffffffff8114d9c4)
Location: include/linux/sched.h:2204
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff81f25b31)
Location: include/linux/sched.h:2204
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f26570)
Location: include/linux/sched.h:2204
Inline: True
```
```
In kernel/rcu/update.c (ffffffff81173bd8)
Location: include/linux/sched.h:2204
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/rcu/tree.c (ffffffff81e5f8a0)
Location: include/linux/sched.h:2204
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_check_gp_kthread_expired_fqs_timer
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/stop_machine.c (ffffffff811ddb91)
Location: include/linux/sched.h:2204
Inline: True
Inline callers:
  - kernel/stop_machine.c:print_stop_info
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811f9a66)
Location: include/linux/sched.h:2204
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_pid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fd8dc)
Location: include/linux/sched.h:2204
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811fdb7e)
Location: include/linux/sched.h:2204
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122eccb)
Location: include/linux/sched.h:2204
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff812cf58e)
Location: include/linux/sched.h:2204
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
```
In fs/proc/array.c (ffffffff814a6569)
Location: include/linux/sched.h:2204
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In io_uring/io_uring.c (ffffffff81e900ac)
Location: include/linux/sched.h:2204
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_show_fdinfo
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81084f97)
Location: include/linux/sched.h:2231
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/core.c (ffffffff8114232f)
Location: include/linux/sched.h:2231
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/fair.c (ffffffff8114ca07)
Location: include/linux/sched.h:2231
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/build_policy.c (ffffffff81164d9e)
Location: include/linux/sched.h:2231
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/sched/build_policy.c:yield_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:select_task_rq_idle
```
```
In kernel/sched/build_utility.c (ffffffff8117aab5)
Location: include/linux/sched.h:2231
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
  - kernel/sched/build_utility.c:psi_flags_change
  - kernel/sched/build_utility.c:put_prev_task_stop
  - kernel/sched/build_utility.c:select_task_rq_stop
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:print_cpu
```
```
In kernel/locking/mutex.c (ffffffff8117cca7)
Location: include/linux/sched.h:2231
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff820d1502)
Location: include/linux/sched.h:2231
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/rtmutex_api.c (ffffffff8117e389)
Location: include/linux/sched.h:2231
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rtmutex_spin_on_owner
```
```
In kernel/rcu/update.c (ffffffff811ab53e)
Location: include/linux/sched.h:2231
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:trc_check_slow_task
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/rcu/tree.c (ffffffff811afb78)
Location: include/linux/sched.h:2231
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_expired_fqs_timer
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/stop_machine.c (ffffffff81223621)
Location: include/linux/sched.h:2231
Inline: True
Inline callers:
  - kernel/stop_machine.c:print_stop_info
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81240fb6)
Location: include/linux/sched.h:2231
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_pid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff812450ac)
Location: include/linux/sched.h:2231
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8124539e)
Location: include/linux/sched.h:2231
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127aced)
Location: include/linux/sched.h:2231
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff8133785e)
Location: include/linux/sched.h:2231
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
```
In fs/proc/array.c (ffffffff8153bba9)
Location: include/linux/sched.h:2231
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In io_uring/fdinfo.c (ffffffff8179b8cb)
Location: include/linux/sched.h:2231
Inline: True
Inline callers:
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81087807)
Location: include/linux/sched.h:2248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/core.c (ffffffff8114dfaa)
Location: include/linux/sched.h:2248
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:sched_core_next
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/fair.c (ffffffff8115aeb4)
Location: include/linux/sched.h:2248
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/build_policy.c (ffffffff8117553e)
Location: include/linux/sched.h:2248
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/sched/build_policy.c:yield_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:select_task_rq_idle
```
```
In kernel/sched/build_utility.c (ffffffff8118b615)
Location: include/linux/sched.h:2248
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
  - kernel/sched/build_utility.c:psi_flags_change
  - kernel/sched/build_utility.c:put_prev_task_stop
  - kernel/sched/build_utility.c:select_task_rq_stop
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:print_cpu
```
```
In kernel/locking/mutex.c (ffffffff8118d847)
Location: include/linux/sched.h:2248
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff8215578e)
Location: include/linux/sched.h:2248
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/rtmutex_api.c (ffffffff82156473)
Location: include/linux/sched.h:2248
Inline: True
```
```
In kernel/rcu/update.c (ffffffff811bd45e)
Location: include/linux/sched.h:2248
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:trc_check_slow_task
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/rcu/tree.c (ffffffff811c1be8)
Location: include/linux/sched.h:2248
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_expired_fqs_timer
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/stop_machine.c (ffffffff81239cc1)
Location: include/linux/sched.h:2248
Inline: True
Inline callers:
  - kernel/stop_machine.c:print_stop_info
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81258046)
Location: include/linux/sched.h:2248
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_pid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8125c13c)
Location: include/linux/sched.h:2248
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8125c42e)
Location: include/linux/sched.h:2248
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8129280d)
Location: include/linux/sched.h:2248
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_osnoise.c (ffffffff81295a20)
Location: include/linux/sched.h:2248
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:trace_sched_migrate_callback
```
```
In kernel/events/core.c (ffffffff8136862e)
Location: include/linux/sched.h:2248
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
```
In fs/proc/array.c (ffffffff81573ed4)
Location: include/linux/sched.h:2248
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In io_uring/fdinfo.c (ffffffff817dc9f0)
Location: include/linux/sched.h:2248
Inline: True
Inline callers:
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108e407)
Location: include/linux/sched.h:2110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/sched/core.c (ffffffff81159de4)
Location: include/linux/sched.h:2110
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:__do_set_cpus_allowed
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:sched_core_next
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/fair.c (ffffffff8116c176)
Location: include/linux/sched.h:2110
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/build_policy.c (ffffffff8118383e)
Location: include/linux/sched.h:2110
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:__dequeue_dl_entity
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:task_contending
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:find_lock_lowest_rq
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/sched/build_policy.c:yield_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:select_task_rq_idle
```
```
In kernel/sched/build_utility.c (ffffffff81199f45)
Location: include/linux/sched.h:2110
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
  - kernel/sched/build_utility.c:psi_flags_change
  - kernel/sched/build_utility.c:select_task_rq_stop
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:cpuacct_charge
```
```
In kernel/locking/mutex.c (ffffffff8119c1f7)
Location: include/linux/sched.h:2110
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff822385ce)
Location: include/linux/sched.h:2110
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/locking/rtmutex_api.c (ffffffff822392b3)
Location: include/linux/sched.h:2110
Inline: True
```
```
In kernel/rcu/update.c (ffffffff811cc6ca)
Location: include/linux/sched.h:2110
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/update.c:trc_check_slow_task
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:check_holdout_task
  - kernel/rcu/update.c:check_holdout_task
```
```
In kernel/rcu/tree.c (ffffffff811d3da1)
Location: include/linux/sched.h:2110
Inline: True
Inline callers:
  - kernel/rcu/tree.c:show_rcu_nocb_state
  - kernel/rcu/tree.c:show_rcu_nocb_gp_state
  - kernel/rcu/tree.c:rcu_check_gp_kthread_expired_fqs_timer
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/time/tick-sched.c (ffffffff8121c6d5)
Location: include/linux/sched.h:2110
Inline: True
```
```
In kernel/stop_machine.c (ffffffff81253991)
Location: include/linux/sched.h:2110
Inline: True
Inline callers:
  - kernel/stop_machine.c:print_stop_info
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81271f36)
Location: include/linux/sched.h:2110
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_pid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8127607e)
Location: include/linux/sched.h:2110
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8127636e)
Location: include/linux/sched.h:2110
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812adef3)
Location: include/linux/sched.h:2110
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b1080)
Location: include/linux/sched.h:2110
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:trace_sched_migrate_callback
```
```
In kernel/events/core.c (ffffffff8139154e)
Location: include/linux/sched.h:2110
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_attach
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:event_function_call
```
```
In fs/proc/array.c (ffffffff815ac8a3)
Location: include/linux/sched.h:2110
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In arch/arm64/kernel/smp.c (ffff80001009c230)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:secondary_start_kernel
```
```
In kernel/sched/core.c (ffff80001013d6e0)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/idle.c (ffff80001013f7b0)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/idle.c:select_task_rq_idle
```
```
In kernel/sched/fair.c (ffff800010146b48)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/rt.c (ffff800010150c68)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffff8000101570b4)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffff80001015dd18)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:select_task_rq_stop
```
```
In kernel/sched/debug.c (ffff8000101631b8)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/sched/psi.c (ffff8000101672d4)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/locking/mutex.c (ffff800010168664)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffff800010169d34)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/rcu/update.c (ffff800010188f64)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffff800010192b1c)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/debug/kdb/kdb_main.c (ffff800010202ca8)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffff8000102047d4)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffff800010230770)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffff800010290fa0)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/events/core.c:task_function_call
```
```
In fs/proc/array.c (ffff8000104459a8)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/sched/core.c (c038d708)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/idle.c (c038f73c)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/idle.c:select_task_rq_idle
```
```
In kernel/sched/fair.c (c0397184)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_change_group_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:hrtick_start_fair
```
```
In kernel/sched/rt.c (c039c030)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (c03a4c28)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (c03a9b94)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:select_task_rq_stop
```
```
In kernel/sched/debug.c (c03ade04)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/sched/psi.c (c03b40f4)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/locking/mutex.c (c03b4d48)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (c03b6014)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/rcu/update.c (c03d7774)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (c03e0108)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/debug/kdb/kdb_main.c (c0441cbc)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (c04434a8)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (c046c810)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (c04c0d2c)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/events/core.c:task_function_call
```
```
In fs/proc/array.c (c060ab10)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In arch/powerpc/kernel/process.c (c0000000000205bc)
Location: include/linux/sched.h:1814
Inline: True
```
```
In arch/powerpc/xmon/xmon.c (c00000000010930c)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:show_task
```
```
In kernel/sched/core.c (c00000000018c548)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/idle.c (c00000000018e838)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/idle.c:select_task_rq_idle
```
```
In kernel/sched/fair.c (c000000000197ff0)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:attach_task
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/rt.c (c0000000001a2544)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (c0000000001abb70)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (c0000000001b2948)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:select_task_rq_stop
```
```
In kernel/sched/debug.c (c0000000001b99c8)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
```
```
In kernel/sched/psi.c (c0000000001bee34)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/locking/mutex.c (c0000000001c04a4)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (c0000000001c1c0c)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/rcu/update.c (c0000000001e3264)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (c0000000001eddf4)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/debug/kdb/kdb_main.c (c00000000027cf40)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (c00000000027f394)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002bae64)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (c00000000033eb20)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/events/core.c:task_function_call
```
```
In fs/proc/array.c (c00000000055b434)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/sched/core.c (ffffffe0000ec568)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/idle.c (ffffffe0000edc2e)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/idle.c:select_task_rq_idle
```
```
In kernel/sched/fair.c (ffffffe0000f1d20)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:hrtick_start_fair
```
```
In kernel/sched/rt.c (ffffffe0000f932c)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffe0000fdf66)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffe00010226a)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:select_task_rq_stop
```
```
In kernel/sched/debug.c (ffffffe0001053ec)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/sched/psi.c (ffffffe000109916)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/rcu/update.c (ffffffe00011e2e4)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffe00012541a)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe0001890e2)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffe0001c3baa)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/events/core.c:task_function_call
```
```
In fs/proc/array.c (ffffffe0002db9b0)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b205)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d7f72)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/idle.c (ffffffff810d9e45)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/idle.c:select_task_rq_idle
```
```
In kernel/sched/fair.c (ffffffff810e0de3)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/rt.c (ffffffff810e8ec1)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810eddd5)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff810f2835)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:select_task_rq_stop
```
```
In kernel/sched/debug.c (ffffffff810f6ce2)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/sched/psi.c (ffffffff810fb905)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/locking/mutex.c (ffffffff810fc873)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff810fd751)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/rcu/update.c (ffffffff8111c3fd)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff81122c6b)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118471b)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81185977)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab127)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff811ffbae)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/events/core.c:task_function_call
```
```
In fs/proc/array.c (ffffffff81371b78)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104b375)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c6943)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/idle.c (ffffffff810c8e35)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/idle.c:select_task_rq_idle
```
```
In kernel/sched/fair.c (ffffffff810cfec3)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/rt.c (ffffffff810d8d5d)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810dde65)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff810e28a5)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:select_task_rq_stop
```
```
In kernel/sched/debug.c (ffffffff810e6eb2)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/sched/psi.c (ffffffff810ebb25)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/locking/mutex.c (ffffffff810eca83)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff810ed94b)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/rcu/update.c (ffffffff8110d342)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff81115724)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8117785b)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81178ab7)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e437)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff811f28fe)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/events/core.c:task_function_call
```
```
In fs/proc/array.c (ffffffff81362654)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b635)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d4762)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/idle.c (ffffffff810d6185)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/idle.c:select_task_rq_idle
```
```
In kernel/sched/fair.c (ffffffff810dd163)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/rt.c (ffffffff810e5ed2)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
```
```
In kernel/sched/deadline.c (ffffffff810eaf05)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff810ef965)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:select_task_rq_stop
```
```
In kernel/sched/debug.c (ffffffff810f3ef2)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/sched/psi.c (ffffffff810f8ac5)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/locking/mutex.c (ffffffff810f9a33)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff810fa911)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/rcu/update.c (ffffffff8111a2ed)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff81120b5b)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811824eb)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81183747)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a8ef7)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff811fd97e)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/events/core.c:task_function_call
```
```
In fs/proc/array.c (ffffffff8136f648)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105caf5)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/sched/core.c (ffffffff810dfb6b)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:yield_to
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:sched_exec
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:migrate_swap_stop
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:perf_trace_sched_migrate_task
  - kernel/sched/core.c:perf_trace_sched_wakeup_template
  - kernel/sched/core.c:trace_event_raw_event_sched_migrate_task
  - kernel/sched/core.c:trace_event_raw_event_sched_wakeup_template
```
```
In kernel/sched/idle.c (ffffffff810e1a95)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/idle.c:select_task_rq_idle
```
```
In kernel/sched/fair.c (ffffffff810e8ed0)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/rt.c (ffffffff810f0a55)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f5ef5)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:find_later_rq
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/stop_task.c (ffffffff810fa9b5)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:select_task_rq_stop
```
```
In kernel/sched/debug.c (ffffffff810feee5)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/sched/psi.c (ffffffff81103c15)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/locking/mutex.c (ffffffff81104ba5)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_spin_on_owner
```
```
In kernel/locking/rwsem.c (ffffffff81105ae3)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_spin_on_owner
```
```
In kernel/rcu/update.c (ffffffff81125a6d)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff8112ce30)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118fe0b)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81191087)
Location: include/linux/sched.h:1814
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b6d37)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/events/core.c (ffffffff8120c7be)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - kernel/events/core.c:task_function_call
```
```
In fs/proc/array.c (ffffffff81382fd8)
Location: include/linux/sched.h:1814
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
</details>
</li>
</ul>

## Differences
