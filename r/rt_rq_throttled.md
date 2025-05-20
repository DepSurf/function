# Function: <code>rt_rq_throttled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:603
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:611
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:611
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:612
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:602
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:601
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:603
Inline: True
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
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:603
Inline: True
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
In kernel/sched/rt.c (ffffffff810ee549)
Location: kernel/sched/rt.c:523
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810f7a31)
Location: kernel/sched/rt.c:645
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:do_sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810f5c11)
Location: kernel/sched/rt.c:646
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:do_sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810f7f71)
Location: kernel/sched/rt.c:646
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:do_sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff81113593)
Location: kernel/sched/rt.c:657
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:do_sched_rt_period_timer
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
In kernel/sched/build_policy.c (ffffffff81130c77)
Location: kernel/sched/rt.c:693
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
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
In kernel/sched/build_policy.c (ffffffff8115ab77)
Location: kernel/sched/rt.c:693
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
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
In kernel/sched/build_policy.c (ffffffff81167bc1)
Location: kernel/sched/rt.c:693
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_is_throttled_rt
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
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
In kernel/sched/build_policy.c (ffffffff811749c1)
Location: kernel/sched/rt.c:649
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_is_throttled_rt
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
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
In kernel/sched/rt.c (ffff80001014f71c)
Location: kernel/sched/rt.c:523
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (c039cec4)
Location: kernel/sched/rt.c:523
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (c0000000001a2d64)
Location: kernel/sched/rt.c:523
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:enqueue_top_rt_rq
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffe0000f800c)
Location: kernel/sched/rt.c:523
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:604
Inline: True
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
In kernel/sched/rt.c (ffffffff810d7909)
Location: kernel/sched/rt.c:523
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810e4a79)
Location: kernel/sched/rt.c:523
Inline: True
Inline callers:
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:604
Inline: True
```
</details>
</li>
</ul>

## Differences
