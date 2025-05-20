# Function: <code>cfs_rq_of</code>

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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:275
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:275
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:288
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:290
Inline: True
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:292
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:277
Inline: True
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:274
Inline: True
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:267
Inline: True
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:267
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
In kernel/sched/fair.c (ffffffff810e93d2)
Location: kernel/sched/fair.c:279
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_rr_interval_fair
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_cfs_rq_h_load
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:put_prev_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
  - kernel/sched/fair.c:update_curr_fair
  - kernel/sched/fair.c:post_init_entity_util_avg
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
In kernel/sched/fair.c (ffffffff810e7182)
Location: kernel/sched/fair.c:277
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_rr_interval_fair
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_cfs_rq_h_load
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:put_prev_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
  - kernel/sched/fair.c:update_curr_fair
  - kernel/sched/fair.c:post_init_entity_util_avg
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
In kernel/sched/fair.c (ffffffff810e8ab2)
Location: kernel/sched/fair.c:287
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_rr_interval_fair
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:put_prev_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
  - kernel/sched/fair.c:update_curr_fair
  - kernel/sched/fair.c:post_init_entity_util_avg
  - kernel/sched/fair.c:sched_slice
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
In kernel/sched/fair.c (ffffffff811001e2)
Location: kernel/sched/sched.h:1386
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_rr_interval_fair
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:task_vruntime_update
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:put_prev_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
  - kernel/sched/fair.c:update_curr_fair
  - kernel/sched/fair.c:post_init_entity_util_avg
  - kernel/sched/fair.c:sched_slice
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
In kernel/sched/fair.c (ffffffff811227ec)
Location: kernel/sched/sched.h:1372
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_rr_interval_fair
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:switched_from_fair
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:task_vruntime_update
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:put_prev_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
  - kernel/sched/fair.c:update_curr_fair
  - kernel/sched/fair.c:post_init_entity_util_avg
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
In kernel/sched/fair.c (ffffffff8114a52c)
Location: kernel/sched/sched.h:1418
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_rr_interval_fair
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:task_vruntime_update
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:put_prev_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
  - kernel/sched/fair.c:update_curr_fair
  - kernel/sched/fair.c:post_init_entity_util_avg
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
In kernel/sched/fair.c (ffffffff8115ab9c)
Location: kernel/sched/sched.h:1426
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_rr_interval_fair
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:task_vruntime_update
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:put_prev_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:clear_buddies
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
  - kernel/sched/fair.c:update_curr_fair
  - kernel/sched/fair.c:post_init_entity_util_avg
  - kernel/sched/fair.c:sched_slice
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
In kernel/sched/fair.c (ffffffff811744f9)
Location: kernel/sched/sched.h:1445
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:switched_from_fair
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:cfs_prio_less
  - kernel/sched/fair.c:task_vruntime_update
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:put_prev_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup_fair
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
  - kernel/sched/fair.c:update_curr_fair
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/build_utility.c (ffffffff81188cc8)
Location: kernel/sched/sched.h:1445
Inline: True
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:267
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
In kernel/sched/fair.c (c03905d4)
Location: kernel/sched/fair.c:267
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_rr_interval_fair
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:set_next_task_fair
  - kernel/sched/fair.c:attach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:yield_to_task_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:put_prev_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:set_next_buddy
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:remove_entity_load_avg
  - kernel/sched/fair.c:sync_entity_load_avg
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
  - kernel/sched/fair.c:update_curr_fair
  - kernel/sched/fair.c:post_init_entity_util_avg
  - kernel/sched/fair.c:sched_slice
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:267
Inline: True
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
Location: kernel/sched/fair.c:267
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:267
Inline: True
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:267
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:267
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:267
Inline: True
```
</details>
</li>
</ul>

## Differences
