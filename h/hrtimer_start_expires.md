# Function: <code>hrtimer_start_expires</code>

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
In kernel/softirq.c (ffffffff81084e0b)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
```
```
In kernel/signal.c (ffffffff8108d76a)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (ffffffff810a67c9)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick_start
```
```
In kernel/sched/fair.c (ffffffff810b3ecd)
Location: include/linux/hrtimer.h:399
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810c09b9)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/locking/rtmutex.c (ffffffff81822c45)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
```
In kernel/time/hrtimer.c (ffffffff81823673)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/posix-timers.c (ffffffff810f1203)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:do_schedule_next_timer
```
```
In kernel/time/alarmtimer.c (ffffffff810fb193)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/tick-sched.c (ffffffff810fe642)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff811000df)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/events/core.c (ffffffff8117b03e)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff812584f0)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:do_timerfd_gettime
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
In kernel/softirq.c (ffffffff8108811b)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
```
```
In kernel/signal.c (ffffffff81090638)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (ffffffff810acedd)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (ffffffff810b693d)
Location: include/linux/hrtimer.h:399
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810c4418)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/locking/rtmutex.c (ffffffff8189d19c)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
```
In kernel/time/hrtimer.c (ffffffff8189e2e3)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/posix-timers.c (ffffffff810f8282)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:do_schedule_next_timer
```
```
In kernel/time/alarmtimer.c (ffffffff81102493)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/tick-sched.c (ffffffff81106139)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart
```
```
In kernel/futex.c (ffffffff811070de)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/events/core.c (ffffffff8118c52e)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff81280f9e)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/softirq.c (ffffffff8108d07b)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
```
```
In kernel/signal.c (ffffffff810955b0)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (ffffffff810b2f6d)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (ffffffff810bc0d9)
Location: include/linux/hrtimer.h:399
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810ca46f)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/locking/rtmutex.c (ffffffff818d20f3)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
```
In kernel/time/hrtimer.c (ffffffff818d3184)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81104463)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff81105ba2)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:do_schedule_next_timer
```
```
In kernel/time/tick-sched.c (ffffffff8110d899)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart
```
```
In kernel/futex.c (ffffffff8110e89e)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/events/core.c (ffffffff8119bb07)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff81294ad2)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
```
In block/blk-mq.c (ffffffff81421f1d)
Location: include/linux/hrtimer.h:399
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid_sleep
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
In kernel/softirq.c (ffffffff81089e68)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
```
```
In kernel/signal.c (ffffffff81092848)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (ffffffff810aee8d)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (ffffffff810b6c99)
Location: include/linux/hrtimer.h:383
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810c3fb9)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/locking/rtmutex.c (ffffffff819092e0)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
```
In kernel/time/hrtimer.c (ffffffff8190a307)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81106510)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff8110752b)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffffffff8110f799)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/futex.c (ffffffff81111db8)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/events/core.c (ffffffff811a0c77)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff812a1d62)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
```
In block/blk-mq.c (ffffffff81430744)
Location: include/linux/hrtimer.h:383
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
In kernel/softirq.c (ffffffff81090baa)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
```
```
In kernel/signal.c (ffffffff810996d7)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (ffffffff810b60d3)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (ffffffff810bde8b)
Location: include/linux/hrtimer.h:383
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810cb78b)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/locking/rtmutex.c (ffffffff819933fc)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
```
In kernel/time/hrtimer.c (ffffffff81994649)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81111590)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff81112661)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffffffff8111aa75)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/futex.c (ffffffff8111dca4)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/events/core.c (ffffffff811b4546)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff812c5083)
Location: include/linux/hrtimer.h:383
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
```
In block/blk-mq.c (ffffffff8145bc1f)
Location: include/linux/hrtimer.h:383
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
In kernel/softirq.c (ffffffff8109475d)
Location: include/linux/hrtimer.h:404
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
```
```
In kernel/signal.c (ffffffff8109d7cc)
Location: include/linux/hrtimer.h:404
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (ffffffff810bdf30)
Location: include/linux/hrtimer.h:404
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (ffffffff810c5d15)
Location: include/linux/hrtimer.h:404
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810d30ca)
Location: include/linux/hrtimer.h:404
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/locking/rtmutex.c (ffffffff819ef9c4)
Location: include/linux/hrtimer.h:404
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
```
In kernel/time/hrtimer.c (ffffffff819f0e8c)
Location: include/linux/hrtimer.h:404
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8111cf8f)
Location: include/linux/hrtimer.h:404
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff8111e0ec)
Location: include/linux/hrtimer.h:404
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffffffff811277e5)
Location: include/linux/hrtimer.h:404
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
```
```
In kernel/futex.c (ffffffff8112a7dd)
Location: include/linux/hrtimer.h:404
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/events/core.c (ffffffff811d6c07)
Location: include/linux/hrtimer.h:404
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff812ee151)
Location: include/linux/hrtimer.h:404
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
```
In block/blk-mq.c (ffffffff8148f3bf)
Location: include/linux/hrtimer.h:404
Inline: True
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
In kernel/softirq.c (ffffffff8109cabd)
Location: include/linux/hrtimer.h:401
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
```
```
In kernel/signal.c (ffffffff810a5a41)
Location: include/linux/hrtimer.h:401
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (ffffffff810c71e0)
Location: include/linux/hrtimer.h:401
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (ffffffff810ce6b5)
Location: include/linux/hrtimer.h:401
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810dd30a)
Location: include/linux/hrtimer.h:401
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/locking/rtmutex.c (ffffffff81a2ad14)
Location: include/linux/hrtimer.h:401
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
```
In kernel/time/hrtimer.c (ffffffff81a2c20c)
Location: include/linux/hrtimer.h:401
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8112873f)
Location: include/linux/hrtimer.h:401
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff8112994c)
Location: include/linux/hrtimer.h:401
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffffffff81132ed5)
Location: include/linux/hrtimer.h:401
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
```
```
In kernel/futex.c (ffffffff8113634b)
Location: include/linux/hrtimer.h:401
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/events/core.c (ffffffff811e34c7)
Location: include/linux/hrtimer.h:401
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff81302be1)
Location: include/linux/hrtimer.h:401
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
```
In block/blk-mq.c (ffffffff814a8e8b)
Location: include/linux/hrtimer.h:401
Inline: True
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
In kernel/signal.c (ffffffff810aa710)
Location: include/linux/hrtimer.h:387
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (ffffffff810cd6f0)
Location: include/linux/hrtimer.h:387
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (ffffffff810d6aa0)
Location: include/linux/hrtimer.h:387
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810e42d4)
Location: include/linux/hrtimer.h:387
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/locking/rtmutex.c (ffffffff81a9b9fb)
Location: include/linux/hrtimer.h:387
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
```
In kernel/time/hrtimer.c (ffffffff81a9c3b4)
Location: include/linux/hrtimer.h:387
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81133184)
Location: include/linux/hrtimer.h:387
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff811343cc)
Location: include/linux/hrtimer.h:387
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffffffff8113da75)
Location: include/linux/hrtimer.h:387
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
```
```
In kernel/futex.c (ffffffff81141c1e)
Location: include/linux/hrtimer.h:387
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/events/core.c (ffffffff811fa697)
Location: include/linux/hrtimer.h:387
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff81324831)
Location: include/linux/hrtimer.h:387
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
```
In block/blk-mq.c (ffffffff814d6828)
Location: include/linux/hrtimer.h:387
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
In kernel/signal.c (ffffffff810b0d12)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (ffffffff810d7220)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (ffffffff810e1108)
Location: include/linux/hrtimer.h:427
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810ee86f)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
```
```
In kernel/locking/rtmutex.c (ffffffff81ad334b)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
```
In kernel/time/hrtimer.c (ffffffff81ad3c63)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8113f0e4)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff811403dc)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffffffff81149618)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
```
```
In kernel/events/core.c (ffffffff81207767)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff81337591)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff810b9046)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (ffffffff810e1c43)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (ffffffff810e9228)
Location: include/linux/hrtimer.h:427
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810f83b0)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
```
```
In kernel/locking/rtmutex.c (ffffffff81bcb3bd)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
```
In kernel/time/hrtimer.c (ffffffff81bcbc6f)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8114e82c)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff8114fc7c)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffffffff81159638)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart
```
```
In kernel/events/core.c (ffffffff81231d67)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff81370906)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff810b42f6)
Location: include/linux/hrtimer.h:428
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/fair.c (ffffffff810e6fd8)
Location: include/linux/hrtimer.h:428
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810f65c0)
Location: include/linux/hrtimer.h:428
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
```
```
In kernel/locking/rtmutex.c (ffffffff81c4425d)
Location: include/linux/hrtimer.h:428
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
```
In kernel/time/hrtimer.c (ffffffff81c44a8f)
Location: include/linux/hrtimer.h:428
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8114aa9c)
Location: include/linux/hrtimer.h:428
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff8114befc)
Location: include/linux/hrtimer.h:428
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffffffff811555f4)
Location: include/linux/hrtimer.h:428
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart
```
```
In kernel/events/core.c (ffffffff8123b9d7)
Location: include/linux/hrtimer.h:428
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff8137e689)
Location: include/linux/hrtimer.h:428
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff810b5f06)
Location: include/linux/hrtimer.h:428
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/fair.c (ffffffff810e9088)
Location: include/linux/hrtimer.h:428
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810f85dd)
Location: include/linux/hrtimer.h:428
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/hrtimer.h:428
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81c37cfc)
Location: include/linux/hrtimer.h:428
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8114bf5c)
Location: include/linux/hrtimer.h:428
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff8114d3ac)
Location: include/linux/hrtimer.h:428
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffffffff81156994)
Location: include/linux/hrtimer.h:428
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart
```
```
In kernel/events/core.c (ffffffff81240db7)
Location: include/linux/hrtimer.h:428
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff81385309)
Location: include/linux/hrtimer.h:428
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff810c8d95)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/fair.c (ffffffff811008b8)
Location: include/linux/hrtimer.h:424
Inline: True
```
```
In kernel/sched/rt.c (ffffffff81113c60)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/time/hrtimer.c (ffffffff81d565bc)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8116fca3)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff8117176c)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffffffff8117b6b4)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart
```
```
In kernel/events/core.c (ffffffff8127b7a7)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff813d2589)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff810e0327)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/fair.c (ffffffff8111b898)
Location: include/linux/hrtimer.h:424
Inline: True
```
```
In kernel/sched/build_policy.c (ffffffff8113136a)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/time/hrtimer.c (ffffffff81f28428)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811a4193)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff811a6219)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffffffff811b0d14)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart
```
```
In kernel/events/core.c (ffffffff812cf698)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff8145c12c)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff811009b7)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/fair.c (ffffffff811433c8)
Location: include/linux/hrtimer.h:424
Inline: True
```
```
In kernel/sched/build_policy.c (ffffffff8115b2e4)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/time/hrtimer.c (ffffffff820d4078)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811e3a63)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff811e5d59)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffffffff811f1904)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart
```
```
In kernel/events/core.c (ffffffff8133762b)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff814eb7fc)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff8110caba)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/fair.c (ffffffff81153398)
Location: include/linux/hrtimer.h:424
Inline: True
```
```
In kernel/sched/build_policy.c (ffffffff8116b51b)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/time/hrtimer.c (ffffffff821582d2)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811f80d3)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff811fa1df)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffffffff8120609e)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart
```
```
In kernel/events/core.c (ffffffff8136839b)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff8152259f)
Location: include/linux/hrtimer.h:424
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff8111649a)
Location: include/linux/hrtimer.h:386
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/fair.c (ffffffff8115f0a8)
Location: include/linux/hrtimer.h:386
Inline: True
```
```
In kernel/sched/build_policy.c (ffffffff81178e19)
Location: include/linux/hrtimer.h:386
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/time/hrtimer.c (ffffffff8223b142)
Location: include/linux/hrtimer.h:386
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8120e273)
Location: include/linux/hrtimer.h:386
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff812103cf)
Location: include/linux/hrtimer.h:386
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffffffff8121d26e)
Location: include/linux/hrtimer.h:386
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart_sched_tick
```
```
In kernel/events/core.c (ffffffff813912bb)
Location: include/linux/hrtimer.h:386
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff81556bbf)
Location: include/linux/hrtimer.h:386
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffff80001010b900)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (ffff800010137d0c)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (ffff8000101415f0)
Location: include/linux/hrtimer.h:427
Inline: True
```
```
In kernel/sched/rt.c (ffff80001014f9fc)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
```
```
In kernel/locking/rtmutex.c (ffff800010da5cf4)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
```
In kernel/time/hrtimer.c (ffff800010da6808)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffff8000101a9278)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffff8000101aa714)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffff8000101b5bd4)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
```
```
In kernel/events/core.c (ffff800010296cb4)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffff8000103f49d4)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (c0364b10)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (c0382254)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/core.c:__hrtick_restart
```
```
In kernel/sched/fair.c (c0391668)
Location: include/linux/hrtimer.h:427
Inline: True
```
```
In kernel/sched/rt.c (c039d1b4)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
```
```
In kernel/locking/rtmutex.c (c0e9db64)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
```
In kernel/time/hrtimer.c (c0e9e618)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (c03f442c)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (c03f5c6c)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (c03ffbe0)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
```
```
In kernel/events/core.c (c04c1a18)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (c05c9a68)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (c0000000001535dc)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (c000000000183200)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (c0000000001920a8)
Location: include/linux/hrtimer.h:427
Inline: True
```
```
In kernel/sched/rt.c (c0000000001a3118)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
```
```
In kernel/locking/rtmutex.c (c000000000ee83d0)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
```
In kernel/time/hrtimer.c (c000000000ee9054)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (c00000000020c288)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (c00000000020e180)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (c00000000021b56c)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
```
```
In kernel/events/core.c (c00000000033ef70)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (c0000000004fd5d8)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffe0000cdee0)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (ffffffe0000e7f4c)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (ffffffe0000efade)
Location: include/linux/hrtimer.h:427
Inline: True
```
```
In kernel/sched/rt.c (ffffffe0000f8268)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
```
```
In kernel/locking/rtmutex.c (ffffffe0008c8370)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
```
In kernel/time/hrtimer.c (ffffffe0008c8ba8)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffe000134998)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffe000135b54)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffffffe00013bdd8)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
```
```
In kernel/events/core.c (ffffffe0001c3d60)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffe0002a630e)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff810ab082)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (ffffffff810d16f0)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (ffffffff810db2b8)
Location: include/linux/hrtimer.h:427
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810e86c2)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/locking/rtmutex.c (ffffffff81a721bb)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
```
In kernel/time/hrtimer.c (ffffffff81a72ad3)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81137894)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff81138b8c)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffffffff81141c38)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
```
```
In kernel/events/core.c (ffffffff811ffd87)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff8132fb71)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff81099a22)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (ffffffff810bfcb0)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (ffffffff810ca2c8)
Location: include/linux/hrtimer.h:427
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810d7c2f)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
```
```
In kernel/locking/rtmutex.c (ffffffff81a2e58b)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
```
In kernel/time/hrtimer.c (ffffffff81a2eea3)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8112a2e4)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff8112b5dc)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffffffff81134f98)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart_sched_tick
```
```
In kernel/events/core.c (ffffffff811f2ad7)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff81320791)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff810aa5e2)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (ffffffff810cf8b0)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (ffffffff810d7638)
Location: include/linux/hrtimer.h:427
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810e4d9f)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
```
```
In kernel/locking/rtmutex.c (ffffffff81ade5cb)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
```
In kernel/time/hrtimer.c (ffffffff81adeee3)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811355b4)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff811368ac)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffffffff8113fae8)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
```
```
In kernel/events/core.c (ffffffff811fdb57)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff8132d641)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff810b26c0)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/sched/core.c (ffffffff810d8dd0)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (ffffffff810e2fe8)
Location: include/linux/hrtimer.h:427
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810f1420)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/locking/rtmutex.c (ffffffff81aeaa7b)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
```
In kernel/time/hrtimer.c (ffffffff81aeb373)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81141fe4)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff8114333c)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In kernel/time/tick-sched.c (ffffffff8114c618)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
```
```
In kernel/events/core.c (ffffffff8120cbb7)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
```
```
In fs/timerfd.c (ffffffff8133f311)
Location: include/linux/hrtimer.h:427
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
</details>
</li>
</ul>

## Differences
