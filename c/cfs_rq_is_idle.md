# Function: <code>cfs_rq_is_idle</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8111165b)
Location: kernel/sched/fair.c:439
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
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
In kernel/sched/fair.c (ffffffff8112d889)
Location: kernel/sched/fair.c:497
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:sched_slice
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
In kernel/sched/fair.c (ffffffff8115766e)
Location: kernel/sched/fair.c:513
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:sched_slice
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
In kernel/sched/fair.c (ffffffff8116769d)
Location: kernel/sched/fair.c:513
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:sched_slice
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
In kernel/sched/fair.c (ffffffff8117448d)
Location: kernel/sched/fair.c:466
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:check_preempt_wakeup_fair
  - kernel/sched/fair.c:check_preempt_wakeup_fair
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
