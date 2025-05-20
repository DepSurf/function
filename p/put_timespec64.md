# Function: <code>put_timespec64</code>

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
int put_timespec64(const struct timespec *ts, struct timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fae66)
Location: kernel/time/time.c:911
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/time/posix-timers.c:SyS_clock_getres
  - kernel/time/posix-timers.c:SyS_clock_gettime
```
**Symbols:**

```
ffffffff810fae00-ffffffff810fae60: put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int put_timespec64(const struct timespec *ts, struct timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811057f6)
Location: kernel/time/time.c:860
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/time/posix-timers.c:SyS_clock_getres
  - kernel/time/posix-timers.c:SyS_clock_gettime
  - fs/select.c:poll_select_copy_remaining
```
**Symbols:**

```
ffffffff81105790-ffffffff811057f0: put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int put_timespec64(const struct timespec64 *ts, struct timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811108de)
Location: kernel/time/time.c:877
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - fs/select.c:poll_select_copy_remaining
```
**Symbols:**

```
ffffffff81110850-ffffffff811108b0: put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int put_timespec64(const struct timespec64 *ts, struct timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111be6e)
Location: kernel/time/time.c:815
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - fs/select.c:poll_select_copy_remaining
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff8111bde0-ffffffff8111be40: put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int put_timespec64(const struct timespec64 *ts, struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811268ae)
Location: kernel/time/time.c:893
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - fs/select.c:poll_select_finish
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff81126820-ffffffff81126880: put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int put_timespec64(const struct timespec64 *ts, struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113284e)
Location: kernel/time/time.c:894
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - fs/select.c:poll_select_finish
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff811327c0-ffffffff81132820: put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int put_timespec64(const struct timespec64 *ts, struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81142538)
Location: kernel/time/time.c:804
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - fs/select.c:poll_select_finish
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff81141b40-ffffffff81141b9e: put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int put_timespec64(const struct timespec64 *ts, struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113e748)
Location: kernel/time/time.c:804
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - fs/select.c:poll_select_finish
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff8113dd50-ffffffff8113ddae: put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int put_timespec64(const struct timespec64 *ts, struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113f978)
Location: kernel/time/time.c:804
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - fs/select.c:poll_select_finish
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff8113efa0-ffffffff8113effb: put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int put_timespec64(const struct timespec64 *ts, struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81162e08)
Location: kernel/time/time.c:804
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - fs/select.c:poll_select_finish
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff81162430-ffffffff8116248b: put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int put_timespec64(const struct timespec64 *ts, struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81195d58)
Location: kernel/time/time.c:804
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
  - kernel/time/hrtimer.c:nanosleep_copyout
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - fs/select.c:poll_select_finish
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff811953c0-ffffffff81195425: put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int put_timespec64(const struct timespec64 *ts, struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d3cc8)
Location: kernel/time/time.c:804
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
  - kernel/time/hrtimer.c:nanosleep_copyout
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - fs/select.c:poll_select_finish
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff811d3210-ffffffff811d3275: put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int put_timespec64(const struct timespec64 *ts, struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e7fb8)
Location: kernel/time/time.c:804
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
  - kernel/time/hrtimer.c:nanosleep_copyout
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - fs/select.c:poll_select_finish
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff811e7500-ffffffff811e7565: put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int put_timespec64(const struct timespec64 *ts, struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fdce8)
Location: kernel/time/time.c:902
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
  - kernel/time/hrtimer.c:nanosleep_copyout
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - fs/select.c:poll_select_finish
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff811fd230-ffffffff811fd295: put_timespec64 (STB_GLOBAL)
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
int put_timespec64(const struct timespec64 *ts, struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff80001019b084)
Location: kernel/time/time.c:894
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:__arm64_sys_sched_rr_get_interval
  - kernel/time/posix-timers.c:__arm64_sys_clock_getres
  - kernel/time/posix-timers.c:__arm64_sys_clock_gettime
  - fs/select.c:poll_select_finish
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffff80001019acc0-ffff80001019ae5c: put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int put_timespec64(const struct timespec64 *ts, struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e4d0c)
Location: kernel/time/time.c:894
Inline: False
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_rr_get_interval
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/posix-timers.c:__se_sys_clock_getres
  - kernel/time/posix-timers.c:__se_sys_clock_gettime
  - fs/select.c:poll_select_finish
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
c03e4d0c-c03e4dd0: put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int put_timespec64(const struct timespec64 *ts, struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fa4a4)
Location: kernel/time/time.c:894
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_rr_get_interval
  - kernel/time/posix-timers.c:__se_sys_clock_getres
  - kernel/time/posix-timers.c:__se_sys_clock_gettime
  - fs/select.c:poll_select_finish
  - net/socket.c:__sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
c0000000001fa350-c0000000001fa3e0: put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int put_timespec64(const struct timespec64 *ts, struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a5fc)
Location: kernel/time/time.c:894
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_rr_get_interval
  - kernel/time/posix-timers.c:__se_sys_clock_getres
  - kernel/time/posix-timers.c:__se_sys_clock_gettime
  - fs/select.c:poll_select_finish
  - net/socket.c:__sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffe00012a552-ffffffe00012a59a: put_timespec64 (STB_GLOBAL)
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
int put_timespec64(const struct timespec64 *ts, struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112affe)
Location: kernel/time/time.c:894
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - fs/select.c:poll_select_finish
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff8112af70-ffffffff8112afd0: put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int put_timespec64(const struct timespec64 *ts, struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111d86e)
Location: kernel/time/time.c:894
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - fs/select.c:poll_select_finish
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff8111d7e0-ffffffff8111d840: put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int put_timespec64(const struct timespec64 *ts, struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81128d1e)
Location: kernel/time/time.c:894
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - fs/select.c:poll_select_finish
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff81128c90-ffffffff81128cf0: put_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int put_timespec64(const struct timespec64 *ts, struct __kernel_timespec *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113536e)
Location: kernel/time/time.c:894
Inline: True
Inline callers:
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres
  - kernel/time/posix-timers.c:__x64_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime
  - fs/select.c:poll_select_finish
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff811352e0-ffffffff81135340: put_timespec64 (STB_GLOBAL)
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
<code>const struct timespec *ts</code> ➡️ <code>const struct timespec64 *ts</code>
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
<code>struct timespec *uts</code> ➡️ <code>struct __kernel_timespec *uts</code>
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
