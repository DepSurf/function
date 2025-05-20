# Function: <code>ns_to_ktime</code>

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
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c15e0)
Location: include/linux/ktime.h:283
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/ktime.h:283
Inline: True
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
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c50a0)
Location: include/linux/ktime.h:283
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In block/cfq-iosched.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/ktime.h:283
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/ktime.h:283
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff81015f65)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810cb0cf)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/watchdog.c (ffffffff8114cbaa)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In block/cfq-iosched.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/ktime.h:262
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff81014415)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/watchdog.c (ffffffff8114eb2a)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In block/cfq-iosched.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/ktime.h:262
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff81014c60)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/watchdog.c (ffffffff8115b37a)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In block/cfq-iosched.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In drivers/md/dm-rq.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/ktime.h:262
Inline: True
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
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/core.c (ffffffff810bc598)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:262
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810d4752)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_rt_bandwidth
```
```
In kernel/sched/deadline.c (ffffffff810d563f)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/hrtimer.c (ffffffff819f0e4c)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (ffffffff8111799b)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/futex.c (ffffffff81129167)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/watchdog.c (ffffffff8116a1a5)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff811d6b18)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In block/cfq-iosched.c (ffffffff814b49ce)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
```
```
In drivers/md/dm-rq.c (ffffffff818164ac)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_old_request_fn
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8182d3d9)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In net/core/dev.c (ffffffff81895466)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff818cf4f1)
Location: include/linux/ktime.h:262
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff818ff093)
Location: include/linux/ktime.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
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
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/core.c (ffffffff810c4d78)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (0)
Location: include/linux/ktime.h:265
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810de182)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_rt_bandwidth
```
```
In kernel/sched/deadline.c (ffffffff810df06f)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/hrtimer.c (ffffffff81a2c1cc)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (ffffffff81122fbb)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/ktime.h:265
Inline: True
```
```
In kernel/futex.c (ffffffff81134657)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/watchdog.c (ffffffff8117719a)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff811e7158)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/base/power/runtime.c (ffffffff816ae92c)
Location: include/linux/ktime.h:265
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818593bc)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In net/core/dev.c (ffffffff818b70dd)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff818faac1)
Location: include/linux/ktime.h:265
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8192d43e)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81935225)
Location: include/linux/ktime.h:265
Inline: True
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
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:265
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810df5e8)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810e51b6)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_rt_bandwidth
```
```
In kernel/sched/deadline.c (ffffffff810e690f)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/hrtimer.c (ffffffff81a9c37e)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
```
```
In kernel/time/timekeeping.c (ffffffff8112d7a2)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/futex.c (ffffffff8113f61d)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/watchdog.c (ffffffff81183f7b)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff811fe773)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In drivers/base/power/runtime.c (ffffffff816e88f9)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8189cd00)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In net/core/dev.c (ffffffff81902ef1)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff8195a371)
Location: include/linux/ktime.h:265
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81990841)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81998be9)
Location: include/linux/ktime.h:265
Inline: True
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
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:265
Inline: True
```
```
In kernel/sched/idle.c (ffffffff810e0226)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (ffffffff810e9bf6)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810f0602)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/sched/deadline.c (ffffffff810f127f)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/hrtimer.c (ffffffff81ad3c47)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
```
```
In kernel/time/timekeeping.c (ffffffff81139712)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/futex.c (ffffffff8114b0cd)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/watchdog.c (ffffffff8118fdfb)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff8120b903)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In block/blk-iocost.c (ffffffff8150fc74)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/base/power/runtime.c (ffffffff8170c959)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818cf020)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/linux/ktime.h:265
Inline: True
```
```
In net/core/dev.c (ffffffff81935c85)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff81990811)
Location: include/linux/ktime.h:265
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819c4503)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819cf6fe)
Location: include/linux/ktime.h:265
Inline: True
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
Location: include/linux/ktime.h:221
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/core.c (ffffffff810df371)
Location: include/linux/ktime.h:221
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/idle.c (ffffffff810e8591)
Location: include/linux/ktime.h:221
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle_precise
```
```
In kernel/sched/fair.c (ffffffff810f4300)
Location: include/linux/ktime.h:221
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810f9b3f)
Location: include/linux/ktime.h:221
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_rt_bandwidth
```
```
In kernel/sched/deadline.c (ffffffff810fa6ef)
Location: include/linux/ktime.h:221
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/hrtimer.c (ffffffff81bcbc4f)
Location: include/linux/ktime.h:221
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (ffffffff81148921)
Location: include/linux/ktime.h:221
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/futex.c (ffffffff8115bc3d)
Location: include/linux/ktime.h:221
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/watchdog.c (ffffffff811a497b)
Location: include/linux/ktime.h:221
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff81235533)
Location: include/linux/ktime.h:221
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In block/blk-iocost.c (ffffffff81570d7a)
Location: include/linux/ktime.h:221
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/base/power/runtime.c (ffffffff817c7df8)
Location: include/linux/ktime.h:221
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a1805)
Location: include/linux/ktime.h:221
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/linux/ktime.h:221
Inline: True
```
```
In net/core/dev.c (ffffffff81a0a9e5)
Location: include/linux/ktime.h:221
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff81a680dd)
Location: include/linux/ktime.h:221
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81ab1869)
Location: include/linux/ktime.h:221
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81abfd84)
Location: include/linux/ktime.h:221
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/core.c (ffffffff810dc011)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/idle.c (ffffffff810e6198)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle_precise
```
```
In kernel/sched/fair.c (ffffffff810f2590)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810f7f1f)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_rt_bandwidth
```
```
In kernel/sched/deadline.c (ffffffff810f8b8f)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/hrtimer.c (ffffffff81c44a6f)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (ffffffff81144d91)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/futex.c (ffffffff8115781d)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/watchdog.c (ffffffff811a1a1b)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff8123dfe3)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In block/blk-iocost.c (ffffffff8158d311)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/base/power/runtime.c (ffffffff817dc826)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a4871)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/linux/ktime.h:222
Inline: True
```
```
In net/core/dev.c (ffffffff81a0c69e)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff81a707ed)
Location: include/linux/ktime.h:222
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81abc829)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81acb7ef)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/core.c (ffffffff810de031)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/idle.c (ffffffff810e8168)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle_precise
```
```
In kernel/sched/fair.c (ffffffff810f485d)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810fa086)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_rt_bandwidth
```
```
In kernel/sched/deadline.c (ffffffff810fac2f)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/hrtimer.c (ffffffff81c37cdc)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (ffffffff81145c81)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/futex.c (ffffffff81158c6d)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/watchdog.c (ffffffff811a26eb)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff81241223)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In block/blk-iocost.c (ffffffff815946f7)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/base/power/runtime.c (ffffffff817c0be6)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81989491)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/linux/ktime.h:222
Inline: True
```
```
In net/core/dev.c (ffffffff819f297e)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff81a590ed)
Location: include/linux/ktime.h:222
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81aa793a)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81ab69a4)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/core.c (ffffffff810f2ce8)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/idle.c (ffffffff810ff828)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle_precise
```
```
In kernel/sched/fair.c (ffffffff8110e22f)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff81114e6f)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_rt_bandwidth
```
```
In kernel/sched/deadline.c (ffffffff811165de)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/hrtimer.c (ffffffff81d5659c)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (ffffffff811693e7)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/futex.c (ffffffff8117db3d)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/watchdog.c (ffffffff811cbecb)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/bpf/helpers.c (ffffffff812503c2)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_timer_start
```
```
In kernel/events/core.c (ffffffff8127bc4b)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In block/blk-iocost.c (ffffffff815fbc07)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/base/power/runtime.c (ffffffff8184ca66)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/ptp/ptp_vclock.c (ffffffff819db181)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_convert_timestamp
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81a3394d)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/linux/ktime.h:222
Inline: True
```
```
In net/core/dev.c (ffffffff81aa484b)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff81b1228d)
Location: include/linux/ktime.h:222
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81b63023)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81b73adc)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/core.c (ffffffff8110eab4)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff81129f53)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/build_policy.c (ffffffff811304fe)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:sched_rt_handler
  - kernel/sched/build_policy.c:init_rt_bandwidth
  - kernel/sched/build_policy.c:play_idle_precise
```
```
In kernel/time/hrtimer.c (ffffffff81f28408)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (ffffffff8119d047)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/futex/core.c (ffffffff811b255a)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_setup_timer
```
```
In kernel/watchdog.c (ffffffff811ffc6a)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/bpf/helpers.c (ffffffff81297a12)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_timer_start
```
```
In kernel/events/core.c (ffffffff812cf9bd)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In fs/aio.c (ffffffff81461fd4)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-iocost.c (ffffffff816af1de)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8191fc3a)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
```
In drivers/base/power/runtime.c (ffffffff8198fd34)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81b3ea11)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_convert_timestamp
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81ba007d)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/linux/ktime.h:222
Inline: True
```
```
In net/core/dev.c (ffffffff81c1bfaa)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff81c9956d)
Location: include/linux/ktime.h:222
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81cf1cf7)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81d03159)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/core.c (ffffffff81135874)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff81153973)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/build_policy.c (ffffffff8115a03e)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:sched_rt_handler
  - kernel/sched/build_policy.c:init_rt_bandwidth
  - kernel/sched/build_policy.c:play_idle_precise
```
```
In kernel/time/hrtimer.c (ffffffff820d4058)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (ffffffff811dbaf7)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/futex/core.c (ffffffff811f33ea)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_setup_timer
```
```
In kernel/watchdog.c (ffffffff812476ca)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/bpf/helpers.c (ffffffff812f29c2)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_timer_start
```
```
In kernel/events/core.c (ffffffff8133950d)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In fs/aio.c (ffffffff814f2194)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-iocost.c (ffffffff8176e6fe)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7c20a)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
```
In drivers/base/power/runtime.c (ffffffff81affec4)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81cd4d49)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_convert_timestamp
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81d41bb0)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/linux/ktime.h:222
Inline: True
```
```
In net/core/dev.c (ffffffff81dccf7a)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff81e5585d)
Location: include/linux/ktime.h:222
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81eb6557)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81ec8122)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/core.c (ffffffff811449cd)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff8116350c)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/build_policy.c (ffffffff8116a24e)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:sched_rt_handler
  - kernel/sched/build_policy.c:init_rt_bandwidth
  - kernel/sched/build_policy.c:play_idle_precise
```
```
In kernel/time/hrtimer.c (ffffffff821582ae)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (ffffffff811f0037)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/futex/core.c (ffffffff81207b6a)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_setup_timer
```
```
In kernel/watchdog.c (ffffffff8125eafa)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/trace_osnoise.c (ffffffff81296b99)
Location: include/linux/ktime.h:222
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff8131f398)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_timer_start
```
```
In kernel/events/core.c (ffffffff8136900c)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In fs/aio.c (ffffffff81528dd4)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-iocost.c (ffffffff817ae27e)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81ac753a)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
```
In drivers/base/power/runtime.c (ffffffff81b4e22c)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/dma-fence-unwrap.c (0)
Location: include/linux/ktime.h:222
Inline: True
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81d3c9a9)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_convert_timestamp
```
```
In drivers/cpuidle/cpuidle.c (ffffffff82142334)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/linux/ktime.h:222
Inline: True
```
```
In net/core/dev.c (ffffffff81e3dada)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff81eb1100)
Location: include/linux/ktime.h:222
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81f14979)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81f26bb9)
Location: include/linux/ktime.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/core.c (ffffffff8114ff0f)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff8117024c)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/build_policy.c (ffffffff81177917)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:sched_rt_handler
  - kernel/sched/build_policy.c:init_rt_bandwidth
  - kernel/sched/build_policy.c:play_idle_precise
```
```
In kernel/time/hrtimer.c (ffffffff8223b11e)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (ffffffff81206177)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/futex/core.c (ffffffff8121ed7a)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_setup_timer
```
```
In kernel/watchdog.c (ffffffff81278b0a)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b21b9)
Location: include/linux/ktime.h:220
Inline: True
```
```
In kernel/bpf/helpers.c (ffffffff813417f5)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_timer_start
```
```
In kernel/events/core.c (ffffffff8139236c)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In fs/aio.c (ffffffff8155cff4)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-iocost.c (ffffffff817f208e)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1a9ca)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:__stop_tx_rs485
```
```
In drivers/base/power/runtime.c (ffffffff81ba67b3)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/dma-buf/dma-fence-unwrap.c (0)
Location: include/linux/ktime.h:220
Inline: True
```
```
In drivers/dma-buf/sync_file.c (ffffffff81c195bb)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb17fe)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_timeline_wait_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_wait_ioctl
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb4254)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_next_vblank_start
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81df32e9)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_convert_timestamp
```
```
In drivers/cpuidle/cpuidle.c (ffffffff82224a24)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/linux/ktime.h:220
Inline: True
```
```
In net/core/dev.c (ffffffff81efc37a)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff81f73ba0)
Location: include/linux/ktime.h:220
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81fd8ea4)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81feb5a1)
Location: include/linux/ktime.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In virt/kvm/arm/arch_timer.c (ffff8000100eccf0)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - virt/kvm/arm/arch_timer.c:kvm_hrtimer_expire
  - virt/kvm/arm/arch_timer.c:kvm_bg_timer_expire
```
```
In kernel/sched/core.c (ffff80001013873c)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/idle.c (ffff80001013ff34)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (ffff800010149ca4)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffff800010151d10)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/sched/deadline.c (ffff800010153e74)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/hrtimer.c (ffff800010da6808)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
```
```
In kernel/time/timekeeping.c (ffff8000101a34d8)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/time/sched_clock.c (ffff80001144921c)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:sched_clock_register
```
```
In kernel/futex.c (ffff8000101b9398)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/watchdog.c (ffff800010207620)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffff80001029aaa8)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In block/blk-iocost.c (ffff80001061546c)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/base/power/runtime.c (ffff8000108fbb34)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e66b8)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_hwtstamp
```
```
In drivers/media/cec/cec-pin.c (ffff800010ac4ab8)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
```
```
In drivers/cpuidle/cpuidle.c (ffff800010b26d94)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/linux/ktime.h:265
Inline: True
```
```
In drivers/perf/arm-ccn.c (ffff800010b9338c)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_timer_handler
```
```
In net/core/dev.c (ffff800010bd41b8)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffff800010c3c89c)
Location: include/linux/ktime.h:265
Inline: True
```
```
In net/ipv4/tcp_input.c (ffff800010c7b790)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffff800010c81e70)
Location: include/linux/ktime.h:265
Inline: True
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
In arch/arm/mach-imx/mmdc.c (c0333610)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_timer_handler
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_start
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:265
Inline: True
```
```
In kernel/sched/idle.c (c038fea8)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (c03979b8)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (c039efc4)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/sched/deadline.c (c03a09d0)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/hrtimer.c (c0e9e5e4)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
```
```
In kernel/time/timekeeping.c (c03ed5e8)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/time/sched_clock.c (c1523340)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:sched_clock_register
```
```
In kernel/futex.c (c04025a4)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/watchdog.c (c04463c8)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (c04c2b20)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In block/blk-iocost.c (c07be600)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/base/power/runtime.c (c09e76fc)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0ac8814)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_hwtstamp
```
```
In drivers/net/ethernet/ti/cpts.c (c0ad0dd0)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpts.c:cpts_tx_timestamp
  - drivers/net/ethernet/ti/cpts.c:cpts_rx_timestamp
  - drivers/net/ethernet/ti/cpts.c:cpts_fifo_read
```
```
In drivers/cpuidle/cpuidle.c (c0c01c10)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/firmware/tegra/bpmp.c (c0c41ee0)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic
```
```
In drivers/powercap/idle_inject.c (c0c7a1ec)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_start
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
```
In drivers/perf/arm-ccn.c (c0c7cff0)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_timer_handler
```
```
In sound/soc/fsl/imx-pcm-fiq.c (c0cc22ec)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - sound/soc/fsl/imx-pcm-fiq.c:snd_imx_pcm_trigger
  - sound/soc/fsl/imx-pcm-fiq.c:snd_hrtimer_callback
```
```
In net/core/dev.c (c0cef9c8)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (c0d4e770)
Location: include/linux/ktime.h:265
Inline: True
```
```
In net/ipv4/tcp_input.c (c0d8796c)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (c0d91170)
Location: include/linux/ktime.h:265
Inline: True
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
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:265
Inline: True
```
```
In kernel/sched/idle.c (c00000000018f13c)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (c00000000019bcec)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (c0000000001a569c)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/sched/deadline.c (c0000000001a7504)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/hrtimer.c (c000000000ee9028)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (c000000000204de0)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/futex.c (c00000000021e940)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/watchdog.c (c000000000283cf4)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (c000000000342ae4)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In block/blk-iocost.c (c0000000007b22cc)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/base/power/runtime.c (c00000000099a78c)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/cpuidle/cpuidle.c (c000000000c1ded0)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/linux/ktime.h:265
Inline: True
```
```
In net/core/dev.c (c000000000cb3190)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (c000000000d36654)
Location: include/linux/ktime.h:265
Inline: True
```
```
In net/ipv4/tcp_input.c (c000000000d7f12c)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (c000000000d8d570)
Location: include/linux/ktime.h:265
Inline: True
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
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:265
Inline: True
```
```
In kernel/sched/idle.c (ffffffe0000ee0f0)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (ffffffe0000f39fc)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffe0000f9ed2)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/sched/deadline.c (ffffffe0000fb6f8)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/hrtimer.c (ffffffe0008c8b94)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
```
In kernel/time/timekeeping.c (ffffffe0001300e0)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/time/sched_clock.c (ffffffe00000a6d0)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:sched_clock_register
```
```
In kernel/futex.c (ffffffe00013d104)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/watchdog.c (ffffffe000169db8)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffe0001c68b6)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In block/blk-iocost.c (ffffffe00044ae04)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/base/power/runtime.c (ffffffe00058ad4c)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In net/core/dev.c (ffffffe00075e14c)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffe0007ad0b6)
Location: include/linux/ktime.h:265
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffe0007da188)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffe0007e4144)
Location: include/linux/ktime.h:265
Inline: True
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
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:265
Inline: True
```
```
In kernel/sched/idle.c (ffffffff810da3d6)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (ffffffff810e3d56)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810e9aa6)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_rt_bandwidth
```
```
In kernel/sched/deadline.c (ffffffff810ea67f)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/hrtimer.c (ffffffff81a72ab7)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
```
```
In kernel/time/timekeeping.c (ffffffff81131ec2)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/futex.c (ffffffff811436ed)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/watchdog.c (ffffffff8118841b)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff81203f23)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In block/blk-iocost.c (ffffffff81508254)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/base/power/runtime.c (ffffffff816d20a9)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81872ae0)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
```
In net/core/dev.c (ffffffff818d5c55)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff81930681)
Location: include/linux/ktime.h:265
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81964373)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff8196f56e)
Location: include/linux/ktime.h:265
Inline: True
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
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:265
Inline: True
```
```
In kernel/sched/idle.c (ffffffff810c93e6)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (ffffffff810d2f06)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810d99c2)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/sched/deadline.c (ffffffff810da6af)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/hrtimer.c (ffffffff81a2ee87)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
```
```
In kernel/time/timekeeping.c (ffffffff81124922)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/futex.c (ffffffff811375ad)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/watchdog.c (ffffffff8117b55b)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff811f6cb3)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In block/blk-iocost.c (ffffffff814f8704)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/base/power/runtime.c (ffffffff816ad3a3)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8183c8c0)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In net/core/dev.c (ffffffff8188fac5)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff818ea181)
Location: include/linux/ktime.h:265
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8191de63)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff8192903e)
Location: include/linux/ktime.h:265
Inline: True
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
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/core.c (0)
Location: include/linux/ktime.h:265
Inline: True
```
```
In kernel/sched/idle.c (ffffffff810d6756)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (ffffffff810e0126)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810e6b32)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
```
In kernel/sched/deadline.c (ffffffff810e77af)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/hrtimer.c (ffffffff81adeec7)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
```
```
In kernel/time/timekeeping.c (ffffffff8112fbe2)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/futex.c (ffffffff8114159d)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/watchdog.c (ffffffff811861eb)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff81201cf3)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In block/blk-iocost.c (ffffffff815042e4)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/base/power/runtime.c (ffffffff81700619)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818c44d0)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/linux/ktime.h:265
Inline: True
```
```
In net/core/dev.c (ffffffff81926c85)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff81981811)
Location: include/linux/ktime.h:265
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819ceb43)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819d9d3e)
Location: include/linux/ktime.h:265
Inline: True
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
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_start
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/core.c (ffffffff810d9c13)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/idle.c (ffffffff810e205d)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/sched/fair.c (ffffffff810ebca6)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810f1b14)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:init_rt_bandwidth
```
```
In kernel/sched/deadline.c (ffffffff810f2daf)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/sched/deadline.c:start_dl_timer
```
```
In kernel/time/hrtimer.c (ffffffff81aeb357)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
```
```
In kernel/time/timekeeping.c (ffffffff8113c602)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:timekeeping_update
```
```
In kernel/futex.c (ffffffff8114e90d)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
```
```
In kernel/watchdog.c (ffffffff81193b3b)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff812113c3)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In block/blk-iocost.c (ffffffff8151d894)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - block/blk-iocost.c:iocg_kick_delay
  - block/blk-iocost.c:iocg_kick_waitq
```
```
In drivers/base/power/runtime.c (ffffffff8171b902)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/media/cec/cec-pin.c (ffffffff8188c3b4)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818e0850)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/linux/ktime.h:265
Inline: True
```
```
In net/core/dev.c (ffffffff819482d5)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/core/dev.c:napi_complete_done
```
```
In net/sched/sch_api.c (ffffffff819a3d91)
Location: include/linux/ktime.h:265
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819d86d3)
Location: include/linux/ktime.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819e399e)
Location: include/linux/ktime.h:265
Inline: True
```
</details>
</li>
</ul>

## Differences
