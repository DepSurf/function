# Function: <code>hrtimer_callback_running</code>

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
In kernel/sched/fair.c (ffffffff810b6ffa)
Location: include/linux/hrtimer.h:439
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
```
In kernel/time/hrtimer.c (ffffffff810eefa5)
Location: include/linux/hrtimer.h:439
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff810bf959)
Location: include/linux/hrtimer.h:439
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff810f6f95)
Location: include/linux/hrtimer.h:439
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff810c5819)
Location: include/linux/hrtimer.h:439
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff810fe055)
Location: include/linux/hrtimer.h:439
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff810bf3c6)
Location: include/linux/hrtimer.h:423
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff8110038f)
Location: include/linux/hrtimer.h:423
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff810c6be6)
Location: include/linux/hrtimer.h:423
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff8110b18f)
Location: include/linux/hrtimer.h:423
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff810ceae6)
Location: include/linux/hrtimer.h:445
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff81116cfd)
Location: include/linux/hrtimer.h:445
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff810d806e)
Location: include/linux/hrtimer.h:442
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff8112233d)
Location: include/linux/hrtimer.h:442
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff810df3a5)
Location: include/linux/hrtimer.h:428
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff8112cc9c)
Location: include/linux/hrtimer.h:428
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff810e9ad5)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff81138c7c)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff810f414c)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/sched/fair.c:do_sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff81147b92)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff810f23ec)
Location: include/linux/hrtimer.h:482
Inline: True
Inline callers:
  - kernel/sched/fair.c:do_sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff81144024)
Location: include/linux/hrtimer.h:482
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff810f46d3)
Location: include/linux/hrtimer.h:482
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff811451b4)
Location: include/linux/hrtimer.h:482
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff8110e093)
Location: include/linux/hrtimer.h:478
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff81168a14)
Location: include/linux/hrtimer.h:478
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff81129d93)
Location: include/linux/hrtimer.h:478
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff8119c561)
Location: include/linux/hrtimer.h:478
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_try_to_cancel
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff811537a3)
Location: include/linux/hrtimer.h:478
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff811daf31)
Location: include/linux/hrtimer.h:478
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_try_to_cancel
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff81163343)
Location: include/linux/hrtimer.h:478
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff811ef45b)
Location: include/linux/hrtimer.h:478
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff81170083)
Location: include/linux/hrtimer.h:440
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff812055e3)
Location: include/linux/hrtimer.h:440
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_cpu_dying
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffff800010149a38)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffff8000101a2854)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/sched/fair.c (c03977c8)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (c03ec524)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/sched/fair.c (c00000000019ba80)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (c000000000203d80)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffe0000f38a0)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffe00012ed02)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff810e3c35)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff8113142c)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff810d2de5)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff81123e96)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff810e0005)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff8112f14c)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
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
In kernel/sched/fair.c (ffffffff810ebb85)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff8113bb4f)
Location: include/linux/hrtimer.h:477
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
```
</details>
</li>
</ul>

## Differences
