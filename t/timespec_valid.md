# Function: <code>timespec_valid</code>

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
In kernel/signal.c (ffffffff81091242)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/time.c (ffffffff810eb33a)
Location: include/linux/time.h:92
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff810f0006)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:SyS_nanosleep
```
```
In kernel/time/posix-timers.c (ffffffff810f1a1b)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_clock_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff810f4d6e)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_init
```
```
In kernel/futex.c (ffffffff811030b5)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/futex.c:SyS_futex
```
```
In kernel/futex_compat.c (ffffffff8110342f)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_SyS_futex
```
```
In kernel/compat.c (ffffffff81110498)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_nanosleep
```
```
In fs/select.c (ffffffff81220fb5)
Location: include/linux/time.h:92
Inline: True
```
```
In fs/timerfd.c (ffffffff81258784)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In ipc/mqueue.c (ffffffff8132bd47)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - ipc/mqueue.c:prepare_timeout
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
In kernel/signal.c (ffffffff810943af)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/time.c (ffffffff810f1fdc)
Location: include/linux/time.h:92
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff810f6e46)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:SyS_nanosleep
```
```
In kernel/time/posix-timers.c (ffffffff810f91ee)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_clock_nanosleep
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
```
In kernel/time/timekeeping.c (ffffffff81fa9461)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/futex.c (ffffffff8110a599)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/futex.c:SyS_futex
```
```
In kernel/futex_compat.c (ffffffff8110a903)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_SyS_futex
```
```
In kernel/compat.c (ffffffff81117bf8)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_nanosleep
  - kernel/compat.c:compat_SyS_settimeofday
```
```
In fs/select.c (ffffffff81248c35)
Location: include/linux/time.h:92
Inline: True
```
```
In fs/timerfd.c (ffffffff81281087)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In ipc/mqueue.c (ffffffff813609e7)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - ipc/mqueue.c:prepare_timeout
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
In kernel/signal.c (ffffffff8109939f)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/time.c (ffffffff810f915c)
Location: include/linux/time.h:92
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff810fdf06)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:SyS_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff81fe4f8c)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/time/posix-timers.c (ffffffff81106b7e)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_clock_nanosleep
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:posix_clock_realtime_set
```
```
In kernel/futex.c (ffffffff81111d8d)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/futex.c:SyS_futex
```
```
In kernel/futex_compat.c (ffffffff81112101)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_SyS_futex
```
```
In kernel/compat.c (ffffffff8111f318)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_nanosleep
  - kernel/compat.c:compat_SyS_settimeofday
```
```
In fs/select.c (ffffffff8125bc65)
Location: include/linux/time.h:92
Inline: True
```
```
In fs/timerfd.c (ffffffff81294bb7)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In ipc/mqueue.c (ffffffff81377207)
Location: include/linux/time.h:92
Inline: True
Inline callers:
  - ipc/mqueue.c:prepare_timeout
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
In kernel/signal.c (ffffffff810930ff)
Location: include/linux/time.h:101
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/time.c (ffffffff810fb50c)
Location: include/linux/time.h:101
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81100220)
Location: include/linux/time.h:101
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:compat_SyS_nanosleep
  - kernel/time/hrtimer.c:SyS_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff820c5c35)
Location: include/linux/time.h:101
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In kernel/time/posix-timers.c (ffffffff81109079)
Location: include/linux/time.h:101
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:compat_SyS_clock_nanosleep
  - kernel/time/posix-timers.c:SyS_clock_nanosleep
  - kernel/time/posix-timers.c:do_timer_settime
  - kernel/time/posix-timers.c:do_timer_settime
```
```
In kernel/futex.c (ffffffff81113375)
Location: include/linux/time.h:101
Inline: True
Inline callers:
  - kernel/futex.c:SyS_futex
```
```
In kernel/futex_compat.c (ffffffff811136ec)
Location: include/linux/time.h:101
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_SyS_futex
```
```
In fs/select.c (ffffffff81269cc5)
Location: include/linux/time.h:101
Inline: True
```
```
In fs/timerfd.c (ffffffff812a1e47)
Location: include/linux/time.h:101
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In ipc/mqueue.c (ffffffff8138d7eb)
Location: include/linux/time.h:101
Inline: True
Inline callers:
  - ipc/mqueue.c:compat_SyS_mq_timedreceive
  - ipc/mqueue.c:compat_SyS_mq_timedsend
  - ipc/mqueue.c:prepare_timeout
```
</details>
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109dfd2)
Location: include/linux/time32.h:97
Inline: True
```
```
In kernel/futex.c (ffffffff8112b83f)
Location: include/linux/time32.h:97
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In kernel/futex_compat.c (ffffffff8112becd)
Location: include/linux/time32.h:97
Inline: True
Inline callers:
  - kernel/futex_compat.c:__x32_compat_sys_futex
  - kernel/futex_compat.c:__ia32_compat_sys_futex
```
</details>
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
