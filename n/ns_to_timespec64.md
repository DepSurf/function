# Function: <code>ns_to_timespec64</code>

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
struct timespec ns_to_timespec64(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81105b4a)
Location: kernel/time/time.c:533
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
  - fs/pstore/platform.c:pstore_record_init
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/rtc/rtc-lib.c:rtc_ktime_to_tm
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
ffffffff81105bd0-ffffffff81105c33: ns_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81110e15)
Location: kernel/time/time.c:545
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
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
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/pstore/platform.c:pstore_record_init
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/rtc-lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
**Symbols:**

```
ffffffff81110fa0-ffffffff81110ffb: ns_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111c5e5)
Location: kernel/time/time.c:483
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
  - kernel/sys.c:do_sysinfo
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
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
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/proc/uptime.c:uptime_proc_show
  - fs/pstore/platform.c:pstore_record_init
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
**Symbols:**

```
ffffffff8111c660-ffffffff8111c6bb: ns_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81126f15)
Location: kernel/time/time.c:551
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
  - kernel/sys.c:do_sysinfo
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
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
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/proc/uptime.c:uptime_proc_show
  - fs/pstore/platform.c:pstore_record_init
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_gettstamp
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff81126f90-ffffffff81126feb: ns_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81132eb5)
Location: kernel/time/time.c:551
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
  - kernel/sys.c:do_sysinfo
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
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
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/proc/uptime.c:uptime_proc_show
  - fs/pstore/platform.c:pstore_record_init
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_gettstamp
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff81132f30-ffffffff81132f8b: ns_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81142435)
Location: kernel/time/time.c:506
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:posix_get_tai_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_coarse_res
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - fs/proc/uptime.c:uptime_proc_show
  - fs/pstore/platform.c:pstore_dump
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_clock.c:ptp_clock_event
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_gettstamp
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/packet/af_packet.c:__packet_set_timestamp
  - net/packet/af_packet.c:__packet_set_timestamp
```
**Symbols:**

```
ffffffff811419c0-ffffffff81141a3c: ns_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113e645)
Location: kernel/time/time.c:506
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:posix_get_tai_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_coarse_res
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - fs/proc/uptime.c:uptime_proc_show
  - fs/pstore/platform.c:pstore_dump
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_clock.c:ptp_clock_event
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_gettstamp
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/packet/af_packet.c:__packet_set_timestamp
  - net/packet/af_packet.c:__packet_set_timestamp
```
**Symbols:**

```
ffffffff8113dbd0-ffffffff8113dc4c: ns_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113f895)
Location: kernel/time/time.c:506
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:posix_get_tai_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_coarse_res
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - fs/proc/uptime.c:uptime_proc_show
  - fs/pstore/platform.c:pstore_dump
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_clock.c:ptp_clock_event
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_gettstamp
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
```
**Symbols:**

```
ffffffff8113ee20-ffffffff8113ee9c: ns_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81162d25)
Location: kernel/time/time.c:506
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:posix_get_tai_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_coarse_res
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - fs/proc/uptime.c:uptime_proc_show
  - fs/pstore/platform.c:pstore_dump
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_clock.c:ptp_clock_event
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_vclock.c:ptp_vclock_refresh
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_gettstamp
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
**Symbols:**

```
ffffffff811622b0-ffffffff8116232c: ns_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81195c75)
Location: kernel/time/time.c:506
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:posix_get_tai_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_coarse_res
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - fs/proc/uptime.c:uptime_proc_show
  - fs/pstore/platform.c:pstore_dump
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_clock.c:ptp_clock_event
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_vclock.c:ptp_vclock_refresh
  - drivers/ptp/ptp_vclock.c:ptp_vclock_gettimex
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_gettstamp
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
**Symbols:**

```
ffffffff81195230-ffffffff811952bd: ns_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 ns_to_timespec64(s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d3bd5)
Location: kernel/time/time.c:506
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:posix_get_tai_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_coarse_res
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - fs/proc/uptime.c:uptime_proc_show
  - fs/pstore/platform.c:pstore_dump
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_clock.c:ptp_clock_event
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_vclock.c:ptp_vclock_refresh
  - drivers/ptp/ptp_vclock.c:ptp_vclock_gettimex
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_gettstamp
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
**Symbols:**

```
ffffffff811d3050-ffffffff811d30dd: ns_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 ns_to_timespec64(s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e7ec5)
Location: kernel/time/time.c:506
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:posix_get_tai_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_coarse_res
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - fs/proc/uptime.c:uptime_proc_show
  - fs/pstore/platform.c:pstore_record_init
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_clock.c:ptp_clock_event
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_vclock.c:ptp_vclock_refresh
  - drivers/ptp/ptp_vclock.c:ptp_vclock_gettimex
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_gettstamp
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
**Symbols:**

```
ffffffff811e7340-ffffffff811e73cd: ns_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 ns_to_timespec64(s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fdbf5)
Location: kernel/time/time.c:523
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:posix_get_tai_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_coarse_res
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_get
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:do_getitimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/namespace.c:proc_timens_set_offset
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_show
  - fs/timerfd.c:timerfd_show
  - fs/proc/uptime.c:uptime_proc_show
  - fs/pstore/platform.c:pstore_record_init
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/gpu/drm/drm_vblank.c:drm_wait_vblank_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_wait_vblank_ioctl
  - drivers/gpu/drm/drm_vblank.c:send_vblank_event
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_helper_get_vblank_timestamp_internal
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_helper_get_vblank_timestamp_internal
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_clock.c:ptp_clock_event
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_vclock.c:ptp_vclock_refresh
  - drivers/ptp/ptp_vclock.c:ptp_vclock_gettimex
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_gettstamp
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
  - net/ipv4/tcp.c:tcp_update_recv_tstamps
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
**Symbols:**

```
ffffffff811fd070-ffffffff811fd0fd: ns_to_timespec64 (STB_GLOBAL)
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
struct timespec64 ns_to_timespec64(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff80001019a1e8)
Location: kernel/time/time.c:551
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
  - kernel/sys.c:do_sysinfo
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
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
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/proc/uptime.c:uptime_proc_show
  - fs/pstore/platform.c:pstore_record_init
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_gettime
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_gettstamp
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffff80001019a2e0-ffff80001019a358: ns_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e4b10)
Location: kernel/time/time.c:551
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
  - kernel/sys.c:__se_sys_sysinfo
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
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
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/proc/uptime.c:uptime_proc_show
  - fs/pstore/platform.c:pstore_record_init
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_enable
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_gettime
  - drivers/net/ethernet/ti/cpts.c:cpts_overflow_check
  - drivers/net/ethernet/ti/cpts.c:cpts_ptp_gettime
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_gettstamp
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
c03e4b94-c03e4c4c: ns_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fab68)
Location: kernel/time/time.c:551
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
  - arch/powerpc/xmon/xmon.c:show_uptime
  - kernel/sys.c:do_sysinfo
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
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
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/proc/uptime.c:uptime_proc_show
  - fs/pstore/platform.c:pstore_record_init
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_gettstamp
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
c0000000001fac00-c0000000001fac78: ns_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a8d4)
Location: kernel/time/time.c:551
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
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
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - fs/timerfd.c:__se_sys_timerfd_gettime
  - fs/timerfd.c:__se_sys_timerfd_gettime
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/proc/uptime.c:uptime_proc_show
  - fs/pstore/platform.c:pstore_record_init
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_gettstamp
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffe00012a90a-ffffffe00012a974: ns_to_timespec64 (STB_GLOBAL)
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
struct timespec64 ns_to_timespec64(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112b665)
Location: kernel/time/time.c:551
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
  - kernel/sys.c:do_sysinfo
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
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
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/proc/uptime.c:uptime_proc_show
  - fs/pstore/platform.c:pstore_record_init
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_gettstamp
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff8112b6e0-ffffffff8112b73b: ns_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111ded5)
Location: kernel/time/time.c:551
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
  - kernel/sys.c:do_sysinfo
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
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
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/proc/uptime.c:uptime_proc_show
  - fs/pstore/platform.c:pstore_record_init
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_gettstamp
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff8111df50-ffffffff8111dfab: ns_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81129385)
Location: kernel/time/time.c:551
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
  - kernel/sys.c:do_sysinfo
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
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
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/proc/uptime.c:uptime_proc_show
  - fs/pstore/platform.c:pstore_record_init
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_gettstamp
  - net/netfilter/nfnetlink_log.c:__build_packet_message
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff81129400-ffffffff8112945b: ns_to_timespec64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 ns_to_timespec64(const s64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811359d5)
Location: kernel/time/time.c:551
Inline: True
Inline callers:
  - kernel/time/time.c:ns_to_kernel_old_timeval
  - kernel/time/time.c:ns_to_kernel_old_timeval
Direct callers:
  - kernel/sys.c:do_sysinfo
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/timekeeping.c:getboottime64
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
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
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_gettime
  - fs/proc/uptime.c:uptime_proc_show
  - fs/pstore/platform.c:pstore_record_init
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/rtc/lib.c:rtc_ktime_to_tm
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/sock.c:sock_gettstamp
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff81135a50-ffffffff81135aab: ns_to_timespec64 (STB_GLOBAL)
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
<b>Return type changed. </b>
<code>struct timespec</code> ➡️ <code>struct timespec64</code>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const s64 nsec</code> ➡️ <code>s64 nsec</code>
</li>
</ul>
</details>
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
