# Function: <code>raw_spin_rq_lock_nested</code>

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
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void raw_spin_rq_lock_nested(struct rq *rq, int subclass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f2600)
Location: kernel/sched/core.c:467
Inline: True
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:balance_push_set
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:sched_ttwu_pending
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:resched_cpu
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/idle.c:dequeue_task_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:find_lock_lowest_rq
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/topology.c:rq_attach_root
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
**Symbols:**

```
ffffffff810f2600-ffffffff810f266c: raw_spin_rq_lock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void raw_spin_rq_lock_nested(struct rq *rq, int subclass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110e480)
Location: kernel/sched/core.c:537
Inline: True
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/core.c:_raw_spin_rq_lock_irqsave
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:_raw_spin_rq_lock_irqsave
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_policy.c:dequeue_task_idle
  - kernel/sched/build_utility.c:psi_memstall_leave
  - kernel/sched/build_utility.c:psi_memstall_enter
  - kernel/sched/build_utility.c:_raw_spin_rq_lock_irqsave
```
**Symbols:**

```
ffffffff8110e480-ffffffff8110e50e: raw_spin_rq_lock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void raw_spin_rq_lock_nested(struct rq *rq, int subclass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811351c0)
Location: kernel/sched/core.c:530
Inline: True
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/core.c:_raw_spin_rq_lock_irqsave
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:_raw_spin_rq_lock_irqsave
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_policy.c:dequeue_task_idle
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_memstall_enter
  - kernel/sched/build_utility.c:_raw_spin_rq_lock_irqsave
```
**Symbols:**

```
ffffffff811351c0-ffffffff8113524e: raw_spin_rq_lock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void raw_spin_rq_lock_nested(struct rq *rq, int subclass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811443d0)
Location: kernel/sched/core.c:551
Inline: True
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/core.c:_raw_spin_rq_lock_irqsave
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:__cfsb_csd_unthrottle
  - kernel/sched/fair.c:_raw_spin_rq_lock_irqsave
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_policy.c:dequeue_task_idle
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_memstall_enter
  - kernel/sched/build_utility.c:_raw_spin_rq_lock_irqsave
```
**Symbols:**

```
ffffffff811443d0-ffffffff8114445e: raw_spin_rq_lock_nested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void raw_spin_rq_lock_nested(struct rq *rq, int subclass);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114f8f0)
Location: kernel/sched/core.c:552
Inline: True
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:__balance_push_cpu_stop
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_tick_remote
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/core.c:double_rq_lock
  - kernel/sched/core.c:_raw_spin_rq_lock_irqsave
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:active_load_balance_cpu_stop
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:__cfsb_csd_unthrottle
  - kernel/sched/fair.c:_raw_spin_rq_lock_irqsave
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_policy.c:dequeue_task_idle
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:psi_memstall_enter
  - kernel/sched/build_utility.c:_raw_spin_rq_lock_irqsave
```
**Symbols:**

```
ffffffff8114f8f0-ffffffff8114f97e: raw_spin_rq_lock_nested (STB_GLOBAL)
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
