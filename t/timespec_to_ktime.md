# Function: <code>timespec_to_ktime</code>

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
In kernel/time/hrtimer.c (ffffffff810efe40)
Location: include/linux/ktime.h:81
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-timers.c (ffffffff810f11a4)
Location: include/linux/ktime.h:81
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/alarmtimer.c (ffffffff810fb2f7)
Location: include/linux/ktime.h:81
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_set
  - kernel/time/alarmtimer.c:alarm_timer_set
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/futex.c (ffffffff811030d2)
Location: include/linux/ktime.h:81
Inline: True
Inline callers:
  - kernel/futex.c:SyS_futex
```
```
In kernel/futex_compat.c (ffffffff8110344c)
Location: include/linux/ktime.h:81
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_SyS_futex
```
```
In fs/select.c (ffffffff812211ec)
Location: include/linux/ktime.h:81
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_sys_poll
```
```
In fs/eventpoll.c (ffffffff8125545b)
Location: include/linux/ktime.h:81
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff812588a7)
Location: include/linux/ktime.h:81
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff8125beb6)
Location: include/linux/ktime.h:81
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In ipc/mqueue.c (ffffffff8132bd63)
Location: include/linux/ktime.h:81
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
In kernel/signal.c (ffffffff810943d1)
Location: include/linux/ktime.h:81
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffff810f6c7f)
Location: include/linux/ktime.h:81
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/posix-timers.c (ffffffff810f8223)
Location: include/linux/ktime.h:81
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/alarmtimer.c (ffffffff81102828)
Location: include/linux/ktime.h:81
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_set
  - kernel/time/alarmtimer.c:alarm_timer_set
```
```
In kernel/futex.c (ffffffff8110a5b6)
Location: include/linux/ktime.h:81
Inline: True
Inline callers:
  - kernel/futex.c:SyS_futex
```
```
In kernel/futex_compat.c (ffffffff8110a920)
Location: include/linux/ktime.h:81
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_SyS_futex
```
```
In fs/timerfd.c (ffffffff812811cc)
Location: include/linux/ktime.h:81
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff81284966)
Location: include/linux/ktime.h:81
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In ipc/mqueue.c (ffffffff81360a01)
Location: include/linux/ktime.h:81
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
In kernel/signal.c (ffffffff810993c1)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffff810fdd3a)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81105148)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_set
  - kernel/time/alarmtimer.c:alarm_timer_set
```
```
In kernel/time/posix-timers.c (ffffffff81105b43)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/futex.c (ffffffff81111daa)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/futex.c:SyS_futex
```
```
In kernel/futex_compat.c (ffffffff8111211e)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_SyS_futex
```
```
In fs/timerfd.c (ffffffff81294cfc)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff81298616)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In ipc/mqueue.c (ffffffff81377221)
Location: include/linux/ktime.h:70
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
In kernel/signal.c (ffffffff8109311c)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/futex.c (ffffffff81113393)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/futex.c:SyS_futex
```
```
In kernel/futex_compat.c (ffffffff8111370a)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_SyS_futex
```
```
In fs/aio.c (ffffffff812a6100)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In ipc/mqueue.c (ffffffff8138c59f)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
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
In kernel/signal.c (ffffffff81099ffc)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/futex.c (ffffffff8111e923)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/futex.c:SyS_futex
```
```
In kernel/futex_compat.c (ffffffff8111ec9a)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_SyS_futex
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
In kernel/signal.c (ffffffff8109dff1)
Location: include/linux/ktime.h:70
Inline: True
```
```
In kernel/futex.c (ffffffff8112b860)
Location: include/linux/ktime.h:70
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In kernel/futex_compat.c (ffffffff8112beee)
Location: include/linux/ktime.h:70
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
