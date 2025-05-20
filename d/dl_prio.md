# Function: <code>dl_prio</code>

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
In kernel/sched/core.c (ffffffff810a97bf)
Location: include/linux/sched/deadline.h:12
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_can_attach
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:12
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c122b)
Location: include/linux/sched/deadline.h:12
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:pick_next_task_dl
```
```
In kernel/locking/rtmutex.c (ffffffff810cacfa)
Location: include/linux/sched/deadline.h:12
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:__rt_mutex_adjust_prio
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
```
```
In kernel/time/hrtimer.c (ffffffff810efdfd)
Location: include/linux/sched/deadline.h:12
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81157339)
Location: include/linux/sched/deadline.h:12
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff810b1200)
Location: include/linux/sched/deadline.h:12
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:12
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c5175)
Location: include/linux/sched/deadline.h:12
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/locking/rtmutex.c (ffffffff810d025f)
Location: include/linux/sched/deadline.h:12
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:__rt_mutex_adjust_prio
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/time/hrtimer.c (ffffffff810f6c3d)
Location: include/linux/sched/deadline.h:12
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81161bb9)
Location: include/linux/sched/deadline.h:12
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff810b7480)
Location: include/linux/sched/deadline.h:12
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:12
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810cb1a5)
Location: include/linux/sched/deadline.h:12
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/locking/rtmutex.c (ffffffff810d6c4f)
Location: include/linux/sched/deadline.h:12
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:__rt_mutex_adjust_prio
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/time/hrtimer.c (ffffffff810fdcf1)
Location: include/linux/sched/deadline.h:12
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116c719)
Location: include/linux/sched/deadline.h:12
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff810b372b)
Location: include/linux/sched/deadline.h:14
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:14
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c5b55)
Location: include/linux/sched/deadline.h:14
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rtmutex.c (ffffffff810d5c27)
Location: include/linux/sched/deadline.h:14
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/time/hrtimer.c (ffffffff810fffa7)
Location: include/linux/sched/deadline.h:14
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116faba)
Location: include/linux/sched/deadline.h:14
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff810ba99b)
Location: include/linux/sched/deadline.h:15
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:15
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810cd276)
Location: include/linux/sched/deadline.h:15
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rtmutex.c (ffffffff810ddbe7)
Location: include/linux/sched/deadline.h:15
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/time/hrtimer.c (ffffffff8110ad97)
Location: include/linux/sched/deadline.h:15
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8117cbcc)
Location: include/linux/sched/deadline.h:15
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff810c1e0b)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:11
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810d5115)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rtmutex.c (ffffffff810e6263)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/time/hrtimer.c (ffffffff81116791)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81121f6a)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118bc39)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff810cb13b)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:11
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810deb45)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rtmutex.c (ffffffff810f17e3)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/time/hrtimer.c (ffffffff81121dd1)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112d68a)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81199659)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff810d2de4)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:11
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810e5b95)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rtmutex.c (ffffffff810fa0d0)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/time/hrtimer.c (ffffffff8112c721)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113804f)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a7279)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff810dd274)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:11
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f4604)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rtmutex.c (ffffffff81105ec0)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/time/hrtimer.c (ffffffff81138733)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114414a)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2a69)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff810e5e34)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:11
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810fddf4)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rtmutex.c (ffffffff81110e20)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/time/hrtimer.c (ffffffff81147547)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81153d4e)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cb110)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff810e3b84)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:11
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810fc3c4)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rtmutex.c (ffffffff8110dfd0)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/time/hrtimer.c (ffffffff81143a5e)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811501d2)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c87f0)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff810e5b54)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:11
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810fe6de)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rtmutex.c (ffffffff81c37358)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/time/hrtimer.c (ffffffff81144c0e)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81151602)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c9b3f)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff810fcc38)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:11
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff81119ffe)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rtmutex_api.c (ffffffff81d5602c)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/time/hrtimer.c (ffffffff8116845e)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81175a02)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f539f)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff81119590)
Location: include/linux/sched/deadline.h:13
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/build_policy.c (ffffffff81139d40)
Location: include/linux/sched/deadline.h:13
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:__dequeue_dl_entity
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f27fd8)
Location: include/linux/sched/deadline.h:13
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/time/hrtimer.c (ffffffff8119be9d)
Location: include/linux/sched/deadline.h:13
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811aa9b6)
Location: include/linux/sched/deadline.h:13
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122ebfc)
Location: include/linux/sched/deadline.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff81140e70)
Location: include/linux/sched/deadline.h:13
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/build_policy.c (ffffffff811645a0)
Location: include/linux/sched/deadline.h:13
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d3b88)
Location: include/linux/sched/deadline.h:13
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/time/hrtimer.c (ffffffff811da80d)
Location: include/linux/sched/deadline.h:13
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811eaaa6)
Location: include/linux/sched/deadline.h:13
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127ac1c)
Location: include/linux/sched/deadline.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff811473d9)
Location: include/linux/sched/deadline.h:13
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/build_policy.c (ffffffff81174d40)
Location: include/linux/sched/deadline.h:13
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
```
```
In kernel/locking/rtmutex_api.c (ffffffff82157e08)
Location: include/linux/sched/deadline.h:13
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811ff1f6)
Location: include/linux/sched/deadline.h:13
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
```
In kernel/cgroup/cgroup.c (ffffffff81225a70)
Location: include/linux/sched/deadline.h:13
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
```
```
In kernel/cgroup/cpuset.c (ffffffff8122e246)
Location: include/linux/sched/deadline.h:13
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8129273c)
Location: include/linux/sched/deadline.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff81152c09)
Location: include/linux/sched/deadline.h:15
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/build_policy.c (ffffffff81183040)
Location: include/linux/sched/deadline.h:15
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:yield_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
```
```
In kernel/locking/rtmutex_api.c (ffffffff8223ac78)
Location: include/linux/sched/deadline.h:15
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:try_to_take_rt_mutex
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/time/posix-cpu-timers.c (ffffffff812155bd)
Location: include/linux/sched/deadline.h:15
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
```
In kernel/cgroup/cgroup.c (ffffffff8123d700)
Location: include/linux/sched/deadline.h:15
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
```
```
In kernel/cgroup/cpuset.c (ffffffff8124679a)
Location: include/linux/sched/deadline.h:15
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ade22)
Location: include/linux/sched/deadline.h:15
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffff80001013cd6c)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:11
Inline: True
```
```
In kernel/sched/deadline.c (ffff800010156a9c)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rtmutex.c (ffff80001016c070)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/time/hrtimer.c (ffff8000101a23e0)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ae6cc)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffff8000102306cc)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (c038d1d4)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:11
Inline: True
```
```
In kernel/sched/deadline.c (c03a475c)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rtmutex.c (c03b79a8)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/sched/deadline.h:11
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (c03f974c)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (c046c6c4)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (c00000000018b4cc)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:11
Inline: True
```
```
In kernel/sched/deadline.c (c0000000001ab4d8)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rtmutex.c (c0000000001c3bd0)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/time/hrtimer.c (c0000000002038cc)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (c000000000212c5c)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002bad60)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffe0000ec552)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:11
Inline: True
```
```
In kernel/sched/deadline.c (ffffffe0000fdaa6)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rtmutex.c (ffffffe00010c2a0)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/time/hrtimer.c (ffffffe00012f4ec)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffe000138188)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe00018905c)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff810d7464)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:11
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810eda04)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rtmutex.c (ffffffff810ff1d0)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/time/hrtimer.c (ffffffff81130ee3)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113c8fa)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab089)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff810c5d84)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:11
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810dda94)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rtmutex.c (ffffffff810ef3c0)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/time/hrtimer.c (ffffffff81123953)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112f36a)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e399)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff810d40c4)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:11
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810eab34)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rtmutex.c (ffffffff810fc390)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/time/hrtimer.c (ffffffff8112ec03)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113a61a)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a8e59)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff810df044)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/rt.c (0)
Location: include/linux/sched/deadline.h:11
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f5ae4)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/locking/rtmutex.c (ffffffff811075b0)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_enqueue_pi
  - kernel/locking/rtmutex.c:rt_mutex_enqueue
```
```
In kernel/time/hrtimer.c (ffffffff8113b603)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811470da)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b6c99)
Location: include/linux/sched/deadline.h:11
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
</details>
</li>
</ul>

## Differences
