# Function: <code>throttled_hierarchy</code>

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
In kernel/sched/fair.c (ffffffff810b2f71)
Location: kernel/sched/fair.c:3518
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_shares
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:update_blocked_averages
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
In kernel/sched/fair.c (ffffffff810b8d54)
Location: kernel/sched/fair.c:3858
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:update_cfs_shares
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
In kernel/sched/fair.c (ffffffff810be237)
Location: kernel/sched/fair.c:4075
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:update_cfs_shares
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
In kernel/sched/fair.c (ffffffff810bac3c)
Location: kernel/sched/fair.c:4197
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:update_cfs_shares
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
In kernel/sched/fair.c (ffffffff810c008c)
Location: kernel/sched/fair.c:4536
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (ffffffff810cab36)
Location: kernel/sched/fair.c:4709
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (ffffffff810d2bfd)
Location: kernel/sched/fair.c:4400
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (ffffffff810db1ea)
Location: kernel/sched/fair.c:4498
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (ffffffff810e50fa)
Location: kernel/sched/fair.c:4436
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (ffffffff810ee66b)
Location: kernel/sched/fair.c:4674
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (ffffffff810ec4ab)
Location: kernel/sched/fair.c:4708
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (ffffffff810eee52)
Location: kernel/sched/fair.c:4771
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (ffffffff811074f2)
Location: kernel/sched/fair.c:4786
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (ffffffff8112533a)
Location: kernel/sched/fair.c:4833
Inline: True
Inline callers:
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (ffffffff8114e5ba)
Location: kernel/sched/fair.c:5239
Inline: True
Inline callers:
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (ffffffff81154095)
Location: kernel/sched/fair.c:5345
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_is_throttled_fair
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (ffffffff811601e5)
Location: kernel/sched/fair.c:5674
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_is_throttled_fair
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (ffff8000101450d0)
Location: kernel/sched/fair.c:4436
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (c0391294)
Location: kernel/sched/fair.c:4436
Inline: True
Inline callers:
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (c000000000196278)
Location: kernel/sched/fair.c:4436
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (ffffffe0000ef7f6)
Location: kernel/sched/fair.c:4436
Inline: True
Inline callers:
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (ffffffff810df2aa)
Location: kernel/sched/fair.c:4436
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (ffffffff810ce2ba)
Location: kernel/sched/fair.c:4436
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (ffffffff810db62a)
Location: kernel/sched/fair.c:4436
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:update_cfs_group
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
In kernel/sched/fair.c (ffffffff810e731a)
Location: kernel/sched/fair.c:4436
Inline: True
Inline callers:
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:update_cfs_group
```
</details>
</li>
</ul>

## Differences
