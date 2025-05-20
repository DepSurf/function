# Function: <code>hrtimer_init_on_stack</code>

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
In kernel/time/hrtimer.c (ffffffff8182374a)
Location: include/linux/hrtimer.h:370
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:hrtimer_nanosleep
```
```
In kernel/futex.c (ffffffff81100386)
Location: include/linux/hrtimer.h:370
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_lock_pi
```
```
In fs/aio.c (ffffffff8125bf73)
Location: include/linux/hrtimer.h:370
Inline: True
Inline callers:
  - fs/aio.c:read_events
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
In kernel/time/hrtimer.c (ffffffff810f6c63)
Location: include/linux/hrtimer.h:370
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex.c (ffffffff81108e63)
Location: include/linux/hrtimer.h:370
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (ffffffff81284a23)
Location: include/linux/hrtimer.h:370
Inline: True
Inline callers:
  - fs/aio.c:read_events
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
In kernel/sched/idle.c (ffffffff810cdb92)
Location: include/linux/hrtimer.h:370
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/time/hrtimer.c (ffffffff810fdd1a)
Location: include/linux/hrtimer.h:370
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex.c (ffffffff81110653)
Location: include/linux/hrtimer.h:370
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (ffffffff812986ce)
Location: include/linux/hrtimer.h:370
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (ffffffff81421eb0)
Location: include/linux/hrtimer.h:370
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
In kernel/sched/idle.c (ffffffff810ca5a2)
Location: include/linux/hrtimer.h:354
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/time/hrtimer.c (ffffffff810fffd6)
Location: include/linux/hrtimer.h:354
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex.c (ffffffff81111b3f)
Location: include/linux/hrtimer.h:354
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (ffffffff812a61cc)
Location: include/linux/hrtimer.h:354
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (ffffffff814306ee)
Location: include/linux/hrtimer.h:354
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
In kernel/sched/idle.c (ffffffff810d1db2)
Location: include/linux/hrtimer.h:354
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/time/hrtimer.c (ffffffff8110adc6)
Location: include/linux/hrtimer.h:354
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/futex.c (ffffffff8111da3f)
Location: include/linux/hrtimer.h:354
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (ffffffff812c967f)
Location: include/linux/hrtimer.h:354
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (ffffffff8145bbca)
Location: include/linux/hrtimer.h:354
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
In kernel/sched/idle.c (ffffffff810c4557)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/time/hrtimer.c (ffffffff819f0e25)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/time/alarmtimer.c (ffffffff8111dafe)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
```
```
In kernel/futex.c (ffffffff8112a48f)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (ffffffff812f2560)
Location: include/linux/hrtimer.h:374
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (ffffffff8148f367)
Location: include/linux/hrtimer.h:374
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
In kernel/sched/idle.c (ffffffff810cd817)
Location: include/linux/hrtimer.h:371
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/time/hrtimer.c (ffffffff81a2c1a5)
Location: include/linux/hrtimer.h:371
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/time/alarmtimer.c (ffffffff811293fe)
Location: include/linux/hrtimer.h:371
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
```
```
In kernel/futex.c (ffffffff81135fff)
Location: include/linux/hrtimer.h:371
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (ffffffff81306f60)
Location: include/linux/hrtimer.h:371
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (ffffffff814a8e33)
Location: include/linux/hrtimer.h:371
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
In kernel/sched/idle.c (ffffffff810d5c07)
Location: include/linux/hrtimer.h:357
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/time/hrtimer.c (ffffffff81a9c345)
Location: include/linux/hrtimer.h:357
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/time/alarmtimer.c (ffffffff81133e60)
Location: include/linux/hrtimer.h:357
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
```
```
In kernel/futex.c (ffffffff811418cf)
Location: include/linux/hrtimer.h:357
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
```
```
In fs/aio.c (ffffffff81328530)
Location: include/linux/hrtimer.h:357
Inline: True
Inline callers:
  - fs/aio.c:read_events
```
```
In block/blk-mq.c (ffffffff814d67c4)
Location: include/linux/hrtimer.h:357
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
In kernel/sched/idle.c (ffffffff810e0207)
Location: include/linux/hrtimer.h:389
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/time/alarmtimer.c (ffffffff8113fe30)
Location: include/linux/hrtimer.h:389
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
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
In kernel/sched/idle.c (ffffffff810e8576)
Location: include/linux/hrtimer.h:389
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle_precise
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/hrtimer.h:389
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
In kernel/sched/idle.c (ffffffff810e617d)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle_precise
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/hrtimer.h:390
Inline: True
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
In kernel/sched/idle.c (ffffffff810e814d)
Location: include/linux/hrtimer.h:390
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle_precise
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/hrtimer.h:390
Inline: True
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
In kernel/sched/idle.c (ffffffff810ff80d)
Location: include/linux/hrtimer.h:386
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle_precise
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/hrtimer.h:386
Inline: True
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
In kernel/sched/build_policy.c (ffffffff81133843)
Location: include/linux/hrtimer.h:386
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:play_idle_precise
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/hrtimer.h:386
Inline: True
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
In kernel/sched/build_policy.c (ffffffff8115dc73)
Location: include/linux/hrtimer.h:386
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:play_idle_precise
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/hrtimer.h:386
Inline: True
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
In kernel/sched/build_policy.c (ffffffff8116e353)
Location: include/linux/hrtimer.h:386
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:play_idle_precise
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/hrtimer.h:386
Inline: True
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
In kernel/sched/build_policy.c (ffffffff8117b913)
Location: include/linux/hrtimer.h:348
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:play_idle_precise
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/hrtimer.h:348
Inline: True
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
In kernel/sched/idle.c (ffff80001013ff0c)
Location: include/linux/hrtimer.h:389
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/time/alarmtimer.c (ffff8000101a9a8c)
Location: include/linux/hrtimer.h:389
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
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
In kernel/sched/idle.c (c038fe7c)
Location: include/linux/hrtimer.h:389
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/time/alarmtimer.c (c03f54a4)
Location: include/linux/hrtimer.h:389
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
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
In kernel/sched/idle.c (c00000000018f118)
Location: include/linux/hrtimer.h:389
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/time/alarmtimer.c (c00000000020d7cc)
Location: include/linux/hrtimer.h:389
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
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
In kernel/sched/idle.c (ffffffe0000ee0b8)
Location: include/linux/hrtimer.h:389
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/time/alarmtimer.c (ffffffe000135616)
Location: include/linux/hrtimer.h:389
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
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
In kernel/sched/idle.c (ffffffff810da3b7)
Location: include/linux/hrtimer.h:389
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/time/alarmtimer.c (ffffffff811385e0)
Location: include/linux/hrtimer.h:389
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
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
In kernel/sched/idle.c (ffffffff810c93c7)
Location: include/linux/hrtimer.h:389
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/time/alarmtimer.c (ffffffff8112b030)
Location: include/linux/hrtimer.h:389
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
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
In kernel/sched/idle.c (ffffffff810d6737)
Location: include/linux/hrtimer.h:389
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/time/alarmtimer.c (ffffffff81136300)
Location: include/linux/hrtimer.h:389
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
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
In kernel/sched/idle.c (ffffffff810e203e)
Location: include/linux/hrtimer.h:389
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
```
```
In kernel/time/alarmtimer.c (ffffffff81142d80)
Location: include/linux/hrtimer.h:389
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
```
</details>
</li>
</ul>

## Differences
