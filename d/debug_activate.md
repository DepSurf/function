# Function: <code>debug_activate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81823407)
Location: kernel/time/timer.c:662
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:mod_timer_pending
  - kernel/time/timer.c:mod_timer
```
```
In kernel/time/hrtimer.c (ffffffff810eea84)
Location: kernel/time/hrtimer.c:448
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8189def6)
Location: kernel/time/timer.c:770
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffff810f5ce4)
Location: kernel/time/hrtimer.c:444
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff818d2d6e)
Location: kernel/time/timer.c:770
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffff810fce14)
Location: kernel/time/hrtimer.c:444
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81909f53)
Location: kernel/time/timer.c:741
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffff810ff214)
Location: kernel/time/hrtimer.c:445
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81994306)
Location: kernel/time/timer.c:745
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffff81109ff4)
Location: kernel/time/hrtimer.c:445
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff819f0880)
Location: kernel/time/timer.c:762
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffff81115775)
Location: kernel/time/hrtimer.c:462
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a2bc00)
Location: kernel/time/timer.c:761
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:add_timer_on
  - kernel/time/timer.c:timer_reduce
  - kernel/time/timer.c:mod_timer_pending
```
```
In kernel/time/hrtimer.c (ffffffff81120e45)
Location: kernel/time/hrtimer.c:453
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112b5c5)
Location: kernel/time/hrtimer.c:452
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81137745)
Location: kernel/time/hrtimer.c:473
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81146365)
Location: kernel/time/hrtimer.c:473
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81142abe)
Location: kernel/time/hrtimer.c:472
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81143ade)
Location: kernel/time/hrtimer.c:472
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81166efe)
Location: kernel/time/hrtimer.c:472
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119a74e)
Location: kernel/time/hrtimer.c:472
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811d8eee)
Location: kernel/time/hrtimer.c:472
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811ed32e)
Location: kernel/time/hrtimer.c:474
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8120316e)
Location: kernel/time/hrtimer.c:474
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a0fec)
Location: kernel/time/hrtimer.c:473
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ea4d4)
Location: kernel/time/hrtimer.c:473
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000201844)
Location: kernel/time/hrtimer.c:473
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012e966)
Location: kernel/time/hrtimer.c:473
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112fef5)
Location: kernel/time/hrtimer.c:473
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81122965)
Location: kernel/time/hrtimer.c:473
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112dc15)
Location: kernel/time/hrtimer.c:473
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113a545)
Location: kernel/time/hrtimer.c:473
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
</details>
</li>
</ul>

## Differences
