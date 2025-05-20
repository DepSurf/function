# Function: <code>put_old_timespec32</code>

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
int put_old_timespec32(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111c4e0)
Location: kernel/time/time.c:862
Inline: True
Direct callers:
  - kernel/sched/core.c:__x32_compat_sys_sched_rr_get_interval
  - kernel/sched/core.c:__ia32_compat_sys_sched_rr_get_interval
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_getres
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_getres
  - kernel/time/posix-timers.c:__x32_compat_sys_clock_gettime
  - kernel/time/posix-timers.c:__ia32_compat_sys_clock_gettime
  - fs/select.c:poll_select_copy_remaining
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff8111c4e0-ffffffff8111c55e: put_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int put_old_timespec32(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81126e10)
Location: kernel/time/time.c:940
Inline: True
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - fs/select.c:poll_select_finish
  - net/socket.c:__sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff81126e10-ffffffff81126e8e: put_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int put_old_timespec32(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81132db0)
Location: kernel/time/time.c:941
Inline: True
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - fs/select.c:poll_select_finish
  - net/socket.c:__sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff81132db0-ffffffff81132e2e: put_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int put_old_timespec32(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81141f50)
Location: kernel/time/time.c:851
Inline: True
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - fs/select.c:poll_select_finish
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff81141f50-ffffffff81141fce: put_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int put_old_timespec32(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113e160)
Location: kernel/time/time.c:851
Inline: True
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - fs/select.c:poll_select_finish
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff8113e160-ffffffff8113e1de: put_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int put_old_timespec32(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113f3a0)
Location: kernel/time/time.c:851
Inline: True
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - fs/select.c:poll_select_finish
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff8113f3a0-ffffffff8113f428: put_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int put_old_timespec32(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81162830)
Location: kernel/time/time.c:851
Inline: True
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - fs/select.c:poll_select_finish
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff81162830-ffffffff811628b8: put_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int put_old_timespec32(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81195940)
Location: kernel/time/time.c:851
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/time/hrtimer.c:nanosleep_copyout
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - fs/select.c:poll_select_finish
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff81195940-ffffffff811959a3: put_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int put_old_timespec32(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d3850)
Location: kernel/time/time.c:851
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/time/hrtimer.c:nanosleep_copyout
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - fs/select.c:poll_select_finish
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff811d3850-ffffffff811d38b3: put_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int put_old_timespec32(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e7b40)
Location: kernel/time/time.c:851
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/time/hrtimer.c:nanosleep_copyout
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - fs/select.c:poll_select_finish
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff811e7b40-ffffffff811e7ba3: put_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int put_old_timespec32(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fd870)
Location: kernel/time/time.c:968
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/time/hrtimer.c:nanosleep_copyout
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - fs/select.c:poll_select_finish
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff811fd870-ffffffff811fd8d3: put_old_timespec32 (STB_GLOBAL)
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
int put_old_timespec32(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff80001019ab20)
Location: kernel/time/time.c:941
Inline: False
Direct callers:
  - kernel/sched/core.c:__arm64_sys_sched_rr_get_interval_time32
  - kernel/time/posix-timers.c:__arm64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__arm64_sys_clock_gettime32
  - fs/select.c:poll_select_finish
  - net/socket.c:__sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffff80001019ab20-ffff80001019acbc: put_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int put_old_timespec32(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e4c4c)
Location: kernel/time/time.c:941
Inline: False
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_rr_get_interval_time32
  - kernel/time/posix-timers.c:__se_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__se_sys_clock_gettime32
  - fs/select.c:poll_select_finish
  - net/socket.c:__sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
c03e4c4c-c03e4d0c: put_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int put_old_timespec32(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fa3e0)
Location: kernel/time/time.c:941
Inline: False
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_rr_get_interval_time32
  - kernel/time/posix-timers.c:__se_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__se_sys_clock_gettime32
  - fs/select.c:poll_select_finish
  - net/socket.c:__sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
c0000000001fa3e0-c0000000001fa470: put_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int put_old_timespec32(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a59a)
Location: kernel/time/time.c:941
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffe00012a59a-ffffffe00012a5e2: put_old_timespec32 (STB_GLOBAL)
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
int put_old_timespec32(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112b560)
Location: kernel/time/time.c:941
Inline: True
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - fs/select.c:poll_select_finish
  - net/socket.c:__sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff8112b560-ffffffff8112b5de: put_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int put_old_timespec32(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111ddd0)
Location: kernel/time/time.c:941
Inline: True
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - fs/select.c:poll_select_finish
  - net/socket.c:__sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff8111ddd0-ffffffff8111de4e: put_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int put_old_timespec32(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81129280)
Location: kernel/time/time.c:941
Inline: True
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - fs/select.c:poll_select_finish
  - net/socket.c:__sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff81129280-ffffffff811292fe: put_old_timespec32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int put_old_timespec32(const struct timespec64 *ts, void *uts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811358d0)
Location: kernel/time/time.c:941
Inline: True
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_rr_get_interval_time32
  - kernel/sched/core.c:__x64_sys_sched_rr_get_interval_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__x64_sys_clock_getres_time32
  - kernel/time/posix-timers.c:__ia32_sys_clock_gettime32
  - kernel/time/posix-timers.c:__x64_sys_clock_gettime32
  - fs/select.c:poll_select_finish
  - net/socket.c:__sys_recvmmsg
  - net/core/sock.c:sock_gettstamp
```
**Symbols:**

```
ffffffff811358d0-ffffffff8113594e: put_old_timespec32 (STB_GLOBAL)
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
