# Function: <code>hrtimer_forward</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810eeb60)
Location: kernel/time/hrtimer.c:833
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:mbm_hrtimer_handle
  - arch/x86/events/intel/rapl.c:rapl_hrtimer_handle
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:do_schedule_next_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_swevent_hrtimer
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
**Symbols:**

```
ffffffff810eeb60-ffffffff810eec91: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810f5ba0)
Location: kernel/time/hrtimer.c:823
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:mbm_hrtimer_handle
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:do_schedule_next_timer
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
**Symbols:**

```
ffffffff810f5ba0-ffffffff810f5cd0: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fcc50)
Location: kernel/time/hrtimer.c:823
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:mbm_hrtimer_handle
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_timer_get
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:do_schedule_next_timer
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
**Symbols:**

```
ffffffff810fcc50-ffffffff810fcd85: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fef30)
Location: kernel/time/hrtimer.c:796
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
**Symbols:**

```
ffffffff810fef30-ffffffff810ff011: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81109d10)
Location: kernel/time/hrtimer.c:796
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
**Symbols:**

```
ffffffff81109d10-ffffffff81109df7: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811152e0)
Location: kernel/time/hrtimer.c:907
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
```
**Symbols:**

```
ffffffff811152e0-ffffffff811153c5: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81120920)
Location: kernel/time/hrtimer.c:898
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
```
**Symbols:**

```
ffffffff81120920-ffffffff81120a05: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/hrtimer.c (0)
Location: kernel/time/hrtimer.c:897
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff8112cd77-ffffffff8112cd8a: hrtimer_forward.cold (STB_LOCAL)
ffffffff8112b6b0-ffffffff8112b760: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811371b0)
Location: kernel/time/hrtimer.c:918
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff811371b0-ffffffff81137258: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81145f00)
Location: kernel/time/hrtimer.c:918
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_switch_to_nohz
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
  - drivers/mailbox/mailbox.c:txdone_hrtimer
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff81145f00-ffffffff81145fab: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81142420)
Location: kernel/time/hrtimer.c:935
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_switch_to_nohz
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
  - drivers/mailbox/mailbox.c:txdone_hrtimer
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff81142420-ffffffff811424cb: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81143600)
Location: kernel/time/hrtimer.c:935
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
  - drivers/mailbox/mailbox.c:txdone_hrtimer
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff81143600-ffffffff811436ab: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81166be0)
Location: kernel/time/hrtimer.c:1037
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
  - drivers/mailbox/mailbox.c:txdone_hrtimer
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff81166be0-ffffffff81166c8b: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119a350)
Location: kernel/time/hrtimer.c:1037
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
  - drivers/mailbox/mailbox.c:txdone_hrtimer
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff8119a350-ffffffff8119a42e: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811d8a70)
Location: kernel/time/hrtimer.c:1037
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
  - drivers/mailbox/mailbox.c:txdone_hrtimer
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff811d8a70-ffffffff811d8b4e: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811ecea0)
Location: kernel/time/hrtimer.c:1040
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
  - drivers/mailbox/mailbox.c:txdone_hrtimer
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff811ecea0-ffffffff811ecf7e: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81203000)
Location: kernel/time/hrtimer.c:1040
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_highres_handler
  - kernel/time/tick-sched.c:tick_nohz_lowres_handler
  - kernel/time/tick-sched.c:tick_nohz_restart_sched_tick
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
  - drivers/mailbox/mailbox.c:txdone_hrtimer
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff81203000-ffffffff812030de: hrtimer_forward (STB_GLOBAL)
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
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a0688)
Location: kernel/time/hrtimer.c:918
Inline: False
Direct callers:
  - virt/kvm/arm/arch_timer.c:kvm_hrtimer_expire
  - virt/kvm/arm/arch_timer.c:kvm_bg_timer_expire
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/sched_clock.c:sched_clock_poll
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffff8000101a0688-ffff8000101a0774: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03eb844)
Location: kernel/time/hrtimer.c:918
Inline: False
Direct callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_poll
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_timer_handler
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/sched_clock.c:sched_clock_poll
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_timer_handler
  - sound/soc/fsl/imx-pcm-fiq.c:snd_hrtimer_callback
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
c03eb844-c03eba4c: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000201fd0)
Location: kernel/time/hrtimer.c:918
Inline: False
Direct callers:
  - arch/powerpc/kernel/watchdog.c:watchdog_timer_fn
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
c000000000201fd0-c0000000002020d8: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012df38)
Location: kernel/time/hrtimer.c:918
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/sched_clock.c:sched_clock_poll
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:__se_sys_timerfd_gettime
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffe00012df38-ffffffe00012dfe8: hrtimer_forward (STB_GLOBAL)
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
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112f960)
Location: kernel/time/hrtimer.c:918
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff8112f960-ffffffff8112fa08: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811223d0)
Location: kernel/time/hrtimer.c:918
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:tick_nohz_restart_sched_tick
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff811223d0-ffffffff81122478: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112d680)
Location: kernel/time/hrtimer.c:918
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff8112d680-ffffffff8112d728: hrtimer_forward (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 hrtimer_forward(struct hrtimer *timer, ktime_t now, ktime_t interval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81139fb0)
Location: kernel/time/hrtimer.c:918
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer
  - kernel/signal.c:dequeue_signal
  - kernel/sched/fair.c:sched_cfs_period_timer
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/time/posix-timers.c:common_hrtimer_forward
  - kernel/time/posix-timers.c:posix_timer_fn
  - kernel/time/posix-timers.c:common_hrtimer_rearm
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_handler
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_mux_hrtimer_restart
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
  - drivers/rtc/interface.c:rtc_pie_update_irq
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/powercap/idle_inject.c:idle_inject_timer_fn
  - net/xfrm/xfrm_state.c:xfrm_timer_handler
```
**Symbols:**

```
ffffffff81139fb0-ffffffff8113a058: hrtimer_forward (STB_GLOBAL)
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
