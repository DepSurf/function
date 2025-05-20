# Function: <code>timespec64_valid</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099fdf)
Location: include/linux/time64.h:88
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/time.c (ffffffff81105e8a)
Location: include/linux/time64.h:88
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff8110b010)
Location: include/linux/time64.h:88
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:compat_SyS_nanosleep
  - kernel/time/hrtimer.c:SyS_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff826ce2db)
Location: include/linux/time64.h:88
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/time/posix-timers.c (ffffffff81114249)
Location: include/linux/time64.h:88
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:compat_SyS_clock_nanosleep
  - kernel/time/posix-timers.c:SyS_clock_nanosleep
  - kernel/time/posix-timers.c:do_timer_settime
  - kernel/time/posix-timers.c:do_timer_settime
```
```
In kernel/futex.c (ffffffff8111e905)
Location: include/linux/time64.h:88
Inline: True
Inline callers:
  - kernel/futex.c:SyS_futex
```
```
In kernel/futex_compat.c (ffffffff8111ec7c)
Location: include/linux/time64.h:88
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_SyS_futex
```
```
In fs/select.c (ffffffff8128c565)
Location: include/linux/time64.h:88
Inline: True
```
```
In fs/timerfd.c (ffffffff812c5167)
Location: include/linux/time64.h:88
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In ipc/mqueue.c (ffffffff813b2c0b)
Location: include/linux/time64.h:88
Inline: True
Inline callers:
  - ipc/mqueue.c:compat_SyS_mq_timedreceive
  - ipc/mqueue.c:compat_SyS_mq_timedsend
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
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
In kernel/time/time.c (ffffffff8111129a)
Location: include/linux/time64.h:89
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81116b62)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__x32_compat_sys_nanosleep
  - kernel/time/hrtimer.c:__ia32_compat_sys_nanosleep
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff826f8a32)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/posix-timers.c (ffffffff8112063e)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
```
```
In fs/select.c (ffffffff812b2cf5)
Location: include/linux/time64.h:89
Inline: True
```
```
In fs/timerfd.c (ffffffff812ee4de)
Location: include/linux/time64.h:89
Inline: True
```
```
In ipc/mqueue.c (ffffffff813e2bc9)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_compat_sys_mq_timedreceive
  - ipc/mqueue.c:__x32_compat_sys_mq_timedsend
  - ipc/mqueue.c:__ia32_compat_sys_mq_timedsend
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
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
In kernel/signal.c (ffffffff810a62e1)
Location: include/linux/time64.h:90
Inline: True
```
```
In kernel/time/time.c (ffffffff8111c9aa)
Location: include/linux/time64.h:90
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff811221a2)
Location: include/linux/time64.h:90
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__x32_compat_sys_nanosleep
  - kernel/time/hrtimer.c:__ia32_compat_sys_nanosleep
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff828af90d)
Location: include/linux/time64.h:90
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/posix-timers.c (ffffffff8112be1e)
Location: include/linux/time64.h:90
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
```
```
In kernel/futex.c (ffffffff811375fd)
Location: include/linux/time64.h:90
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_futex
  - kernel/futex.c:__ia32_compat_sys_futex
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812c7e15)
Location: include/linux/time64.h:90
Inline: True
```
```
In fs/timerfd.c (ffffffff81302e6e)
Location: include/linux/time64.h:90
Inline: True
```
```
In ipc/mqueue.c (ffffffff813fd619)
Location: include/linux/time64.h:90
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_compat_sys_mq_timedreceive
  - ipc/mqueue.c:__x32_compat_sys_mq_timedsend
  - ipc/mqueue.c:__ia32_compat_sys_mq_timedsend
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
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
In kernel/signal.c (ffffffff810aafe2)
Location: include/linux/time64.h:93
Inline: True
```
```
In kernel/time/time.c (ffffffff811272ee)
Location: include/linux/time64.h:93
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff8112c991)
Location: include/linux/time64.h:93
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff828c849f)
Location: include/linux/time64.h:93
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/posix-timers.c (ffffffff811350bd)
Location: include/linux/time64.h:93
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
```
```
In kernel/futex.c (ffffffff811423f9)
Location: include/linux/time64.h:93
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812e49b5)
Location: include/linux/time64.h:93
Inline: True
```
```
In fs/timerfd.c (ffffffff813244a2)
Location: include/linux/time64.h:93
Inline: True
```
```
In ipc/mqueue.c (ffffffff81429ad8)
Location: include/linux/time64.h:93
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
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
In kernel/signal.c (ffffffff810b15e2)
Location: include/linux/time64.h:95
Inline: True
```
```
In kernel/time/time.c (ffffffff8113328e)
Location: include/linux/time64.h:95
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81138971)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff828d0a7d)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/posix-timers.c (ffffffff811410dd)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
```
In kernel/futex.c (ffffffff8114e269)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812f63d5)
Location: include/linux/time64.h:95
Inline: True
```
```
In fs/timerfd.c (ffffffff81337202)
Location: include/linux/time64.h:95
Inline: True
```
```
In ipc/mqueue.c (ffffffff81443808)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
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
In kernel/signal.c (ffffffff810b90fc)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/time.c (ffffffff811425ab)
Location: include/linux/time64.h:87
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff811477d5)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff82cf19be)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/posix-timers.c (ffffffff811520ed)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
```
In kernel/futex.c (ffffffff8115eb05)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff8132f782)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
```
In fs/timerfd.c (ffffffff81370c7f)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In ipc/mqueue.c (ffffffff814944d8)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
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
In kernel/signal.c (ffffffff810b43ac)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/time.c (ffffffff8113e7bb)
Location: include/linux/time64.h:87
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81143c65)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff82fde448)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/posix-timers.c (ffffffff8114e36d)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
```
In kernel/futex.c (ffffffff8115a9d5)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff8133b0b2)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
```
In fs/timerfd.c (ffffffff8137e9ff)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In ipc/mqueue.c (ffffffff814b1e38)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
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
In kernel/signal.c (ffffffff810b5fbc)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/time.c (ffffffff8113f9eb)
Location: include/linux/time64.h:87
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81144df5)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff831e8f72)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/posix-timers.c (ffffffff8114ee5d)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
```
In kernel/futex.c (ffffffff8115bd8b)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff81341582)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
```
In fs/timerfd.c (ffffffff8138567f)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In ipc/mqueue.c (ffffffff814b7cb8)
Location: include/linux/time64.h:87
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
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
In kernel/signal.c (ffffffff810c8e4c)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/time.c (ffffffff81162e7b)
Location: include/linux/time64.h:89
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81168645)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff832cd526)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/posix-timers.c (ffffffff81172fcd)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
```
In kernel/futex.c (ffffffff81180ddb)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff8138f092)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - fs/select.c:__x64_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x64_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
```
In fs/timerfd.c (ffffffff813d27ff)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In ipc/mqueue.c (ffffffff815104c8)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
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
In kernel/signal.c (ffffffff810e03d3)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/time.c (ffffffff81195ecb)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - kernel/time/time.c:do_sys_settimeofday64
```
```
In kernel/time/hrtimer.c (ffffffff8119c145)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff83481114)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/time/posix-timers.c (ffffffff811a853d)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:do_timer_settime
  - kernel/time/posix-timers.c:do_timer_settime
```
```
In kernel/futex/syscalls.c (ffffffff811b418d)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff81410055)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
```
In fs/timerfd.c (ffffffff8145b06b)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In ipc/sem.c (ffffffff8159ab14)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff815a25f8)
Location: include/linux/time64.h:89
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
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
In kernel/signal.c (ffffffff81100a73)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/time.c (ffffffff811d3e5b)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - kernel/time/time.c:do_sys_settimeofday64
```
```
In kernel/time/hrtimer.c (ffffffff811daad5)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff83eadf47)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/time/posix-timers.c (ffffffff811e82cd)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:do_timer_settime
  - kernel/time/posix-timers.c:do_timer_settime
```
```
In kernel/futex/syscalls.c (ffffffff811f51ed)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff8149acd5)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
```
In fs/timerfd.c (ffffffff814ea67b)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In ipc/sem.c (ffffffff81643e64)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff8164c0e8)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
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
In kernel/signal.c (ffffffff8110cb70)
Location: include/linux/time64.h:92
Inline: True
```
```
In kernel/time/time.c (ffffffff811e814b)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - kernel/time/time.c:do_sys_settimeofday64
```
```
In kernel/time/hrtimer.c (ffffffff811eefe5)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff836d2f87)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/time/posix-timers.c (ffffffff811fc8bd)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:do_timer_settime
  - kernel/time/posix-timers.c:do_timer_settime
```
```
In kernel/futex/syscalls.c (ffffffff812099a4)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff814cfd85)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
```
In fs/timerfd.c (ffffffff8152141b)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In ipc/sem.c (ffffffff8167c3a4)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff81684828)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
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
In kernel/signal.c (ffffffff81116550)
Location: include/linux/time64.h:92
Inline: True
```
```
In kernel/time/time.c (ffffffff811fde7b)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - kernel/time/time.c:do_sys_settimeofday64
```
```
In kernel/time/hrtimer.c (ffffffff81205165)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff83904d47)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/time/posix-timers.c (ffffffff81212aad)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:do_timer_settime
  - kernel/time/posix-timers.c:do_timer_settime
```
```
In kernel/futex/syscalls.c (ffffffff81220924)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:futex2_setup_timeout
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff815026c5)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
```
In fs/timerfd.c (ffffffff81555a5b)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In ipc/sem.c (ffffffff816b8774)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff816c0c68)
Location: include/linux/time64.h:92
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
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
In kernel/signal.c (ffff80001010d218)
Location: include/linux/time64.h:95
Inline: True
```
```
In kernel/time/time.c (ffff80001019ba54)
Location: include/linux/time64.h:95
Inline: True
```
```
In kernel/time/hrtimer.c (ffff8000101a2610)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__arm64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__arm64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffff8000114489e0)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/posix-timers.c (ffff8000101ab288)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__arm64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__arm64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__arm64_sys_timer_settime32
  - kernel/time/posix-timers.c:__arm64_sys_timer_settime32
  - kernel/time/posix-timers.c:__arm64_sys_timer_settime
  - kernel/time/posix-timers.c:__arm64_sys_timer_settime
```
```
In kernel/futex.c (ffff8000101bc468)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/futex.c:__arm64_sys_futex_time32
  - kernel/futex.c:__arm64_sys_futex
```
```
In fs/select.c (ffff8000103a36bc)
Location: include/linux/time64.h:95
Inline: True
```
```
In fs/timerfd.c (ffff8000103f50a8)
Location: include/linux/time64.h:95
Inline: True
```
```
In ipc/mqueue.c (ffff80001052b610)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - ipc/mqueue.c:__arm64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__arm64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__arm64_sys_mq_timedreceive
  - ipc/mqueue.c:__arm64_sys_mq_timedsend
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
In kernel/signal.c (c03654d0)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/time.c (c03e56dc)
Location: include/linux/time64.h:95
Inline: True
```
```
In kernel/time/hrtimer.c (c03ec2e4)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__se_sys_nanosleep_time32
```
```
In kernel/time/timekeeping.c (c15229f0)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/posix-timers.c (c03f7bbc)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__se_sys_timer_settime32
  - kernel/time/posix-timers.c:__se_sys_timer_settime32
  - kernel/time/posix-timers.c:__se_sys_timer_settime
  - kernel/time/posix-timers.c:__se_sys_timer_settime
```
```
In kernel/futex.c (c0404af8)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/futex.c:__se_sys_futex_time32
  - kernel/futex.c:__se_sys_futex
```
```
In fs/select.c (c0585e94)
Location: include/linux/time64.h:95
Inline: True
```
```
In fs/timerfd.c (c05c9fcc)
Location: include/linux/time64.h:95
Inline: True
```
```
In ipc/mqueue.c (c06e51dc)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__se_sys_mq_timedsend_time32
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
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
In kernel/signal.c (c000000000154320)
Location: include/linux/time64.h:95
Inline: True
```
```
In kernel/time/time.c (c0000000001fb438)
Location: include/linux/time64.h:95
Inline: True
```
```
In kernel/time/hrtimer.c (c000000000203b58)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__se_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__se_sys_nanosleep
```
```
In kernel/time/timekeeping.c (c00000000136db50)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/posix-timers.c (c00000000020f6c0)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__se_sys_timer_settime32
  - kernel/time/posix-timers.c:__se_sys_timer_settime32
  - kernel/time/posix-timers.c:__se_sys_timer_settime
  - kernel/time/posix-timers.c:__se_sys_timer_settime
```
```
In kernel/futex.c (c000000000222668)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/futex.c:__se_sys_futex_time32
  - kernel/futex.c:__se_sys_futex
```
```
In fs/select.c (c00000000049d438)
Location: include/linux/time64.h:95
Inline: True
```
```
In fs/timerfd.c (c0000000004fd2ac)
Location: include/linux/time64.h:95
Inline: True
```
```
In ipc/mqueue.c (c000000000676f38)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__se_sys_mq_timedsend_time32
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
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
In kernel/signal.c (ffffffe0000d139e)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigtimedwait
```
```
In kernel/time/time.c (ffffffe00012aaaa)
Location: include/linux/time64.h:95
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffe00012f60c)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__se_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffe00013152c)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/posix-timers.c (ffffffe000136dca)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__se_sys_timer_settime
  - kernel/time/posix-timers.c:__se_sys_timer_settime
```
```
In kernel/futex.c (ffffffe0001402e4)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/futex.c:__se_sys_futex
```
```
In fs/select.c (ffffffe00026b48a)
Location: include/linux/time64.h:95
Inline: True
```
```
In fs/timerfd.c (ffffffe0002a5dec)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:__se_sys_timerfd_settime
```
```
In ipc/mqueue.c (ffffffe00038dfe6)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
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
In kernel/signal.c (ffffffff810ab952)
Location: include/linux/time64.h:95
Inline: True
```
```
In kernel/time/time.c (ffffffff8112ba3e)
Location: include/linux/time64.h:95
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81131121)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff828b992e)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/posix-timers.c (ffffffff8113988d)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
```
In kernel/futex.c (ffffffff81146889)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812ee9b5)
Location: include/linux/time64.h:95
Inline: True
```
```
In fs/timerfd.c (ffffffff8132f7e2)
Location: include/linux/time64.h:95
Inline: True
```
```
In ipc/mqueue.c (ffffffff8143bde8)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
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
In kernel/signal.c (ffffffff8109a2f2)
Location: include/linux/time64.h:95
Inline: True
```
```
In kernel/time/time.c (ffffffff8111e2ae)
Location: include/linux/time64.h:95
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81123b91)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff828b1e7f)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/posix-timers.c (ffffffff8112c2dd)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
```
In kernel/futex.c (ffffffff81139b89)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812df5e5)
Location: include/linux/time64.h:95
Inline: True
```
```
In fs/timerfd.c (ffffffff81320402)
Location: include/linux/time64.h:95
Inline: True
```
```
In ipc/mqueue.c (ffffffff8142c858)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
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
In kernel/signal.c (ffffffff810aaeb2)
Location: include/linux/time64.h:95
Inline: True
```
```
In kernel/time/time.c (ffffffff8112975e)
Location: include/linux/time64.h:95
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff8112ee41)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff828cc6b1)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/posix-timers.c (ffffffff811375ad)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
```
In kernel/futex.c (ffffffff81144739)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812ec7c5)
Location: include/linux/time64.h:95
Inline: True
```
```
In fs/timerfd.c (ffffffff8132d2b2)
Location: include/linux/time64.h:95
Inline: True
```
```
In ipc/mqueue.c (ffffffff81437f88)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
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
In kernel/signal.c (ffffffff810b2f90)
Location: include/linux/time64.h:95
Inline: True
```
```
In kernel/time/time.c (ffffffff81135dae)
Location: include/linux/time64.h:95
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff8113b841)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff828d1aab)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In kernel/time/posix-timers.c (ffffffff8114403d)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__x64_sys_timer_settime32
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__ia32_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
  - kernel/time/posix-timers.c:__x64_sys_timer_settime
```
```
In kernel/futex.c (ffffffff811512b9)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812fd7c5)
Location: include/linux/time64.h:95
Inline: True
```
```
In fs/timerfd.c (ffffffff8133fda2)
Location: include/linux/time64.h:95
Inline: True
```
```
In ipc/mqueue.c (ffffffff8144e508)
Location: include/linux/time64.h:95
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
</details>
</li>
</ul>

## Differences
