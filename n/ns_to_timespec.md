# Function: <code>ns_to_timespec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct timespec ns_to_timespec(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810eb0ba)
Location: kernel/time/time.c:389
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
Direct callers:
  - kernel/sys.c:do_sysinfo
  - kernel/time/hrtimer.c:update_rmtp
  - kernel/time/posix-timers.c:posix_get_coarse_res
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-cpu-timers.c:sample_to_timespec
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/alarmtimer.c:alarm_timer_get
  - kernel/time/alarmtimer.c:alarm_timer_get
  - kernel/time/alarmtimer.c:alarm_clock_get
  - kernel/time/alarmtimer.c:update_rmtp
  - kernel/time/timer_stats.c:tstats_show
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/rtc/rtc-lib.c:rtc_ktime_to_tm
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestampns
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestampns
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
```
**Symbols:**

```
ffffffff810eb160-ffffffff810eb1bb: ns_to_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct timespec ns_to_timespec(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f1d8a)
Location: kernel/time/time.c:396
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
Direct callers:
  - kernel/sys.c:do_sysinfo
  - kernel/time/hrtimer.c:update_rmtp
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/time/posix-timers.c:posix_get_coarse_res
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:sample_to_timespec
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/alarmtimer.c:update_rmtp
  - kernel/time/alarmtimer.c:alarm_timer_get
  - kernel/time/alarmtimer.c:alarm_timer_get
  - kernel/time/alarmtimer.c:alarm_clock_get
  - kernel/time/timer_stats.c:tstats_show
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/rtc/rtc-lib.c:rtc_ktime_to_tm
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestampns
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestampns
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
```
**Symbols:**

```
ffffffff810f1e00-ffffffff810f1e5b: ns_to_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct timespec ns_to_timespec(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f8f0a)
Location: kernel/time/time.c:396
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
Direct callers:
  - kernel/sys.c:do_sysinfo
  - kernel/time/hrtimer.c:update_rmtp
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/alarmtimer.c:update_rmtp
  - kernel/time/alarmtimer.c:alarm_timer_get
  - kernel/time/alarmtimer.c:alarm_timer_get
  - kernel/time/alarmtimer.c:alarm_clock_get
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/time/posix-timers.c:posix_get_coarse_res
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:sample_to_timespec
  - kernel/time/timer_stats.c:tstats_show
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/rtc/rtc-lib.c:rtc_ktime_to_tm
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestampns
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestampns
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
```
**Symbols:**

```
ffffffff810f8f80-ffffffff810f8fdb: ns_to_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct timespec ns_to_timespec(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fb1aa)
Location: kernel/time/time.c:486
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
Direct callers:
  - kernel/sys.c:do_sysinfo
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_clock_get
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/time/posix-timers.c:posix_get_coarse_res
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get_task
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/rtc/rtc-lib.c:rtc_ktime_to_tm
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestampns
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestampns
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
```
**Symbols:**

```
ffffffff810fb230-ffffffff810fb293: ns_to_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct timespec ns_to_timespec(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81110d95)
Location: kernel/time/time.c:454
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
Direct callers:
  - kernel/sys.c:do_sysinfo
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - fs/proc/uptime.c:uptime_proc_show
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestampns
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestampns
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
```
**Symbols:**

```
ffffffff81111000-ffffffff8111105b: ns_to_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct timespec ns_to_timespec(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111c565)
Location: kernel/time/time.c:392
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
  - kernel/time/time.c:ns_to_timeval
Direct callers:
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestampns
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
```
**Symbols:**

```
ffffffff8111c6c0-ffffffff8111c71b: ns_to_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct timespec ns_to_timespec(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81126e95)
Location: kernel/time/time.c:460
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
  - kernel/time/time.c:ns_to_timeval
Direct callers:
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - net/socket.c:__sock_recv_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
```
**Symbols:**

```
ffffffff81126ff0-ffffffff8112704b: ns_to_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct timespec ns_to_timespec(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81132e35)
Location: kernel/time/time.c:460
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
  - kernel/time/time.c:ns_to_timeval
Direct callers:
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - net/socket.c:__sock_recv_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
```
**Symbols:**

```
ffffffff81132f90-ffffffff81132feb: ns_to_timespec (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct timespec ns_to_timespec(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff80001019a150)
Location: kernel/time/time.c:460
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
  - kernel/time/time.c:ns_to_timeval
Direct callers:
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - net/socket.c:__sock_recv_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
```
**Symbols:**

```
ffff80001019a268-ffff80001019a2e0: ns_to_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct timespec ns_to_timespec(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/time.c (c03e4a7c)
Location: kernel/time/time.c:460
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
Direct callers:
  - kernel/time/time.c:ns_to_timeval
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - sound/core/pcm_lib.c:update_audio_tstamp
  - net/socket.c:__sock_recv_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
```
**Symbols:**

```
c03e4934-c03e49c0: ns_to_timespec.part.0 (STB_LOCAL)
c03e49c0-c03e4a3c: ns_to_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct timespec ns_to_timespec(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001faac8)
Location: kernel/time/time.c:460
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
  - kernel/time/time.c:ns_to_timeval
Direct callers:
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - net/socket.c:__sock_recv_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
```
**Symbols:**

```
c0000000001fac80-c0000000001facf8: ns_to_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct timespec ns_to_timespec(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a888)
Location: kernel/time/time.c:460
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
  - kernel/time/time.c:ns_to_timeval
Direct callers:
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - net/socket.c:__sock_recv_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
```
**Symbols:**

```
ffffffe00012a974-ffffffe00012a9de: ns_to_timespec (STB_GLOBAL)
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
struct timespec ns_to_timespec(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112b5e5)
Location: kernel/time/time.c:460
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
  - kernel/time/time.c:ns_to_timeval
Direct callers:
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - net/socket.c:__sock_recv_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
```
**Symbols:**

```
ffffffff8112b740-ffffffff8112b79b: ns_to_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct timespec ns_to_timespec(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111de55)
Location: kernel/time/time.c:460
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
  - kernel/time/time.c:ns_to_timeval
Direct callers:
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - net/socket.c:__sock_recv_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
```
**Symbols:**

```
ffffffff8111dfb0-ffffffff8111e00b: ns_to_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct timespec ns_to_timespec(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81129305)
Location: kernel/time/time.c:460
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
  - kernel/time/time.c:ns_to_timeval
Direct callers:
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - net/socket.c:__sock_recv_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
```
**Symbols:**

```
ffffffff81129460-ffffffff811294bb: ns_to_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct timespec ns_to_timespec(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81135955)
Location: kernel/time/time.c:460
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_timeval
  - kernel/time/time.c:ns_to_timeval
Direct callers:
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - net/socket.c:__sock_recv_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
  - net/packet/af_packet.c:tpacket_get_timestamp
```
**Symbols:**

```
ffffffff81135ab0-ffffffff81135b0b: ns_to_timespec (STB_GLOBAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
