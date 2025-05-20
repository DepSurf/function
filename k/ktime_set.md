# Function: <code>ktime_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff810efe40)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/itimer.c (ffffffff810f0694)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/posix-timers.c (ffffffff810f11a4)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/timekeeping.c (ffffffff810f4a4b)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:do_adjtimex
```
```
In kernel/time/ntp.c (ffffffff810f6e3e)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff810fb2f7)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_set
  - kernel/time/alarmtimer.c:alarm_timer_set
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In kernel/futex.c (ffffffff811030d2)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - kernel/futex.c:SyS_futex
```
```
In kernel/futex_compat.c (ffffffff8110344c)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_SyS_futex
```
```
In fs/select.c (ffffffff812211ec)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - fs/select.c:do_select
  - fs/select.c:do_sys_poll
```
```
In fs/eventpoll.c (ffffffff8125545b)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff812588a7)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff8125beb6)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In ipc/mqueue.c (ffffffff8132bd63)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - ipc/mqueue.c:prepare_timeout
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In drivers/rtc/rtc-lib.c (ffffffff81673302)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In drivers/power/charger-manager.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff817b91a8)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810943d1)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff810f6c7f)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/itimer.c (ffffffff810f76c4)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/posix-timers.c (ffffffff810f8223)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/timekeeping.c (ffffffff810fdd85)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_set_tai_offset
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff810fdfbe)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff81102828)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_set
  - kernel/time/alarmtimer.c:alarm_timer_set
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In kernel/futex.c (ffffffff8110a5b6)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - kernel/futex.c:SyS_futex
```
```
In kernel/futex_compat.c (ffffffff8110a920)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_SyS_futex
```
```
In fs/select.c (ffffffff81249f91)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8127d7db)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff812811cc)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff81284966)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In ipc/mqueue.c (ffffffff81360a01)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - ipc/mqueue.c:prepare_timeout
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816922a1)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_enable_event
```
```
In drivers/rtc/rtc-lib.c (ffffffff816d3af2)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In drivers/power/charger-manager.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/ktime.h:50
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff818268c5)
Location: include/linux/ktime.h:50
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810993c1)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffff810fdd3a)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff81100b75)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:timekeeping_set_tai_offset
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff81100dae)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff81105148)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_set
  - kernel/time/alarmtimer.c:alarm_timer_set
```
```
In kernel/time/posix-timers.c (ffffffff81105b43)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/itimer.c (ffffffff81109d84)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/futex.c (ffffffff81111daa)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex.c:SyS_futex
```
```
In kernel/futex_compat.c (ffffffff8111211e)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_SyS_futex
```
```
In fs/select.c (ffffffff8125cf4f)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8129136b)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff81294cfc)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff81298616)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In ipc/mqueue.c (ffffffff81377221)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:prepare_timeout
```
```
In drivers/rtc/rtc-lib.c (ffffffff817037d2)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff818580d5)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109311c)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffff810ffff0)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff81102d2b)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff81102eec)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff81107178)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff81107836)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81109eab)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff8110bc09)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In kernel/futex.c (ffffffff81113393)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex.c:SyS_futex
```
```
In kernel/futex_compat.c (ffffffff8111370a)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_SyS_futex
```
```
In fs/select.c (ffffffff81269a28)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8129e2e9)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff812a1f84)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff812a6100)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In ipc/mqueue.c (ffffffff8138c59f)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/rtc/rtc-lib.c (ffffffff81718fb2)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8172ace2)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In net/xfrm/xfrm_state.c (ffffffff8187bd9c)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099ffc)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffff8110ade0)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff8110ddad)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff8110e07c)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff811122a8)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff811129ab)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8111507b)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff81116e59)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In kernel/futex.c (ffffffff8111e923)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex.c:SyS_futex
```
```
In kernel/futex_compat.c (ffffffff8111ec9a)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex_compat.c:compat_SyS_futex
```
```
In fs/select.c (ffffffff8128c2cf)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff812c17d9)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff812c52a4)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff812c9f51)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In ipc/mqueue.c (ffffffff813b194f)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fd240)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/rtc/rtc-lib.c (ffffffff8178a192)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8179c482)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In net/xfrm/xfrm_state.c (ffffffff818fccb2)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109dff1)
Location: include/linux/ktime.h:37
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff811167ce)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff8111969b)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff81119a7e)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff8111db61)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff8111e3eb)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112180d)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff811237dc)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In kernel/futex.c (ffffffff8112b860)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In kernel/futex_compat.c (ffffffff8112beee)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex_compat.c:__x32_compat_sys_futex
  - kernel/futex_compat.c:__ia32_compat_sys_futex
```
```
In fs/select.c (ffffffff812b2ba4)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff812ea5e3)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff812ee635)
Location: include/linux/ktime.h:37
Inline: True
```
```
In fs/aio.c (ffffffff812f3195)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In ipc/mqueue.c (ffffffff813e24a4)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81636565)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/rtc/rtc-lib.c (ffffffff817cb2a2)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/rtc/rtc-lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff817dec8a)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/power/supply/charger-manager.c (ffffffff817e4cbf)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff819534d9)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a6301)
Location: include/linux/ktime.h:37
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81121e0e)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff81124b8b)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff81124f8e)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff81129461)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff81129c3b)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112cf2d)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff8112eeac)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In kernel/futex.c (ffffffff8113761e)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_futex
  - kernel/futex.c:__ia32_compat_sys_futex
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812c7cc3)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8130076c)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff81302fc5)
Location: include/linux/ktime.h:37
Inline: True
```
```
In fs/aio.c (ffffffff81308195)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In ipc/mqueue.c (ffffffff813fcef4)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81654a75)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/rtc/lib.c (ffffffff817f2952)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff8180a0ca)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/power/supply/charger-manager.c (ffffffff818103d0)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81987f3b)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab003)
Location: include/linux/ktime.h:37
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff8112c757)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff8112f513)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff8112f9ee)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff81133ec0)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff811346bf)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811378ed)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff8113991c)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In kernel/futex.c (ffffffff8114241a)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812e4817)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff81321a46)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff813241d2)
Location: include/linux/ktime.h:37
Inline: True
```
```
In fs/aio.c (ffffffff81329c55)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In ipc/mqueue.c (ffffffff81429532)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81689492)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/rtc/lib.c (ffffffff81833632)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff8184be51)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/power/supply/charger-manager.c (ffffffff81851f54)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8185d8bd)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In net/xfrm/xfrm_state.c (ffffffff819f1d11)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1603)
Location: include/linux/ktime.h:37
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81138766)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff8113b4d3)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff8113b92e)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff8113fe90)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff811406cf)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81143852)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff8114559e)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In kernel/futex.c (ffffffff8114e28a)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812f61de)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff81333fa6)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff81336f32)
Location: include/linux/ktime.h:37
Inline: True
```
```
In fs/aio.c (ffffffff8133cab5)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffff813427fb)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In ipc/mqueue.c (ffffffff81443262)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816abbb2)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/rtc/lib.c (ffffffff81864f72)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff8187d681)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/power/supply/charger-manager.c (ffffffff81883941)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8188e84b)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In net/xfrm/xfrm_state.c (ffffffff81a28be1)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9121)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffff81147826)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff8114a530)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff8114acae)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff8114f024)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff81150240)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81152f77)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff81154c0e)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/namespace.c (ffffffff81159f32)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/namespace.c:do_timens_ktime_to_host
  - kernel/time/namespace.c:do_timens_ktime_to_host
```
```
In kernel/futex.c (ffffffff8115eb2a)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff8132dea9)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8136e4d5)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff81370e27)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff81375e85)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffff81381d54)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_issue_sqe
```
```
In ipc/mqueue.c (ffffffff81493ef2)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81760798)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/rtc/lib.c (ffffffff8193853b)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff8194bab1)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/power/supply/charger-manager.c (ffffffff81952763)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8195d44b)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1b24c)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b43d1)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffff81143cb6)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff81146a80)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff81147485)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff8114b344)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff8114c4c0)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114f217)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff81150e8e)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/namespace.c (ffffffff81155e82)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/namespace.c:do_timens_ktime_to_host
  - kernel/time/namespace.c:do_timens_ktime_to_host
```
```
In kernel/futex.c (ffffffff8115a9fa)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In kernel/bpf/helpers.c (ffffffff812164cd)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
```
In fs/select.c (ffffffff81339706)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8137b9f6)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8137eba5)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff81383e01)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffff81391c37)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_timeout
  - fs/io_uring.c:io_timeout_remove
```
```
In ipc/mqueue.c (ffffffff814b1852)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177b618)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/rtc/lib.c (ffffffff8193e86b)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff819514c1)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/power/supply/charger-manager.c (ffffffff81c2573f)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81963dfb)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In net/xfrm/xfrm_state.c (ffffffff81b29a1c)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5fe1)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffff81144e3c)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff81147bf0)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff811485b5)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff8114c804)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff8114d98a)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811506a7)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff811522be)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/namespace.c (ffffffff81157122)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/namespace.c:do_timens_ktime_to_host
  - kernel/time/namespace.c:do_timens_ktime_to_host
```
```
In kernel/futex.c (ffffffff8115bda8)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In kernel/bpf/helpers.c (ffffffff8121920d)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
```
In fs/select.c (ffffffff8133fe03)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff81382176)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff81385825)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff8138aa51)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffff81397067)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_issue_sqe
```
```
In ipc/mqueue.c (ffffffff814b76d2)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/rtc/lib.c (ffffffff8192206b)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff81935341)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/power/supply/charger-manager.c (ffffffff81c176c6)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8194821b)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1763e)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c8e71)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffff8116868c)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff8116b71c)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff8116c165)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff8117074e)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff8117181a)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81174975)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff8117688e)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/namespace.c (ffffffff8117bf72)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/namespace.c:do_timens_ktime_to_host
  - kernel/time/namespace.c:do_timens_ktime_to_host
```
```
In kernel/futex.c (ffffffff81180df8)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In kernel/bpf/helpers.c (ffffffff8124f9ed)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
```
In fs/select.c (ffffffff8138d62f)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff813cf3e6)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff813d299f)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff813d7d61)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffff813e5717)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_issue_sqe
```
```
In ipc/mqueue.c (ffffffff81510042)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/rtc/lib.c (ffffffff819c525b)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff819d89a7)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/power/supply/charger-manager.c (ffffffff81d2670b)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819ed1ca)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In net/xfrm/xfrm_state.c (ffffffff81bdb9ee)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e03f2)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffff8119c18c)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff8119f788)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff811a0122)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff811a4d01)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff811a62ea)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811a97c6)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff811abd1d)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/namespace.c (ffffffff811b16ae)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/namespace.c:do_timens_ktime_to_host
  - kernel/time/namespace.c:do_timens_ktime_to_host
```
```
In kernel/futex/syscalls.c (ffffffff811b41aa)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
```
In kernel/bpf/helpers.c (ffffffff81296c9d)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
```
In fs/select.c (ffffffff8140eac0)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff814581c1)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8145b207)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff81462481)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In ipc/sem.c (ffffffff8159ab38)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff815a212b)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In io_uring/io_uring.c (ffffffff816cf7b8)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_queue_linked_timeout
  - io_uring/io_uring.c:io_timeout
  - io_uring/io_uring.c:io_timeout_remove
  - io_uring/io_uring.c:io_timeout_remove
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/rtc/lib.c (ffffffff81b2583b)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff81b3be85)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/power/supply/charger-manager.c (ffffffff81ef2415)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81b53ac6)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In net/xfrm/xfrm_state.c (ffffffff81d72761)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81100a92)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffff811dab27)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff811de487)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff811def32)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff811e4601)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff811e5e4a)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811e9716)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff811ebfbd)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/namespace.c (ffffffff811f23ee)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/namespace.c:do_timens_ktime_to_host
  - kernel/time/namespace.c:do_timens_ktime_to_host
```
```
In kernel/futex/syscalls.c (ffffffff811f520a)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
```
In kernel/bpf/helpers.c (ffffffff812f1c4d)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
```
In fs/select.c (ffffffff8149962d)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff814e7af1)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff814ea817)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff814f2ad1)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In ipc/sem.c (ffffffff81643e88)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff8164bbfb)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In io_uring/io_uring.c (ffffffff81791c17)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
```
```
In io_uring/timeout.c (ffffffff81799dda)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_timeout_remove
```
```
In io_uring/cancel.c (ffffffff8179e953)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/rtc/lib.c (ffffffff81cb8deb)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff81cd1dd5)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/power/supply/charger-manager.c (ffffffff81cd95f9)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81ceca0e)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3e44e)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110cb8f)
Location: include/linux/ktime.h:38
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff811ef037)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff811f2957)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff811f3412)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff811f8c61)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff811fa2ca)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fde06)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff812006ea)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/namespace.c (ffffffff81206b73)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/time/namespace.c:do_timens_ktime_to_host
  - kernel/time/namespace.c:do_timens_ktime_to_host
```
```
In kernel/futex/syscalls.c (ffffffff812099c1)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
```
In kernel/bpf/helpers.c (ffffffff8131e82d)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
```
In fs/select.c (ffffffff814ce740)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8151dda4)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff815215ba)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff81529881)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In ipc/sem.c (ffffffff8167c3c8)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff8168432b)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In io_uring/io_uring.c (ffffffff817d0d8a)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
```
```
In io_uring/timeout.c (ffffffff817daeaa)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_complete
```
```
In io_uring/cancel.c (ffffffff817dfb43)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/input/misc/uinput.c (ffffffff81d1f2e3)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/rtc/lib.c (ffffffff81d2051b)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff81d39819)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/power/supply/charger-manager.c (ffffffff81d41869)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:38
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81d5572e)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9dc07)
Location: include/linux/ktime.h:38
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111656f)
Location: include/linux/ktime.h:36
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff812051b7)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__x64_sys_nanosleep_time32
  - kernel/time/hrtimer.c:__ia32_sys_nanosleep
  - kernel/time/hrtimer.c:__x64_sys_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff81208a97)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff81209552)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff8120ee01)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff812104ba)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_nsleep_timens
  - kernel/time/posix-timers.c:common_nsleep
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/posix-cpu-timers.c (ffffffff812141d6)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff81216b8a)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/namespace.c (ffffffff8121dd83)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - kernel/time/namespace.c:do_timens_ktime_to_host
  - kernel/time/namespace.c:do_timens_ktime_to_host
```
```
In kernel/futex/syscalls.c (ffffffff81220941)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:futex2_setup_timeout
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
```
In kernel/bpf/helpers.c (ffffffff81340c5d)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_ktime_get_coarse_ns
```
```
In fs/select.c (ffffffff81501080)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff81552384)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff81555bfa)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/aio.c (ffffffff8155e751)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In ipc/sem.c (ffffffff816b8798)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In ipc/mqueue.c (ffffffff816c0755)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In io_uring/io_uring.c (ffffffff818138e1)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
```
```
In io_uring/timeout.c (ffffffff8181f19a)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_complete
```
```
In io_uring/cancel.c (ffffffff81824005)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
```
```
In drivers/pmdomain/governor.c (0)
Location: include/linux/ktime.h:36
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:36
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/ktime.h:36
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/ktime.h:36
Inline: True
```
```
In drivers/input/misc/uinput.c (ffffffff81dd5013)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/rtc/lib.c (ffffffff81dd624b)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:36
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff81defbd9)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/power/supply/charger-manager.c (ffffffff81df8219)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:36
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0c635)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In net/xfrm/xfrm_state.c (ffffffff8206af67)
Location: include/linux/ktime.h:36
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010d234)
Location: include/linux/ktime.h:37
Inline: True
```
```
In kernel/time/hrtimer.c (ffff8000101a2420)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffff8000101a3294)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffff8000101a5de0)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffff8000101a9ae8)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffff8000101aaa70)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101add44)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffff8000101afee8)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In kernel/futex.c (ffff8000101bc484)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex.c:__arm64_sys_futex_time32
  - kernel/futex.c:__arm64_sys_futex
```
```
In fs/select.c (ffff8000103a32c0)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffff8000103f2744)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffff8000103f4df0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In fs/aio.c (ffff8000103fc4ac)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffff800010404400)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In ipc/mqueue.c (ffff80001052af0c)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/tty/serial/8250/8250_port.c (ffff8000108866c4)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/rtc/lib.c (ffff800010aa67c8)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffff800010ac6f2c)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/power/reset/ltc2952-poweroff.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffff800010acf574)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffff800010ce90b4)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c03654f4)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (c03ec128)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (c03ed2c0)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (c03f0d30)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (c03f5504)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (c03f608c)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (c03f8cf4)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (c03fab98)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In kernel/futex.c (c0404b1c)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex.c:__se_sys_futex_time32
  - kernel/futex.c:__se_sys_futex
```
```
In fs/select.c (c0585c48)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (c05c6610)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/timerfd.c (c05c9ce8)
Location: include/linux/ktime.h:37
Inline: True
```
```
In fs/aio.c (c05cfa74)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (c05d4320)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In ipc/mqueue.c (c06e3220)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/tty/serial/8250/8250_port.c (c0984bd4)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/rtc/lib.c (c0b852a8)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/ptp/ptp_clock.c (c0ba6998)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/power/reset/ltc2952-poweroff.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/power/supply/charger-manager.c (c0bafe70)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In net/xfrm/xfrm_state.c (c0def540)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c00000000015434c)
Location: include/linux/ktime.h:37
Inline: True
```
```
In kernel/time/hrtimer.c (c0000000002038f8)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (c000000000207580)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (c000000000207b78)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (c00000000020d838)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (c00000000020e62c)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (c000000000212010)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (c00000000021480c)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In kernel/futex.c (c000000000222694)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex.c:__se_sys_futex_time32
  - kernel/futex.c:__se_sys_futex
```
```
In fs/select.c (c00000000049d274)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (c0000000004f832c)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (c0000000004fce78)
Location: include/linux/ktime.h:37
Inline: True
```
```
In fs/aio.c (c0000000005051f0)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (c00000000050d064)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In ipc/mqueue.c (c0000000006766b8)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/tty/serial/8250/8250_port.c (c00000000092d3a4)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/rtc/lib.c (c000000000b873a8)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/ptp/ptp_clock.c (c000000000ba8634)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/power/reset/ltc2952-poweroff.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/power/supply/charger-manager.c (c000000000bb2e94)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (c000000000bc73b8)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In net/xfrm/xfrm_state.c (c000000000e0cce4)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d13b2)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffe00012f516)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffe000131b28)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffe000131f9a)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffe000135648)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffe000135dea)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffe000137a3c)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffe00013916a)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In kernel/futex.c (ffffffe0001402fa)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex.c:__se_sys_futex
```
```
In fs/select.c (ffffffe00026b1b6)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffe0002a334c)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/timerfd.c (ffffffe0002a5f2c)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:__se_sys_timerfd_settime
```
```
In fs/aio.c (ffffffe0002aa124)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffe0002af00e)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In ipc/mqueue.c (ffffffe00038dffc)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_timedreceive
  - ipc/mqueue.c:__se_sys_mq_timedsend
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000551912)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/rtc/lib.c (ffffffe0006b2b16)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffe0006c598e)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/power/reset/ltc2952-poweroff.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffe0006cbfd6)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffe0006d7fc8)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In net/xfrm/xfrm_state.c (ffffffe000837294)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab973)
Location: include/linux/ktime.h:37
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81130f16)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff81133c83)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff811340de)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff81138640)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff81138e7f)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113c002)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff8113dd4e)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In kernel/futex.c (ffffffff811468aa)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812ee7be)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8132c586)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8132f512)
Location: include/linux/ktime.h:37
Inline: True
```
```
In fs/aio.c (ffffffff81335095)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffff8133addb)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In ipc/mqueue.c (ffffffff8143b842)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81671622)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/rtc/lib.c (ffffffff81817c22)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff81825bf1)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff818346cb)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In net/xfrm/xfrm_state.c (ffffffff819c8271)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109a313)
Location: include/linux/ktime.h:37
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff81123986)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff811266e3)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff81126b3e)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff8112b090)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff8112b8cf)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112eac2)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff81130878)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In kernel/futex.c (ffffffff81139baa)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812df3ee)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8131be71)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8132013c)
Location: include/linux/ktime.h:37
Inline: True
```
```
In fs/aio.c (ffffffff81325a25)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffff8132bac5)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In ipc/mqueue.c (ffffffff8142c2b2)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81650722)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/rtc/lib.c (ffffffff817df312)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff817ed281)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817fbd5b)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In net/xfrm/xfrm_state.c (ffffffff81985061)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aaed3)
Location: include/linux/ktime.h:37
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff8112ec36)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff811319a3)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff81131dfe)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff81136360)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff81136b9f)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81139d22)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff8113ba6e)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In kernel/futex.c (ffffffff8114475a)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812ec5ce)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8132a056)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8132cfe2)
Location: include/linux/ktime.h:37
Inline: True
```
```
In fs/aio.c (ffffffff81332b65)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffff813388ab)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In ipc/mqueue.c (ffffffff814379e2)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8169f9f2)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/rtc/lib.c (ffffffff81859102)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff81872b31)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/power/supply/charger-manager.c (ffffffff81878df1)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81883cfb)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In net/xfrm/xfrm_state.c (ffffffff81a32cf1)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2fa9)
Location: include/linux/ktime.h:37
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff8113b636)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/time/timekeeping.c (ffffffff8113e3c3)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
  - kernel/time/timekeeping.c:tk_set_wall_to_mono
```
```
In kernel/time/ntp.c (ffffffff8113e81e)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_get_next_leap
```
```
In kernel/time/alarmtimer.c (ffffffff81142de0)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
```
```
In kernel/time/posix-timers.c (ffffffff8114362f)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_get
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81146812)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In kernel/time/itimer.c (ffffffff81148535)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
```
In kernel/futex.c (ffffffff811512da)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
```
In fs/select.c (ffffffff812fd5ce)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
  - fs/select.c:do_select
```
```
In fs/eventpoll.c (ffffffff8133ab31)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
```
```
In fs/timerfd.c (ffffffff8133fae7)
Location: include/linux/ktime.h:37
Inline: True
```
```
In fs/aio.c (ffffffff81345cf5)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
```
```
In fs/io_uring.c (ffffffff8134b124)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In ipc/mqueue.c (ffffffff8144df62)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816b9eb2)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/domain_governor.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/rtc/lib.c (ffffffff818741e2)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
```
```
In drivers/rtc/interface.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff8188e4e1)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_adjtime
```
```
In drivers/power/supply/charger-manager.c (ffffffff81894791)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/ktime.h:37
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8189f7bb)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3e641)
Location: include/linux/ktime.h:37
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
</ul>

## Differences
