# Function: <code>context_tracking_is_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (0)
Location: include/linux/context_tracking_state.h:45
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (0)
Location: include/linux/context_tracking_state.h:45
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (0)
Location: include/linux/context_tracking_state.h:45
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (0)
Location: include/linux/context_tracking_state.h:45
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (0)
Location: include/linux/context_tracking_state.h:46
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (0)
Location: include/linux/context_tracking_state.h:46
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (0)
Location: include/linux/context_tracking_state.h:46
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (0)
Location: include/linux/context_tracking_state.h:46
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (0)
Location: include/linux/context_tracking_state.h:46
Inline: True
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/traps.c (0)
Location: include/linux/context_tracking_state.h:46
Inline: True
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (0)
Location: include/linux/context_tracking_state.h:46
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
In arch/x86/entry/common.c (ffffffff81002da8)
Location: include/linux/context_tracking_state.h:29
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/kernel/kvm.c (ffffffff81066f30)
Location: include/linux/context_tracking_state.h:29
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8106edd5)
Location: include/linux/context_tracking_state.h:29
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_page_fault
  - arch/x86/mm/fault.c:do_page_fault
```
```
In kernel/softirq.c (ffffffff810903b9)
Location: include/linux/context_tracking_state.h:29
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
```
```
In kernel/sched/core.c (ffffffff81a2b4e4)
Location: include/linux/context_tracking_state.h:29
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:schedule_user
  - kernel/sched/core.c:schedule_user
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_nohz_cpu
```
```
In kernel/sched/clock.c (ffffffff828ae79d)
Location: include/linux/context_tracking_state.h:29
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_init_late
  - kernel/sched/clock.c:clear_sched_clock_stable
```
```
In kernel/sched/cputime.c (ffffffff810c8a15)
Location: include/linux/context_tracking_state.h:29
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_gtime
  - kernel/sched/cputime.c:account_process_tick
```
```
In kernel/sched/fair.c (ffffffff810cfc05)
Location: include/linux/context_tracking_state.h:29
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
```
In kernel/sched/rt.c (ffffffff810d6d7c)
Location: include/linux/context_tracking_state.h:29
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810dc0d0)
Location: include/linux/context_tracking_state.h:29
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
```
In kernel/sched/stop_task.c (ffffffff810e2959)
Location: include/linux/context_tracking_state.h:29
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:dequeue_task_stop
  - kernel/sched/stop_task.c:dequeue_task_stop
  - kernel/sched/stop_task.c:enqueue_task_stop
  - kernel/sched/stop_task.c:enqueue_task_stop
```
```
In kernel/sched/membarrier.c (ffffffff810eac4d)
Location: include/linux/context_tracking_state.h:29
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
```
In kernel/rcu/update.c (ffffffff8110d36b)
Location: include/linux/context_tracking_state.h:29
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff811145d4)
Location: include/linux/context_tracking_state.h:29
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In kernel/time/timer.c (ffffffff81120549)
Location: include/linux/context_tracking_state.h:29
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112f8a6)
Location: include/linux/context_tracking_state.h:29
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:set_process_cpu_timer
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:arm_timer
  - kernel/time/posix-cpu-timers.c:arm_timer
```
```
In kernel/time/tick-common.c (ffffffff811320fd)
Location: include/linux/context_tracking_state.h:29
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81134b49)
Location: include/linux/context_tracking_state.h:29
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_irq_exit
  - kernel/time/tick-sched.c:__tick_nohz_task_switch
```
```
In kernel/watchdog.c (ffffffff828b5649)
Location: include/linux/context_tracking_state.h:29
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
```
```
In kernel/events/core.c (ffffffff811fb2d4)
Location: include/linux/context_tracking_state.h:29
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_event_task_tick
```
```
In kernel/context_tracking.c (ffffffff8120aa55)
Location: include/linux/context_tracking_state.h:29
Inline: True
Inline callers:
  - kernel/context_tracking.c:context_tracking_user_exit
  - kernel/context_tracking.c:context_tracking_user_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (0)
Location: include/linux/context_tracking_state.h:46
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (0)
Location: include/linux/context_tracking_state.h:46
Inline: True
```
</details>
</li>
</ul>

## Differences
