# Function: <code>task_on_rq_migrating</code>

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
In kernel/sched/core.c (ffffffff810aa3fb)
Location: kernel/sched/sched.h:1044
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:task_sched_runtime
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:sched_setnuma
  - kernel/sched/core.c:sched_move_task
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:1044
Inline: True
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1082
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1082
Inline: True
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1116
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1116
Inline: True
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1284
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1284
Inline: True
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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:1321
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1321
Inline: True
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
In kernel/sched/core.c (ffffffff810bcd07)
Location: kernel/sched/sched.h:1410
Inline: True
Inline callers:
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810cbf8b)
Location: kernel/sched/sched.h:1410
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/core.c (ffffffff810c5f27)
Location: kernel/sched/sched.h:1564
Inline: True
Inline callers:
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810d4694)
Location: kernel/sched/sched.h:1564
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/core.c (ffffffff810cf9e7)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810dcb25)
Location: kernel/sched/sched.h:1622
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/core.c (ffffffff810d98a9)
Location: kernel/sched/sched.h:1636
Inline: True
Inline callers:
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810e6f55)
Location: kernel/sched/sched.h:1636
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/core.c (ffffffff810e2ae7)
Location: kernel/sched/sched.h:1676
Inline: True
Inline callers:
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810f10e1)
Location: kernel/sched/sched.h:1676
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/core.c (ffffffff810dfc8a)
Location: kernel/sched/sched.h:1741
Inline: True
Inline callers:
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810efd61)
Location: kernel/sched/sched.h:1741
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/core.c (ffffffff810e1a6a)
Location: kernel/sched/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810f1792)
Location: kernel/sched/sched.h:1752
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/core.c (ffffffff810f7c4b)
Location: kernel/sched/sched.h:2040
Inline: True
Inline callers:
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff8110b2bf)
Location: kernel/sched/sched.h:2040
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/core.c (ffffffff81113f37)
Location: kernel/sched/sched.h:2035
Inline: True
Inline callers:
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/build_utility.c (ffffffff81147ec6)
Location: kernel/sched/sched.h:2035
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__update_stats_wait_end
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
In kernel/sched/core.c (ffffffff8113b255)
Location: kernel/sched/sched.h:2085
Inline: True
Inline callers:
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff81143b48)
Location: kernel/sched/sched.h:2085
Inline: True
Inline callers:
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/build_utility.c (ffffffff81176636)
Location: kernel/sched/sched.h:2085
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__update_stats_wait_end
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
In kernel/sched/core.c (ffffffff8115184f)
Location: kernel/sched/sched.h:2128
Inline: True
Inline callers:
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff81153b08)
Location: kernel/sched/sched.h:2128
Inline: True
Inline callers:
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/build_utility.c (ffffffff81187276)
Location: kernel/sched/sched.h:2128
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__update_stats_wait_end
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
In kernel/sched/core.c (ffffffff8115d6e0)
Location: kernel/sched/sched.h:2170
Inline: True
Inline callers:
  - kernel/sched/core.c:try_steal_cookie
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:push_cpu_stop
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff8115fc58)
Location: kernel/sched/sched.h:2170
Inline: True
Inline callers:
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:dequeue_entity
```
```
In kernel/sched/build_utility.c (ffffffff811959a6)
Location: kernel/sched/sched.h:2170
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__update_stats_wait_end
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
In kernel/sched/core.c (ffff8000101397dc)
Location: kernel/sched/sched.h:1636
Inline: True
Inline callers:
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffff800010146e6c)
Location: kernel/sched/sched.h:1636
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/core.c (c0388f94)
Location: kernel/sched/sched.h:1636
Inline: True
Inline callers:
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (c03950a0)
Location: kernel/sched/sched.h:1636
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/core.c (c00000000018657c)
Location: kernel/sched/sched.h:1636
Inline: True
Inline callers:
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (c000000000198448)
Location: kernel/sched/sched.h:1636
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/core.c (ffffffe0000e924e)
Location: kernel/sched/sched.h:1636
Inline: True
Inline callers:
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffe0000f26e8)
Location: kernel/sched/sched.h:1636
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/core.c (ffffffff810d3d57)
Location: kernel/sched/sched.h:1636
Inline: True
Inline callers:
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810e1105)
Location: kernel/sched/sched.h:1636
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/core.c (ffffffff810c23a9)
Location: kernel/sched/sched.h:1636
Inline: True
Inline callers:
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810d01e5)
Location: kernel/sched/sched.h:1636
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/core.c (ffffffff810d0fd9)
Location: kernel/sched/sched.h:1636
Inline: True
Inline callers:
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810dd485)
Location: kernel/sched/sched.h:1636
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/core.c (ffffffff810db510)
Location: kernel/sched/sched.h:1636
Inline: True
Inline callers:
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
  - kernel/sched/core.c:__task_rq_lock
```
```
In kernel/sched/fair.c (ffffffff810e9205)
Location: kernel/sched/sched.h:1636
Inline: True
Inline callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
</ul>

## Differences
