# Function: <code>hrtimer_try_to_cancel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810eef40)
Location: kernel/time/hrtimer.c:1034
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/posix-timers.c:common_timer_del
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - fs/timerfd.c:do_timerfd_settime
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
**Symbols:**

```
ffffffff810eef40-ffffffff810ef064: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810f6000)
Location: kernel/time/hrtimer.c:1024
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/posix-timers.c:common_timer_del
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/timerfd.c:do_timerfd_settime
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
**Symbols:**

```
ffffffff810f6000-ffffffff810f6119: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fd0a0)
Location: kernel/time/hrtimer.c:1024
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_timer_del
  - kernel/time/posix-timers.c:common_timer_set
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/timerfd.c:do_timerfd_settime
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
**Symbols:**

```
ffffffff810fd0a0-ffffffff810fd1b9: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ff430)
Location: kernel/time/hrtimer.c:994
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/timerfd.c:do_timerfd_settime
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
**Symbols:**

```
ffffffff810ff430-ffffffff810ff536: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8110a230)
Location: kernel/time/hrtimer.c:994
Inline: True
Direct callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/timerfd.c:do_timerfd_settime
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
**Symbols:**

```
ffffffff8110a230-ffffffff8110a339: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81116110)
Location: kernel/time/hrtimer.c:1132
Inline: True
Direct callers:
  - kernel/sched/deadline.c:dl_change_utilization
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff81116110-ffffffff81116212: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811210f0)
Location: kernel/time/hrtimer.c:1123
Inline: True
Direct callers:
  - kernel/sched/deadline.c:dl_change_utilization
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff811210f0-ffffffff811211f2: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112b910)
Location: kernel/time/hrtimer.c:1123
Inline: True
Direct callers:
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:dl_change_utilization
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:hrtimer_cancel
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff8112b910-ffffffff8112ba12: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811379b0)
Location: kernel/time/hrtimer.c:1151
Inline: True
Direct callers:
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:dl_change_utilization
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff811379b0-ffffffff81137ab1: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81bcbc8a)
Location: kernel/time/hrtimer.c:1151
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/sched/deadline.c:dl_change_utilization
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/timerfd.c:do_timerfd_settime
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:__io_timeout_cancel
  - fs/io_uring.c:__io_fail_links
  - fs/io_uring.c:io_req_link_next
  - fs/io_uring.c:io_commit_cqring
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff81146e60-ffffffff81146f42: hrtimer_try_to_cancel.part.0 (STB_LOCAL)
ffffffff81146f50-ffffffff81146f7b: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81c44aaa)
Location: kernel/time/hrtimer.c:1168
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_change_utilization
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/timerfd.c:do_timerfd_settime
  - fs/io_uring.c:io_timeout_extract
  - fs/io_uring.c:io_kill_linked_timeout
  - fs/io_uring.c:io_flush_timeouts
  - fs/io_uring.c:io_kill_timeouts
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff81143310-ffffffff811433e1: hrtimer_try_to_cancel.part.0 (STB_LOCAL)
ffffffff811433f0-ffffffff8114341b: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81c37d17)
Location: kernel/time/hrtimer.c:1168
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:dl_change_utilization
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/timerfd.c:do_timerfd_settime
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_timeout_extract
  - fs/io_uring.c:io_disarm_next
  - fs/io_uring.c:io_commit_cqring
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff81144400-ffffffff811444d1: hrtimer_try_to_cancel.part.0 (STB_LOCAL)
ffffffff811444e0-ffffffff8114450b: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81d565d7)
Location: kernel/time/hrtimer.c:1316
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/timerfd.c:do_timerfd_settime
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_timeout_extract
  - fs/io_uring.c:io_disarm_next
  - fs/io_uring.c:__io_commit_cqring_flush
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff81167670-ffffffff8116773e: hrtimer_try_to_cancel.part.0 (STB_LOCAL)
ffffffff81167740-ffffffff8116776b: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119aad0)
Location: kernel/time/hrtimer.c:1316
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/timerfd.c:do_timerfd_settime
  - io_uring/io_uring.c:io_timeout_remove
  - io_uring/io_uring.c:io_timeout_extract
  - io_uring/io_uring.c:io_disarm_next
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff8119aad0-ffffffff8119abe4: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811d9650)
Location: kernel/time/hrtimer.c:1316
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/timerfd.c:do_timerfd_settime
  - io_uring/timeout.c:io_kill_timeouts
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_extract
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_flush_timeouts
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff811d9650-ffffffff811d9764: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff821582ec)
Location: kernel/time/hrtimer.c:1319
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/timerfd.c:do_timerfd_settime
  - io_uring/timeout.c:io_kill_timeouts
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_extract
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_flush_timeouts
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff811ee250-ffffffff811ee342: hrtimer_try_to_cancel.part.0 (STB_LOCAL)
ffffffff811ee360-ffffffff811ee390: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8223b15c)
Location: kernel/time/hrtimer.c:1320
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
Direct callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:task_contending
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/timerfd.c:do_timerfd_settime
  - io_uring/timeout.c:io_kill_timeouts
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_extract
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_flush_timeouts
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff812043d0-ffffffff812044c2: hrtimer_try_to_cancel.part.0 (STB_LOCAL)
ffffffff812044e0-ffffffff81204510: hrtimer_try_to_cancel (STB_GLOBAL)
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
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a1aa8)
Location: kernel/time/hrtimer.c:1151
Inline: True
Direct callers:
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:dl_change_utilization
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffff8000101a1aa8-ffff8000101a1c0c: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03eab24)
Location: kernel/time/hrtimer.c:1151
Inline: True
Direct callers:
  - kernel/sched/deadline.c:dl_change_utilization
  - kernel/time/hrtimer.c:hrtimer_cancel
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
c03eab24-c03eac80: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c0000000002023e0)
Location: kernel/time/hrtimer.c:1151
Inline: True
Direct callers:
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:dl_change_utilization
  - kernel/time/hrtimer.c:hrtimer_cancel
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
c0000000002023e0-c000000000202564: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012e63a)
Location: kernel/time/hrtimer.c:1151
Inline: True
Direct callers:
  - kernel/sched/deadline.c:dl_change_utilization
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_done
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffe00012e63a-ffffffe00012e746: hrtimer_try_to_cancel (STB_GLOBAL)
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
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81130160)
Location: kernel/time/hrtimer.c:1151
Inline: True
Direct callers:
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:dl_change_utilization
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff81130160-ffffffff81130261: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81122bd0)
Location: kernel/time/hrtimer.c:1151
Inline: True
Direct callers:
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:dl_change_utilization
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff81122bd0-ffffffff81122cd1: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112de80)
Location: kernel/time/hrtimer.c:1151
Inline: True
Direct callers:
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:dl_change_utilization
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff8112de80-ffffffff8112df81: hrtimer_try_to_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int hrtimer_try_to_cancel(struct hrtimer *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113a7f0)
Location: kernel/time/hrtimer.c:1151
Inline: True
Direct callers:
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:dl_change_utilization
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/posix-timers.c:common_hrtimer_try_to_cancel
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/tick-broadcast-hrtimer.c:bc_shutdown
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/rtc/interface.c:rtc_update_hrtimer
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
**Symbols:**

```
ffffffff8113a7f0-ffffffff8113a909: hrtimer_try_to_cancel (STB_GLOBAL)
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
