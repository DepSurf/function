# Function: <code>set_normalized_timespec64</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811061ed)
Location: kernel/time/time.c:505
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:get_monotonic_coarse64
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - fs/select.c:compat_poll_select_copy_remaining
  - fs/select.c:poll_select_copy_remaining
  - fs/select.c:select_estimate_accuracy
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff81105450-ffffffff81105491: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111172d)
Location: kernel/time/time.c:517
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - fs/select.c:compat_poll_select_copy_remaining
  - fs/select.c:poll_select_copy_remaining
  - fs/select.c:select_estimate_accuracy
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff811102b0-ffffffff811102f1: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111ce3d)
Location: kernel/time/time.c:455
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - fs/select.c:poll_select_copy_remaining
  - fs/select.c:select_estimate_accuracy
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff8111b8a0-ffffffff8111b8e1: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81127ae1)
Location: kernel/time/time.c:523
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff811262d0-ffffffff81126311: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81133a81)
Location: kernel/time/time.c:523
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff81132270-ffffffff811322b1: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81142d11)
Location: kernel/time/time.c:478
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/ntp.c:sync_cmos_clock
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff811416e0-ffffffff81141721: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113ef21)
Location: kernel/time/time.c:478
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff8113d8f0-ffffffff8113d931: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81140151)
Location: kernel/time/time.c:478
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff8113eb40-ffffffff8113eb81: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811635e1)
Location: kernel/time/time.c:478
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff81161fd0-ffffffff81162011: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81196641)
Location: kernel/time/time.c:478
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/class.c:rtc_suspend
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff81194f00-ffffffff81194f4b: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d4671)
Location: kernel/time/time.c:478
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/class.c:rtc_suspend
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff811d2c50-ffffffff811d2c9b: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e8961)
Location: kernel/time/time.c:478
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/class.c:rtc_suspend
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff811e6f40-ffffffff811e6f8b: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fe691)
Location: kernel/time/time.c:495
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_monotonic_coarse
  - kernel/time/posix-timers.c:posix_get_monotonic_raw
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/class.c:rtc_suspend
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff811fcc90-ffffffff811fccdb: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff80001019c16c)
Location: kernel/time/time.c:523
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - arch/arm/xen/enlighten.c:xen_pm_init
  - arch/arm/xen/enlighten.c:xen_pvclock_gtod_notify
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffff800010199c60-ffff800010199ce0: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e5db8)
Location: kernel/time/time.c:523
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
c03e4690-c03e4730: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fbc00)
Location: kernel/time/time.c:523
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
c0000000001f9f30-c0000000001f9f8c: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012aca2)
Location: kernel/time/time.c:523
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffe00012a18c-ffffffe00012a1f0: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112c231)
Location: kernel/time/time.c:523
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff8112aa20-ffffffff8112aa61: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111eaa1)
Location: kernel/time/time.c:523
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff8111d290-ffffffff8111d2d1: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81129f51)
Location: kernel/time/time.c:523
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff81128740-ffffffff81128781: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void set_normalized_timespec64(struct timespec64 *ts, time64_t sec, s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811365a1)
Location: kernel/time/time.c:523
Inline: True
Inline callers:
  - kernel/time/time.c:timespec64_add_safe
Direct callers:
  - arch/x86/kernel/pvclock.c:pvclock_read_wallclock
  - kernel/time/timekeeping.c:ktime_get_coarse_ts64
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - drivers/rtc/systohc.c:rtc_set_ntp_time
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff81134dc0-ffffffff81134e01: set_normalized_timespec64 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
