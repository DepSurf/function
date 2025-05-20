# Function: <code>dl_task</code>

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
In kernel/sched/core.c (ffffffff810a97bb)
Location: include/linux/sched/deadline.h:19
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:task_can_attach
```
```
In kernel/sched/rt.c (ffffffff810c0d99)
Location: include/linux/sched/deadline.h:19
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c122b)
Location: include/linux/sched/deadline.h:19
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:pick_next_task_dl
```
```
In kernel/time/hrtimer.c (ffffffff810efdfd)
Location: include/linux/sched/deadline.h:19
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81157339)
Location: include/linux/sched/deadline.h:19
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
Location: include/linux/sched/deadline.h:19
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (ffffffff810c4829)
Location: include/linux/sched/deadline.h:19
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c5175)
Location: include/linux/sched/deadline.h:19
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/time/hrtimer.c (ffffffff810f6c3d)
Location: include/linux/sched/deadline.h:19
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81161bb9)
Location: include/linux/sched/deadline.h:19
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
Location: include/linux/sched/deadline.h:19
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (ffffffff810ca874)
Location: include/linux/sched/deadline.h:19
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810cb1a5)
Location: include/linux/sched/deadline.h:19
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
```
```
In kernel/time/hrtimer.c (ffffffff810fdcf1)
Location: include/linux/sched/deadline.h:19
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116c719)
Location: include/linux/sched/deadline.h:19
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
Location: include/linux/sched/deadline.h:21
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (ffffffff810c4384)
Location: include/linux/sched/deadline.h:21
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c5b55)
Location: include/linux/sched/deadline.h:21
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/hrtimer.c (ffffffff810fffa7)
Location: include/linux/sched/deadline.h:21
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116faba)
Location: include/linux/sched/deadline.h:21
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
Location: include/linux/sched/deadline.h:22
Inline: True
Inline callers:
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (ffffffff810cbc64)
Location: include/linux/sched/deadline.h:22
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810cd276)
Location: include/linux/sched/deadline.h:22
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/hrtimer.c (ffffffff8110ad97)
Location: include/linux/sched/deadline.h:22
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8117cbcc)
Location: include/linux/sched/deadline.h:22
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
In kernel/sched/core.c (ffffffff810c2816)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (ffffffff810d43e4)
Location: include/linux/sched/deadline.h:18
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810d5115)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/hrtimer.c (ffffffff81116791)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81121f6a)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118bc39)
Location: include/linux/sched/deadline.h:18
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
In kernel/sched/core.c (ffffffff810cbb16)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (ffffffff810dd8f4)
Location: include/linux/sched/deadline.h:18
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810deb45)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/hrtimer.c (ffffffff81121dd1)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112d68a)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81199659)
Location: include/linux/sched/deadline.h:18
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
In kernel/sched/core.c (ffffffff810d3b86)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (ffffffff810e48ec)
Location: include/linux/sched/deadline.h:18
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810e5b95)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/hrtimer.c (ffffffff8112c721)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113804f)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a7279)
Location: include/linux/sched/deadline.h:18
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
In kernel/sched/core.c (ffffffff810de066)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (ffffffff810efabc)
Location: include/linux/sched/deadline.h:18
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f4604)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/hrtimer.c (ffffffff81138733)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114414a)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2a69)
Location: include/linux/sched/deadline.h:18
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
In kernel/sched/core.c (ffffffff810e661a)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (ffffffff810f949d)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
```
```
In kernel/sched/deadline.c (ffffffff810fddf4)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/hrtimer.c (ffffffff81147547)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81153d4e)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cb110)
Location: include/linux/sched/deadline.h:18
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
In kernel/sched/core.c (ffffffff810e451a)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (ffffffff810f778d)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
```
```
In kernel/sched/deadline.c (ffffffff810fc3c4)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/hrtimer.c (ffffffff81143a5e)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811501d2)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c87f0)
Location: include/linux/sched/deadline.h:18
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
In kernel/sched/core.c (ffffffff810e64ca)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (ffffffff810f9c9d)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
```
```
In kernel/sched/deadline.c (ffffffff810fe6de)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/hrtimer.c (ffffffff81144c0e)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81151602)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c9b3f)
Location: include/linux/sched/deadline.h:18
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
In kernel/sched/core.c (ffffffff810fda01)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (ffffffff81112bed)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
```
```
In kernel/sched/deadline.c (ffffffff81119ffe)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/hrtimer.c (ffffffff8116845e)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81175a02)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f539a)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff8111a41e)
Location: include/linux/sched/deadline.h:20
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/build_policy.c (ffffffff81139d40)
Location: include/linux/sched/deadline.h:20
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
```
```
In kernel/time/hrtimer.c (ffffffff8119be9d)
Location: include/linux/sched/deadline.h:20
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811aa9b6)
Location: include/linux/sched/deadline.h:20
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122ebf3)
Location: include/linux/sched/deadline.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff81141c8e)
Location: include/linux/sched/deadline.h:20
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/build_policy.c (ffffffff811645a0)
Location: include/linux/sched/deadline.h:20
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
```
```
In kernel/time/hrtimer.c (ffffffff811da80d)
Location: include/linux/sched/deadline.h:20
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811eaaa6)
Location: include/linux/sched/deadline.h:20
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127ac13)
Location: include/linux/sched/deadline.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff8114d95e)
Location: include/linux/sched/deadline.h:20
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/build_policy.c (ffffffff81174d40)
Location: include/linux/sched/deadline.h:20
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811ff1f6)
Location: include/linux/sched/deadline.h:20
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
```
```
In kernel/cgroup/cgroup.c (ffffffff81225a70)
Location: include/linux/sched/deadline.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
```
```
In kernel/cgroup/cpuset.c (ffffffff8122e246)
Location: include/linux/sched/deadline.h:20
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81292733)
Location: include/linux/sched/deadline.h:20
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffffffff8115976e)
Location: include/linux/sched/deadline.h:22
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/build_policy.c (ffffffff81183040)
Location: include/linux/sched/deadline.h:22
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:pick_next_pushable_dl_task
  - kernel/sched/build_policy.c:find_lock_later_rq
  - kernel/sched/build_policy.c:balance_dl
  - kernel/sched/build_policy.c:yield_task_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
```
```
In kernel/time/posix-cpu-timers.c (ffffffff812155bd)
Location: include/linux/sched/deadline.h:22
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
```
In kernel/cgroup/cgroup.c (ffffffff8123d700)
Location: include/linux/sched/deadline.h:22
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
```
```
In kernel/cgroup/cpuset.c (ffffffff8124679a)
Location: include/linux/sched/deadline.h:22
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ade19)
Location: include/linux/sched/deadline.h:22
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
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
In kernel/sched/core.c (ffff80001013dab0)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (ffff800010150e8c)
Location: include/linux/sched/deadline.h:18
Inline: True
```
```
In kernel/sched/deadline.c (ffff800010156a9c)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/hrtimer.c (ffff8000101a23e0)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ae6cc)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffff8000102306cc)
Location: include/linux/sched/deadline.h:18
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
In kernel/sched/core.c (c038da8c)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (c039c1cc)
Location: include/linux/sched/deadline.h:18
Inline: True
```
```
In kernel/sched/deadline.c (c03a475c)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/hrtimer.c (c03ec0f0)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (c03f974c)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (c046c6c4)
Location: include/linux/sched/deadline.h:18
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
In kernel/sched/core.c (c00000000018ca4c)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (c0000000001a2834)
Location: include/linux/sched/deadline.h:18
Inline: True
```
```
In kernel/sched/deadline.c (c0000000001ab4d8)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/hrtimer.c (c0000000002038cc)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (c000000000212c5c)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002bad60)
Location: include/linux/sched/deadline.h:18
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
In kernel/sched/core.c (ffffffe0000ec9a4)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (ffffffe0000f94ec)
Location: include/linux/sched/deadline.h:18
Inline: True
```
```
In kernel/sched/deadline.c (ffffffe0000fdaa6)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/hrtimer.c (ffffffe00012f4ec)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffe000138188)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe00018905c)
Location: include/linux/sched/deadline.h:18
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
In kernel/sched/core.c (ffffffff810d8256)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (ffffffff810e93ac)
Location: include/linux/sched/deadline.h:18
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810eda04)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/hrtimer.c (ffffffff81130ee3)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113c8fa)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab089)
Location: include/linux/sched/deadline.h:18
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
In kernel/sched/core.c (ffffffff810c6c66)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (ffffffff810d8e7c)
Location: include/linux/sched/deadline.h:18
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810dda94)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/hrtimer.c (ffffffff81123953)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112f36a)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e399)
Location: include/linux/sched/deadline.h:18
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
In kernel/sched/core.c (ffffffff810d4a46)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (ffffffff810e5fec)
Location: include/linux/sched/deadline.h:18
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810eab34)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/hrtimer.c (ffffffff8112ec03)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113a61a)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a8e59)
Location: include/linux/sched/deadline.h:18
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
In kernel/sched/core.c (ffffffff810dfe36)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
```
```
In kernel/sched/rt.c (ffffffff810f07fc)
Location: include/linux/sched/deadline.h:18
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f5ae4)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:pick_next_pushable_dl_task
  - kernel/sched/deadline.c:find_lock_later_rq
  - kernel/sched/deadline.c:balance_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/hrtimer.c (ffffffff8113b603)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811470da)
Location: include/linux/sched/deadline.h:18
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b6c99)
Location: include/linux/sched/deadline.h:18
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
