# Function: <code>context_tracking_enabled</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (0)
Location: include/linux/context_tracking_state.h:50
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/context_tracking_state.h:50
Inline: False
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
In kernel/rcu/tree.c (0)
Location: include/linux/context_tracking_state.h:50
Inline: False
```
```
In kernel/entry/common.c (0)
Location: include/linux/context_tracking_state.h:50
Inline: True
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
In kernel/rcu/tree.c (0)
Location: include/linux/context_tracking_state.h:50
Inline: False
```
```
In kernel/entry/common.c (0)
Location: include/linux/context_tracking_state.h:50
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
In kernel/rcu/tree.c (0)
Location: include/linux/context_tracking_state.h:50
Inline: False
```
```
In kernel/entry/common.c (0)
Location: include/linux/context_tracking_state.h:50
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
In kernel/rcu/tree.c (0)
Location: include/linux/context_tracking_state.h:50
Inline: True
```
```
In kernel/entry/common.c (0)
Location: include/linux/context_tracking_state.h:50
Inline: True
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
In kernel/entry/common.c (0)
Location: include/linux/context_tracking_state.h:141
Inline: True
```
```
In kernel/context_tracking.c (0)
Location: include/linux/context_tracking_state.h:141
Inline: True
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
In kernel/entry/common.c (0)
Location: include/linux/context_tracking_state.h:143
Inline: True
```
```
In kernel/context_tracking.c (0)
Location: include/linux/context_tracking_state.h:143
Inline: True
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
In arch/x86/entry/common.c (ffffffff8221b8b5)
Location: include/linux/context_tracking_state.h:106
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_int80_emulation
  - arch/x86/entry/common.c:do_int80_emulation
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:do_syscall_64
```
```
In kernel/softirq.c (ffffffff81108ff2)
Location: include/linux/context_tracking_state.h:106
Inline: True
Inline callers:
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:irq_enter_rcu
```
```
In kernel/sched/core.c (ffffffff8115533e)
Location: include/linux/context_tracking_state.h:106
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_nohz_cpu
```
```
In kernel/sched/fair.c (ffffffff8117249c)
Location: include/linux/context_tracking_state.h:106
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/build_policy.c (ffffffff8117d3ff)
Location: include/linux/context_tracking_state.h:106
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:__dequeue_dl_entity
  - kernel/sched/build_policy.c:kcpustat_cpu_fetch
  - kernel/sched/build_policy.c:kcpustat_field
  - kernel/sched/build_policy.c:task_gtime
  - kernel/sched/build_policy.c:account_process_tick
  - kernel/sched/build_policy.c:dequeue_rt_stack
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff8118fb54)
Location: include/linux/context_tracking_state.h:106
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:dequeue_task_stop
  - kernel/sched/build_utility.c:enqueue_task_stop
  - kernel/sched/build_utility.c:clear_sched_clock_stable
  - kernel/sched/build_utility.c:__set_sched_clock_stable
```
```
In kernel/rcu/update.c (ffffffff811cc7fa)
Location: include/linux/context_tracking_state.h:106
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/update.c:check_holdout_task
```
```
In kernel/rcu/tree.c (ffffffff811d9e79)
Location: include/linux/context_tracking_state.h:106
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
  - kernel/rcu/tree.c:rcutree_offline_cpu
  - kernel/rcu/tree.c:rcutree_dead_cpu
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:__rcu_irq_enter_check_tick
  - kernel/rcu/tree.c:__rcu_irq_enter_check_tick
```
```
In kernel/entry/common.c (ffffffff82223e00)
Location: include/linux/context_tracking_state.h:106
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:irqentry_enter_from_user_mode
  - kernel/entry/common.c:irqentry_enter_from_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
  - kernel/entry/common.c:syscall_exit_to_user_mode_prepare
  - kernel/entry/common.c:syscall_exit_to_user_mode_prepare
  - kernel/entry/common.c:syscall_enter_from_user_mode_prepare
  - kernel/entry/common.c:syscall_enter_from_user_mode_prepare
  - kernel/entry/common.c:irqentry_enter
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81214ecb)
Location: include/linux/context_tracking_state.h:106
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - kernel/time/posix-cpu-timers.c:arm_timer
  - kernel/time/posix-cpu-timers.c:arm_timer
  - kernel/time/posix-cpu-timers.c:update_rlimit_cpu
```
```
In kernel/time/tick-common.c (ffffffff81218c7b)
Location: include/linux/context_tracking_state.h:106
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-sched.c (ffffffff8121d0ed)
Location: include/linux/context_tracking_state.h:106
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:can_stop_idle_tick
  - kernel/time/tick-sched.c:__tick_nohz_task_switch
```
```
In kernel/watchdog.c (ffffffff83909c95)
Location: include/linux/context_tracking_state.h:106
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
```
```
In kernel/events/core.c (ffffffff81394be7)
Location: include/linux/context_tracking_state.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:__perf_event_account_interrupt
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:perf_event_task_tick
```
```
In kernel/context_tracking.c (ffffffff813b0c25)
Location: include/linux/context_tracking_state.h:106
Inline: True
Inline callers:
  - kernel/context_tracking.c:user_exit_callable
  - kernel/context_tracking.c:user_enter_callable
  - kernel/context_tracking.c:ct_nmi_enter
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
