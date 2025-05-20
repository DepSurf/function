# Function: <code>timens_ktime_to_host</code>

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
In kernel/time/alarmtimer.c (ffffffff8114f0b4)
Location: include/linux/time_namespace.h:82
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff81150273)
Location: include/linux/time_namespace.h:82
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_timer_set
```
```
In fs/timerfd.c (ffffffff813710e5)
Location: include/linux/time_namespace.h:82
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
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
In kernel/time/alarmtimer.c (ffffffff8114b3f7)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff8114c4f3)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/futex.c (ffffffff8115aa3b)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/timerfd.c (ffffffff8137ee69)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
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
In kernel/time/alarmtimer.c (ffffffff8114c8ab)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff8114d9b3)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/futex.c (ffffffff8115bdfc)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/timerfd.c (ffffffff81385ae9)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
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
In kernel/time/alarmtimer.c (ffffffff81170802)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff81171843)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/futex.c (ffffffff81180e4c)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/timerfd.c (ffffffff813d2c2c)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
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
In kernel/time/alarmtimer.c (ffffffff811a4dbd)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff811a631f)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/futex/syscalls.c (ffffffff811b4235)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
```
In fs/timerfd.c (ffffffff8145b4ab)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
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
In kernel/time/alarmtimer.c (ffffffff811e46bd)
Location: include/linux/time_namespace.h:97
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff811e5e7f)
Location: include/linux/time_namespace.h:97
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/futex/syscalls.c (ffffffff811f5295)
Location: include/linux/time_namespace.h:97
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
```
In fs/timerfd.c (ffffffff814eaabb)
Location: include/linux/time_namespace.h:97
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
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
In kernel/time/alarmtimer.c (ffffffff811f8d1d)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff811fa2ff)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/futex/syscalls.c (ffffffff81209a98)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
```
In fs/timerfd.c (ffffffff8152185e)
Location: include/linux/time_namespace.h:96
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
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
In kernel/time/alarmtimer.c (ffffffff8120eebd)
Location: include/linux/time_namespace.h:99
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff812104ef)
Location: include/linux/time_namespace.h:99
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/futex/syscalls.c (ffffffff81220a18)
Location: include/linux/time_namespace.h:99
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:futex2_setup_timeout
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
```
In fs/timerfd.c (ffffffff81555e9e)
Location: include/linux/time_namespace.h:99
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
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
