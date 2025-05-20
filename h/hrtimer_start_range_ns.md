# Function: <code>hrtimer_start_range_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, long unsigned int delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ef420)
Location: kernel/time/hrtimer.c:981
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:__mbm_start_timer
  - arch/x86/events/intel/rapl.c:__rapl_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:do_schedule_next_timer
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/futex.c:futex_wait_queue_me
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/aio.c:read_events
  - drivers/usb/host/ehci-hcd.c:ehci_enable_event
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - drivers/mailbox/mailbox.c:msg_submit
  - net/core/dev.c:napi_complete_done
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff810ef420-ffffffff810ef7f7: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810f64b0)
Location: kernel/time/hrtimer.c:971
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:__mbm_start_timer
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:do_schedule_next_timer
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/futex.c:futex_wait_queue_me
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:read_events
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - drivers/usb/host/ehci-hcd.c:ehci_enable_event
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - drivers/mailbox/mailbox.c:msg_submit
  - net/core/dev.c:napi_complete_done
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff810f64b0-ffffffff810f687b: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fd4d0)
Location: kernel/time/hrtimer.c:971
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:__mbm_start_timer
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/idle.c:play_idle
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/posix-timers.c:do_schedule_next_timer
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/futex.c:futex_wait_queue_me
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:read_events
  - block/blk-mq.c:blk_mq_poll_hybrid_sleep
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - drivers/mailbox/mailbox.c:msg_submit
  - net/core/dev.c:napi_complete_done
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff810fd4d0-ffffffff810fd89c: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ff800)
Location: kernel/time/hrtimer.c:943
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/idle.c:play_idle
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:read_events
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - drivers/mailbox/mailbox.c:msg_submit
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff810ff800-ffffffff810ffb2a: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8110a610)
Location: kernel/time/hrtimer.c:943
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/idle.c:play_idle
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:read_events
  - block/cfq-iosched.c:cfq_completed_request
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - drivers/mailbox/mailbox.c:msg_submit
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_output.c:tcp_transmit_skb
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff8110a610-ffffffff8110a942: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81115ab0)
Location: kernel/time/hrtimer.c:1101
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:read_events
  - block/cfq-iosched.c:cfq_completed_request
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/mailbox/mailbox.c:msg_submit
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff81115ab0-ffffffff81115d61: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811215c0)
Location: kernel/time/hrtimer.c:1092
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:read_events
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/mailbox/mailbox.c:msg_submit
  - drivers/powercap/idle_inject.c:idle_inject_start
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff811215c0-ffffffff81121871: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112be80)
Location: kernel/time/hrtimer.c:1091
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_queue_me
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:read_events
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/mailbox/mailbox.c:msg_submit
  - drivers/powercap/idle_inject.c:idle_inject_start
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff8112be80-ffffffff8112c183: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81137e80)
Location: kernel/time/hrtimer.c:1115
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:read_events
  - fs/io_uring.c:__io_submit_sqe
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/mailbox/mailbox.c:msg_submit
  - drivers/powercap/idle_inject.c:idle_inject_start
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81137e80-ffffffff81138182: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81146cd0)
Location: kernel/time/hrtimer.c:1115
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/idle.c:play_idle_precise
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:read_events
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_issue_sqe
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:scan_async
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/mailbox/mailbox.c:msg_submit
  - drivers/powercap/idle_inject.c:idle_inject_start
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81146cd0-ffffffff81146d94: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81142de0)
Location: kernel/time/hrtimer.c:1132
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/idle.c:play_idle_precise
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:read_events
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_timeout
  - fs/io_uring.c:io_timeout_remove
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:scan_async
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/mailbox/mailbox.c:msg_submit
  - drivers/powercap/idle_inject.c:idle_inject_start
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81142de0-ffffffff81142ea4: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81144310)
Location: kernel/time/hrtimer.c:1132
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/idle.c:play_idle_precise
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:read_events
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_issue_sqe
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/mailbox/mailbox.c:msg_submit
  - drivers/powercap/idle_inject.c:idle_inject_start
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81144310-ffffffff811443d4: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81167bc0)
Location: kernel/time/hrtimer.c:1280
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/idle.c:play_idle_precise
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/watchdog.c:watchdog_enable
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:read_events
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_issue_sqe
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/mailbox/mailbox.c:msg_submit
  - drivers/powercap/idle_inject.c:idle_inject_start
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81167bc0-ffffffff81167c84: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119b570)
Location: kernel/time/hrtimer.c:1280
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/watchdog.c:watchdog_enable
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - block/blk-iocost.c:iocg_kick_waitq
  - io_uring/io_uring.c:io_queue_linked_timeout
  - io_uring/io_uring.c:io_timeout
  - io_uring/io_uring.c:io_timeout_remove
  - io_uring/io_uring.c:io_timeout_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/mailbox/mailbox.c:msg_submit
  - drivers/powercap/idle_inject.c:idle_inject_start
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff8119b570-ffffffff8119b63f: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811d9df0)
Location: kernel/time/hrtimer.c:1280
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/watchdog.c:watchdog_enable
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - block/blk-iocost.c:iocg_kick_waitq
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_timeout_remove
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/mailbox/mailbox.c:msg_submit
  - drivers/powercap/idle_inject.c:idle_inject_start
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff811d9df0-ffffffff811d9ebf: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811edf50)
Location: kernel/time/hrtimer.c:1283
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/watchdog.c:watchdog_enable
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - block/blk-iocost.c:iocg_kick_waitq
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_complete
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/mailbox/mailbox.c:msg_submit
  - drivers/powercap/idle_inject.c:idle_inject_start
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff811edf50-ffffffff811ee01f: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff812042b0)
Location: kernel/time/hrtimer.c:1284
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/ntp.c:sync_hw_clock
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart_sched_tick
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/watchdog.c:watchdog_enable
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - block/blk-iocost.c:iocg_kick_waitq
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_complete
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:unlink_empty_async
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:end_free_itds
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_start_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_handle_controller_death
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/mailbox/mailbox.c:msg_submit
  - drivers/powercap/idle_inject.c:idle_inject_start
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff812042b0-ffffffff8120437f: hrtimer_start_range_ns (STB_GLOBAL)
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
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a16a8)
Location: kernel/time/hrtimer.c:1115
Inline: False
Direct callers:
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_put
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_load
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/sched_clock.c:sched_clock_resume
  - kernel/time/sched_clock.c:generic_sched_clock_init
  - kernel/time/sched_clock.c:sched_clock_register
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:read_events
  - fs/io_uring.c:__io_submit_sqe
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - drivers/media/cec/cec-pin.c:cec_pin_adap_enable
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_timer_trigger
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/mailbox/mailbox.c:msg_submit
  - drivers/powercap/idle_inject.c:idle_inject_start
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffff8000101a16a8-ffff8000101a1a68: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03eb294)
Location: kernel/time/hrtimer.c:1115
Inline: False
Direct callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_add
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_start
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:__hrtick_restart
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/sched_clock.c:sched_clock_resume
  - kernel/time/sched_clock.c:generic_sched_clock_init
  - kernel/time/sched_clock.c:sched_clock_register
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:do_io_getevents
  - fs/io_uring.c:__io_submit_sqe
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_timer_trigger
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/mailbox/mailbox.c:msg_submit
  - drivers/powercap/idle_inject.c:idle_inject_start
  - sound/soc/fsl/imx-pcm-fiq.c:snd_imx_pcm_trigger
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
c03eb294-c03eb704: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000202bd0)
Location: kernel/time/hrtimer.c:1115
Inline: False
Direct callers:
  - arch/powerpc/kernel/watchdog.c:start_watchdog
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:read_events
  - fs/io_uring.c:__io_submit_sqe
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_timer_trigger
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/mailbox/mailbox.c:msg_submit
  - drivers/powercap/idle_inject.c:idle_inject_start
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
c000000000202bd0-c000000000203010: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012ec0c)
Location: kernel/time/hrtimer.c:1115
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/sched_clock.c:sched_clock_resume
  - kernel/time/sched_clock.c:generic_sched_clock_init
  - kernel/time/sched_clock.c:sched_clock_register
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:__se_sys_timerfd_gettime
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:read_events
  - fs/io_uring.c:__io_submit_sqe
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_timer_trigger
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/mailbox/mailbox.c:msg_submit
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffe00012ec0c-ffffffe00012ef40: hrtimer_start_range_ns (STB_GLOBAL)
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
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81130630)
Location: kernel/time/hrtimer.c:1115
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:read_events
  - fs/io_uring.c:__io_submit_sqe
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/mailbox/mailbox.c:msg_submit
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81130630-ffffffff81130932: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811230a0)
Location: kernel/time/hrtimer.c:1115
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart_sched_tick
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:read_events
  - fs/io_uring.c:__io_submit_sqe
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/mailbox/mailbox.c:msg_submit
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff811230a0-ffffffff811233a2: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112e350)
Location: kernel/time/hrtimer.c:1115
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:read_events
  - fs/io_uring.c:__io_submit_sqe
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/mailbox/mailbox.c:msg_submit
  - drivers/powercap/idle_inject.c:idle_inject_start
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff8112e350-ffffffff8112e652: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hrtimer_start_range_ns(struct hrtimer *timer, ktime_t tim, u64 delta_ns, const enum hrtimer_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113ad30)
Location: kernel/time/hrtimer.c:1115
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - kernel/signal.c:dequeue_signal
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
  - kernel/sched/idle.c:play_idle
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/posix-timers.c:common_hrtimer_arm
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
  - kernel/watchdog.c:watchdog_enable
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - fs/aio.c:read_events
  - fs/io_uring.c:__io_submit_sqe
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - drivers/media/cec/cec-pin.c:cec_pin_adap_enable
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/mailbox/mailbox.c:msg_submit
  - drivers/powercap/idle_inject.c:idle_inject_start
  - net/core/dev.c:napi_complete_done
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff8113ad30-ffffffff8113b052: hrtimer_start_range_ns (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int delta_ns</code> ➡️ <code>u64 delta_ns</code>
</li>
</ul>
</details>
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
