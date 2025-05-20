# Function: <code>timerqueue_init_head</code>

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
In kernel/time/hrtimer.c (ffffffff81f7ffe0)
Location: include/linux/timerqueue.h:45
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
```
In kernel/time/alarmtimer.c (ffffffff81f8080e)
Location: include/linux/timerqueue.h:45
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffff81673a21)
Location: include/linux/timerqueue.h:45
Inline: True
Inline callers:
  - drivers/rtc/class.c:rtc_device_register
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
In kernel/time/hrtimer.c (ffffffff81fa9087)
Location: include/linux/timerqueue.h:45
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
```
In kernel/time/alarmtimer.c (ffffffff81fa9878)
Location: include/linux/timerqueue.h:45
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffff816d4201)
Location: include/linux/timerqueue.h:45
Inline: True
Inline callers:
  - drivers/rtc/class.c:rtc_device_register
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
In kernel/time/hrtimer.c (ffffffff81fe4f1f)
Location: include/linux/timerqueue.h:45
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
```
In kernel/time/alarmtimer.c (ffffffff81fe54c0)
Location: include/linux/timerqueue.h:45
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffff81703ee1)
Location: include/linux/timerqueue.h:45
Inline: True
Inline callers:
  - drivers/rtc/class.c:rtc_device_register
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
In kernel/time/hrtimer.c (ffffffff820c5bbe)
Location: include/linux/timerqueue.h:45
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
```
In kernel/time/alarmtimer.c (ffffffff820c6139)
Location: include/linux/timerqueue.h:45
Inline: True
```
```
In drivers/rtc/class.c (ffffffff817197cb)
Location: include/linux/timerqueue.h:45
Inline: True
Inline callers:
  - drivers/rtc/class.c:rtc_allocate_device
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
In kernel/time/hrtimer.c (ffffffff826ce255)
Location: include/linux/timerqueue.h:46
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
```
In kernel/time/alarmtimer.c (ffffffff826ce7da)
Location: include/linux/timerqueue.h:46
Inline: True
```
```
In drivers/rtc/class.c (ffffffff8178aa36)
Location: include/linux/timerqueue.h:46
Inline: True
Inline callers:
  - drivers/rtc/class.c:rtc_allocate_device
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
In kernel/time/hrtimer.c (ffffffff81116c09)
Location: include/linux/timerqueue.h:46
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (ffffffff826f8eed)
Location: include/linux/timerqueue.h:46
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffff817cbc0d)
Location: include/linux/timerqueue.h:46
Inline: True
Inline callers:
  - drivers/rtc/class.c:rtc_allocate_device
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
In kernel/time/hrtimer.c (ffffffff81122249)
Location: include/linux/timerqueue.h:46
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (ffffffff828afdc7)
Location: include/linux/timerqueue.h:46
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffff817f3259)
Location: include/linux/timerqueue.h:46
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
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
In kernel/time/hrtimer.c (ffffffff8112cb79)
Location: include/linux/timerqueue.h:46
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (ffffffff828c895f)
Location: include/linux/timerqueue.h:46
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffff81833ee2)
Location: include/linux/timerqueue.h:46
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
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
In kernel/time/hrtimer.c (ffffffff81138b59)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (ffffffff828d0f2a)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffff81865852)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
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
In kernel/time/hrtimer.c (ffffffff81147a38)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (ffffffff82cf1d59)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffff8193907d)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - drivers/rtc/class.c:rtc_allocate_device
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
In kernel/time/hrtimer.c (ffffffff81143ed3)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (ffffffff82fde80f)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffff8193f25d)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - drivers/rtc/class.c:rtc_allocate_device
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
In kernel/time/hrtimer.c (ffffffff81145063)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (ffffffff831e9338)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffff81922a87)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
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
In kernel/time/hrtimer.c (ffffffff811688c7)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (ffffffff832cd8e5)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffff819c5a37)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
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
In kernel/time/hrtimer.c (ffffffff8119c417)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (ffffffff8348154a)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffff81b261e3)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - drivers/rtc/class.c:rtc_allocate_device
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
In kernel/time/hrtimer.c (ffffffff811dadd7)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (ffffffff83eae5cb)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffff81cb9933)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - drivers/rtc/class.c:rtc_allocate_device
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
In kernel/time/hrtimer.c (ffffffff811ef2f2)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (ffffffff836d35ab)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffff81d21063)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - drivers/rtc/class.c:rtc_allocate_device
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
In kernel/time/hrtimer.c (ffffffff81205472)
Location: include/linux/timerqueue.h:45
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (ffffffff8390536b)
Location: include/linux/timerqueue.h:45
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffff81dd6dc2)
Location: include/linux/timerqueue.h:45
Inline: True
Inline callers:
  - drivers/rtc/class.c:rtc_allocate_device
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
In kernel/time/hrtimer.c (ffff8000101a26cc)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (ffff800011448f60)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffff800010aa6bc0)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
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
In kernel/time/hrtimer.c (c03ec3b0)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (c1523034)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (c0b856e0)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
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
In kernel/time/hrtimer.c (c000000000203c24)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (c00000000136e2fc)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (c000000000b882b8)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
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
In kernel/time/hrtimer.c (ffffffe00012f690)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (ffffffe00000a44e)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffe0006b3082)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
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
In kernel/time/hrtimer.c (ffffffff81131309)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (ffffffff828b9ddb)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffff81818502)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
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
In kernel/time/hrtimer.c (ffffffff81123d79)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (ffffffff828b232c)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffff817dfbf2)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
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
In kernel/time/hrtimer.c (ffffffff8112f029)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (ffffffff828ccb5e)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffff818599e2)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
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
In kernel/time/hrtimer.c (ffffffff8113ba29)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_prepare_cpu
```
```
In kernel/time/alarmtimer.c (ffffffff828d1f58)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
```
```
In drivers/rtc/class.c (ffffffff81874ac2)
Location: include/linux/timerqueue.h:56
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_allocate_device
```
</details>
</li>
</ul>

## Differences
