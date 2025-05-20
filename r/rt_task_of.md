# Function: <code>rt_task_of</code>

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
In kernel/sched/rt.c (ffffffff810c0054)
Location: kernel/sched/rt.c:229
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
In kernel/sched/rt.c (ffffffff810c3a74)
Location: kernel/sched/rt.c:237
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
In kernel/sched/rt.c (ffffffff810c9ae4)
Location: kernel/sched/rt.c:237
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
In kernel/sched/rt.c (ffffffff810c4c60)
Location: kernel/sched/rt.c:238
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
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
In kernel/sched/rt.c (ffffffff810cc316)
Location: kernel/sched/rt.c:228
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
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
In kernel/sched/rt.c (ffffffff810d37aa)
Location: kernel/sched/rt.c:224
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:update_curr_rt
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
In kernel/sched/rt.c (ffffffff810dcb4f)
Location: kernel/sched/rt.c:226
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:update_curr_rt
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
In kernel/sched/rt.c (ffffffff810e3af7)
Location: kernel/sched/rt.c:226
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:update_curr_rt
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
In kernel/sched/rt.c (ffffffff810ee17d)
Location: kernel/sched/rt.c:113
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:requeue_rt_entity
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
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
In kernel/sched/rt.c (ffffffff810f7b3d)
Location: kernel/sched/rt.c:229
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
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
In kernel/sched/rt.c (ffffffff810f5d3d)
Location: kernel/sched/rt.c:229
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
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
In kernel/sched/rt.c (ffffffff810f809d)
Location: kernel/sched/rt.c:229
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:update_curr_rt
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
In kernel/sched/rt.c (ffffffff81113701)
Location: kernel/sched/rt.c:238
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:update_curr_rt
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
In kernel/sched/build_policy.c (ffffffff81138441)
Location: kernel/sched/rt.c:285
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_rt
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
In kernel/sched/build_policy.c (ffffffff81158bbe)
Location: kernel/sched/rt.c:285
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_task_rt
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
In kernel/sched/build_policy.c (ffffffff81168e9e)
Location: kernel/sched/rt.c:285
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_task_rt
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
In kernel/sched/build_policy.c (ffffffff811761ee)
Location: kernel/sched/rt.c:288
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_task_rt
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
In kernel/sched/rt.c (ffff80001014ee38)
Location: kernel/sched/rt.c:113
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:requeue_rt_entity
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__delist_rt_entity
  - kernel/sched/rt.c:__delist_rt_entity
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
In kernel/sched/rt.c (c039d2ac)
Location: kernel/sched/rt.c:113
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:requeue_rt_entity
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__delist_rt_entity
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
In kernel/sched/rt.c (c0000000001a3260)
Location: kernel/sched/rt.c:113
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:requeue_rt_entity
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__delist_rt_entity
  - kernel/sched/rt.c:__delist_rt_entity
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
In kernel/sched/rt.c (ffffffe0000f7d14)
Location: kernel/sched/rt.c:113
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:requeue_rt_entity
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__delist_rt_entity
  - kernel/sched/rt.c:__delist_rt_entity
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
In kernel/sched/rt.c (ffffffff810e8eb7)
Location: kernel/sched/rt.c:227
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:update_curr_rt
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
In kernel/sched/rt.c (ffffffff810d74cd)
Location: kernel/sched/rt.c:113
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:requeue_rt_entity
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
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
In kernel/sched/rt.c (ffffffff810e46ad)
Location: kernel/sched/rt.c:113
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:requeue_rt_entity
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
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
In kernel/sched/rt.c (ffffffff810f0a4b)
Location: kernel/sched/rt.c:227
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:check_preempt_curr_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:update_curr_rt
```
</details>
</li>
</ul>

## Differences
