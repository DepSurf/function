# Function: <code>hrtimer_restart</code>

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
In kernel/softirq.c (ffffffff81084e0b)
Location: include/linux/hrtimer.h:410
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
```
```
In kernel/signal.c (ffffffff8108d76a)
Location: include/linux/hrtimer.h:410
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/posix-timers.c (ffffffff810f1331)
Location: include/linux/hrtimer.h:410
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_schedule_next_timer
```
```
In kernel/time/alarmtimer.c (ffffffff810fb193)
Location: include/linux/hrtimer.h:410
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In fs/timerfd.c (ffffffff812584f0)
Location: include/linux/hrtimer.h:410
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:do_timerfd_gettime
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
In kernel/softirq.c (ffffffff8108811b)
Location: include/linux/hrtimer.h:410
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
```
```
In kernel/signal.c (ffffffff81090638)
Location: include/linux/hrtimer.h:410
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/posix-timers.c (ffffffff810f83b1)
Location: include/linux/hrtimer.h:410
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_schedule_next_timer
```
```
In kernel/time/alarmtimer.c (ffffffff81102493)
Location: include/linux/hrtimer.h:410
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In fs/timerfd.c (ffffffff81280f9e)
Location: include/linux/hrtimer.h:410
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/softirq.c (ffffffff8108d07b)
Location: include/linux/hrtimer.h:410
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
```
```
In kernel/signal.c (ffffffff810955b0)
Location: include/linux/hrtimer.h:410
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffff81104463)
Location: include/linux/hrtimer.h:410
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff81105d43)
Location: include/linux/hrtimer.h:410
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_schedule_next_timer
```
```
In fs/timerfd.c (ffffffff81294ad2)
Location: include/linux/hrtimer.h:410
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/softirq.c (ffffffff81089e68)
Location: include/linux/hrtimer.h:394
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
```
```
In kernel/signal.c (ffffffff81092848)
Location: include/linux/hrtimer.h:394
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffff81106510)
Location: include/linux/hrtimer.h:394
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff8110758d)
Location: include/linux/hrtimer.h:394
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffffffff812a1d62)
Location: include/linux/hrtimer.h:394
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/softirq.c (ffffffff81090baa)
Location: include/linux/hrtimer.h:394
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
```
```
In kernel/signal.c (ffffffff810996d7)
Location: include/linux/hrtimer.h:394
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffff81111590)
Location: include/linux/hrtimer.h:394
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff811126bc)
Location: include/linux/hrtimer.h:394
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffffffff812c5083)
Location: include/linux/hrtimer.h:394
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/softirq.c (ffffffff8109475d)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
```
```
In kernel/signal.c (ffffffff8109d7cc)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffff8111cf8f)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff8111e150)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffffffff812ee151)
Location: include/linux/hrtimer.h:415
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/softirq.c (ffffffff8109cabd)
Location: include/linux/hrtimer.h:412
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hrtimer_trampoline
```
```
In kernel/signal.c (ffffffff810a5a41)
Location: include/linux/hrtimer.h:412
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffff8112873f)
Location: include/linux/hrtimer.h:412
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff811299ab)
Location: include/linux/hrtimer.h:412
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffffffff81302be1)
Location: include/linux/hrtimer.h:412
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff810aa710)
Location: include/linux/hrtimer.h:398
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffff81133184)
Location: include/linux/hrtimer.h:398
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff8113442b)
Location: include/linux/hrtimer.h:398
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffffffff81324831)
Location: include/linux/hrtimer.h:398
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff810b0d12)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffff8113f0e4)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff8114043b)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffffffff81337591)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff810b9046)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffff8114e82c)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff811501fb)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffffffff81370906)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff810b42f6)
Location: include/linux/hrtimer.h:442
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffff8114aa9c)
Location: include/linux/hrtimer.h:442
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff8114c47b)
Location: include/linux/hrtimer.h:442
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffffffff8137e689)
Location: include/linux/hrtimer.h:442
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff810b5f06)
Location: include/linux/hrtimer.h:442
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffff8114bf5c)
Location: include/linux/hrtimer.h:442
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff8114d93b)
Location: include/linux/hrtimer.h:442
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffffffff81385309)
Location: include/linux/hrtimer.h:442
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff810c8d95)
Location: include/linux/hrtimer.h:438
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffff8116fca3)
Location: include/linux/hrtimer.h:438
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff811717cb)
Location: include/linux/hrtimer.h:438
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffffffff813d2589)
Location: include/linux/hrtimer.h:438
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff810e0327)
Location: include/linux/hrtimer.h:438
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffff811a4193)
Location: include/linux/hrtimer.h:438
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff811a628b)
Location: include/linux/hrtimer.h:438
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffffffff8145c12c)
Location: include/linux/hrtimer.h:438
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff811009b7)
Location: include/linux/hrtimer.h:438
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffff811e3a63)
Location: include/linux/hrtimer.h:438
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff811e5ddb)
Location: include/linux/hrtimer.h:438
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffffffff814eb7fc)
Location: include/linux/hrtimer.h:438
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff8110caba)
Location: include/linux/hrtimer.h:438
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffff811f80d3)
Location: include/linux/hrtimer.h:438
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff811fa25b)
Location: include/linux/hrtimer.h:438
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffffffff8152259f)
Location: include/linux/hrtimer.h:438
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff8111649a)
Location: include/linux/hrtimer.h:400
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffff8120e273)
Location: include/linux/hrtimer.h:400
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff8121044b)
Location: include/linux/hrtimer.h:400
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffffffff81556bbf)
Location: include/linux/hrtimer.h:400
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffff80001010b900)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffff8000101a9278)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffff8000101aa794)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffff8000103f49d4)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (c0364b10)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (c03f442c)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (c03f5d0c)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (c05c9a68)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (c0000000001535dc)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (c00000000020c288)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (c00000000020e23c)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (c0000000004fd5d8)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffe0000cdee0)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffe000134998)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffe000135b98)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffffffe0002a630e)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff810ab082)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffff81137894)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff81138beb)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffffffff8132fb71)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff81099a22)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffff8112a2e4)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff8112b63b)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffffffff81320791)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff810aa5e2)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffff811355b4)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff8113690b)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffffffff8132d641)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
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
In kernel/signal.c (ffffffff810b26c0)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
```
```
In kernel/time/alarmtimer.c (ffffffff81141fe4)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_restart
```
```
In kernel/time/posix-timers.c (ffffffff8114339b)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:common_hrtimer_rearm
```
```
In fs/timerfd.c (ffffffff8133f311)
Location: include/linux/hrtimer.h:441
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:timerfd_read
```
</details>
</li>
</ul>

## Differences
