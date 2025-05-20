# Function: <code>cfs_rq_util_change</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b946a)
Location: kernel/sched/fair.c:2876
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810c0a0d)
Location: kernel/sched/fair.c:3170
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810c2736)
Location: kernel/sched/fair.c:3279
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810c9b44)
Location: kernel/sched/fair.c:3015
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810d1d5d)
Location: kernel/sched/fair.c:3043
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810db6c1)
Location: kernel/sched/fair.c:3024
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810dda3a)
Location: kernel/sched/fair.c:3109
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810e80fa)
Location: kernel/sched/fair.c:3109
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810edbb7)
Location: kernel/sched/fair.c:3265
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810eb9e7)
Location: kernel/sched/fair.c:3279
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810ed345)
Location: kernel/sched/fair.c:3276
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffffffff81105fd4)
Location: kernel/sched/fair.c:3266
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffffffff81121592)
Location: kernel/sched/fair.c:3293
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffffffff81148ab8)
Location: kernel/sched/fair.c:3501
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffffffff81158968)
Location: kernel/sched/fair.c:3558
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffffffff81164f08)
Location: kernel/sched/fair.c:3985
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffff800010145acc)
Location: kernel/sched/fair.c:3109
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (c039378c)
Location: kernel/sched/fair.c:3109
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (c000000000199694)
Location: kernel/sched/fair.c:3109
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3109
Inline: True
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
In kernel/sched/fair.c (ffffffff810e22aa)
Location: kernel/sched/fair.c:3109
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810d138a)
Location: kernel/sched/fair.c:3109
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810de62a)
Location: kernel/sched/fair.c:3109
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810ea12a)
Location: kernel/sched/fair.c:3109
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
```
</details>
</li>
</ul>

## Differences
