# Function: <code>set_restart_fn</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81143b1c)
Location: include/linux/thread_info.h:67
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8114b3d4)
Location: include/linux/thread_info.h:67
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114fe43)
Location: include/linux/thread_info.h:67
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
```
In kernel/futex.c (ffffffff81157936)
Location: include/linux/thread_info.h:67
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In fs/select.c (ffffffff8133b452)
Location: include/linux/thread_info.h:67
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
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
In kernel/time/hrtimer.c (ffffffff81144cd0)
Location: include/linux/thread_info.h:67
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8114c894)
Location: include/linux/thread_info.h:67
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81151273)
Location: include/linux/thread_info.h:67
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
```
In kernel/futex.c (ffffffff81158d8a)
Location: include/linux/thread_info.h:67
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In fs/select.c (ffffffff81341926)
Location: include/linux/thread_info.h:67
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
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
In kernel/time/hrtimer.c (ffffffff81168520)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811707eb)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81175643)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
```
In kernel/futex.c (ffffffff8117dc5a)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In fs/select.c (ffffffff8138f2e6)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
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
In kernel/time/hrtimer.c (ffffffff8119bfe3)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811a4da6)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811a9f8f)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
```
In kernel/futex/waitwake.c (ffffffff811b778a)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wait
```
```
In fs/select.c (ffffffff81410445)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
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
In kernel/time/hrtimer.c (ffffffff811da953)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811e46a6)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811e9f1f)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
```
In kernel/futex/waitwake.c (ffffffff811f891a)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wait
```
```
In fs/select.c (ffffffff8149b0f5)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
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
In kernel/time/hrtimer.c (ffffffff811eee19)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811f8d06)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fe62f)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
```
In kernel/futex/waitwake.c (ffffffff8120d0da)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wait
```
```
In fs/select.c (ffffffff814d01a5)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
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
In kernel/time/hrtimer.c (ffffffff81204f99)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8120eea6)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-cpu-timers.c (ffffffff812149bf)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:process_cpu_nsleep
```
```
In kernel/futex/waitwake.c (ffffffff812248c6)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wait
```
```
In fs/select.c (ffffffff81502ae5)
Location: include/linux/thread_info.h:68
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
  - fs/select.c:do_restart_poll
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
