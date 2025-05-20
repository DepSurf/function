# Function: <code>rq_of</code>

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
Location: kernel/sched/fair.c:249
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
Location: kernel/sched/fair.c:249
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
Location: kernel/sched/fair.c:264
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
Location: kernel/sched/fair.c:266
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
Location: kernel/sched/fair.c:268
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
Location: kernel/sched/fair.c:253
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
Location: kernel/sched/fair.c:253
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
Location: kernel/sched/sched.h:999
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
Location: kernel/sched/sched.h:1007
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
In kernel/sched/fair.c (ffffffff810e8a0e)
Location: kernel/sched/sched.h:1037
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_cpu
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_cfs_rq_h_load
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810e67be)
Location: kernel/sched/sched.h:1070
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_cpu
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_cfs_rq_h_load
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810e877e)
Location: kernel/sched/sched.h:1083
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_cpu
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff810ffe4e)
Location: kernel/sched/sched.h:1119
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_cpu
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff8112d2d1)
Location: kernel/sched/sched.h:1116
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:propagate_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff8115704b)
Location: kernel/sched/sched.h:1162
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_curr
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
In kernel/sched/fair.c (ffffffff81167104)
Location: kernel/sched/sched.h:1169
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:post_init_entity_util_avg
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
In kernel/sched/fair.c (ffffffff81173e84)
Location: kernel/sched/sched.h:1187
Inline: True
Inline callers:
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:switched_from_fair
  - kernel/sched/fair.c:switched_from_fair
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:post_init_entity_util_avg
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
Location: kernel/sched/sched.h:1007
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
In kernel/sched/fair.c (c03901b8)
Location: kernel/sched/sched.h:1007
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_cpu
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:post_init_entity_util_avg
  - kernel/sched/fair.c:post_init_entity_util_avg
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
In kernel/sched/fair.c (c00000000018f590)
Location: kernel/sched/sched.h:1007
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_cpu
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_cfs_rq_h_load
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:post_init_entity_util_avg
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
In kernel/sched/fair.c (ffffffe0000ee2fe)
Location: kernel/sched/sched.h:1007
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_trace_cfs_rq_cpu
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_cfs_rq_h_load
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:distribute_cfs_runtime
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:post_init_entity_util_avg
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
Location: kernel/sched/sched.h:1007
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
Location: kernel/sched/sched.h:1007
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
Location: kernel/sched/sched.h:1007
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
Location: kernel/sched/sched.h:1007
Inline: True
```
</details>
</li>
</ul>

## Differences
