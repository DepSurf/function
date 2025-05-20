# Function: <code>ktime_add_safe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ee940)
Location: kernel/time/hrtimer.c:308
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_nanosleep
Direct callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/futex.c:futex_wait
  - kernel/futex.c:SyS_futex
  - kernel/futex_compat.c:compat_SyS_futex
  - drivers/md/dm.c:dm_request_fn
```
**Symbols:**

```
ffffffff810ee940-ffffffff810ee971: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810f6ca0)
Location: kernel/time/hrtimer.c:308
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/futex.c:SyS_futex
  - kernel/futex.c:futex_wait
  - kernel/futex_compat.c:compat_SyS_futex
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff810f5a10-ffffffff810f5a41: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fdd61)
Location: kernel/time/hrtimer.c:308
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/futex.c:SyS_futex
  - kernel/futex.c:futex_wait
  - kernel/futex_compat.c:compat_SyS_futex
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff810fca50-ffffffff810fca7f: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81100014)
Location: kernel/time/hrtimer.c:309
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex.c:SyS_futex
  - kernel/futex.c:futex_wait
  - kernel/futex_compat.c:compat_SyS_futex
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff810feea0-ffffffff810feed1: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8110ae04)
Location: kernel/time/hrtimer.c:309
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex.c:SyS_futex
  - kernel/futex.c:futex_wait
  - kernel/futex_compat.c:compat_SyS_futex
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff81109c80-ffffffff81109cb1: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff819f0e4c)
Location: kernel/time/hrtimer.c:323
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/futex.c:futex_wait
  - kernel/futex_compat.c:__x32_compat_sys_futex
  - kernel/futex_compat.c:__ia32_compat_sys_futex
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff811152a0-ffffffff811152d1: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81a2c1cc)
Location: kernel/time/hrtimer.c:314
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex.c:__x32_compat_sys_futex
  - kernel/futex.c:__ia32_compat_sys_futex
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/futex.c:futex_wait
```
**Symbols:**

```
ffffffff811208e0-ffffffff81120911: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81a9c37e)
Location: kernel/time/hrtimer.c:313
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
**Symbols:**

```
ffffffff8112b1e0-ffffffff8112b213: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81ad3c47)
Location: kernel/time/hrtimer.c:323
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
**Symbols:**

```
ffffffff81137170-ffffffff811371a3: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81bcbc4f)
Location: kernel/time/hrtimer.c:323
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
**Symbols:**

```
ffffffff81145ec0-ffffffff81145ef3: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81c44a6f)
Location: kernel/time/hrtimer.c:327
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
**Symbols:**

```
ffffffff811423e0-ffffffff81142413: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81c37cdc)
Location: kernel/time/hrtimer.c:327
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
**Symbols:**

```
ffffffff811435d0-ffffffff81143600: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81d5659c)
Location: kernel/time/hrtimer.c:327
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
**Symbols:**

```
ffffffff81166bb0-ffffffff81166be0: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81f28408)
Location: kernel/time/hrtimer.c:327
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex/core.c:futex_setup_timer
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
  - fs/aio.c:read_events
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff8119a310-ffffffff8119a34a: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff820d4058)
Location: kernel/time/hrtimer.c:327
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex/core.c:futex_setup_timer
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
  - fs/aio.c:read_events
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff811d8a20-ffffffff811d8a5a: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff821582ae)
Location: kernel/time/hrtimer.c:329
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex/core.c:futex_setup_timer
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
  - fs/aio.c:read_events
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff811ece50-ffffffff811ece8a: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8223b11e)
Location: kernel/time/hrtimer.c:329
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_timer_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex/core.c:futex_setup_timer
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
  - fs/aio.c:read_events
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff81202fb0-ffffffff81202fea: ktime_add_safe (STB_GLOBAL)
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff800010da6808)
Location: kernel/time/hrtimer.c:323
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex.c:__arm64_sys_futex_time32
  - kernel/futex.c:__arm64_sys_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
**Symbols:**

```
ffff8000101a0640-ffff8000101a0688: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c0e9e5e4)
Location: kernel/time/hrtimer.c:323
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex.c:__se_sys_futex_time32
  - kernel/futex.c:__se_sys_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
**Symbols:**

```
c03ea150-c03ea1b8: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000ee9028)
Location: kernel/time/hrtimer.c:323
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex.c:__se_sys_futex_time32
  - kernel/futex.c:__se_sys_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
**Symbols:**

```
c0000000002014f0-c000000000201520: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe0008c8b94)
Location: kernel/time/hrtimer.c:323
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex.c:__se_sys_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
**Symbols:**

```
ffffffe00012de72-ffffffe00012deac: ktime_add_safe (STB_GLOBAL)
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
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81a72ab7)
Location: kernel/time/hrtimer.c:323
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
**Symbols:**

```
ffffffff8112f920-ffffffff8112f953: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81a2ee87)
Location: kernel/time/hrtimer.c:323
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
**Symbols:**

```
ffffffff81122390-ffffffff811223c3: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81adeec7)
Location: kernel/time/hrtimer.c:323
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
**Symbols:**

```
ffffffff8112d640-ffffffff8112d673: ktime_add_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ktime_t ktime_add_safe(const ktime_t lhs, const ktime_t rhs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81aeb357)
Location: kernel/time/hrtimer.c:323
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:hrtimer_forward
  - kernel/time/hrtimer.c:hrtimer_forward
Direct callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_arm
  - kernel/time/alarmtimer.c:alarm_forward
  - kernel/time/alarmtimer.c:alarm_start_relative
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
**Symbols:**

```
ffffffff81139f70-ffffffff81139fa3: ktime_add_safe (STB_GLOBAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
