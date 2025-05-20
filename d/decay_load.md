# Function: <code>decay_load</code>

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
In kernel/sched/fair.c (ffffffff810b2bd2)
Location: kernel/sched/fair.c:2485
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:remove_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810b9d9f)
Location: kernel/sched/fair.c:2619
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_task_cfs_rq
  - kernel/sched/fair.c:attach_task_cfs_rq
  - kernel/sched/fair.c:attach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
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
In kernel/sched/fair.c (ffffffff810c3bf0)
Location: kernel/sched/fair.c:2751
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:sync_entity_load_avg
  - kernel/sched/fair.c:sync_entity_load_avg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u64 decay_load(u64 val, u64 n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b5bcf)
Location: kernel/sched/fair.c:2798
Inline: True
Inline callers:
  - kernel/sched/fair.c:__accumulate_pelt_segments
  - kernel/sched/fair.c:__accumulate_pelt_segments
Direct callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
**Symbols:**

```
ffffffff810b5b40-ffffffff810b5ba6: decay_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u64 decay_load(u64 val, u64 n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bceaf)
Location: kernel/sched/fair.c:3045
Inline: True
Inline callers:
  - kernel/sched/fair.c:__accumulate_pelt_segments
  - kernel/sched/fair.c:__accumulate_pelt_segments
Direct callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
**Symbols:**

```
ffffffff810bce20-ffffffff810bce86: decay_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u64 decay_load(u64 val, u64 n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c4995)
Location: kernel/sched/fair.c:3071
Inline: True
Inline callers:
  - kernel/sched/fair.c:__accumulate_pelt_segments
  - kernel/sched/fair.c:__accumulate_pelt_segments
```
**Symbols:**

```
ffffffff810c4940-ffffffff810c4983: decay_load (STB_LOCAL)
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
In kernel/sched/pelt.c (ffffffff810e78f4)
Location: kernel/sched/pelt.c:36
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
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
In kernel/sched/pelt.c (ffffffff810ee7f2)
Location: kernel/sched/pelt.c:37
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
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
In kernel/sched/pelt.c (ffffffff810fa3d2)
Location: kernel/sched/pelt.c:37
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
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
In kernel/sched/pelt.c (ffffffff811046b8)
Location: kernel/sched/pelt.c:37
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
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
In kernel/sched/pelt.c (ffffffff81102d41)
Location: kernel/sched/pelt.c:35
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
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
In kernel/sched/pelt.c (ffffffff81105086)
Location: kernel/sched/pelt.c:35
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
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
In kernel/sched/pelt.c (ffffffff81122aad)
Location: kernel/sched/pelt.c:35
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
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
In kernel/sched/build_policy.c (ffffffff811386cc)
Location: kernel/sched/pelt.c:31
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
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
In kernel/sched/build_policy.c (ffffffff81162d5c)
Location: kernel/sched/pelt.c:31
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
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
In kernel/sched/build_policy.c (ffffffff811735d3)
Location: kernel/sched/pelt.c:31
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
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
In kernel/sched/build_policy.c (ffffffff81180f03)
Location: kernel/sched/pelt.c:31
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
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
In kernel/sched/pelt.c (ffff80001015edbc)
Location: kernel/sched/pelt.c:37
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
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
In kernel/sched/pelt.c (c03ab500)
Location: kernel/sched/pelt.c:37
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
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
In kernel/sched/pelt.c (c0000000001b4044)
Location: kernel/sched/pelt.c:37
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
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
In kernel/sched/pelt.c (ffffffe0001031aa)
Location: kernel/sched/pelt.c:37
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
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
In kernel/sched/pelt.c (ffffffff810f37d2)
Location: kernel/sched/pelt.c:37
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
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
In kernel/sched/pelt.c (ffffffff810e38e2)
Location: kernel/sched/pelt.c:37
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
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
In kernel/sched/pelt.c (ffffffff810f0902)
Location: kernel/sched/pelt.c:37
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
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
In kernel/sched/pelt.c (ffffffff810fb9a2)
Location: kernel/sched/pelt.c:37
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
  - kernel/sched/pelt.c:__accumulate_pelt_segments
  - kernel/sched/pelt.c:__accumulate_pelt_segments
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
