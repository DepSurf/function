# Function: <code>timerqueue_init</code>

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
In kernel/time/hrtimer.c (ffffffff810eeced)
Location: include/linux/timerqueue.h:40
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffff810fa94f)
Location: include/linux/timerqueue.h:40
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_create
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
```
```
In drivers/rtc/interface.c (ffffffff81675286)
Location: include/linux/timerqueue.h:40
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff810f5da3)
Location: include/linux/timerqueue.h:40
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffff811027f5)
Location: include/linux/timerqueue.h:40
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In drivers/rtc/interface.c (ffffffff816d5a56)
Location: include/linux/timerqueue.h:40
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff810fced3)
Location: include/linux/timerqueue.h:40
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffff81105115)
Location: include/linux/timerqueue.h:40
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In drivers/rtc/interface.c (ffffffff81705736)
Location: include/linux/timerqueue.h:40
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff810ff2e6)
Location: include/linux/timerqueue.h:40
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffff81107145)
Location: include/linux/timerqueue.h:40
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In drivers/rtc/interface.c (ffffffff8171b1d6)
Location: include/linux/timerqueue.h:40
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff8110a0bd)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffff81112275)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In drivers/rtc/interface.c (ffffffff8178c476)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff811158e5)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffff8111db23)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In drivers/rtc/interface.c (ffffffff817ce9f5)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff81120fb5)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffff81129423)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In drivers/rtc/interface.c (ffffffff817f5b35)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff8112b7f1)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffff81133e83)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In drivers/rtc/interface.c (ffffffff818367f5)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff811378c6)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffff8113fe53)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811432e6)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
```
```
In drivers/rtc/interface.c (ffffffff81868165)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff811462d5)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffff8114efdd)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811528ba)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In drivers/rtc/interface.c (ffffffff8193bc85)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff811427f5)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffff8114b2fd)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114eb0a)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In drivers/rtc/interface.c (ffffffff81941f55)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff811439c3)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffff8114c7bd)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114ff9a)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In drivers/rtc/interface.c (ffffffff819256e5)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff81166dbf)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffff81170707)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8117418a)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In drivers/rtc/interface.c (ffffffff819c8665)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff81f2873a)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/time/alarmtimer.c (ffffffff811a4cbb)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811a8ec1)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In drivers/rtc/interface.c (ffffffff81b29575)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff820d437a)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
```
```
In kernel/time/alarmtimer.c (ffffffff811e45bb)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811e8d31)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In drivers/rtc/interface.c (ffffffff81cbd125)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff811ed140)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffff811f8c1b)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fd801)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In drivers/rtc/interface.c (ffffffff81d24a35)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff81203370)
Location: include/linux/timerqueue.h:30
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffff8120edbb)
Location: include/linux/timerqueue.h:30
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81213a01)
Location: include/linux/timerqueue.h:30
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In drivers/rtc/interface.c (ffffffff81dda795)
Location: include/linux/timerqueue.h:30
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffff8000101a0df0)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffff8000101a9ab8)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ad400)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
```
```
In drivers/rtc/interface.c (ffff800010aa9e0c)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (c03ea9e8)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (c03f54c8)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In kernel/time/posix-cpu-timers.c (c03f8388)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In drivers/rtc/interface.c (c0b88c60)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (c0000000002021ac)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (c00000000020d800)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In kernel/time/posix-cpu-timers.c (c0000000002116f0)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
```
```
In drivers/rtc/interface.c (c000000000b8bfe8)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffe00012e52a)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffe000135640)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffe0001373e6)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:do_cpu_nanosleep
```
```
In drivers/rtc/interface.c (ffffffe0006b5404)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff81130076)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffff81138603)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113ba96)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
```
```
In drivers/rtc/interface.c (ffffffff8181ae15)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff81122ae6)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffff8112b053)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112e456)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
```
```
In drivers/rtc/interface.c (ffffffff817e2505)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff8112dd96)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffff81136323)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811397b6)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
```
```
In drivers/rtc/interface.c (ffffffff8185c2f5)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
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
In kernel/time/hrtimer.c (ffffffff8113a6e6)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_init
```
```
In kernel/time/alarmtimer.c (ffffffff81142da3)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/time/alarmtimer.c:alarm_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81146286)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:process_cpu_timer_create
```
```
In drivers/rtc/interface.c (ffffffff81877555)
Location: include/linux/timerqueue.h:41
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_init
```
</details>
</li>
</ul>

## Differences
