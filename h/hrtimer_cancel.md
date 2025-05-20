# Function: <code>hrtimer_cancel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ef070)
Location: kernel/time/hrtimer.c:1069
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/cqm.c:__mbm_stop_timer
  - arch/x86/events/intel/rapl.c:rapl_pmu_event_stop
  - arch/x86/events/intel/rapl.c:rapl_cpu_notifier
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:hotplug_hrtick
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
```
**Symbols:**

```
ffffffff810ef070-ffffffff810ef090: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8189e32c)
Location: kernel/time/hrtimer.c:1059
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/cqm.c:__mbm_stop_timer
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/cfq-iosched.c:cfq_exit_queue
  - block/cfq-iosched.c:cfq_exit_queue
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
```
**Symbols:**

```
ffffffff810f6120-ffffffff810f6140: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff818d31cd)
Location: kernel/time/hrtimer.c:1059
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/cqm.c:__mbm_stop_timer
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/blk-mq.c:blk_mq_poll_hybrid_sleep
  - block/cfq-iosched.c:cfq_exit_queue
  - block/cfq-iosched.c:cfq_exit_queue
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
```
**Symbols:**

```
ffffffff810fd1c0-ffffffff810fd1e0: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8190a350)
Location: kernel/time/hrtimer.c:1029
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/cfq-iosched.c:cfq_exit_queue
  - block/cfq-iosched.c:cfq_exit_queue
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
```
**Symbols:**

```
ffffffff810ff540-ffffffff810ff560: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8199469c)
Location: kernel/time/hrtimer.c:1029
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/cfq-iosched.c:cfq_exit_queue
  - block/cfq-iosched.c:cfq_exit_queue
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
```
**Symbols:**

```
ffffffff8110a340-ffffffff8110a360: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81116220)
Location: kernel/time/hrtimer.c:1167
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/cfq-iosched.c:cfq_exit_queue
  - block/cfq-iosched.c:cfq_exit_queue
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
```
**Symbols:**

```
ffffffff81116220-ffffffff81116240: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81121200)
Location: kernel/time/hrtimer.c:1158
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - kernel/events/core.c:cpu_clock_event_stop
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff81121200-ffffffff81121220: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112ba20)
Location: kernel/time/hrtimer.c:1158
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff8112ba20-ffffffff8112ba40: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81137ac0)
Location: kernel/time/hrtimer.c:1273
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/rt.c:free_rt_sched_group
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_pd_free
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff81137ac0-ffffffff81137ae0: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81146f80)
Location: kernel/time/hrtimer.c:1273
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_del
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_pd_free
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff81146f80-ffffffff81146fbb: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81143420)
Location: kernel/time/hrtimer.c:1290
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_del
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-iocost.c:ioc_pd_free
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff81143420-ffffffff8114345b: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81c37d17)
Location: kernel/time/hrtimer.c:1290
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_del
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-iocost.c:ioc_pd_free
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff81144510-ffffffff8114454b: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81d565d7)
Location: kernel/time/hrtimer.c:1438
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:lockup_detector_offline_cpu
  - kernel/watchdog.c:softlockup_stop_fn
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_del
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-iocost.c:ioc_pd_free
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff81167770-ffffffff811677ab: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119abf0)
Location: kernel/time/hrtimer.c:1438
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/waitwake.c:futex_wait
  - kernel/watchdog.c:lockup_detector_offline_cpu
  - kernel/watchdog.c:softlockup_stop_fn
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_del
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-iocost.c:ioc_pd_free
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff8119abf0-ffffffff8119ac19: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811d9780)
Location: kernel/time/hrtimer.c:1438
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/waitwake.c:futex_wait
  - kernel/watchdog.c:lockup_detector_offline_cpu
  - kernel/watchdog.c:softlockup_stop_fn
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_del
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/blk-mq.c:blk_mq_poll_hybrid
  - block/blk-iocost.c:ioc_pd_free
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff811d9780-ffffffff811d97a9: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff821582ec)
Location: kernel/time/hrtimer.c:1441
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:destroy_cfs_bandwidth
  - kernel/sched/fair.c:destroy_cfs_bandwidth
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/waitwake.c:futex_wait
  - kernel/watchdog.c:lockup_detector_offline_cpu
  - kernel/watchdog.c:softlockup_stop_fn
  - kernel/trace/trace_osnoise.c:timerlat_fd_release
  - kernel/trace/trace_osnoise.c:timerlat_main
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_del
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/blk-iocost.c:ioc_pd_free
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff811ee3a0-ffffffff811ee3e1: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8223b15c)
Location: kernel/time/hrtimer.c:1442
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:destroy_cfs_bandwidth
  - kernel/sched/fair.c:destroy_cfs_bandwidth
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart_sched_tick
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/futex/syscalls.c:__ia32_sys_futex_wait
  - kernel/futex/syscalls.c:__x64_sys_futex_wait
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/waitwake.c:futex_wait
  - kernel/watchdog.c:lockup_detector_offline_cpu
  - kernel/watchdog.c:softlockup_stop_fn
  - kernel/trace/trace_osnoise.c:timerlat_fd_release
  - kernel/trace/trace_osnoise.c:timerlat_main
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/events/core.c:task_clock_event_del
  - kernel/events/core.c:cpu_clock_event_del
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/blk-iocost.c:ioc_pd_free
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff81204520-ffffffff81204561: hrtimer_cancel (STB_GLOBAL)
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
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a1c10)
Location: kernel/time/hrtimer.c:1273
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_terminate
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_reset
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_put
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_load
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_load
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/rt.c:free_rt_sched_group
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/sched_clock.c:sched_clock_suspend
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - kernel/events/core.c:task_clock_event_stop
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_pd_free
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/media/cec/cec-pin.c:cec_pin_adap_enable
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_del
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffff8000101a1c10-ffff8000101a1c48: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03eac80)
Location: kernel/time/hrtimer.c:1273
Inline: False
Direct callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_del
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_del
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/rt.c:free_rt_sched_group
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/sched_clock.c:sched_clock_suspend
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:do_io_getevents
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_pd_free
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_del
  - sound/soc/fsl/imx-pcm-fiq.c:snd_imx_close
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
c03eac80-c03eacd8: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000202570)
Location: kernel/time/hrtimer.c:1273
Inline: False
Direct callers:
  - arch/powerpc/kernel/watchdog.c:stop_watchdog
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/rt.c:free_rt_sched_group
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - kernel/watchdog.c:watchdog_disable
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_pd_free
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
c000000000202570-c0000000002025cc: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe0008c8bcc)
Location: kernel/time/hrtimer.c:1273
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/rt.c:free_rt_sched_group
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/sched_clock.c:sched_clock_suspend
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - kernel/events/core.c:cpu_clock_event_stop
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_pd_free
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_remove
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffe00012e746-ffffffe00012e77a: hrtimer_cancel (STB_GLOBAL)
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
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81130270)
Location: kernel/time/hrtimer.c:1273
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_pd_free
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff81130270-ffffffff81130290: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81122ce0)
Location: kernel/time/hrtimer.c:1273
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/rt.c:free_rt_sched_group
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart_sched_tick
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_pd_free
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff81122ce0-ffffffff81122d00: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112df90)
Location: kernel/time/hrtimer.c:1273
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/rt.c:free_rt_sched_group
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_pd_free
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff8112df90-ffffffff8112dfb0: hrtimer_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113a910)
Location: kernel/time/hrtimer.c:1273
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_stop
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:__schedule
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/tick-sched.c:tick_cancel_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_disable
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:read_events
  - block/blk-iocost.c:ioc_pd_free
  - block/blk-iocost.c:ioc_pd_free
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_destroy
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/host/ehci-hcd.c:ehci_stop
  - drivers/usb/host/ehci-hcd.c:ehci_shutdown
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/media/cec/cec-pin.c:cec_pin_adap_enable
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/dev.c:napi_disable
  - net/sched/sch_api.c:qdisc_watchdog_cancel
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
**Symbols:**

```
ffffffff8113a910-ffffffff8113a930: hrtimer_cancel (STB_GLOBAL)
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
