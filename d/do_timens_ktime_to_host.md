# Function: <code>do_timens_ktime_to_host</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
ktime_t do_timens_ktime_to_host(clockid_t clockid, ktime_t tim, struct timens_offsets *ns_offsets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81159f10)
Location: kernel/time/namespace.c:23
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_timer_set
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff81159f10-ffffffff81159f8c: do_timens_ktime_to_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ktime_t do_timens_ktime_to_host(clockid_t clockid, ktime_t tim, struct timens_offsets *ns_offsets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81155e60)
Location: kernel/time/namespace.c:23
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff81155e60-ffffffff81155edc: do_timens_ktime_to_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ktime_t do_timens_ktime_to_host(clockid_t clockid, ktime_t tim, struct timens_offsets *ns_offsets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81157100)
Location: kernel/time/namespace.c:23
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff81157100-ffffffff8115717d: do_timens_ktime_to_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ktime_t do_timens_ktime_to_host(clockid_t clockid, ktime_t tim, struct timens_offsets *ns_offsets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff8117bf50)
Location: kernel/time/namespace.c:23
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff8117bf50-ffffffff8117bfcd: do_timens_ktime_to_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ktime_t do_timens_ktime_to_host(clockid_t clockid, ktime_t tim, struct timens_offsets *ns_offsets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff811b1680)
Location: kernel/time/namespace.c:23
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff811b1680-ffffffff811b1715: do_timens_ktime_to_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ktime_t do_timens_ktime_to_host(clockid_t clockid, ktime_t tim, struct timens_offsets *ns_offsets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff811f23c0)
Location: kernel/time/namespace.c:23
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff811f23c0-ffffffff811f2455: do_timens_ktime_to_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ktime_t do_timens_ktime_to_host(clockid_t clockid, ktime_t tim, struct timens_offsets *ns_offsets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81206b50)
Location: kernel/time/namespace.c:23
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff81206b50-ffffffff81206bda: do_timens_ktime_to_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ktime_t do_timens_ktime_to_host(clockid_t clockid, ktime_t tim, struct timens_offsets *ns_offsets);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff8121dd60)
Location: kernel/time/namespace.c:23
Inline: False
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:futex2_setup_timeout
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff8121dd60-ffffffff8121ddea: do_timens_ktime_to_host (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
