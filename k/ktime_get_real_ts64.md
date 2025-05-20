# Function: <code>ktime_get_real_ts64</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81118650)
Location: kernel/time/timekeeping.c:713
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_gettimeofday
  - kernel/time/posix-timers.c:posix_clock_realtime_get
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff81118650-ffffffff8111872c: ktime_get_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81123c70)
Location: kernel/time/timekeeping.c:720
Inline: False
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_get
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff81123c70-ffffffff81123d4c: ktime_get_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:726
Inline: False
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_get
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff8112f7d7-ffffffff8112f7ea: ktime_get_real_ts64.cold (STB_LOCAL)
ffffffff8112eb60-ffffffff8112ec35: ktime_get_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113ab20)
Location: kernel/time/timekeeping.c:726
Inline: False
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_get
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff8113ab20-ffffffff8113abfc: ktime_get_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81149820)
Location: kernel/time/timekeeping.c:726
Inline: False
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/ntp.c:sync_cmos_clock
  - kernel/time/posix-timers.c:posix_get_realtime_timespec
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_take_timestamp_post
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff81149820-ffffffff811498fe: ktime_get_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811460f0)
Location: kernel/time/timekeeping.c:796
Inline: False
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/posix-timers.c:posix_get_realtime_timespec
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_take_timestamp_post
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff811460f0-ffffffff811461c9: ktime_get_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81146bd0)
Location: kernel/time/timekeeping.c:796
Inline: False
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/posix-timers.c:posix_get_realtime_timespec
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_take_timestamp_post
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff81146bd0-ffffffff81146ca9: ktime_get_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:796
Inline: False
Direct callers:
  - kernel/time/time.c:__x64_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/posix-timers.c:posix_get_realtime_timespec
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff81cb0e7b-ffffffff81cb0e9f: ktime_get_real_ts64.cold (STB_LOCAL)
ffffffff8116a060-ffffffff8116a144: ktime_get_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:815
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/posix-timers.c:posix_get_realtime_timespec
  - kernel/trace/blktrace.c:trace_note_time
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_suspend
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff81e623e8-ffffffff81e6240c: ktime_get_real_ts64.cold (STB_LOCAL)
ffffffff8119dca0-ffffffff8119dd84: ktime_get_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:815
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/posix-timers.c:posix_get_realtime_timespec
  - kernel/trace/blktrace.c:trace_note_time
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_suspend
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff8205b259-ffffffff8205b27d: ktime_get_real_ts64.cold (STB_LOCAL)
ffffffff811dc940-ffffffff811dca24: ktime_get_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:815
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/posix-timers.c:posix_get_realtime_timespec
  - kernel/trace/blktrace.c:trace_note_time
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_take_timestamp_post
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_suspend
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff820d9aed-ffffffff820d9b11: ktime_get_real_ts64.cold (STB_LOCAL)
ffffffff811f0d50-ffffffff811f0e34: ktime_get_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:815
Inline: False
Direct callers:
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/posix-timers.c:posix_get_realtime_timespec
  - kernel/trace/blktrace.c:trace_note_time
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_take_timestamp_post
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_suspend
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff821b53ec-ffffffff821b5410: ktime_get_real_ts64.cold (STB_LOCAL)
ffffffff81206e90-ffffffff81206f74: ktime_get_real_ts64 (STB_GLOBAL)
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
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a2e30)
Location: kernel/time/timekeeping.c:726
Inline: False
Direct callers:
  - kernel/time/time.c:__arm64_compat_sys_gettimeofday
  - kernel/time/time.c:__arm64_sys_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/posix-timers.c:posix_clock_realtime_get
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffff8000101a2e30-ffff8000101a2f2c: ktime_get_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03ecc24)
Location: kernel/time/timekeeping.c:726
Inline: False
Direct callers:
  - kernel/time/time.c:__se_sys_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/posix-timers.c:posix_clock_realtime_get
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/blktrace.c:__blk_trace_startstop
  - fs/kernfs/inode.c:__kernfs_iattrs
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - sound/core/timer.c:snd_timer_user_tinterrupt
  - sound/core/timer.c:snd_timer_notify1
  - sound/core/pcm_native.c:snd_pcm_trigger_tstamp
  - sound/core/pcm_native.c:snd_pcm_status
  - sound/core/pcm_lib.c:update_audio_tstamp
  - sound/core/pcm_lib.c:__snd_pcm_xrun
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
c03ecc24-c03ecdd0: ktime_get_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c0000000002044d0)
Location: kernel/time/timekeeping.c:726
Inline: False
Direct callers:
  - kernel/time/time.c:__se_compat_sys_gettimeofday
  - kernel/time/time.c:__se_sys_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_get
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/blktrace.c:__blk_trace_startstop
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
c0000000002044d0-c0000000002045fc: ktime_get_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe00012fb04)
Location: kernel/time/timekeeping.c:726
Inline: False
Direct callers:
  - kernel/time/time.c:__se_sys_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/posix-timers.c:posix_clock_realtime_get
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/blktrace.c:__blk_trace_startstop
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffe00012fb04-ffffffe00012fbc0: ktime_get_real_ts64 (STB_GLOBAL)
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
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811332d0)
Location: kernel/time/timekeeping.c:726
Inline: False
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_get
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff811332d0-ffffffff811333ac: ktime_get_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81125d30)
Location: kernel/time/timekeeping.c:726
Inline: False
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_get
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff81125d30-ffffffff81125e0c: ktime_get_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81130ff0)
Location: kernel/time/timekeeping.c:726
Inline: False
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_get
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff81130ff0-ffffffff811310cc: ktime_get_real_ts64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ktime_get_real_ts64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113da10)
Location: kernel/time/timekeeping.c:726
Inline: False
Direct callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/posix-timers.c:posix_clock_realtime_get
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/kernfs/dir.c:kernfs_add_one
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ipv4/af_inet.c:inet_current_timestamp
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:prb_retire_current_block
  - net/packet/af_packet.c:prb_open_block
```
**Symbols:**

```
ffffffff8113da10-ffffffff8113daec: ktime_get_real_ts64 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
