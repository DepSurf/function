# Function: <code>get_old_timespec32</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int get_old_timespec32(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111c450)
Location: kernel/time/time.c:853
Inline: True
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/time/hrtimer.c:__x32_compat_sys_nanosleep
  - kernel/time/hrtimer.c:__ia32_compat_sys_nanosleep
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_settime
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_settime
  - kernel/futex.c:__x32_compat_sys_futex
  - kernel/futex.c:__ia32_compat_sys_futex
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
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff8111c450-ffffffff8111c4e0: get_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int get_old_timespec32(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81126d70)
Location: kernel/time/time.c:931
Inline: True
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff81126d70-ffffffff81126e04: get_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int get_old_timespec32(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81132d10)
Location: kernel/time/time.c:932
Inline: True
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff81132d10-ffffffff81132da4: get_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int get_old_timespec32(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81141eb0)
Location: kernel/time/time.c:842
Inline: True
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
```
**Symbols:**

```
ffffffff81141eb0-ffffffff81141f42: get_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int get_old_timespec32(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113e0c0)
Location: kernel/time/time.c:842
Inline: True
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
```
**Symbols:**

```
ffffffff8113e0c0-ffffffff8113e152: get_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int get_old_timespec32(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113f310)
Location: kernel/time/time.c:842
Inline: True
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/aio.c:__do_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
```
**Symbols:**

```
ffffffff8113f310-ffffffff8113f39f: get_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int get_old_timespec32(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811627a0)
Location: kernel/time/time.c:842
Inline: True
Direct callers:
  - kernel/signal.c:__x64_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - fs/select.c:__x64_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/aio.c:__x64_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
```
**Symbols:**

```
ffffffff811627a0-ffffffff8116282f: get_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_old_timespec32(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811959b0)
Location: kernel/time/time.c:842
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
```
**Symbols:**

```
ffffffff811959b0-ffffffff81195a28: get_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_old_timespec32(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d38d0)
Location: kernel/time/time.c:842
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
```
**Symbols:**

```
ffffffff811d38d0-ffffffff811d3948: get_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_old_timespec32(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e7bc0)
Location: kernel/time/time.c:842
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
```
**Symbols:**

```
ffffffff811e7bc0-ffffffff811e7c38: get_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_old_timespec32(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fd8f0)
Location: kernel/time/time.c:949
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
```
**Symbols:**

```
ffffffff811fd8f0-ffffffff811fd968: get_old_timespec32 (STB_GLOBAL)
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
int get_old_timespec32(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff80001019aa08)
Location: kernel/time/time.c:932
Inline: False
Direct callers:
  - kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__arm64_sys_rt_sigtimedwait_time32
  - kernel/time/hrtimer.c:__arm64_sys_nanosleep_time32
  - kernel/time/posix-timers.c:__arm64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__arm64_sys_clock_settime32
  - kernel/futex.c:__arm64_sys_futex_time32
  - fs/select.c:__arm64_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/utimes.c:__arm64_sys_utimensat_time32
  - fs/utimes.c:__arm64_sys_utimensat_time32
  - fs/aio.c:__arm64_compat_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_getevents_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/mqueue.c:__arm64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__arm64_sys_mq_timedsend_time32
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffff80001019aa08-ffff80001019aa84: get_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_old_timespec32(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e4f34)
Location: kernel/time/time.c:932
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_rt_sigtimedwait_time32
  - kernel/time/hrtimer.c:__se_sys_nanosleep_time32
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__se_sys_clock_settime32
  - kernel/futex.c:__se_sys_futex_time32
  - fs/select.c:__se_sys_ppoll_time32
  - fs/select.c:do_pselect
  - fs/utimes.c:__se_sys_utimensat_time32
  - fs/utimes.c:__se_sys_utimensat_time32
  - fs/aio.c:__se_sys_io_getevents_time32
  - fs/aio.c:__se_sys_io_pgetevents_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/mqueue.c:__se_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__se_sys_mq_timedsend_time32
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
c03e4f34-c03e4ff4: get_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_old_timespec32(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fa730)
Location: kernel/time/time.c:932
Inline: False
Direct callers:
  - kernel/signal.c:__se_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__se_sys_rt_sigtimedwait_time32
  - kernel/time/hrtimer.c:__se_sys_nanosleep_time32
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__se_sys_clock_settime32
  - kernel/futex.c:__se_sys_futex_time32
  - fs/select.c:__se_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/utimes.c:__se_sys_utimensat_time32
  - fs/utimes.c:__se_sys_utimensat_time32
  - fs/aio.c:__se_compat_sys_io_pgetevents
  - fs/aio.c:__se_sys_io_getevents_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/mqueue.c:__se_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__se_sys_mq_timedsend_time32
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
c0000000001fa730-c0000000001fa7c0: get_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_old_timespec32(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a6fc)
Location: kernel/time/time.c:932
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffe00012a6fc-ffffffe00012a746: get_old_timespec32 (STB_GLOBAL)
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
int get_old_timespec32(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112b4c0)
Location: kernel/time/time.c:932
Inline: True
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff8112b4c0-ffffffff8112b554: get_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int get_old_timespec32(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111dd30)
Location: kernel/time/time.c:932
Inline: True
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff8111dd30-ffffffff8111ddc4: get_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int get_old_timespec32(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811291e0)
Location: kernel/time/time.c:932
Inline: True
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff811291e0-ffffffff81129274: get_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int get_old_timespec32(struct timespec64 *ts, const void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81135830)
Location: kernel/time/time.c:932
Inline: True
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime32
  - kernel/time/posix-timers.c:__x64_sys_clock_settime32
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__ia32_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/utimes.c:__x64_sys_utimensat_time32
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
  - ipc/sem.c:compat_ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff81135830-ffffffff811358c4: get_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
