# Function: <code>compat_get_timespec64</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timespec64(struct timespec *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811204b0)
Location: kernel/compat.c:149
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:compat_SyS_nanosleep
  - kernel/time/posix-timers.c:compat_SyS_clock_nanosleep
  - kernel/time/posix-timers.c:compat_SyS_clock_settime
```
**Symbols:**

```
ffffffff811204b0-ffffffff81120540: compat_get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timespec64(struct timespec *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8112bbe0)
Location: kernel/compat.c:149
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:compat_SyS_nanosleep
  - kernel/time/posix-timers.c:compat_SyS_clock_nanosleep
  - kernel/time/posix-timers.c:compat_SyS_clock_settime
  - fs/select.c:compat_SyS_ppoll
  - fs/select.c:compat_SyS_pselect6
  - fs/utimes.c:compat_SyS_utimensat
  - fs/utimes.c:compat_SyS_utimensat
  - fs/aio.c:compat_SyS_io_getevents
  - ipc/sem.c:compat_SyS_semtimedop
  - ipc/mqueue.c:compat_SyS_mq_timedreceive
  - ipc/mqueue.c:compat_SyS_mq_timedsend
```
**Symbols:**

```
ffffffff8112bbe0-ffffffff8112bc70: compat_get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int compat_get_timespec64(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81110e90)
Location: kernel/time/time.c:915
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:__x32_compat_sys_nanosleep
  - kernel/time/hrtimer.c:__ia32_compat_sys_nanosleep
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_settime
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_settime
  - fs/select.c:__x32_compat_sys_ppoll
  - fs/select.c:__ia32_compat_sys_ppoll
  - fs/select.c:do_compat_pselect
  - fs/utimes.c:__x32_compat_sys_utimensat
  - fs/utimes.c:__x32_compat_sys_utimensat
  - fs/utimes.c:__ia32_compat_sys_utimensat
  - fs/utimes.c:__ia32_compat_sys_utimensat
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__x32_compat_sys_io_getevents
  - fs/aio.c:__ia32_compat_sys_io_getevents
  - ipc/mqueue.c:__x32_compat_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_compat_sys_mq_timedreceive
  - ipc/mqueue.c:__x32_compat_sys_mq_timedsend
  - ipc/mqueue.c:__ia32_compat_sys_mq_timedsend
```
**Symbols:**

```
ffffffff81110e90-ffffffff81110f20: compat_get_timespec64 (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *ts</code> ➡️ <code>struct timespec64 *ts</code>
</li>
</ul>
</details>
</li>
</ul>
