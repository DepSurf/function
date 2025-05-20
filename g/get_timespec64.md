# Function: <code>get_timespec64</code>

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
int get_timespec64(struct timespec *ts, const struct timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fafe6)
Location: kernel/time/time.c:894
Inline: True
Inline callers:
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
Direct callers:
  - kernel/time/hrtimer.c:SyS_nanosleep
  - kernel/time/posix-timers.c:SyS_clock_nanosleep
  - kernel/time/posix-timers.c:SyS_clock_settime
```
**Symbols:**

```
ffffffff810faf70-ffffffff810fafd3: get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int get_timespec64(struct timespec *ts, const struct timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81105986)
Location: kernel/time/time.c:843
Inline: True
Inline callers:
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
Direct callers:
  - kernel/time/hrtimer.c:SyS_nanosleep
  - kernel/time/posix-timers.c:SyS_clock_nanosleep
  - kernel/time/posix-timers.c:SyS_clock_settime
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_pselect6
  - fs/utimes.c:SyS_utimensat
  - fs/utimes.c:SyS_utimensat
  - fs/aio.c:SyS_io_getevents
  - ipc/sem.c:SyS_semtimedop
  - ipc/mqueue.c:SyS_mq_timedreceive
  - ipc/mqueue.c:SyS_mq_timedsend
```
**Symbols:**

```
ffffffff81105910-ffffffff81105973: get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int get_timespec64(struct timespec64 *ts, const struct timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81110aee)
Location: kernel/time/time.c:855
Inline: True
Inline callers:
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
Direct callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:do_pselect
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
```
**Symbols:**

```
ffffffff81110a50-ffffffff81110ab3: get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int get_timespec64(struct timespec64 *ts, const struct timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111c19e)
Location: kernel/time/time.c:793
Inline: True
Inline callers:
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:do_compat_pselect
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff8111c100-ffffffff8111c163: get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_timespec64(struct timespec64 *ts, const struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81126b40)
Location: kernel/time/time.c:871
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:do_compat_pselect
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__do_sys_pselect6
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - ipc/sem.c:ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff81126b40-ffffffff81126bca: get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_timespec64(struct timespec64 *ts, const struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81132ae0)
Location: kernel/time/time.c:871
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:do_compat_pselect
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - fs/io_uring.c:__io_submit_sqe
  - ipc/sem.c:ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff81132ae0-ffffffff81132b6a: get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_timespec64(struct timespec64 *ts, const struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81141d20)
Location: kernel/time/time.c:781
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:do_compat_pselect
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - fs/io_uring.c:io_timeout_prep
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
```
**Symbols:**

```
ffffffff81141d20-ffffffff81141da9: get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_timespec64(struct timespec64 *ts, const struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113df30)
Location: kernel/time/time.c:781
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:do_compat_pselect
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_timeout_prep
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
```
**Symbols:**

```
ffffffff8113df30-ffffffff8113dfb9: get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_timespec64(struct timespec64 *ts, const struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113f180)
Location: kernel/time/time.c:781
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:do_compat_pselect
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/aio.c:__do_compat_sys_io_pgetevents_time64
  - fs/aio.c:__do_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_timeout_prep
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
```
**Symbols:**

```
ffffffff8113f180-ffffffff8113f209: get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_timespec64(struct timespec64 *ts, const struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81162610)
Location: kernel/time/time.c:781
Inline: False
Direct callers:
  - kernel/signal.c:__x64_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - fs/select.c:__x64_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:do_compat_pselect
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/eventpoll.c:__x64_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/aio.c:__x64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_timeout_prep
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
```
**Symbols:**

```
ffffffff81162610-ffffffff81162699: get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int get_timespec64(struct timespec64 *ts, const struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81195df0)
Location: kernel/time/time.c:781
Inline: True
Inline callers:
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:do_compat_pselect
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:__io_timeout_prep
  - io_uring/io_uring.c:io_timeout_remove_prep
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
```
**Symbols:**

```
ffffffff811955f0-ffffffff81195685: get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int get_timespec64(struct timespec64 *ts, const struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d3d70)
Location: kernel/time/time.c:781
Inline: True
Inline callers:
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:do_compat_pselect
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/timeout.c:__io_timeout_prep
  - io_uring/timeout.c:io_timeout_remove_prep
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
```
**Symbols:**

```
ffffffff811d3470-ffffffff811d3505: get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int get_timespec64(struct timespec64 *ts, const struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e8060)
Location: kernel/time/time.c:781
Inline: True
Inline callers:
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:do_compat_pselect
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/timeout.c:__io_timeout_prep
  - io_uring/timeout.c:io_timeout_remove_prep
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
```
**Symbols:**

```
ffffffff811e7760-ffffffff811e77f5: get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int get_timespec64(struct timespec64 *ts, const struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fdd90)
Location: kernel/time/time.c:871
Inline: True
Inline callers:
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
Direct callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/futex/syscalls.c:futex2_setup_timeout
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:do_compat_pselect
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait2
  - fs/eventpoll.c:__ia32_sys_epoll_pwait2
  - fs/eventpoll.c:__x64_sys_epoll_pwait2
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - ipc/sem.c:__ia32_sys_semtimedop
  - ipc/sem.c:__x64_sys_semtimedop
  - ipc/sem.c:ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/timeout.c:__io_timeout_prep
  - io_uring/timeout.c:io_timeout_remove_prep
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
```
**Symbols:**

```
ffffffff811fd490-ffffffff811fd525: get_timespec64 (STB_GLOBAL)
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
int get_timespec64(struct timespec64 *ts, const struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff80001019a928)
Location: kernel/time/time.c:871
Inline: False
Direct callers:
  - kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__arm64_sys_rt_sigtimedwait
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/hrtimer.c:__arm64_sys_nanosleep
  - kernel/time/posix-timers.c:__arm64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__arm64_sys_clock_settime
  - kernel/futex.c:__arm64_sys_futex
  - fs/select.c:__arm64_compat_sys_ppoll_time64
  - fs/select.c:do_compat_pselect
  - fs/select.c:__arm64_sys_ppoll
  - fs/select.c:__arm64_sys_pselect6
  - fs/utimes.c:__arm64_sys_utimensat
  - fs/utimes.c:__arm64_sys_utimensat
  - fs/aio.c:__arm64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__arm64_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_getevents
  - fs/io_uring.c:__io_submit_sqe
  - ipc/sem.c:ksys_semtimedop
  - ipc/mqueue.c:__arm64_sys_mq_timedreceive
  - ipc/mqueue.c:__arm64_sys_mq_timedsend
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffff80001019a928-ffff80001019a9c0: get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_timespec64(struct timespec64 *ts, const struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e4ff4)
Location: kernel/time/time.c:871
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__se_sys_clock_settime
  - kernel/futex.c:__se_sys_futex
  - fs/select.c:__se_sys_ppoll
  - fs/select.c:do_pselect
  - fs/utimes.c:__se_sys_utimensat
  - fs/utimes.c:__se_sys_utimensat
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/io_uring.c:__io_submit_sqe
  - ipc/sem.c:ksys_semtimedop
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
c03e4ff4-c03e50b4: get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_timespec64(struct timespec64 *ts, const struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fa610)
Location: kernel/time/time.c:871
Inline: False
Direct callers:
  - kernel/signal.c:__se_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/hrtimer.c:__se_sys_nanosleep
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__se_sys_clock_settime
  - kernel/futex.c:__se_sys_futex
  - fs/select.c:__se_compat_sys_ppoll_time64
  - fs/select.c:do_compat_pselect
  - fs/select.c:__se_sys_ppoll
  - fs/select.c:__se_sys_pselect6
  - fs/utimes.c:__se_sys_utimensat
  - fs/utimes.c:__se_sys_utimensat
  - fs/aio.c:__se_compat_sys_io_pgetevents_time64
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/aio.c:__se_sys_io_getevents
  - fs/io_uring.c:__io_submit_sqe
  - ipc/sem.c:ksys_semtimedop
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
c0000000001fa610-c0000000001fa6c0: get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int get_timespec64(struct timespec64 *ts, const struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a760)
Location: kernel/time/time.c:871
Inline: True
Inline callers:
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
Direct callers:
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/time/hrtimer.c:__se_sys_nanosleep
  - kernel/time/posix-timers.c:__se_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__se_sys_clock_settime
  - kernel/futex.c:__se_sys_futex
  - fs/select.c:__se_sys_ppoll
  - fs/select.c:__se_sys_pselect6
  - fs/utimes.c:__se_sys_utimensat
  - fs/utimes.c:__se_sys_utimensat
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/aio.c:__se_sys_io_getevents
  - fs/io_uring.c:__io_submit_sqe
  - ipc/sem.c:ksys_semtimedop
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffe00012a6b2-ffffffe00012a6fc: get_timespec64 (STB_GLOBAL)
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
int get_timespec64(struct timespec64 *ts, const struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112b290)
Location: kernel/time/time.c:871
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:do_compat_pselect
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - fs/io_uring.c:__io_submit_sqe
  - ipc/sem.c:ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff8112b290-ffffffff8112b31a: get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_timespec64(struct timespec64 *ts, const struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111db00)
Location: kernel/time/time.c:871
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:do_compat_pselect
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - fs/io_uring.c:__io_submit_sqe
  - ipc/sem.c:ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff8111db00-ffffffff8111db8a: get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_timespec64(struct timespec64 *ts, const struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81128fb0)
Location: kernel/time/time.c:871
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:do_compat_pselect
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - fs/io_uring.c:__io_submit_sqe
  - ipc/sem.c:ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff81128fb0-ffffffff8112903a: get_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_timespec64(struct timespec64 *ts, const struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81135600)
Location: kernel/time/time.c:871
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/time.c:get_itimerspec64
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__x64_sys_clock_nanosleep
  - kernel/time/posix-timers.c:__ia32_sys_clock_settime
  - kernel/time/posix-timers.c:__x64_sys_clock_settime
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:do_compat_pselect
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__ia32_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/utimes.c:__x64_sys_utimensat
  - fs/aio.c:__x32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_compat_sys_io_pgetevents_time64
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_getevents
  - fs/aio.c:__x64_sys_io_getevents
  - fs/io_uring.c:__io_submit_sqe
  - ipc/sem.c:ksys_semtimedop
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive
  - ipc/mqueue.c:__x64_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_sys_mq_timedsend
  - ipc/mqueue.c:__x64_sys_mq_timedsend
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff81135600-ffffffff8113568a: get_timespec64 (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct timespec *uts</code> ➡️ <code>const struct __kernel_timespec *uts</code>
</li>
</ul>
</details>
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
