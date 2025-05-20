# Function: <code>hrtimer_cancel_wait_running</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81ad3cbb)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8113fc21)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff81140195)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff8114553b)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In fs/timerfd.c (ffffffff81336e9b)
Location: include/linux/hrtimer.h:366
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
In kernel/time/hrtimer.c (ffffffff81bcbca4)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8114eb0f)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff8114f585)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff81154b9e)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In fs/timerfd.c (ffffffff81370d5d)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
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
In kernel/time/hrtimer.c (ffffffff81c44ac4)
Location: include/linux/hrtimer.h:367
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8114ad7f)
Location: include/linux/hrtimer.h:367
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff8114b805)
Location: include/linux/hrtimer.h:367
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff81150e1e)
Location: include/linux/hrtimer.h:367
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In fs/timerfd.c (ffffffff8137eadb)
Location: include/linux/hrtimer.h:367
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
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
In kernel/time/hrtimer.c (ffffffff81c37d31)
Location: include/linux/hrtimer.h:367
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8114c23c)
Location: include/linux/hrtimer.h:367
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff8114ccb5)
Location: include/linux/hrtimer.h:367
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff8115224e)
Location: include/linux/hrtimer.h:367
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In fs/timerfd.c (ffffffff8138575b)
Location: include/linux/hrtimer.h:367
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
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
In kernel/time/hrtimer.c (ffffffff81d565f1)
Location: include/linux/hrtimer.h:363
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81170003)
Location: include/linux/hrtimer.h:363
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff81170b45)
Location: include/linux/hrtimer.h:363
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff8117681e)
Location: include/linux/hrtimer.h:363
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In fs/timerfd.c (ffffffff813d28d5)
Location: include/linux/hrtimer.h:363
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
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
In kernel/time/hrtimer.c (ffffffff81f28473)
Location: include/linux/hrtimer.h:363
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811a4543)
Location: include/linux/hrtimer.h:363
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff811a5155)
Location: include/linux/hrtimer.h:363
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff811abc9b)
Location: include/linux/hrtimer.h:363
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In fs/timerfd.c (ffffffff8145b13d)
Location: include/linux/hrtimer.h:363
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
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
In kernel/time/hrtimer.c (ffffffff820d40c3)
Location: include/linux/hrtimer.h:363
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811e3e63)
Location: include/linux/hrtimer.h:363
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff811e4a95)
Location: include/linux/hrtimer.h:363
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff811ebf3b)
Location: include/linux/hrtimer.h:363
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In fs/timerfd.c (ffffffff814ea74d)
Location: include/linux/hrtimer.h:363
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
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
In kernel/time/hrtimer.c (ffffffff82158304)
Location: include/linux/hrtimer.h:363
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811f84d3)
Location: include/linux/hrtimer.h:363
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff811f90f5)
Location: include/linux/hrtimer.h:363
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff8120066b)
Location: include/linux/hrtimer.h:363
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In fs/timerfd.c (ffffffff815214f0)
Location: include/linux/hrtimer.h:363
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
In kernel/time/hrtimer.c (ffffffff8223b174)
Location: include/linux/hrtimer.h:325
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8120e673)
Location: include/linux/hrtimer.h:325
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff8120f2e5)
Location: include/linux/hrtimer.h:325
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff81216b0b)
Location: include/linux/hrtimer.h:325
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In fs/timerfd.c (ffffffff81555b30)
Location: include/linux/hrtimer.h:325
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
In kernel/time/hrtimer.c (ffff800010da686c)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffff8000101a9834)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffff8000101aa598)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffff8000101afe48)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In fs/timerfd.c (ffff8000103f4cc8)
Location: include/linux/hrtimer.h:366
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
In kernel/time/hrtimer.c (c03eaca0)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_cancel
```
```
In kernel/time/alarmtimer.c (c03f3d38)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
  - kernel/time/alarmtimer.c:alarm_cancel
```
```
In kernel/time/posix-timers.c (c03f584c)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (c03fab18)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In fs/timerfd.c (c05c9c0c)
Location: include/linux/hrtimer.h:366
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
In kernel/time/hrtimer.c (c00000000020259c)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_cancel
```
```
In kernel/time/alarmtimer.c (c00000000020d510)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (c00000000020dd28)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (c000000000214790)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In fs/timerfd.c (c0000000004fcdd0)
Location: include/linux/hrtimer.h:366
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
In kernel/time/hrtimer.c (ffffffe0008c8bd8)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffe00013545a)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffe0001358d2)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffe00013911e)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In fs/timerfd.c (ffffffe0002a5ed2)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:__se_sys_timerfd_settime
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
In kernel/time/hrtimer.c (ffffffff81a72b2b)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811383d1)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff81138945)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff8113dceb)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In fs/timerfd.c (ffffffff8132f47b)
Location: include/linux/hrtimer.h:366
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
In kernel/time/hrtimer.c (ffffffff81a2eefb)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8112ae21)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff8112b395)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff81130815)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In fs/timerfd.c (ffffffff813200a5)
Location: include/linux/hrtimer.h:366
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
In kernel/time/hrtimer.c (ffffffff81adef3b)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811360f1)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff81136665)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff8113ba0b)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In fs/timerfd.c (ffffffff8132cf4b)
Location: include/linux/hrtimer.h:366
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
In kernel/time/hrtimer.c (ffffffff81aeb3cb)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:schedule_hrtimeout_range_clock
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81142b71)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_wait_running
```
```
In kernel/time/posix-timers.c (ffffffff81142fa5)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_timer_wait_running
```
```
In kernel/time/itimer.c (ffffffff811484d2)
Location: include/linux/hrtimer.h:366
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
```
```
In fs/timerfd.c (ffffffff8133fa50)
Location: include/linux/hrtimer.h:366
Inline: True
```
</details>
</li>
</ul>

## Differences
