# Function: <code>hrtimer_set_expires</code>

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
In kernel/sched/core.c (ffffffff810aa226)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
```
```
In kernel/time/posix-timers.c (ffffffff810f11c5)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/alarmtimer.c (ffffffff810fb104)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_fired
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff810fde6b)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/tick-sched.c (ffffffff810fe618)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_restart
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
```
In kernel/futex.c (ffffffff8110193c)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
```
```
In fs/timerfd.c (ffffffff81258936)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
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
In kernel/sched/core.c (ffffffff810ace86)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
```
```
In kernel/time/posix-timers.c (ffffffff810f8244)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/alarmtimer.c (ffffffff8110249a)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff811051fb)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
```
```
In kernel/time/tick-sched.c (ffffffff8110631f)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart
```
```
In kernel/futex.c (ffffffff81108e8c)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
```
```
In fs/timerfd.c (ffffffff81281260)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
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
In kernel/sched/core.c (ffffffff810b2f16)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
```
```
In kernel/time/alarmtimer.c (ffffffff8110446a)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffff81105b64)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_set
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff8110c94b)
Location: include/linux/hrtimer.h:209
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8110da9b)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart
```
```
In kernel/futex.c (ffffffff8111067c)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
```
```
In fs/timerfd.c (ffffffff81294d90)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In block/blk-mq.c (ffffffff81421ed9)
Location: include/linux/hrtimer.h:209
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid_sleep
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
In kernel/sched/core.c (ffffffff810aee36)
Location: include/linux/hrtimer.h:197
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
```
```
In kernel/time/alarmtimer.c (ffffffff81106517)
Location: include/linux/hrtimer.h:197
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffff8110751b)
Location: include/linux/hrtimer.h:197
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff8110e822)
Location: include/linux/hrtimer.h:197
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8110f99b)
Location: include/linux/hrtimer.h:197
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/futex.c (ffffffff81111b6f)
Location: include/linux/hrtimer.h:197
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
```
```
In fs/timerfd.c (ffffffff812a200d)
Location: include/linux/hrtimer.h:197
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In block/blk-mq.c (ffffffff81430707)
Location: include/linux/hrtimer.h:197
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
In kernel/sched/core.c (ffffffff810b607c)
Location: include/linux/hrtimer.h:197
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
```
```
In kernel/time/alarmtimer.c (ffffffff81111597)
Location: include/linux/hrtimer.h:197
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffff81112651)
Location: include/linux/hrtimer.h:197
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff81119ab2)
Location: include/linux/hrtimer.h:197
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8111ac7b)
Location: include/linux/hrtimer.h:197
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:__tick_nohz_idle_enter
```
```
In kernel/futex.c (ffffffff8111da6f)
Location: include/linux/hrtimer.h:197
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
```
```
In fs/timerfd.c (ffffffff812c532d)
Location: include/linux/hrtimer.h:197
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In block/blk-mq.c (ffffffff8145bbe3)
Location: include/linux/hrtimer.h:197
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
In kernel/sched/core.c (ffffffff810bded5)
Location: include/linux/hrtimer.h:223
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
```
```
In kernel/time/alarmtimer.c (ffffffff8111cf87)
Location: include/linux/hrtimer.h:223
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffff8111e0ce)
Location: include/linux/hrtimer.h:223
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff81126671)
Location: include/linux/hrtimer.h:223
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff811279d5)
Location: include/linux/hrtimer.h:223
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In kernel/futex.c (ffffffff8112a4b8)
Location: include/linux/hrtimer.h:223
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
```
```
In fs/timerfd.c (ffffffff812ee6a5)
Location: include/linux/hrtimer.h:223
Inline: True
```
```
In block/blk-mq.c (ffffffff8148f371)
Location: include/linux/hrtimer.h:223
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
In kernel/sched/core.c (ffffffff810c7185)
Location: include/linux/hrtimer.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
```
```
In kernel/time/alarmtimer.c (ffffffff81128737)
Location: include/linux/hrtimer.h:220
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffff8112992e)
Location: include/linux/hrtimer.h:220
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff81131d51)
Location: include/linux/hrtimer.h:220
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff811330c5)
Location: include/linux/hrtimer.h:220
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In kernel/futex.c (ffffffff81136028)
Location: include/linux/hrtimer.h:220
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
```
```
In fs/timerfd.c (ffffffff81303035)
Location: include/linux/hrtimer.h:220
Inline: True
```
```
In block/blk-mq.c (ffffffff814a8e3d)
Location: include/linux/hrtimer.h:220
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
In kernel/sched/core.c (ffffffff810cd695)
Location: include/linux/hrtimer.h:220
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
```
```
In kernel/time/alarmtimer.c (ffffffff8113317a)
Location: include/linux/hrtimer.h:220
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffff811343ae)
Location: include/linux/hrtimer.h:220
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-broadcast-hrtimer.c (ffffffff8113c881)
Location: include/linux/hrtimer.h:220
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8113dc57)
Location: include/linux/hrtimer.h:220
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In fs/timerfd.c (ffffffff81324244)
Location: include/linux/hrtimer.h:220
Inline: True
```
```
In block/blk-mq.c (ffffffff814d67ce)
Location: include/linux/hrtimer.h:220
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
In kernel/sched/core.c (ffffffff810d71c5)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
```
```
In kernel/time/alarmtimer.c (ffffffff8113f0da)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffff811403be)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-sched.c (ffffffff8114980a)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In fs/timerfd.c (ffffffff81336fa4)
Location: include/linux/hrtimer.h:239
Inline: True
```
```
In block/blk-mq.c (ffffffff814efb3e)
Location: include/linux/hrtimer.h:239
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
In kernel/sched/core.c (ffffffff810e1c05)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
```
```
In kernel/time/alarmtimer.c (ffffffff8114e824)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffff8114fc5e)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-sched.c (ffffffff81159614)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_switch_to_nohz
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
```
```
In fs/timerfd.c (ffffffff81370ea7)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In block/blk-mq.c (ffffffff8154ef5d)
Location: include/linux/hrtimer.h:239
Inline: True
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
In kernel/time/alarmtimer.c (ffffffff8114aa94)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffff8114bede)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-sched.c (ffffffff811555d2)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_switch_to_nohz
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
```
```
In fs/timerfd.c (ffffffff8137ec25)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In block/blk-mq.c (ffffffff8156cbc2)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
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
In kernel/time/alarmtimer.c (ffffffff8114bf54)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffff8114d38e)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-sched.c (ffffffff81156b66)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
```
```
In fs/timerfd.c (ffffffff813858a5)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In block/blk-mq.c (ffffffff81574a62)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
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
In kernel/time/alarmtimer.c (ffffffff8116fc9b)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffff8117174e)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-sched.c (ffffffff8117b8f2)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
```
```
In fs/timerfd.c (ffffffff813d2a1f)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In block/blk-mq.c (ffffffff815d8f86)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
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
In kernel/time/alarmtimer.c (ffffffff811a418b)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffff811a61b3)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-sched.c (ffffffff811b0f90)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
```
```
In fs/timerfd.c (ffffffff8145b282)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In block/blk-mq.c (ffffffff81686c91)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
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
In kernel/time/alarmtimer.c (ffffffff811e3a5b)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffff811e5cf3)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-sched.c (ffffffff811f1bd0)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
```
```
In fs/timerfd.c (ffffffff814ea892)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
```
```
In block/blk-mq.c (ffffffff81744961)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
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
In kernel/sched/fair.c (ffffffff8116395f)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_cfs_bandwidth
```
```
In kernel/time/alarmtimer.c (ffffffff811f80cb)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffff811fa171)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-sched.c (ffffffff8120637b)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_restart
```
```
In fs/timerfd.c (ffffffff81521635)
Location: include/linux/hrtimer.h:240
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
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
In kernel/sched/fair.c (ffffffff811706b2)
Location: include/linux/hrtimer.h:202
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_cfs_bandwidth
```
```
In kernel/time/alarmtimer.c (ffffffff8120e26b)
Location: include/linux/hrtimer.h:202
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffff81210361)
Location: include/linux/hrtimer.h:202
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-sched.c (ffffffff8121d58b)
Location: include/linux/hrtimer.h:202
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart_sched_tick
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In fs/timerfd.c (ffffffff81555c75)
Location: include/linux/hrtimer.h:202
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
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
In kernel/sched/core.c (ffff800010137cb4)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
```
```
In kernel/time/alarmtimer.c (ffff8000101a9274)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffff8000101aa6f8)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-sched.c (ffff8000101b5f34)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In fs/timerfd.c (ffff8000103f4e4c)
Location: include/linux/hrtimer.h:239
Inline: True
```
```
In block/blk-mq.c (ffff8000105ed928)
Location: include/linux/hrtimer.h:239
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
In kernel/sched/core.c (c0386758)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
```
```
In kernel/time/alarmtimer.c (c03f442c)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (c03f5c4c)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-sched.c (c03ffec8)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In fs/timerfd.c (c05c9d6c)
Location: include/linux/hrtimer.h:239
Inline: True
```
```
In block/blk-mq.c (c079b250)
Location: include/linux/hrtimer.h:239
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
In kernel/sched/core.c (c000000000183188)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
```
```
In kernel/time/alarmtimer.c (c00000000020c278)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (c00000000020e134)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-sched.c (c00000000021b954)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In fs/timerfd.c (c0000000004fcef0)
Location: include/linux/hrtimer.h:239
Inline: True
```
```
In block/blk-mq.c (c000000000785040)
Location: include/linux/hrtimer.h:239
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
In kernel/sched/core.c (ffffffe0000e7ee4)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
```
```
In kernel/time/alarmtimer.c (ffffffe00013499c)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffe000135b2c)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-sched.c (ffffffe00013c040)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In fs/timerfd.c (ffffffe0002a5faa)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_settime
```
```
In block/blk-mq.c (ffffffe00042e126)
Location: include/linux/hrtimer.h:239
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
In kernel/sched/core.c (ffffffff810d1695)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
```
```
In kernel/time/alarmtimer.c (ffffffff8113788a)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffff81138b6e)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-sched.c (ffffffff81141e2a)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In fs/timerfd.c (ffffffff8132f584)
Location: include/linux/hrtimer.h:239
Inline: True
```
```
In block/blk-mq.c (ffffffff814e811e)
Location: include/linux/hrtimer.h:239
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
In kernel/sched/core.c (ffffffff810bfc55)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
```
```
In kernel/time/alarmtimer.c (ffffffff8112a2da)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffff8112b5be)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-sched.c (ffffffff8113518a)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:tick_nohz_restart_sched_tick
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In fs/timerfd.c (ffffffff813201ae)
Location: include/linux/hrtimer.h:239
Inline: True
```
```
In block/blk-mq.c (ffffffff814d868e)
Location: include/linux/hrtimer.h:239
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
In kernel/sched/core.c (ffffffff810cf855)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
```
```
In kernel/time/alarmtimer.c (ffffffff811355aa)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffff8113688e)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-sched.c (ffffffff8113fcda)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In fs/timerfd.c (ffffffff8132d054)
Location: include/linux/hrtimer.h:239
Inline: True
```
```
In block/blk-mq.c (ffffffff814e41ae)
Location: include/linux/hrtimer.h:239
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
In kernel/sched/core.c (ffffffff810d8d75)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/sched/core.c:hrtick_start
```
```
In kernel/time/alarmtimer.c (ffffffff81141fda)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-timers.c (ffffffff8114331e)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_arm
```
```
In kernel/time/tick-sched.c (ffffffff8114c80a)
Location: include/linux/hrtimer.h:239
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_check_oneshot_change
  - kernel/time/tick-sched.c:tick_setup_sched_timer
  - kernel/time/tick-sched.c:__tick_nohz_idle_restart_tick
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In fs/timerfd.c (ffffffff8133fb59)
Location: include/linux/hrtimer.h:239
Inline: True
```
```
In block/blk-mq.c (ffffffff814fd72e)
Location: include/linux/hrtimer.h:239
Inline: True
```
</details>
</li>
</ul>

## Differences
