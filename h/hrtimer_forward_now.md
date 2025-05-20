# Function: <code>hrtimer_forward_now</code>

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
In arch/x86/events/intel/cqm.c (ffffffff8100e2e4)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:mbm_hrtimer_handle
```
```
In arch/x86/events/intel/rapl.c (ffffffff81014d92)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - arch/x86/events/intel/rapl.c:rapl_hrtimer_handle
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016b19)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff810b3ea6)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810bfc93)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:enqueue_task_rt
```
```
In kernel/time/tick-sched.c (ffffffff810fefbd)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffff8113a9a8)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff8117b007)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_swevent_hrtimer
```
```
In fs/timerfd.c (ffffffff812584d2)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
```
In drivers/rtc/interface.c (ffffffff81675023)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff816eb8ba)
Location: include/linux/hrtimer.h:464
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
In arch/x86/events/intel/cqm.c (ffffffff8100dfcd)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:mbm_hrtimer_handle
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015d9a)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff810bfa33)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810c43ec)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff81106327)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffff81142ed8)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff8118abd5)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff81280f7e)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff816d57f3)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff817503a9)
Location: include/linux/hrtimer.h:464
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
In arch/x86/events/intel/cqm.c (ffffffff8100e08d)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:mbm_hrtimer_handle
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015f6a)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff810c58f3)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810ca443)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff8110daa3)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffff8114cbb1)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff8119a8f5)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff81294aaf)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff817054d3)
Location: include/linux/hrtimer.h:464
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff8177bf69)
Location: include/linux/hrtimer.h:464
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
In arch/x86/events/intel/uncore.c (ffffffff8101441a)
Location: include/linux/hrtimer.h:448
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff810bf4ac)
Location: include/linux/hrtimer.h:448
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810c3f8f)
Location: include/linux/hrtimer.h:448
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff8110f9a3)
Location: include/linux/hrtimer.h:448
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffff8114eb31)
Location: include/linux/hrtimer.h:448
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff811a346b)
Location: include/linux/hrtimer.h:448
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff812a1d3f)
Location: include/linux/hrtimer.h:448
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff8171af73)
Location: include/linux/hrtimer.h:448
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff8179aad2)
Location: include/linux/hrtimer.h:448
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
In arch/x86/events/intel/uncore.c (ffffffff81014c65)
Location: include/linux/hrtimer.h:448
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff810c6ccc)
Location: include/linux/hrtimer.h:448
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810cb762)
Location: include/linux/hrtimer.h:448
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff8111ac83)
Location: include/linux/hrtimer.h:448
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffff8115b381)
Location: include/linux/hrtimer.h:448
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff811b7431)
Location: include/linux/hrtimer.h:448
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff812c505f)
Location: include/linux/hrtimer.h:448
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff8178c213)
Location: include/linux/hrtimer.h:448
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff81810e98)
Location: include/linux/hrtimer.h:448
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
In arch/x86/events/intel/uncore.c (ffffffff810157dc)
Location: include/linux/hrtimer.h:470
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff810cebcc)
Location: include/linux/hrtimer.h:470
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810d30b2)
Location: include/linux/hrtimer.h:470
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff811279e4)
Location: include/linux/hrtimer.h:470
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffff81169f95)
Location: include/linux/hrtimer.h:470
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff811d6b35)
Location: include/linux/hrtimer.h:470
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff812ee116)
Location: include/linux/hrtimer.h:470
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff817ce643)
Location: include/linux/hrtimer.h:470
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff8185ad33)
Location: include/linux/hrtimer.h:470
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff81015efc)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff810d8153)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810dd2f2)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff811330d4)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffff81176e99)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff811e7175)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff81302ba6)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff817f5653)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff8187a133)
Location: include/linux/hrtimer.h:467
Inline: True
```
```
In drivers/powercap/idle_inject.c (ffffffff81883cbc)
Location: include/linux/hrtimer.h:467
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
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
In arch/x86/events/intel/uncore.c (ffffffff8101750a)
Location: include/linux/hrtimer.h:453
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff810df49a)
Location: include/linux/hrtimer.h:453
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810e42ba)
Location: include/linux/hrtimer.h:453
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff8113dc68)
Location: include/linux/hrtimer.h:453
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffff81183cf9)
Location: include/linux/hrtimer.h:453
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff811fe793)
Location: include/linux/hrtimer.h:453
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff813247f6)
Location: include/linux/hrtimer.h:453
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff81836313)
Location: include/linux/hrtimer.h:453
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff818bf6e3)
Location: include/linux/hrtimer.h:453
Inline: True
```
```
In drivers/powercap/idle_inject.c (ffffffff818ce3cc)
Location: include/linux/hrtimer.h:453
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
```
In net/xfrm/xfrm_state.c (ffffffff819f08a1)
Location: include/linux/hrtimer.h:453
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff81017eba)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff810e9bb6)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810ee859)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff8114981b)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffff8118fb69)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff8120b923)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff81337556)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff81867c83)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff818f2233)
Location: include/linux/hrtimer.h:502
Inline: True
```
```
In drivers/powercap/idle_inject.c (ffffffff819007bc)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
```
In net/xfrm/xfrm_state.c (ffffffff81a27771)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff81019a5a)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff810f423e)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810f8396)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff81158a9f)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_switch_to_nohz
```
```
In kernel/watchdog.c (ffffffff811a4796)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff8123710c)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff813708ce)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff8193b753)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff819c7bc3)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
```
In drivers/powercap/idle_inject.c (ffffffff819d77dc)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1949d)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff8101a0ca)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff810f24d2)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810f65a6)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff81154aa7)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_switch_to_nohz
```
```
In kernel/watchdog.c (ffffffff811a1836)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff81240ccd)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff8137e64d)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff81941ab3)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff819c7b16)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
```
In drivers/powercap/idle_inject.c (ffffffff819d691c)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2871d)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff8101b463)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff810f47a2)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810f85c3)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff81156b70)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffff811a2449)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff81244a74)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff813852cd)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff81925243)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff819aca56)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
```
In drivers/powercap/idle_inject.c (ffffffff819bca9c)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1630d)
Location: include/linux/hrtimer.h:507
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff8101dde1)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff8110e162)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff81113c46)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff8117b8fa)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffff811cbc29)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff8127fa14)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff813d254d)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff819c81d3)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff81a5af66)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
```
In drivers/powercap/idle_inject.c (ffffffff81a6bf59)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
```
In net/xfrm/xfrm_state.c (ffffffff81bda6bd)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff8102088b)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff81129e62)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/build_policy.c (ffffffff81131350)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff811b0f9a)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffff811ff9c8)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff812d4a68)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff8145c0f0)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff81b28fb3)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff81bca808)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
```
In drivers/powercap/idle_inject.c (ffffffff81bdca04)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
```
In net/xfrm/xfrm_state.c (ffffffff81d70689)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff810251eb)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff81153882)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/build_policy.c (ffffffff8115b2ca)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff811f1bda)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffff812473e8)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff8133d027)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff814eb7c0)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff81cbcb13)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff81d73ea8)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
```
In drivers/powercap/idle_inject.c (ffffffff81d87bce)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3c007)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff810250db)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff81163422)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/build_policy.c (ffffffff8116b501)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff81206385)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffff8125e4a8)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff8136e1a0)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff81522563)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff81d24423)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff81de1b42)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
```
In drivers/powercap/idle_inject.c (ffffffff81df61c7)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9b947)
Location: include/linux/hrtimer.h:503
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff8102b23b)
Location: include/linux/hrtimer.h:465
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff81170162)
Location: include/linux/hrtimer.h:465
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/build_policy.c (ffffffff81178dff)
Location: include/linux/hrtimer.h:465
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff8121d595)
Location: include/linux/hrtimer.h:465
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffff812783e8)
Location: include/linux/hrtimer.h:465
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff813972d0)
Location: include/linux/hrtimer.h:465
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff81556b83)
Location: include/linux/hrtimer.h:465
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff81dda183)
Location: include/linux/hrtimer.h:465
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff81e97b02)
Location: include/linux/hrtimer.h:465
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:txdone_hrtimer
```
```
In drivers/powercap/idle_inject.c (ffffffff81eac8b7)
Location: include/linux/hrtimer.h:465
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
```
In net/xfrm/xfrm_state.c (ffffffff82068ca7)
Location: include/linux/hrtimer.h:465
Inline: True
Inline callers:
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
In virt/kvm/arm/arch_timer.c (ffff8000100eccf0)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - virt/kvm/arm/arch_timer.c:kvm_hrtimer_expire
  - virt/kvm/arm/arch_timer.c:kvm_bg_timer_expire
```
```
In kernel/sched/fair.c (ffff800010149c60)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffff80001014f9dc)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/sched_clock.c (ffff8000101b4510)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:sched_clock_poll
```
```
In kernel/time/tick-sched.c (ffff8000101b5f34)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffff800010207320)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffff80001029aac0)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffff8000103f499c)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffff800010aa98a8)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/media/cec/cec-pin.c (ffff800010ac4bd8)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
```
```
In drivers/mailbox/mailbox.c (ffff800010b7a5ac)
Location: include/linux/hrtimer.h:502
Inline: True
```
```
In drivers/powercap/idle_inject.c (ffff800010b8ffec)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
```
In drivers/perf/arm-ccn.c (ffff800010b933a4)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_timer_handler
```
```
In net/xfrm/xfrm_state.c (ffff800010ce6a20)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
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
In arch/arm/mm/cache-l2x0-pmu.c (c0324be4)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_poll
```
```
In arch/arm/mach-imx/mmdc.c (c033362c)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_timer_handler
```
```
In kernel/sched/fair.c (c039795c)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (c039d190)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/sched_clock.c (c03fe118)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:sched_clock_poll
```
```
In kernel/time/tick-sched.c (c03ffedc)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (c044606c)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (c04c5098)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (c05c9a24)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (c0b88670)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (c0c600e8)
Location: include/linux/hrtimer.h:502
Inline: True
```
```
In drivers/powercap/idle_inject.c (c0c7a058)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
```
In drivers/perf/arm-ccn.c (c0c7d00c)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_timer_handler
```
```
In sound/soc/fsl/imx-pcm-fiq.c (c0cc24b8)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - sound/soc/fsl/imx-pcm-fiq.c:snd_hrtimer_callback
```
```
In net/xfrm/xfrm_state.c (c0ded3a4)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
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
In arch/powerpc/kernel/watchdog.c (c0000000000376dc)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/sched/fair.c (c00000000019bc98)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (c0000000001a30f0)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (c00000000021b960)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (c0000000002838fc)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (c000000000342af4)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (c0000000004fd588)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (c000000000b8b968)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (c000000000c59b40)
Location: include/linux/hrtimer.h:502
Inline: True
```
```
In drivers/powercap/idle_inject.c (c000000000c6f1e4)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
```
In net/xfrm/xfrm_state.c (c000000000e08184)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
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
In kernel/sched/fair.c (ffffffe0000f39c4)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffe0000f8248)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/sched_clock.c (ffffffe00013a8c4)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/time/sched_clock.c:sched_clock_poll
```
```
In kernel/time/tick-sched.c (ffffffe00013c03e)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffe000169a52)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffe0001c68c4)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffe0002a62f8)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_gettime
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffe0006b4f9e)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffe00072c45a)
Location: include/linux/hrtimer.h:502
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffe0008324da)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff81017eba)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff810e3d16)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810e86a8)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff81141e3b)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffff81188189)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff81203f43)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff8132fb36)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff8181a933)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff81893563)
Location: include/linux/hrtimer.h:502
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff819c6e01)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff810172ef)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff810d2ec6)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810d7c19)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff8113519b)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffff8117b2c9)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff811f6cd3)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff81320756)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff817e2023)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff8184ba63)
Location: include/linux/hrtimer.h:502
Inline: True
```
```
In net/xfrm/xfrm_state.c (ffffffff81983bf1)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff81017e7a)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff810e00e6)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810e4d89)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff8113fceb)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffff81185f59)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff81201d13)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff8132d606)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff8185be13)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/mailbox/mailbox.c (ffffffff818e7063)
Location: include/linux/hrtimer.h:502
Inline: True
```
```
In drivers/powercap/idle_inject.c (ffffffff818f11dc)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
```
In net/xfrm/xfrm_state.c (ffffffff81a31881)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
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
In arch/x86/events/intel/uncore.c (ffffffff810180ba)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
```
```
In kernel/sched/fair.c (ffffffff810ebc66)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_period_timer
```
```
In kernel/sched/rt.c (ffffffff810f1406)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_period_timer
```
```
In kernel/time/tick-sched.c (ffffffff8114c81b)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/watchdog.c (ffffffff811938a9)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/events/core.c (ffffffff812113e3)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
```
In fs/timerfd.c (ffffffff8133f2d6)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
```
In drivers/rtc/interface.c (ffffffff81876ff3)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
```
In drivers/media/cec/cec-pin.c (ffffffff8188c896)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
```
```
In drivers/mailbox/mailbox.c (ffffffff81903ce3)
Location: include/linux/hrtimer.h:502
Inline: True
```
```
In drivers/powercap/idle_inject.c (ffffffff8191225c)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3d181)
Location: include/linux/hrtimer.h:502
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
</details>
</li>
</ul>

## Differences
