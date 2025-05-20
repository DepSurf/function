# Function: <code>hrtimer_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ef3a0)
Location: kernel/time/hrtimer.c:1155
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:hrtimer_nanosleep
Direct callers:
  - arch/x86/events/intel/cqm.c:intel_mbm_init
  - arch/x86/events/intel/rapl.c:rapl_cpu_prepare
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/fork.c:copy_process
  - kernel/softirq.c:tasklet_hrtimer_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/rt.c:init_rt_bandwidth
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_lock_pi
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_create
  - fs/aio.c:read_events
  - fs/aio.c:read_events
  - fs/aio.c:read_events
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/rtc/class.c:rtc_device_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
```
**Symbols:**

```
ffffffff810ef3a0-ffffffff810ef41b: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810f6c63)
Location: kernel/time/hrtimer.c:1145
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
Direct callers:
  - arch/x86/events/intel/cqm.c:intel_mbm_init
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/softirq.c:tasklet_hrtimer_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/rt.c:init_rt_bandwidth
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_create
  - fs/aio.c:read_events
  - fs/aio.c:read_events
  - fs/aio.c:read_events
  - block/cfq-iosched.c:cfq_init_queue
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/rtc/class.c:rtc_device_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
```
**Symbols:**

```
ffffffff810f6430-ffffffff810f64a4: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fdd1a)
Location: kernel/time/hrtimer.c:1145
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
Direct callers:
  - arch/x86/events/intel/cqm.c:intel_mbm_init
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/softirq.c:tasklet_hrtimer_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/rt.c:init_rt_bandwidth
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/sched/idle.c:play_idle
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_create
  - fs/aio.c:read_events
  - fs/aio.c:read_events
  - fs/aio.c:read_events
  - block/blk-mq.c:blk_mq_poll_hybrid_sleep
  - block/cfq-iosched.c:cfq_init_queue
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/rtc/class.c:rtc_device_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
```
**Symbols:**

```
ffffffff810fd450-ffffffff810fd4c4: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fffd6)
Location: kernel/time/hrtimer.c:1121
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/softirq.c:tasklet_hrtimer_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/rt.c:init_rt_bandwidth
  - kernel/sched/deadline.c:init_dl_inactive_task_timer
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/sched/idle.c:play_idle
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_create
  - fs/aio.c:read_events
  - fs/aio.c:read_events
  - block/cfq-iosched.c:cfq_init_queue
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff810ff780-ffffffff810ff7f4: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8110adc6)
Location: kernel/time/hrtimer.c:1126
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/softirq.c:tasklet_hrtimer_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/rt.c:init_rt_bandwidth
  - kernel/sched/deadline.c:init_dl_inactive_task_timer
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/sched/idle.c:play_idle
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_create
  - fs/aio.c:read_events
  - block/cfq-iosched.c:cfq_init_queue
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff8110a590-ffffffff8110a607: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff819f0e25)
Location: kernel/time/hrtimer.c:1305
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/softirq.c:tasklet_hrtimer_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/rt.c:init_rt_bandwidth
  - kernel/sched/deadline.c:init_dl_inactive_task_timer
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/aio.c:read_events
  - block/cfq-iosched.c:cfq_init_queue
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff81115d70-ffffffff81115de7: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81a2c1a5)
Location: kernel/time/hrtimer.c:1296
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/softirq.c:tasklet_hrtimer_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/rt.c:init_rt_bandwidth
  - kernel/sched/deadline.c:init_dl_inactive_task_timer
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/aio.c:read_events
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
```
**Symbols:**

```
ffffffff81121540-ffffffff811215b7: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81a9c345)
Location: kernel/time/hrtimer.c:1296
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:sched_init
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/rt.c:init_rt_bandwidth
  - kernel/sched/deadline.c:init_dl_inactive_task_timer
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/aio.c:read_events
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff8112be00-ffffffff8112be77: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81137e00)
Location: kernel/time/hrtimer.c:1424
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:sched_init
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/deadline.c:init_dl_inactive_task_timer
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/io_uring.c:__io_submit_sqe
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff81137e00-ffffffff81137e77: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811463f0)
Location: kernel/time/hrtimer.c:1424
Inline: False
Direct callers:
  - kernel/fork.c:copy_signal
  - kernel/sched/core.c:sched_init
  - kernel/sched/idle.c:play_idle_precise
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/rt.c:init_rt_bandwidth
  - kernel/sched/deadline.c:init_dl_inactive_task_timer
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_switch_to_nohz
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/io_uring.c:io_timeout_prep
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff811463f0-ffffffff81146467: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811429c0)
Location: kernel/time/hrtimer.c:1441
Inline: False
Direct callers:
  - kernel/fork.c:copy_signal
  - kernel/sched/core.c:sched_init
  - kernel/sched/idle.c:play_idle_precise
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/rt.c:init_rt_bandwidth
  - kernel/sched/deadline.c:init_dl_inactive_task_timer
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/time/ntp.c:ntp_init
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_switch_to_nohz
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/io_uring.c:io_timeout_prep
  - fs/io_uring.c:io_timeout_remove
  - block/blk-iocost.c:ioc_pd_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff811429c0-ffffffff81142a24: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81143b40)
Location: kernel/time/hrtimer.c:1441
Inline: False
Direct callers:
  - kernel/fork.c:copy_signal
  - kernel/sched/core.c:sched_init
  - kernel/sched/idle.c:play_idle_precise
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/rt.c:init_rt_bandwidth
  - kernel/sched/deadline.c:init_dl_inactive_task_timer
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/time/ntp.c:ntp_init
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/io_uring.c:io_timeout_prep
  - block/blk-iocost.c:ioc_pd_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff81143b40-ffffffff81143ba4: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811670c0)
Location: kernel/time/hrtimer.c:1589
Inline: False
Direct callers:
  - kernel/fork.c:copy_signal
  - kernel/sched/core.c:sched_init
  - kernel/sched/idle.c:play_idle_precise
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/rt.c:init_rt_bandwidth
  - kernel/sched/deadline.c:init_dl_inactive_task_timer
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/time/ntp.c:ntp_init
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/watchdog.c:watchdog_enable
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/io_uring.c:io_timeout_prep
  - block/blk-iocost.c:ioc_pd_init
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff811670c0-ffffffff81167121: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119b080)
Location: kernel/time/hrtimer.c:1589
Inline: False
Direct callers:
  - kernel/fork.c:copy_signal
  - kernel/sched/core.c:sched_init
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/build_policy.c:init_dl_inactive_task_timer
  - kernel/sched/build_policy.c:init_dl_task_timer
  - kernel/sched/build_policy.c:init_rt_bandwidth
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/time/ntp.c:ntp_init
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/watchdog.c:watchdog_enable
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - block/blk-iocost.c:ioc_pd_init
  - io_uring/io_uring.c:__io_timeout_prep
  - io_uring/io_uring.c:io_timeout_remove
  - io_uring/io_uring.c:io_timeout_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - net/core/dev.c:netif_napi_add_weight
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff8119b080-ffffffff8119b102: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811d98c0)
Location: kernel/time/hrtimer.c:1589
Inline: False
Direct callers:
  - kernel/fork.c:copy_signal
  - kernel/sched/core.c:sched_init
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/build_policy.c:init_dl_inactive_task_timer
  - kernel/sched/build_policy.c:init_dl_task_timer
  - kernel/sched/build_policy.c:init_rt_bandwidth
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/time/ntp.c:ntp_init
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/watchdog.c:watchdog_enable
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - block/blk-iocost.c:ioc_pd_init
  - io_uring/timeout.c:__io_timeout_prep
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - net/core/dev.c:netif_napi_add_weight
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff811d98c0-ffffffff811d9942: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811ee070)
Location: kernel/time/hrtimer.c:1592
Inline: False
Direct callers:
  - kernel/fork.c:copy_signal
  - kernel/sched/core.c:sched_init
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/build_policy.c:init_dl_inactive_task_timer
  - kernel/sched/build_policy.c:init_dl_task_timer
  - kernel/sched/build_policy.c:init_rt_bandwidth
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/time/ntp.c:ntp_init
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/watchdog.c:watchdog_enable
  - kernel/trace/trace_osnoise.c:timerlat_fd_read
  - kernel/trace/trace_osnoise.c:timerlat_main
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - block/blk-iocost.c:ioc_pd_init
  - io_uring/timeout.c:__io_timeout_prep
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - drivers/powercap/idle_inject.c:idle_inject_register_full
  - net/core/dev.c:netif_napi_add_weight
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff811ee070-ffffffff811ee0f2: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81203710)
Location: kernel/time/hrtimer.c:1593
Inline: False
Direct callers:
  - kernel/fork.c:copy_signal
  - kernel/sched/core.c:sched_init
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/build_policy.c:init_dl_entity
  - kernel/sched/build_policy.c:init_dl_entity
  - kernel/sched/build_policy.c:init_rt_bandwidth
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/time/ntp.c:ntp_init
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/watchdog.c:watchdog_enable
  - kernel/trace/trace_osnoise.c:timerlat_fd_open
  - kernel/trace/trace_osnoise.c:timerlat_main
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:task_clock_event_init
  - kernel/events/core.c:cpu_clock_event_init
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - block/blk-iocost.c:ioc_pd_init
  - io_uring/timeout.c:__io_timeout_prep
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init
  - drivers/usb/host/ehci-hcd.c:ehci_init
  - drivers/rtc/class.c:rtc_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - drivers/powercap/idle_inject.c:idle_inject_register_full
  - net/core/dev.c:netif_napi_add_weight
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff81203710-ffffffff81203792: hrtimer_init (STB_GLOBAL)
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
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a0e28)
Location: kernel/time/hrtimer.c:1424
Inline: False
Direct callers:
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_init
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_init
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_init
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:sched_init
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/deadline.c:init_dl_inactive_task_timer
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/sched_clock.c:generic_sched_clock_init
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - fs/timerfd.c:__arm64_sys_timerfd_create
  - fs/io_uring.c:__io_submit_sqe
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/media/cec/cec-pin.c:cec_pin_allocate_adapter
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffff8000101a0e28-ffff8000101a0efc: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03eb1dc)
Location: kernel/time/hrtimer.c:1424
Inline: False
Direct callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_init
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:sched_init
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/deadline.c:init_dl_inactive_task_timer
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/sched_clock.c:generic_sched_clock_init
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - fs/timerfd.c:__se_sys_timerfd_create
  - fs/io_uring.c:__io_submit_sqe
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - sound/soc/fsl/imx-pcm-fiq.c:snd_imx_open
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
c03eb1dc-c03eb294: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000202ac0)
Location: kernel/time/hrtimer.c:1424
Inline: False
Direct callers:
  - arch/powerpc/kernel/watchdog.c:start_watchdog
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:sched_init
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/deadline.c:init_dl_inactive_task_timer
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - fs/timerfd.c:__se_sys_timerfd_create
  - fs/io_uring.c:__io_submit_sqe
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
c000000000202ac0-c000000000202bc8: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012eb74)
Location: kernel/time/hrtimer.c:1424
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:sched_init
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/deadline.c:init_dl_inactive_task_timer
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/sched_clock.c:generic_sched_clock_init
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:__se_sys_timerfd_create
  - fs/io_uring.c:__io_submit_sqe
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffe00012eb74-ffffffe00012ec0c: hrtimer_init (STB_GLOBAL)
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
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811305b0)
Location: kernel/time/hrtimer.c:1424
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:sched_init
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/rt.c:init_rt_bandwidth
  - kernel/sched/deadline.c:init_dl_inactive_task_timer
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/io_uring.c:__io_submit_sqe
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff811305b0-ffffffff81130627: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81123020)
Location: kernel/time/hrtimer.c:1424
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:sched_init
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/deadline.c:init_dl_inactive_task_timer
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/io_uring.c:__io_submit_sqe
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff81123020-ffffffff81123097: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112e2d0)
Location: kernel/time/hrtimer.c:1424
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:sched_init
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/rt.c:alloc_rt_sched_group
  - kernel/sched/deadline.c:init_dl_inactive_task_timer
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/io_uring.c:__io_submit_sqe
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff8112e2d0-ffffffff8112e347: hrtimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hrtimer_init(struct hrtimer *timer, clockid_t clock_id, enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113aca0)
Location: kernel/time/hrtimer.c:1424
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_alloc_box
  - kernel/fork.c:copy_process
  - kernel/sched/core.c:sched_init
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/fair.c:init_cfs_bandwidth
  - kernel/sched/rt.c:init_rt_bandwidth
  - kernel/sched/deadline.c:init_dl_inactive_task_timer
  - kernel/sched/deadline.c:init_dl_task_timer
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_timer_create
  - kernel/time/tick-broadcast-hrtimer.c:tick_setup_hrtimer_broadcast
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_pmu_register
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/io_uring.c:__io_submit_sqe
  - block/blk-iocost.c:ioc_pd_init
  - block/blk-iocost.c:ioc_pd_init
  - drivers/base/power/runtime.c:pm_runtime_init
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
  - drivers/usb/host/ehci-hcd.c:ehci_setup
  - drivers/rtc/class.c:devm_rtc_allocate_device
  - drivers/media/cec/cec-pin.c:cec_pin_allocate_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/mailbox/mailbox.c:mbox_controller_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - net/core/dev.c:netif_napi_add
  - net/sched/sch_api.c:qdisc_watchdog_init
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/ipv4/tcp_timer.c:tcp_init_xmit_timers
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
**Symbols:**

```
ffffffff8113aca0-ffffffff8113ad2c: hrtimer_init (STB_GLOBAL)
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
