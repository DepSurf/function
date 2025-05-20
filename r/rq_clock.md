# Function: <code>rq_clock</code>

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
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:715
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:715
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:715
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
Location: kernel/sched/sched.h:739
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:739
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:739
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:739
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
Location: kernel/sched/sched.h:771
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:771
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:771
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:771
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
In kernel/sched/core.c (ffffffff81905cb3)
Location: kernel/sched/sched.h:880
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:sched_avg_update
```
```
In kernel/sched/fair.c (ffffffff810c287b)
Location: kernel/sched/sched.h:880
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810c483e)
Location: kernel/sched/sched.h:880
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c79ab)
Location: kernel/sched/sched.h:880
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/core.c (ffffffff8198fd2f)
Location: kernel/sched/sched.h:894
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:sched_avg_update
```
```
In kernel/sched/fair.c (ffffffff810c9f73)
Location: kernel/sched/sched.h:894
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810cbdb4)
Location: kernel/sched/sched.h:894
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810ced1b)
Location: kernel/sched/sched.h:894
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/core.c (ffffffff819ec575)
Location: kernel/sched/sched.h:970
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/core.c:sched_avg_update
```
```
In kernel/sched/fair.c (ffffffff810d206f)
Location: kernel/sched/sched.h:970
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810d2da8)
Location: kernel/sched/sched.h:970
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810d7b74)
Location: kernel/sched/sched.h:970
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
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
In kernel/sched/core.c (ffffffff81a277f7)
Location: kernel/sched/sched.h:1028
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
```
```
In kernel/sched/fair.c (ffffffff810db9eb)
Location: kernel/sched/sched.h:1028
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810dcd28)
Location: kernel/sched/sched.h:1028
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810e07a4)
Location: kernel/sched/sched.h:1028
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
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
In kernel/sched/core.c (ffffffff81a9809a)
Location: kernel/sched/sched.h:1086
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
```
```
In kernel/sched/fair.c (ffffffff810ddb1e)
Location: kernel/sched/sched.h:1086
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810e3d0e)
Location: kernel/sched/sched.h:1086
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810e73f6)
Location: kernel/sched/sched.h:1086
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
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
In kernel/sched/core.c (ffffffff81acf970)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
```
```
In kernel/sched/fair.c (ffffffff810e81de)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810ef4df)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f2a16)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
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
In kernel/sched/core.c (ffffffff810ddd7e)
Location: kernel/sched/sched.h:1124
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:ttwu_do_wakeup
```
```
In kernel/sched/fair.c (ffffffff810edc9b)
Location: kernel/sched/sched.h:1124
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
```
```
In kernel/sched/rt.c (ffffffff810f7a68)
Location: kernel/sched/sched.h:1124
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
```
```
In kernel/sched/deadline.c (ffffffff810fc056)
Location: kernel/sched/sched.h:1124
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
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
In kernel/sched/core.c (ffffffff810da2ee)
Location: kernel/sched/sched.h:1167
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:ttwu_do_wakeup
```
```
In kernel/sched/fair.c (ffffffff810ebaba)
Location: kernel/sched/sched.h:1167
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
```
```
In kernel/sched/rt.c (ffffffff810f5c48)
Location: kernel/sched/sched.h:1167
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
```
```
In kernel/sched/deadline.c (ffffffff810fa5b7)
Location: kernel/sched/sched.h:1167
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:update_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
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
In kernel/sched/core.c (ffffffff810e47fb)
Location: kernel/sched/sched.h:1180
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:ttwu_do_wakeup
```
```
In kernel/sched/fair.c (ffffffff810ed42b)
Location: kernel/sched/sched.h:1180
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
```
```
In kernel/sched/rt.c (ffffffff810f7fa8)
Location: kernel/sched/sched.h:1180
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
```
```
In kernel/sched/deadline.c (ffffffff810fc4e6)
Location: kernel/sched/sched.h:1180
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
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
In kernel/sched/core.c (ffffffff810fb5c7)
Location: kernel/sched/sched.h:1467
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:ttwu_do_wakeup
```
```
In kernel/sched/fair.c (ffffffff811060c1)
Location: kernel/sched/sched.h:1467
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
```
```
In kernel/sched/rt.c (ffffffff811135d8)
Location: kernel/sched/sched.h:1467
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
```
```
In kernel/sched/deadline.c (ffffffff8111ab3a)
Location: kernel/sched/sched.h:1467
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/core.c (ffffffff81112d3f)
Location: kernel/sched/sched.h:1448
Inline: True
Inline callers:
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:ttwu_do_wakeup
```
```
In kernel/sched/fair.c (ffffffff811216c9)
Location: kernel/sched/sched.h:1448
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/build_policy.c (ffffffff8113aadf)
Location: kernel/sched/sched.h:1448
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff8114bb3f)
Location: kernel/sched/sched.h:1448
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sched_core_account_forceidle
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_wait_end
  - kernel/sched/build_utility.c:__update_stats_wait_start
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
In kernel/sched/core.c (ffffffff81139db9)
Location: kernel/sched/sched.h:1494
Inline: True
Inline callers:
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:ttwu_do_wakeup
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff81154db5)
Location: kernel/sched/sched.h:1494
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/build_policy.c (ffffffff81165397)
Location: kernel/sched/sched.h:1494
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff8117a5e7)
Location: kernel/sched/sched.h:1494
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sched_core_account_forceidle
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_wait_end
  - kernel/sched/build_utility.c:__update_stats_wait_start
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
In kernel/sched/core.c (ffffffff81149043)
Location: kernel/sched/sched.h:1499
Inline: True
Inline callers:
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff81164f65)
Location: kernel/sched/sched.h:1499
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/build_policy.c (ffffffff81175b37)
Location: kernel/sched/sched.h:1499
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff8118b147)
Location: kernel/sched/sched.h:1499
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sched_core_account_forceidle
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_wait_end
  - kernel/sched/build_utility.c:__update_stats_wait_start
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
In kernel/sched/core.c (ffffffff81154944)
Location: kernel/sched/sched.h:1518
Inline: True
Inline callers:
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff81171cb5)
Location: kernel/sched/sched.h:1518
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/build_policy.c (ffffffff81183ddb)
Location: kernel/sched/sched.h:1518
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_server_start
  - kernel/sched/build_policy.c:dl_server_start
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:task_contending
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
```
```
In kernel/sched/build_utility.c (ffffffff81199a77)
Location: kernel/sched/sched.h:1518
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sched_core_account_forceidle
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_wait_end
  - kernel/sched/build_utility.c:__update_stats_wait_start
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
In kernel/sched/core.c (ffff800010da15b0)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:dequeue_task
  - kernel/sched/core.c:enqueue_task
```
```
In kernel/sched/fair.c (ffff800010145bd0)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffff800010150718)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffff800010154bec)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
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
In kernel/sched/core.c (c0e99600)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
```
```
In kernel/sched/fair.c (c0393834)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (c039e368)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (c03a1db4)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
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
In kernel/sched/core.c (c000000000ee2628)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
```
```
In kernel/sched/fair.c (c000000000199774)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (c0000000001a3680)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (c0000000001aa1b8)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
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
In kernel/sched/core.c (ffffffe0008c4e34)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
```
```
In kernel/sched/fair.c (ffffffe0000f5a56)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
```
In kernel/sched/deadline.c (ffffffe0000fcefa)
Location: kernel/sched/sched.h:1094
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
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a6e7e0)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
```
```
In kernel/sched/fair.c (ffffffff810e238e)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810e819e)
Location: kernel/sched/sched.h:1094
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810ebe16)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
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
In kernel/sched/core.c (ffffffff81a2abd9)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
```
```
In kernel/sched/fair.c (ffffffff810d146e)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810d889f)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810dbe36)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
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
In kernel/sched/core.c (ffffffff81adabf0)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
```
```
In kernel/sched/fair.c (ffffffff810de70e)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810e5a0f)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e8f46)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
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
In kernel/sched/core.c (ffffffff81ae70a2)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
```
```
In kernel/sched/fair.c (ffffffff810ea227)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
```
```
In kernel/sched/rt.c (ffffffff810f0e5e)
Location: kernel/sched/sched.h:1094
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f3ef6)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
</details>
</li>
</ul>

## Differences
