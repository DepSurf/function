# Function: <code>timespec64_to_ktime</code>

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
In kernel/time/timekeeping.c (ffffffff810f4a4b)
Location: include/linux/ktime.h:87
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:timekeeping_update
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
In kernel/time/timekeeping.c (ffffffff810fbe0b)
Location: include/linux/ktime.h:87
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In fs/select.c (ffffffff81249f91)
Location: include/linux/ktime.h:87
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8127d7db)
Location: include/linux/ktime.h:87
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
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
In kernel/time/timekeeping.c (ffffffff810fed0b)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In fs/select.c (ffffffff8125cf4f)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8129136b)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
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
In kernel/time/hrtimer.c (ffffffff810ffff0)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff81100d77)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffffffff81107178)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff81107836)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81109eab)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In fs/select.c (ffffffff81269a28)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8129e2e9)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff812a1f84)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
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
In kernel/time/hrtimer.c (ffffffff8110ade0)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff8110bb7d)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffffffff811122a8)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff811129ab)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8111507b)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In fs/select.c (ffffffff8128c2cf)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff812c17d9)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff812c52a4)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff812c9f51)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In ipc/mqueue.c (ffffffff813b194f)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In kernel/time/hrtimer.c (ffffffff811167ce)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff81117770)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffffffff8111db61)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff8111e3eb)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112180d)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In fs/select.c (ffffffff812b2ba4)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff812ea5e3)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff812ee635)
Location: include/linux/ktime.h:76
Inline: True
```
```
In fs/aio.c (ffffffff812f3195)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In ipc/mqueue.c (ffffffff813e24a4)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/ptp/ptp_clock.c (ffffffff817dec8a)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In kernel/signal.c (ffffffff810a6301)
Location: include/linux/ktime.h:76
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81121e0e)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff81122d90)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffffffff81129461)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff81129c3b)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112cf2d)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/futex.c (ffffffff8113761e)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_futex
  - kernel/futex.c:__ia32_compat_sys_futex
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812c7cc3)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8130076c)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff81302fc5)
Location: include/linux/ktime.h:76
Inline: True
```
```
In fs/aio.c (ffffffff81308195)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In ipc/mqueue.c (ffffffff813fcef4)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/ptp/ptp_clock.c (ffffffff8180a0ca)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In kernel/signal.c (ffffffff810ab003)
Location: include/linux/ktime.h:76
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff8112c757)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff8112d580)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffffffff81133ec0)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff811346bf)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811378ed)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/futex.c (ffffffff8114241a)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812e4817)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff81321a46)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff813241d2)
Location: include/linux/ktime.h:76
Inline: True
```
```
In fs/aio.c (ffffffff81329c55)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In ipc/mqueue.c (ffffffff81429532)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/ptp/ptp_clock.c (ffffffff8184be51)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In kernel/signal.c (ffffffff810b1603)
Location: include/linux/ktime.h:76
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81138766)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff811394f0)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffffffff8113fe90)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff811406cf)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81143852)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/futex.c (ffffffff8114e28a)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812f61de)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff81333fa6)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff81336f32)
Location: include/linux/ktime.h:76
Inline: True
```
```
In fs/aio.c (ffffffff8133cab5)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffff813427fb)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In ipc/mqueue.c (ffffffff81443262)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/ptp/ptp_clock.c (ffffffff8187d681)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In kernel/signal.c (ffffffff810b9121)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffff81147826)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff811481a0)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffffffff8114f024)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff81150240)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81152f77)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff81154c0e)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/namespace.c (ffffffff81159f32)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/time/namespace.c:do_timens_ktime_to_host
  - kernel/time/namespace.c:do_timens_ktime_to_host
```
```
In kernel/futex.c (ffffffff8115eb2a)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff8132dea9)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8136e4d5)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff81370e27)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff81375e85)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffff81381d54)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_issue_sqe
```
```
In ipc/mqueue.c (ffffffff81493ef2)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/ptp/ptp_clock.c (ffffffff8194bab1)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In kernel/signal.c (ffffffff810b43d1)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffff81143cb6)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff811445e0)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffffffff8114b344)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff8114c4c0)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114f217)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff81150e8e)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/namespace.c (ffffffff81155e82)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/namespace.c:do_timens_ktime_to_host
  - kernel/time/namespace.c:do_timens_ktime_to_host
```
```
In kernel/futex.c (ffffffff8115a9fa)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In kernel/bpf/helpers.c (ffffffff812164cd)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
```
In fs/select.c (ffffffff81339706)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8137b9f6)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8137eba5)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff81383e01)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffff81391c37)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_timeout
  - fs/io_uring.c:io_timeout_remove
```
```
In ipc/mqueue.c (ffffffff814b1852)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/ptp/ptp_clock.c (ffffffff819514c1)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In kernel/signal.c (ffffffff810b5fe1)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffff81144e3c)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff81145760)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffffffff8114c804)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff8114d98a)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811506a7)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff811522be)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/namespace.c (ffffffff81157122)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/namespace.c:do_timens_ktime_to_host
  - kernel/time/namespace.c:do_timens_ktime_to_host
```
```
In kernel/futex.c (ffffffff8115bda8)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In kernel/bpf/helpers.c (ffffffff8121920d)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
```
In fs/select.c (ffffffff8133fde3)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff81382176)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff81385825)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff8138aa51)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffff81397067)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_issue_sqe
```
```
In ipc/mqueue.c (ffffffff814b76d2)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/ptp/ptp_clock.c (ffffffff81935341)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In kernel/signal.c (ffffffff810c8e71)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffff8116868c)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff81168e60)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffffffff8117074e)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff8117181a)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81174975)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff8117688e)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/namespace.c (ffffffff8117bf72)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/namespace.c:do_timens_ktime_to_host
  - kernel/time/namespace.c:do_timens_ktime_to_host
```
```
In kernel/futex.c (ffffffff81180df8)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In kernel/bpf/helpers.c (ffffffff8124f9ed)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
```
In fs/select.c (ffffffff8138d619)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff813cf3e6)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff813d299f)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff813d7d61)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffff813e5717)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_issue_sqe
```
```
In ipc/mqueue.c (ffffffff81510042)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/ptp/ptp_clock.c (ffffffff819d89a7)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In kernel/signal.c (ffffffff810e03f2)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffff8119c18c)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff8119ca41)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffffffff811a4d01)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff811a62ea)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811a97c6)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff811abd1d)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/namespace.c (ffffffff811b16ae)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/namespace.c:do_timens_ktime_to_host
  - kernel/time/namespace.c:do_timens_ktime_to_host
```
```
In kernel/futex/syscalls.c (ffffffff811b41aa)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
```
In kernel/bpf/helpers.c (ffffffff81296c9d)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
```
In fs/select.c (ffffffff8140eaaa)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff814581c1)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8145b207)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff81462481)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In ipc/sem.c (ffffffff8159ab38)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff815a212b)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In io_uring/io_uring.c (ffffffff816cf7b8)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_queue_linked_timeout
  - io_uring/io_uring.c:io_timeout
  - io_uring/io_uring.c:io_timeout_remove
  - io_uring/io_uring.c:io_timeout_remove
```
```
In drivers/ptp/ptp_clock.c (ffffffff81b3be85)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In kernel/signal.c (ffffffff81100a92)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffff811dab27)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff811db4b1)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffffffff811e4601)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff811e5e4a)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811e9716)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff811ebfbd)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/namespace.c (ffffffff811f23ee)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/namespace.c:do_timens_ktime_to_host
  - kernel/time/namespace.c:do_timens_ktime_to_host
```
```
In kernel/futex/syscalls.c (ffffffff811f520a)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
```
In kernel/bpf/helpers.c (ffffffff812f1c4d)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
```
In fs/select.c (ffffffff81499617)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff814e7af1)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff814ea817)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff814f2ad1)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In ipc/sem.c (ffffffff81643e88)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff8164bbfb)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In io_uring/io_uring.c (ffffffff81791c17)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
```
```
In io_uring/timeout.c (ffffffff81799dda)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_timeout_remove
```
```
In io_uring/cancel.c (ffffffff8179e953)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
```
```
In drivers/ptp/ptp_clock.c (ffffffff81cd1dd5)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In kernel/signal.c (ffffffff8110cb8f)
Location: include/linux/ktime.h:71
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff811ef037)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff811efa51)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffffffff811f8c61)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff811fa2ca)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fde06)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff812006ea)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/namespace.c (ffffffff81206b73)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/time/namespace.c:do_timens_ktime_to_host
  - kernel/time/namespace.c:do_timens_ktime_to_host
```
```
In kernel/futex/syscalls.c (ffffffff812099c1)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
```
In kernel/bpf/helpers.c (ffffffff8131e82d)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
```
In fs/select.c (ffffffff814ce720)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8151dda4)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff815215ba)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff81529881)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In ipc/sem.c (ffffffff8167c3c8)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff8168432b)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In io_uring/io_uring.c (ffffffff817d0d8a)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
```
```
In io_uring/timeout.c (ffffffff817daeaa)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_complete
```
```
In io_uring/cancel.c (ffffffff817dfb43)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
```
```
In drivers/ptp/ptp_clock.c (ffffffff81d39819)
Location: include/linux/ktime.h:71
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In kernel/signal.c (ffffffff8111656f)
Location: include/linux/ktime.h:69
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff812051b7)
Location: include/linux/ktime.h:69
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff81205b91)
Location: include/linux/ktime.h:69
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffffffff8120ee01)
Location: include/linux/ktime.h:69
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff812104ba)
Location: include/linux/ktime.h:69
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/posix-cpu-timers.c (ffffffff812141d6)
Location: include/linux/ktime.h:69
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff81216b8a)
Location: include/linux/ktime.h:69
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/namespace.c (ffffffff8121dd83)
Location: include/linux/ktime.h:69
Inline: True
Inline callers:
  - kernel/time/namespace.c:do_timens_ktime_to_host
  - kernel/time/namespace.c:do_timens_ktime_to_host
```
```
In kernel/futex/syscalls.c (ffffffff81220941)
Location: include/linux/ktime.h:69
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:futex2_setup_timeout
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
```
In kernel/bpf/helpers.c (ffffffff81340c5d)
Location: include/linux/ktime.h:69
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
```
In fs/select.c (ffffffff81501060)
Location: include/linux/ktime.h:69
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff81552384)
Location: include/linux/ktime.h:69
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff81555bfa)
Location: include/linux/ktime.h:69
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff8155e751)
Location: include/linux/ktime.h:69
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In ipc/sem.c (ffffffff816b8798)
Location: include/linux/ktime.h:69
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff816c0755)
Location: include/linux/ktime.h:69
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In io_uring/io_uring.c (ffffffff818138e1)
Location: include/linux/ktime.h:69
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
```
```
In io_uring/timeout.c (ffffffff8181f19a)
Location: include/linux/ktime.h:69
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_complete
```
```
In io_uring/cancel.c (ffffffff81824005)
Location: include/linux/ktime.h:69
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
```
```
In drivers/ptp/ptp_clock.c (ffffffff81defbd9)
Location: include/linux/ktime.h:69
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In kernel/signal.c (ffff80001010d234)
Location: include/linux/ktime.h:76
Inline: True
```
```
In kernel/time/hrtimer.c (ffff8000101a2420)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffff8000101a3294)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffff8000101a9ae8)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffff8000101aaa70)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101add44)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/futex.c (ffff8000101bc484)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/futex.c:__arm64_sys_futex_time32
  - kernel/futex.c:__arm64_sys_futex
```
```
In fs/select.c (ffff8000103a32c0)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffff8000103f2744)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffff8000103f4df0)
Location: include/linux/ktime.h:76
Inline: True
```
```
In fs/aio.c (ffff8000103fc4ac)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffff800010404400)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In ipc/mqueue.c (ffff80001052af0c)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/ptp/ptp_clock.c (ffff800010ac6f2c)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In kernel/signal.c (c03654f4)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (c03ec11c)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (c03ed2ac)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (c03f5504)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (c03f6080)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (c03f8ce8)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/futex.c (c0404b1c)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/futex.c:__se_sys_futex_time32
  - kernel/futex.c:__se_sys_futex
```
```
In fs/select.c (c0585c44)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (c05c6608)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/timerfd.c (c05c9cdc)
Location: include/linux/ktime.h:76
Inline: True
```
```
In fs/aio.c (c05cfa68)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (c05d4320)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In ipc/mqueue.c (c06e3214)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/ptp/ptp_clock.c (c0ba6998)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In kernel/signal.c (c00000000015434c)
Location: include/linux/ktime.h:76
Inline: True
```
```
In kernel/time/hrtimer.c (c0000000002038f8)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (c000000000204adc)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (c00000000020d838)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (c00000000020e62c)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (c000000000212010)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/futex.c (c000000000222694)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/futex.c:__se_sys_futex_time32
  - kernel/futex.c:__se_sys_futex
```
```
In fs/select.c (c00000000049d274)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (c0000000004f832c)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (c0000000004fce78)
Location: include/linux/ktime.h:76
Inline: True
```
```
In fs/aio.c (c0000000005051f0)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (c00000000050d064)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In ipc/mqueue.c (c0000000006766b8)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/ptp/ptp_clock.c (c000000000ba8634)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In kernel/signal.c (ffffffe0000d13b2)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffe00012f516)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffe00013158e)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffffffe000135648)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffe000135dea)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffe000137a3c)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/futex.c (ffffffe0001402fa)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/futex.c:__se_sys_futex
```
```
In fs/select.c (ffffffe00026b1b6)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffe0002a334c)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/timerfd.c (ffffffe0002a5f2c)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:__se_sys_timerfd_settime
```
```
In fs/aio.c (ffffffe0002aa124)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffe0002af00e)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In ipc/mqueue.c (ffffffe00038dffc)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
```
```
In drivers/ptp/ptp_clock.c (ffffffe0006c598e)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In kernel/signal.c (ffffffff810ab973)
Location: include/linux/ktime.h:76
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81130f16)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff81131ca0)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffffffff81138640)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff81138e7f)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113c002)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/futex.c (ffffffff811468aa)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812ee7be)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8132c586)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8132f512)
Location: include/linux/ktime.h:76
Inline: True
```
```
In fs/aio.c (ffffffff81335095)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffff8133addb)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In ipc/mqueue.c (ffffffff8143b842)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/ptp/ptp_clock.c (ffffffff81825bf1)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In kernel/signal.c (ffffffff8109a313)
Location: include/linux/ktime.h:76
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81123986)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff81124700)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffffffff8112b090)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff8112b8cf)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112eac2)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/futex.c (ffffffff81139baa)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812df3ee)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8131be71)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8132013c)
Location: include/linux/ktime.h:76
Inline: True
```
```
In fs/aio.c (ffffffff81325a25)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffff8132bac5)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In ipc/mqueue.c (ffffffff8142c2b2)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/ptp/ptp_clock.c (ffffffff817ed281)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In kernel/signal.c (ffffffff810aaed3)
Location: include/linux/ktime.h:76
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff8112ec36)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff8112f9c0)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffffffff81136360)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff81136b9f)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81139d22)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/futex.c (ffffffff8114475a)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812ec5ce)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8132a056)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8132cfe2)
Location: include/linux/ktime.h:76
Inline: True
```
```
In fs/aio.c (ffffffff81332b65)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffff813388ab)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In ipc/mqueue.c (ffffffff814379e2)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/ptp/ptp_clock.c (ffffffff81872b31)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
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
In kernel/signal.c (ffffffff810b2fa9)
Location: include/linux/ktime.h:76
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff8113b636)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff8113c3e0)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/alarmtimer.c (ffffffff81142de0)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff8114362f)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81146812)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/futex.c (ffffffff811512da)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812fd5ce)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8133ab31)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8133fae7)
Location: include/linux/ktime.h:76
Inline: True
```
```
In fs/aio.c (ffffffff81345cf5)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffff8134b124)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In ipc/mqueue.c (ffffffff8144df62)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/ptp/ptp_clock.c (ffffffff8188e4e1)
Location: include/linux/ktime.h:76
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
</details>
</li>
</ul>

## Differences
