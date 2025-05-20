# Function: <code>cfs_bandwidth_used</code>

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
Location: kernel/sched/fair.c:3343
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:update_cfs_shares
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:set_curr_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
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
In kernel/sched/fair.c (ffffffff810c213b)
Location: kernel/sched/fair.c:3683
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_curr_task_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_shares
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810c818b)
Location: kernel/sched/fair.c:3900
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_curr_task_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_shares
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810c1e43)
Location: kernel/sched/fair.c:4022
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_curr_task_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_shares
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810c9586)
Location: kernel/sched/fair.c:4361
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_curr_task_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810d1706)
Location: kernel/sched/fair.c:4532
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_curr_task_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810db036)
Location: kernel/sched/fair.c:4223
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_curr_task_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810e2472)
Location: kernel/sched/fair.c:4319
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_curr_task_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810ecb2b)
Location: kernel/sched/fair.c:4318
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810f69c7)
Location: kernel/sched/fair.c:4544
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810f4b7a)
Location: kernel/sched/fair.c:4578
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810f6c6a)
Location: kernel/sched/fair.c:4641
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff81110ebc)
Location: kernel/sched/fair.c:4653
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff8112d0e9)
Location: kernel/sched/fair.c:4691
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff81156e58)
Location: kernel/sched/fair.c:5097
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff81166f07)
Location: kernel/sched/fair.c:5203
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:task_is_throttled_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:__cfsb_csd_unthrottle
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff81173c87)
Location: kernel/sched/fair.c:5532
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:task_is_throttled_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:__cfsb_csd_unthrottle
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffff80001014d088)
Location: kernel/sched/fair.c:4318
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:4333
Inline: True
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
In kernel/sched/fair.c (c00000000019fe64)
Location: kernel/sched/fair.c:4318
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:update_curr
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
Location: kernel/sched/fair.c:4333
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
In kernel/sched/fair.c (ffffffff810e6c8b)
Location: kernel/sched/fair.c:4318
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810d5e2b)
Location: kernel/sched/fair.c:4318
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810e305b)
Location: kernel/sched/fair.c:4318
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810eec3a)
Location: kernel/sched/fair.c:4318
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:update_curr
```
</details>
</li>
</ul>

## Differences
