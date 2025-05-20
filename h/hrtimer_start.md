# Function: <code>hrtimer_start</code>

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
In arch/x86/events/intel/cqm.c (ffffffff8100dbcf)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:__mbm_start_timer
```
```
In arch/x86/events/intel/rapl.c (ffffffff81014c03)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - arch/x86/events/intel/rapl.c:__rapl_pmu_event_start
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016774)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/fair.c (ffffffff810b7036)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810c1643)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/itimer.c (ffffffff810f0773)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/alarmtimer.c (ffffffff810faa1a)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff810fde27)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/tick-sched.c (ffffffff810fe9fa)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/watchdog.c (ffffffff8113abc3)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (ffffffff8117a42b)
Location: include/linux/hrtimer.h:390
Inline: True
```
```
In fs/timerfd.c (ffffffff81258962)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In drivers/rtc/interface.c (ffffffff81673ece)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
```
In drivers/mailbox/mailbox.c (ffffffff816eb3b6)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In net/core/dev.c (ffffffff8171add6)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff817434ad)
Location: include/linux/hrtimer.h:390
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff817b7e28)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In arch/x86/events/intel/cqm.c (ffffffff8100db8f)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:__mbm_start_timer
```
```
In arch/x86/events/intel/uncore.c (ffffffff810146fb)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/fair.c (ffffffff810ba9ce)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810c5109)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/itimer.c (ffffffff810f77a3)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/alarmtimer.c (ffffffff81101c8a)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff811051b7)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/tick-sched.c (ffffffff81105d82)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/watchdog.c (ffffffff811430f6)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (ffffffff8118b11b)
Location: include/linux/hrtimer.h:390
Inline: True
```
```
In fs/timerfd.c (ffffffff81281290)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In block/cfq-iosched.c (ffffffff8142ad7e)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_arm_slice_timer
```
```
In drivers/rtc/interface.c (ffffffff816d46b6)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
```
In drivers/mailbox/mailbox.c (ffffffff8174feb1)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In net/core/dev.c (ffffffff817832d6)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff817b034a)
Location: include/linux/hrtimer.h:390
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff8182761f)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
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
In arch/x86/events/intel/cqm.c (ffffffff8100dc4f)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:__mbm_start_timer
```
```
In arch/x86/events/intel/uncore.c (ffffffff810148c9)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/fair.c (ffffffff810c103d)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810cb135)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/sched/idle.c (ffffffff810cdbb3)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/time/alarmtimer.c (ffffffff81104373)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffff81109e63)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff8110c907)
Location: include/linux/hrtimer.h:390
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8110d4ce)
Location: include/linux/hrtimer.h:390
Inline: True
```
```
In kernel/watchdog.c (ffffffff8114d103)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (ffffffff8119a04b)
Location: include/linux/hrtimer.h:390
Inline: True
```
```
In fs/timerfd.c (ffffffff81294dc0)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In block/cfq-iosched.c (ffffffff81441d42)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_arm_slice_timer
```
```
In drivers/rtc/interface.c (ffffffff81704396)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
```
In drivers/mailbox/mailbox.c (ffffffff8177ba71)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In net/core/dev.c (ffffffff817b0b84)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff817dfa4a)
Location: include/linux/hrtimer.h:390
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81858dff)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
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
In arch/x86/events/intel/uncore.c (ffffffff81012ee9)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/fair.c (ffffffff810bbd7f)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810c6c71)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/sched/idle.c (ffffffff810ca5c3)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/time/alarmtimer.c (ffffffff8110645f)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffff8110bc6b)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff8110e7f2)
Location: include/linux/hrtimer.h:374
Inline: True
```
```
In kernel/watchdog.c (ffffffff8114ee73)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (ffffffff811a1d9b)
Location: include/linux/hrtimer.h:374
Inline: True
```
```
In fs/timerfd.c (ffffffff812a210d)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In block/cfq-iosched.c (ffffffff81450fed)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_arm_slice_timer
```
```
In drivers/rtc/interface.c (ffffffff81719f76)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
```
In drivers/mailbox/mailbox.c (ffffffff8179a591)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In net/core/dev.c (ffffffff817d0f79)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff817fefca)
Location: include/linux/hrtimer.h:374
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81833cd0)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/xfrm/xfrm_state.c (ffffffff8187ce7c)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
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
In arch/x86/events/intel/uncore.c (ffffffff81013708)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/fair.c (ffffffff810c3ab2)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810ce4b0)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/sched/idle.c (ffffffff810d1dd3)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/time/alarmtimer.c (ffffffff811114df)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffff81116ebb)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff81119a82)
Location: include/linux/hrtimer.h:374
Inline: True
```
```
In kernel/watchdog.c (ffffffff8115b633)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (ffffffff811b5a1b)
Location: include/linux/hrtimer.h:374
Inline: True
```
```
In fs/timerfd.c (ffffffff812c5433)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In block/cfq-iosched.c (ffffffff814801bc)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fd230)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/rtc/interface.c (ffffffff8178b1e6)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
```
In drivers/mailbox/mailbox.c (ffffffff8181094a)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In net/core/dev.c (ffffffff8184b069)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff8187cc5a)
Location: include/linux/hrtimer.h:374
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff818b30ba)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/xfrm/xfrm_state.c (ffffffff818fdc56)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
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
In arch/x86/events/intel/uncore.c (ffffffff8101406e)
Location: include/linux/hrtimer.h:395
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/idle.c (ffffffff810c4576)
Location: include/linux/hrtimer.h:395
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (ffffffff810ca7bf)
Location: include/linux/hrtimer.h:395
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810d5699)
Location: include/linux/hrtimer.h:395
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/alarmtimer.c (ffffffff8111cecf)
Location: include/linux/hrtimer.h:395
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffff81123826)
Location: include/linux/hrtimer.h:395
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff81126642)
Location: include/linux/hrtimer.h:395
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81127361)
Location: include/linux/hrtimer.h:395
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In kernel/watchdog.c (ffffffff8116a1a5)
Location: include/linux/hrtimer.h:395
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (ffffffff811d5064)
Location: include/linux/hrtimer.h:395
Inline: True
```
```
In fs/timerfd.c (ffffffff812ee7e2)
Location: include/linux/hrtimer.h:395
Inline: True
```
```
In block/cfq-iosched.c (ffffffff814b49ce)
Location: include/linux/hrtimer.h:395
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81636565)
Location: include/linux/hrtimer.h:395
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/rtc/interface.c (ffffffff817cc9f3)
Location: include/linux/hrtimer.h:395
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817ef772)
Location: include/linux/hrtimer.h:395
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/mailbox/mailbox.c (ffffffff8185a7e7)
Location: include/linux/hrtimer.h:395
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In net/core/dev.c (ffffffff81895466)
Location: include/linux/hrtimer.h:395
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff818cf4f1)
Location: include/linux/hrtimer.h:395
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff818ff093)
Location: include/linux/hrtimer.h:395
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819084ca)
Location: include/linux/hrtimer.h:395
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/xfrm/xfrm_state.c (ffffffff8195484e)
Location: include/linux/hrtimer.h:395
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
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
In arch/x86/events/intel/uncore.c (ffffffff8101476e)
Location: include/linux/hrtimer.h:392
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/idle.c (ffffffff810cd836)
Location: include/linux/hrtimer.h:392
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (ffffffff810d402d)
Location: include/linux/hrtimer.h:392
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810df0c9)
Location: include/linux/hrtimer.h:392
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/alarmtimer.c (ffffffff8112867f)
Location: include/linux/hrtimer.h:392
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffff8112eef6)
Location: include/linux/hrtimer.h:392
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff81131d22)
Location: include/linux/hrtimer.h:392
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff81132a51)
Location: include/linux/hrtimer.h:392
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In kernel/watchdog.c (ffffffff8117719a)
Location: include/linux/hrtimer.h:392
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (ffffffff811e5884)
Location: include/linux/hrtimer.h:392
Inline: True
```
```
In fs/timerfd.c (ffffffff81303172)
Location: include/linux/hrtimer.h:392
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81654a75)
Location: include/linux/hrtimer.h:392
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/runtime.c (ffffffff816b01ad)
Location: include/linux/hrtimer.h:392
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817a36a4)
Location: include/linux/hrtimer.h:392
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff817f3cf3)
Location: include/linux/hrtimer.h:392
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8181b663)
Location: include/linux/hrtimer.h:392
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/mailbox/mailbox.c (ffffffff81879b07)
Location: include/linux/hrtimer.h:392
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In drivers/powercap/idle_inject.c (ffffffff81883df0)
Location: include/linux/hrtimer.h:392
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
```
```
In net/core/dev.c (ffffffff818b70dd)
Location: include/linux/hrtimer.h:392
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff818faac1)
Location: include/linux/hrtimer.h:392
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8192d43e)
Location: include/linux/hrtimer.h:392
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81935225)
Location: include/linux/hrtimer.h:392
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81988f04)
Location: include/linux/hrtimer.h:392
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
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
In arch/x86/events/intel/uncore.c (ffffffff81015bee)
Location: include/linux/hrtimer.h:378
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/idle.c (ffffffff810d5c26)
Location: include/linux/hrtimer.h:378
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (ffffffff810dc1de)
Location: include/linux/hrtimer.h:378
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810e696f)
Location: include/linux/hrtimer.h:378
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/alarmtimer.c (ffffffff811330bf)
Location: include/linux/hrtimer.h:378
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffff8113997c)
Location: include/linux/hrtimer.h:378
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff8113c852)
Location: include/linux/hrtimer.h:378
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8113d5bc)
Location: include/linux/hrtimer.h:378
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In kernel/watchdog.c (ffffffff81183f7b)
Location: include/linux/hrtimer.h:378
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (ffffffff811fcf94)
Location: include/linux/hrtimer.h:378
Inline: True
```
```
In fs/timerfd.c (ffffffff813243fa)
Location: include/linux/hrtimer.h:378
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816894ac)
Location: include/linux/hrtimer.h:378
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/runtime.c (ffffffff816ea04d)
Location: include/linux/hrtimer.h:378
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817e2e63)
Location: include/linux/hrtimer.h:378
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff81834a36)
Location: include/linux/hrtimer.h:378
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8185d8a2)
Location: include/linux/hrtimer.h:378
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/mailbox/mailbox.c (ffffffff818bf097)
Location: include/linux/hrtimer.h:378
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In drivers/powercap/idle_inject.c (ffffffff818ce4fe)
Location: include/linux/hrtimer.h:378
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
```
```
In net/core/dev.c (ffffffff81902ef1)
Location: include/linux/hrtimer.h:378
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff8195a371)
Location: include/linux/hrtimer.h:378
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81990841)
Location: include/linux/hrtimer.h:378
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81998be9)
Location: include/linux/hrtimer.h:378
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff819f2d01)
Location: include/linux/hrtimer.h:378
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In arch/x86/events/intel/uncore.c (ffffffff810165e5)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/idle.c (ffffffff810e0226)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (ffffffff810e6568)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810f12e2)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/alarmtimer.c (ffffffff8113f01f)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffff811455fe)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff81148407)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/tick-sched.c (ffffffff8114915c)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In kernel/watchdog.c (ffffffff8118fdfb)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (ffffffff8120a114)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In fs/timerfd.c (ffffffff8133715a)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In fs/io_uring.c (ffffffff81342815)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816abbcc)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/runtime.c (ffffffff8170e0ad)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81813d53)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff81866356)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8188e829)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/mailbox/mailbox.c (ffffffff818f1c17)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In drivers/powercap/idle_inject.c (ffffffff819008ee)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
```
```
In net/core/dev.c (ffffffff81935c85)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff81990811)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819c4503)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819cf6fe)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81a29bd1)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In arch/x86/events/intel/uncore.c (ffffffff81018b35)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/idle.c (ffffffff810e8591)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle_precise
```
```
In kernel/sched/fair.c (ffffffff810f082a)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810fa759)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/alarmtimer.c (ffffffff8114e8d5)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffff81154c6a)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff81158247)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/tick-sched.c (ffffffff81158829)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/watchdog.c (ffffffff811a497b)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (ffffffff8123d541)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
```
```
In fs/timerfd.c (ffffffff81370eee)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/io_uring.c (ffffffff81381d64)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_issue_sqe
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81760798)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
```
In drivers/base/power/runtime.c (ffffffff817c996e)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818e4e41)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/rtc/interface.c (ffffffff8193b895)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8195d429)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/mailbox/mailbox.c (ffffffff819c74a7)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In drivers/powercap/idle_inject.c (ffffffff819d78e6)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
```
```
In net/core/dev.c (ffffffff81a0a9e5)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/ipv4/tcp_output.c (ffffffff81abfd84)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/xfrm/xfrm_state.c (ffffffff81b18abb)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In arch/x86/events/intel/uncore.c (ffffffff810192b5)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/core.c (ffffffff810df01b)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/idle.c (ffffffff810e6198)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle_precise
```
```
In kernel/sched/fair.c (ffffffff810ef3cd)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810f8bf9)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/rcu/tree.c (ffffffff81133435)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/time/ntp.c (ffffffff8114751e)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
```
```
In kernel/time/alarmtimer.c (ffffffff8114ab47)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffff81150eea)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff811542e7)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/tick-sched.c (ffffffff81154849)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/watchdog.c (ffffffff811a1a1b)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (ffffffff812478e1)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
```
```
In fs/timerfd.c (ffffffff8137ec6c)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/io_uring.c (ffffffff81391c47)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_timeout
  - fs/io_uring.c:io_timeout_remove
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177b618)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
```
In drivers/base/power/runtime.c (ffffffff817de46e)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818ee311)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/rtc/interface.c (ffffffff81941bd5)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81963dd9)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/mailbox/mailbox.c (ffffffff819c73f7)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In drivers/powercap/idle_inject.c (ffffffff819d6a26)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
```
```
In net/core/dev.c (ffffffff81a0c69e)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
```
```
In net/ipv4/tcp_output.c (ffffffff81acb7ef)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/xfrm/xfrm_state.c (ffffffff81b27700)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In arch/x86/events/intel/uncore.c (ffffffff8101a5d5)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/core.c (ffffffff810e0cbd)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/idle.c (ffffffff810e8168)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle_precise
```
```
In kernel/sched/fair.c (ffffffff810f0de2)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810fac9c)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/rcu/tree.c (ffffffff8113352c)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/time/ntp.c (ffffffff8114864e)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
```
```
In kernel/time/alarmtimer.c (ffffffff8114c007)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffff8115231a)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff81155757)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/tick-sched.c (ffffffff81155cc9)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/watchdog.c (ffffffff811a26eb)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (ffffffff8124b78c)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
```
```
In fs/timerfd.c (ffffffff813858ec)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/io_uring.c (ffffffff81397077)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_issue_sqe
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175ec90)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
```
In drivers/base/power/runtime.c (ffffffff817c284e)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818d1aca)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/rtc/interface.c (ffffffff81925365)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819481f9)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/mailbox/mailbox.c (ffffffff819ac337)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In drivers/powercap/idle_inject.c (ffffffff819bcba6)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
```
```
In net/core/dev.c (ffffffff819f297e)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
```
```
In net/ipv4/tcp_output.c (ffffffff81ab69a4)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/xfrm/xfrm_state.c (ffffffff81b15320)
Location: include/linux/hrtimer.h:419
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In arch/x86/events/intel/uncore.c (ffffffff8101cf47)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/core.c (ffffffff810f5bfd)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/idle.c (ffffffff810ff828)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle_precise
```
```
In kernel/sched/fair.c (ffffffff8110a7f5)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff8111665b)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/rcu/tree.c (ffffffff81155891)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/time/ntp.c (ffffffff8116c1fe)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
```
```
In kernel/time/alarmtimer.c (ffffffff8116fd71)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffff811768ea)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff8117a3c7)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/tick-sched.c (ffffffff8117a954)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/watchdog.c (ffffffff811cbecb)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/bpf/helpers.c (ffffffff812503c2)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_timer_start
```
```
In kernel/events/core.c (ffffffff81284cbc)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
```
```
In fs/timerfd.c (ffffffff813d2a66)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In fs/io_uring.c (ffffffff813e9438)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_issue_sqe
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e30f0)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
```
In drivers/base/power/runtime.c (ffffffff8184cc6e)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8196c43c)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/rtc/interface.c (ffffffff819c82f5)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819ed1a8)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/mailbox/mailbox.c (ffffffff81a5a79e)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In drivers/powercap/idle_inject.c (ffffffff81a6c093)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
```
```
In net/core/dev.c (ffffffff81aa484b)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
```
```
In net/ipv4/tcp_output.c (ffffffff81b73adc)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd94a0)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In arch/x86/events/intel/uncore.c (ffffffff8101f782)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/core.c (ffffffff81110cdb)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (ffffffff811261da)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/build_policy.c (ffffffff8113058f)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:play_idle_precise
```
```
In kernel/rcu/tree.c (ffffffff8117f404)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/time/ntp.c (ffffffff811a01bb)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
```
```
In kernel/time/alarmtimer.c (ffffffff811a425b)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffff811abd76)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff811af867)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/tick-sched.c (ffffffff811b0178)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/watchdog.c (ffffffff811ffc6a)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/bpf/helpers.c (ffffffff81297a12)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_timer_start
```
```
In kernel/events/core.c (ffffffff812d91cc)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
```
```
In fs/timerfd.c (ffffffff8145b3df)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In io_uring/io_uring.c (ffffffff816d2ada)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_queue_linked_timeout
  - io_uring/io_uring.c:io_timeout
  - io_uring/io_uring.c:io_timeout_remove
  - io_uring/io_uring.c:io_timeout_remove
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81923f1e)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
```
In drivers/base/power/runtime.c (ffffffff81991eac)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81ac68e5)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/rtc/interface.c (ffffffff81b29105)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81b53a98)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/mailbox/mailbox.c (ffffffff81bc9ebc)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In drivers/powercap/idle_inject.c (ffffffff81bdcb83)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
```
```
In net/core/dev.c (ffffffff81c1bfaa)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
```
```
In net/ipv4/tcp_output.c (ffffffff81d03159)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6fc4c)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In arch/x86/events/intel/uncore.c (ffffffff81023fb2)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/core.c (ffffffff81137c5b)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (ffffffff8114f666)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/build_policy.c (ffffffff8115a0cf)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:play_idle_precise
```
```
In kernel/rcu/tree.c (ffffffff811b8ab0)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/time/ntp.c (ffffffff811defcb)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
```
```
In kernel/time/alarmtimer.c (ffffffff811e3b3b)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffff811ec016)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff811f01a7)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/tick-sched.c (ffffffff811f0c18)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/watchdog.c (ffffffff812476ca)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/bpf/helpers.c (ffffffff812f29c2)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_timer_start
```
```
In kernel/events/core.c (ffffffff8134167c)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_start
```
```
In fs/timerfd.c (ffffffff814ea9ef)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In io_uring/timeout.c (ffffffff81799dea)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_timeout_remove
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a809f6)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
```
In drivers/base/power/runtime.c (ffffffff81b003ec)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81c50a55)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/rtc/interface.c (ffffffff81cbcc85)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81cec9f3)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
```
```
In drivers/mailbox/mailbox.c (ffffffff81d7342c)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In drivers/powercap/idle_inject.c (ffffffff81d87cfd)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
```
```
In net/core/dev.c (ffffffff81dccf7a)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
```
```
In net/ipv4/tcp_output.c (ffffffff81ec8122)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3b442)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In arch/x86/events/intel/uncore.c (ffffffff81023cd2)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/core.c (ffffffff81146d7b)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (ffffffff8115e4d6)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/build_policy.c (ffffffff8116a2df)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:play_idle_precise
```
```
In kernel/rcu/tree.c (ffffffff811ca94f)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/time/ntp.c (ffffffff811f34ab)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
```
```
In kernel/time/alarmtimer.c (ffffffff811f81ab)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffff81200743)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff81204905)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/tick-sched.c (ffffffff8120563a)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/watchdog.c (ffffffff8125eafa)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/trace/trace_osnoise.c (ffffffff81296bb3)
Location: include/linux/hrtimer.h:415
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff8131f398)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_timer_start
```
```
In kernel/events/core.c (ffffffff813725fc)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
```
```
In fs/timerfd.c (ffffffff81521792)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In io_uring/timeout.c (ffffffff817daeba)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_complete
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acc016)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
```
In drivers/base/power/runtime.c (ffffffff81b4e6dc)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb7fd5)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/rtc/interface.c (ffffffff81d24595)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81d55713)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
```
```
In drivers/mailbox/mailbox.c (ffffffff81de120c)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In drivers/powercap/idle_inject.c (ffffffff81df6125)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
```
```
In net/core/dev.c (ffffffff81e3dada)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
```
```
In net/ipv4/tcp_output.c (ffffffff81f26bb9)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9ae62)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In arch/x86/events/intel/uncore.c (ffffffff81029e02)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/core.c (ffffffff811525ab)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
  - kernel/sched/core.c:__hrtick_start
```
```
In kernel/sched/fair.c (ffffffff8116ca5a)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/build_policy.c (ffffffff81177970)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:play_idle_precise
```
```
In kernel/rcu/tree.c (ffffffff811db1ef)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/time/ntp.c (ffffffff812095eb)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - kernel/time/ntp.c:sync_hw_clock
```
```
In kernel/time/alarmtimer.c (ffffffff8120e34b)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffff81216be3)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff8121aec5)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/tick-sched.c (ffffffff8121c09a)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/watchdog.c (ffffffff81278b0a)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b21d3)
Location: include/linux/hrtimer.h:377
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff813417f5)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_timer_start
```
```
In kernel/events/core.c (ffffffff8139b96c)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
```
```
In fs/timerfd.c (ffffffff81555dd2)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In io_uring/timeout.c (ffffffff8181f1aa)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_complete
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1e7b6)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
```
In drivers/base/power/runtime.c (ffffffff81ba6c5c)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6cd45)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
```
In drivers/rtc/interface.c (ffffffff81dda2f5)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0c61a)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
```
```
In drivers/mailbox/mailbox.c (ffffffff81e971cc)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In drivers/powercap/idle_inject.c (ffffffff81eac815)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
```
```
In net/core/dev.c (ffffffff81efc37a)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
```
```
In net/ipv4/tcp_output.c (ffffffff81feb5a1)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/xfrm/xfrm_state.c (ffffffff820681c2)
Location: include/linux/hrtimer.h:377
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In virt/kvm/arm/arch_timer.c (ffff8000100ed2e0)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_put
  - virt/kvm/arm/arch_timer.c:kvm_timer_vcpu_load
```
```
In kernel/sched/idle.c (ffff80001013ff34)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (ffff80001014645c)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffff800010153ee4)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/alarmtimer.c (ffff8000101a9358)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffff8000101aff34)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffff8000101b429c)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/sched_clock.c (ffff8000101b44d0)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:sched_clock_resume
  - kernel/time/sched_clock.c:generic_sched_clock_init
  - kernel/time/sched_clock.c:sched_clock_register
```
```
In kernel/time/tick-sched.c (ffff8000101b55c0)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In kernel/watchdog.c (ffff800010207620)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (ffff8000102932f8)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In fs/timerfd.c (ffff8000103f4f10)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In fs/io_uring.c (ffff80001040441c)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In drivers/tty/serial/8250/8250_port.c (ffff8000108866c4)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/runtime.c (ffff8000108fda68)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4cf08)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In drivers/rtc/interface.c (ffff800010aa7798)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
```
In drivers/media/cec/cec-pin.c (ffff800010ac4178)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_adap_enable
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
```
In drivers/power/reset/ltc2952-poweroff.c (ffff800010ac9f90)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_timer_trigger
```
```
In drivers/watchdog/watchdog_dev.c (ffff800010ae0c58)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/mailbox/mailbox.c (ffff800010b7a280)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In drivers/powercap/idle_inject.c (ffff800010b901a8)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
```
```
In drivers/perf/arm-ccn.c (ffff800010b93f40)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In net/core/dev.c (ffff800010bd41b8)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffff800010c3c89c)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In net/ipv4/tcp_input.c (ffff800010c7b790)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffff800010c81e70)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffff800010ce8334)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In arch/arm/mm/cache-l2x0-pmu.c (c0324c64)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_add
```
```
In arch/arm/mach-imx/mmdc.c (c0332e38)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_start
```
```
In kernel/sched/idle.c (c038fea8)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (c03948cc)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (c03a0aa0)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/alarmtimer.c (c03f4318)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (c03fac64)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (c03fde18)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/sched_clock.c (c03fe0c0)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:sched_clock_resume
  - kernel/time/sched_clock.c:generic_sched_clock_init
  - kernel/time/sched_clock.c:sched_clock_register
```
```
In kernel/time/tick-sched.c (c03ff4d4)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In kernel/watchdog.c (c04463c8)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (c04c38e4)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In fs/timerfd.c (c05c9f30)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In fs/io_uring.c (c05d4340)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In drivers/tty/serial/8250/8250_port.c (c0984bd4)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/runtime.c (c09e7fd4)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/usb/dwc2/hcd_queue.c (c0b1f114)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In drivers/rtc/interface.c (c0b86990)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
```
In drivers/power/reset/ltc2952-poweroff.c (c0baac8c)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_timer_trigger
```
```
In drivers/watchdog/watchdog_dev.c (c0bc0ee8)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/mailbox/mailbox.c (c0c5f6d0)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In drivers/powercap/idle_inject.c (c0c7a1ec)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
```
```
In drivers/perf/arm-ccn.c (c0c7d5bc)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In sound/soc/fsl/imx-pcm-fiq.c (c0cc22ec)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - sound/soc/fsl/imx-pcm-fiq.c:snd_imx_pcm_trigger
```
```
In net/core/dev.c (c0cef9c8)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (c0d4e770)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In net/ipv4/tcp_input.c (c0d8796c)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (c0d91170)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In net/xfrm/xfrm_state.c (c0debfa4)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_check_expire
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In arch/powerpc/kernel/watchdog.c (c000000000036e04)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:start_watchdog
```
```
In kernel/sched/idle.c (c00000000018f13c)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (c000000000197670)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (c0000000001a7584)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/alarmtimer.c (c00000000020c120)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (c000000000214870)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (c000000000219770)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/tick-sched.c (c00000000021ad80)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In kernel/watchdog.c (c000000000283cf4)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (c0000000003417ac)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In fs/timerfd.c (c0000000004fd170)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In fs/io_uring.c (c00000000050d080)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In drivers/tty/serial/8250/8250_port.c (c00000000092d3c0)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/runtime.c (c00000000099a8a8)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/usb/dwc2/hcd_queue.c (c000000000b142c0)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In drivers/rtc/interface.c (c000000000b89550)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
```
In drivers/power/reset/ltc2952-poweroff.c (c000000000babd24)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_timer_trigger
```
```
In drivers/watchdog/watchdog_dev.c (c000000000bc736c)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/mailbox/mailbox.c (c000000000c58c50)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In drivers/powercap/idle_inject.c (c000000000c6f3b0)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
```
```
In net/core/dev.c (c000000000cb3190)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (c000000000d36654)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In net/ipv4/tcp_input.c (c000000000d7f12c)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (c000000000d8d570)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In net/xfrm/xfrm_state.c (c000000000e0ba04)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In kernel/sched/idle.c (ffffffe0000ee0d8)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (ffffffe0000f2074)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffe0000fb74c)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/alarmtimer.c (ffffffe0001348ca)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffe0001391c6)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/sched_clock.c (ffffffe00013a87c)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:sched_clock_resume
  - kernel/time/sched_clock.c:generic_sched_clock_init
  - kernel/time/sched_clock.c:sched_clock_register
```
```
In kernel/time/tick-sched.c (ffffffe00013b806)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In kernel/watchdog.c (ffffffe000169db8)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (ffffffe0001c5ad2)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In fs/timerfd.c (ffffffe0002a615a)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_settime
```
```
In fs/io_uring.c (ffffffe0002af03e)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000551912)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/runtime.c (ffffffe00058c65e)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffe000669930)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In drivers/rtc/interface.c (ffffffe0006b38d0)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
```
In drivers/power/reset/ltc2952-poweroff.c (ffffffe0006c7dbc)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_timer_trigger
```
```
In drivers/watchdog/watchdog_dev.c (ffffffe0006d7f96)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/mailbox/mailbox.c (ffffffe00072bba0)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In net/core/dev.c (ffffffe00075e14c)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffe0007ad0b6)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffe0007da188)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffe0007e4144)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffe0008353c6)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In arch/x86/events/intel/uncore.c (ffffffff810165e5)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/idle.c (ffffffff810da3d6)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (ffffffff810e0718)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810ea6e2)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/alarmtimer.c (ffffffff811377cf)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffff8113ddae)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff81140a27)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/tick-sched.c (ffffffff8114177c)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In kernel/watchdog.c (ffffffff8118841b)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (ffffffff81202734)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In fs/timerfd.c (ffffffff8132f73a)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In fs/io_uring.c (ffffffff8133adf5)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8167163c)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/runtime.c (ffffffff816d37fd)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817cc133)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff81819006)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff818346a9)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/mailbox/mailbox.c (ffffffff81892f47)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In net/core/dev.c (ffffffff818d5c55)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff81930681)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81964373)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff8196f56e)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff819c9261)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In arch/x86/events/intel/uncore.c (ffffffff81015a15)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/idle.c (ffffffff810c93e6)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (ffffffff810cf718)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810da712)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/alarmtimer.c (ffffffff8112a21f)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffff811308d8)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff811337a7)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/tick-sched.c (ffffffff81134489)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/watchdog.c (ffffffff8117b55b)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (ffffffff811f5484)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In fs/timerfd.c (ffffffff8132035e)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In fs/io_uring.c (ffffffff8132badf)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8165073c)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/runtime.c (ffffffff816aeaad)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/rtc/interface.c (ffffffff817e06f6)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817fbd39)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/mailbox/mailbox.c (ffffffff8184b447)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In net/core/dev.c (ffffffff8188fac5)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff818ea181)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8191de63)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff8192903e)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81986051)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In arch/x86/events/intel/uncore.c (ffffffff810165a5)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/idle.c (ffffffff810d6756)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (ffffffff810dca98)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810e7812)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/alarmtimer.c (ffffffff811354ef)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffff8113bace)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff8113e8d7)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/tick-sched.c (ffffffff8113f62c)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In kernel/watchdog.c (ffffffff811861eb)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (ffffffff81200504)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In fs/timerfd.c (ffffffff8132d20a)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In fs/io_uring.c (ffffffff813388c5)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8169fa0c)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/runtime.c (ffffffff81701d6d)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81808bd3)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff8185a4e6)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81883cd9)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/mailbox/mailbox.c (ffffffff818e6a47)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In drivers/powercap/idle_inject.c (ffffffff818f130e)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
```
```
In net/core/dev.c (ffffffff81926c85)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff81981811)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819ceb43)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819d9d3e)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81a33ce1)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In arch/x86/events/intel/uncore.c (ffffffff810167e5)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
```
```
In kernel/sched/idle.c (ffffffff810e205d)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (ffffffff810e87f8)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/deadline.c (ffffffff810f2e12)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/time/alarmtimer.c (ffffffff81141f0f)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_start
```
```
In kernel/time/itimer.c (ffffffff81148595)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff8114b3e7)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/tick-sched.c (ffffffff8114c13c)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In kernel/watchdog.c (ffffffff81193b3b)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/events/core.c (ffffffff8120f594)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In fs/timerfd.c (ffffffff8133fd04)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In fs/io_uring.c (ffffffff8134b13e)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - fs/io_uring.c:__io_submit_sqe
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816b9ecc)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:start_hrtimer_ms
```
```
In drivers/base/power/runtime.c (ffffffff8171bf6d)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81822ce3)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff818755c6)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_update_hrtimer
```
```
In drivers/media/cec/cec-pin.c (ffffffff8188c535)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_adap_enable
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8189f799)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/mailbox/mailbox.c (ffffffff819036c7)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:msg_submit
```
```
In drivers/powercap/idle_inject.c (ffffffff8191238e)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
```
```
In net/core/dev.c (ffffffff819482d5)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff819a3d91)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819d86d3)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819e399e)
Location: include/linux/hrtimer.h:418
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3f631)
Location: include/linux/hrtimer.h:418
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
</details>
</li>
</ul>

## Differences
