# Function: <code>rq_of_rt_rq</code>

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
In kernel/sched/rt.c (ffffffff810c0c83)
Location: kernel/sched/rt.c:234
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_irq_work_func
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
In kernel/sched/rt.c (ffffffff810c4704)
Location: kernel/sched/rt.c:242
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_irq_work_func
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
In kernel/sched/rt.c (ffffffff810ca754)
Location: kernel/sched/rt.c:242
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_irq_work_func
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
In kernel/sched/rt.c (ffffffff810c426c)
Location: kernel/sched/rt.c:243
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_irq_work_func
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
Location: kernel/sched/rt.c:233
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
In kernel/sched/rt.c (ffffffff810d3284)
Location: kernel/sched/rt.c:229
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810dcf24)
Location: kernel/sched/rt.c:231
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (ffffffff810e3ee4)
Location: kernel/sched/rt.c:231
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:121
Inline: True
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
In kernel/sched/rt.c (ffffffff810f7744)
Location: kernel/sched/rt.c:234
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:enqueue_top_rt_rq
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:__disable_runtime
  - kernel/sched/rt.c:do_balance_runtime
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
In kernel/sched/rt.c (ffffffff810f5781)
Location: kernel/sched/rt.c:234
Inline: True
Inline callers:
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:enqueue_top_rt_rq
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:__disable_runtime
  - kernel/sched/rt.c:do_balance_runtime
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
In kernel/sched/rt.c (ffffffff810f78c7)
Location: kernel/sched/rt.c:234
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:enqueue_top_rt_rq
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:__disable_runtime
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
In kernel/sched/rt.c (ffffffff81113ae1)
Location: kernel/sched/rt.c:243
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:enqueue_top_rt_rq
  - kernel/sched/rt.c:dequeue_top_rt_rq
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:do_sched_rt_period_timer
  - kernel/sched/rt.c:__disable_runtime
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
In kernel/sched/build_policy.c (ffffffff81130c55)
Location: kernel/sched/rt.c:290
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
  - kernel/sched/build_policy.c:dequeue_top_rt_rq
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
In kernel/sched/build_policy.c (ffffffff8115ab55)
Location: kernel/sched/rt.c:290
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
  - kernel/sched/build_policy.c:dequeue_top_rt_rq
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
In kernel/sched/build_policy.c (ffffffff8116ad65)
Location: kernel/sched/rt.c:290
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
  - kernel/sched/build_policy.c:dequeue_top_rt_rq
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
In kernel/sched/build_policy.c (ffffffff81178695)
Location: kernel/sched/rt.c:293
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
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
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:121
Inline: True
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
In kernel/sched/rt.c (c039ccd8)
Location: kernel/sched/rt.c:121
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_rq_enqueue
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
In kernel/sched/rt.c (c0000000001a2b18)
Location: kernel/sched/rt.c:121
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:enqueue_top_rt_rq
  - kernel/sched/rt.c:dequeue_top_rt_rq
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:sched_rt_rq_enqueue
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
In kernel/sched/rt.c (ffffffe0000f75fa)
Location: kernel/sched/rt.c:121
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:do_balance_runtime
  - kernel/sched/rt.c:sched_rt_rq_enqueue
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
In kernel/sched/rt.c (ffffffff810e8374)
Location: kernel/sched/rt.c:232
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
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
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:121
Inline: True
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
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:121
Inline: True
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
In kernel/sched/rt.c (ffffffff810f102e)
Location: kernel/sched/rt.c:232
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:sched_rt_period_timer
  - kernel/sched/rt.c:sched_rt_period_timer
```
</details>
</li>
</ul>

## Differences
