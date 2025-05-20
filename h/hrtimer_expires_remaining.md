# Function: <code>hrtimer_expires_remaining</code>

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
In kernel/sched/fair.c (ffffffff810b701c)
Location: include/linux/hrtimer.h:271
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
```
In kernel/time/hrtimer.c (ffffffff810eed87)
Location: include/linux/hrtimer.h:271
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:update_rmtp
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff810bf970)
Location: include/linux/hrtimer.h:271
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff810f5e47)
Location: include/linux/hrtimer.h:271
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:update_rmtp
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff810c5830)
Location: include/linux/hrtimer.h:271
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff810fcf77)
Location: include/linux/hrtimer.h:271
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:update_rmtp
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff810bf3e1)
Location: include/linux/hrtimer.h:259
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff8190a39b)
Location: include/linux/hrtimer.h:259
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff810c6c01)
Location: include/linux/hrtimer.h:259
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff819946f3)
Location: include/linux/hrtimer.h:259
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff810ceafe)
Location: include/linux/hrtimer.h:283
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff819f0c85)
Location: include/linux/hrtimer.h:283
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff810d8082)
Location: include/linux/hrtimer.h:280
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff81a2c005)
Location: include/linux/hrtimer.h:280
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff810df3b7)
Location: include/linux/hrtimer.h:280
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff81a9c1b0)
Location: include/linux/hrtimer.h:280
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff810e9ae7)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff81ad3af2)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff810f4157)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/sched/fair.c:do_sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff81bcba87)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff810f23f7)
Location: include/linux/hrtimer.h:300
Inline: True
Inline callers:
  - kernel/sched/fair.c:do_sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff81c44912)
Location: include/linux/hrtimer.h:300
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff810f46dd)
Location: include/linux/hrtimer.h:300
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff81c37b82)
Location: include/linux/hrtimer.h:300
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff8110e09d)
Location: include/linux/hrtimer.h:300
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff81d563f7)
Location: include/linux/hrtimer.h:300
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff81129d9d)
Location: include/linux/hrtimer.h:300
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff81f285d3)
Location: include/linux/hrtimer.h:300
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff811537ad)
Location: include/linux/hrtimer.h:300
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff820d4224)
Location: include/linux/hrtimer.h:300
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff8116334d)
Location: include/linux/hrtimer.h:300
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff821584d8)
Location: include/linux/hrtimer.h:300
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff8117008d)
Location: include/linux/hrtimer.h:262
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff8223b348)
Location: include/linux/hrtimer.h:262
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffff800010149a54)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffff800010da6678)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (c03977dc)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (c0e9e42c)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (c00000000019baa4)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (c000000000ee8e58)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffe0000f38ae)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffe0008c8aa2)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff810e3c47)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff81a72962)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff810d2df7)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff81a2ed32)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff810e0017)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff81aded72)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
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
In kernel/sched/fair.c (ffffffff810ebb97)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/time/hrtimer.c (ffffffff81aeb1fd)
Location: include/linux/hrtimer.h:299
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/hrtimer.c:__hrtimer_get_remaining
```
</details>
</li>
</ul>

## Differences
