# Function: <code>ktime_get_ts64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ktime_get_ts64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f4770)
Location: kernel/time/timekeeping.c:795
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_ktime_get_ts
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - fs/select.c:poll_select_copy_remaining
  - fs/eventpoll.c:ep_poll
  - fs/compat.c:poll_select_copy_remaining
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff810f4770-ffffffff810f4860: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ktime_get_ts64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fcb80)
Location: kernel/time/timekeeping.c:800
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_ktime_get_ts
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - fs/select.c:poll_select_copy_remaining
  - fs/eventpoll.c:ep_poll
  - fs/compat.c:poll_select_copy_remaining
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff810fcb80-ffffffff810fcc73: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ktime_get_ts64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fe780)
Location: kernel/time/timekeeping.c:829
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_ktime_get_ts
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - fs/select.c:poll_select_copy_remaining
  - fs/eventpoll.c:ep_poll
  - fs/compat.c:poll_select_copy_remaining
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff810fe780-ffffffff810fe873: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ktime_get_ts64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81100a30)
Location: kernel/time/timekeeping.c:861
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_ktime_get_ts
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - fs/select.c:compat_poll_select_copy_remaining
  - fs/select.c:poll_select_copy_remaining
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:ep_poll
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff81100a30-ffffffff81100b0f: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ktime_get_ts64(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110b820)
Location: kernel/time/timekeeping.c:865
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_ktime_get_ts
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - fs/select.c:compat_poll_select_copy_remaining
  - fs/select.c:poll_select_copy_remaining
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:ep_poll
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff8110b820-ffffffff8110b902: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81116ff0)
Location: kernel/time/timekeeping.c:866
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_ktime_get_ts
  - fs/select.c:compat_poll_select_copy_remaining
  - fs/select.c:poll_select_copy_remaining
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:ep_poll
  - drivers/input/misc/uinput.c:uinput_dev_event
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff81116ff0-ffffffff811170cd: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81122630)
Location: kernel/time/timekeeping.c:873
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_ktime_get_ts
  - fs/select.c:poll_select_copy_remaining
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:ep_poll
  - drivers/input/misc/uinput.c:uinput_dev_event
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff81122630-ffffffff8112270d: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:880
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_ktime_get_ts
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:ep_poll
  - drivers/input/misc/uinput.c:uinput_dev_event
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff8112f756-ffffffff8112f769: ktime_get_ts64.cold (STB_LOCAL)
ffffffff8112d430-ffffffff8112d508: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811392d0)
Location: kernel/time/timekeeping.c:880
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_ktime_get_ts
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:ep_poll
  - drivers/input/misc/uinput.c:uinput_dev_event
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff811392d0-ffffffff811393af: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81147f70)
Location: kernel/time/timekeeping.c:880
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:ep_poll
  - drivers/input/misc/uinput.c:uinput_dev_event
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff81147f70-ffffffff81148051: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811443b0)
Location: kernel/time/timekeeping.c:950
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
  - drivers/input/misc/uinput.c:uinput_dev_event
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff811443b0-ffffffff81144499: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81145530)
Location: kernel/time/timekeeping.c:950
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
  - drivers/input/misc/uinput.c:uinput_dev_event
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff81145530-ffffffff81145619: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:950
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/select.c:__x64_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x64_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:__x64_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
  - drivers/input/misc/uinput.c:uinput_dev_event
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff81cb0c8c-ffffffff81cb0cb0: ktime_get_ts64.cold (STB_LOCAL)
ffffffff811697a0-ffffffff8116989c: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:969
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
  - drivers/input/misc/uinput.c:uinput_dev_event
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff81e6240c-ffffffff81e62430: ktime_get_ts64.cold (STB_LOCAL)
ffffffff8119dd90-ffffffff8119de88: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:969
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
  - drivers/input/misc/uinput.c:uinput_dev_event
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff8205b071-ffffffff8205b095: ktime_get_ts64.cold (STB_LOCAL)
ffffffff811dbfb0-ffffffff811dc0a8: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:969
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
  - drivers/input/misc/uinput.c:uinput_dev_event
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff820d9b11-ffffffff820d9b35: ktime_get_ts64.cold (STB_LOCAL)
ffffffff811f0e50-ffffffff811f0f48: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:969
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_get_monotonic_timespec
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_wait
  - fs/eventpoll.c:__x64_sys_epoll_wait
  - drivers/input/misc/uinput.c:uinput_dev_event
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff821b5410-ffffffff821b5434: ktime_get_ts64.cold (STB_LOCAL)
ffffffff81206f90-ffffffff81207088: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a3078)
Location: kernel/time/timekeeping.c:880
Inline: False
Direct callers:
  - arch/arm/xen/enlighten.c:xen_pm_init
  - kernel/time/posix-timers.c:posix_ktime_get_ts
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:ep_poll
  - drivers/input/misc/uinput.c:uinput_dev_event
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffff8000101a3078-ffff8000101a3160: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03ed01c)
Location: kernel/time/timekeeping.c:880
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_ktime_get_ts
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:do_epoll_wait
  - drivers/input/misc/uinput.c:uinput_dev_event
  - sound/core/timer.c:snd_timer_user_tinterrupt
  - sound/core/timer.c:snd_timer_notify1
  - sound/core/pcm_native.c:snd_pcm_trigger_tstamp
  - sound/core/pcm_native.c:snd_pcm_status
  - sound/core/pcm_lib.c:update_audio_tstamp
  - sound/core/pcm_lib.c:__snd_pcm_xrun
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
c03ed01c-c03ed1f0: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c000000000204900)
Location: kernel/time/timekeeping.c:880
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_ktime_get_ts
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:ep_poll
  - drivers/input/misc/uinput.c:uinput_dev_event
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
c000000000204900-c000000000204a2c: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe00012fce4)
Location: kernel/time/timekeeping.c:880
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_ktime_get_ts
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:ep_set_mstimeout
  - drivers/input/misc/uinput.c:uinput_dev_event
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffe00012fce4-ffffffe00012fdaa: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81131a80)
Location: kernel/time/timekeeping.c:880
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_ktime_get_ts
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:ep_poll
  - drivers/input/misc/uinput.c:uinput_dev_event
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff81131a80-ffffffff81131b5f: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811244e0)
Location: kernel/time/timekeeping.c:880
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_ktime_get_ts
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:ep_poll
  - drivers/input/misc/uinput.c:uinput_dev_event
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff811244e0-ffffffff811245bf: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112f7a0)
Location: kernel/time/timekeeping.c:880
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_ktime_get_ts
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:ep_poll
  - drivers/input/misc/uinput.c:uinput_dev_event
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff8112f7a0-ffffffff8112f87f: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ktime_get_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113c1c0)
Location: kernel/time/timekeeping.c:880
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:posix_ktime_get_ts
  - fs/select.c:poll_select_finish
  - fs/select.c:select_estimate_accuracy
  - fs/eventpoll.c:ep_poll
  - drivers/input/misc/uinput.c:uinput_dev_event
  - net/socket.c:do_recvmmsg
```
**Symbols:**

```
ffffffff8113c1c0-ffffffff8113c29f: ktime_get_ts64 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
