# Function: <code>dl_task_of</code>

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
In kernel/sched/deadline.c (ffffffff810c27d6)
Location: kernel/sched/deadline.c:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:pick_next_task_dl
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
In kernel/sched/deadline.c (ffffffff810c677d)
Location: kernel/sched/deadline.c:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/deadline.c (ffffffff810cc76d)
Location: kernel/sched/deadline.c:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/deadline.c (ffffffff810c8116)
Location: kernel/sched/deadline.c:24
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/deadline.c (ffffffff810cf8fc)
Location: kernel/sched/deadline.c:25
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
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
In kernel/sched/deadline.c (ffffffff810d74ac)
Location: kernel/sched/deadline.c:22
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810e1a6c)
Location: kernel/sched/deadline.c:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810e8550)
Location: kernel/sched/deadline.c:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810f3268)
Location: kernel/sched/deadline.c:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810fc91b)
Location: kernel/sched/deadline.c:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810fa909)
Location: kernel/sched/deadline.c:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810fcb19)
Location: kernel/sched/deadline.c:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff81116b51)
Location: kernel/sched/deadline.c:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/build_policy.c (ffffffff811391e0)
Location: kernel/sched/deadline.c:53
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
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
In kernel/sched/build_policy.c (ffffffff811638a0)
Location: kernel/sched/deadline.c:55
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
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
In kernel/sched/build_policy.c (ffffffff81174080)
Location: kernel/sched/deadline.c:57
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_timer
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
In kernel/sched/build_policy.c (ffffffff8117e90d)
Location: kernel/sched/deadline.c:62
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:update_curr_dl_se
  - kernel/sched/build_policy.c:update_curr_dl_se
  - kernel/sched/build_policy.c:dl_task_timer
  - kernel/sched/build_policy.c:task_contending
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
In kernel/sched/deadline.c (ffff8000101554c0)
Location: kernel/sched/deadline.c:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (c03a2cec)
Location: kernel/sched/deadline.c:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (c0000000001a7834)
Location: kernel/sched/deadline.c:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffe0000fcef0)
Location: kernel/sched/deadline.c:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810ec668)
Location: kernel/sched/deadline.c:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810dc708)
Location: kernel/sched/deadline.c:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810e9798)
Location: kernel/sched/deadline.c:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810f4748)
Location: kernel/sched/deadline.c:23
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
```
</details>
</li>
</ul>

## Differences
