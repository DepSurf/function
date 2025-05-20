# Function: <code>rq_clock_task</code>

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
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:721
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:721
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:721
Inline: True
```
```
In kernel/sched/stop_task.c (0)
Location: kernel/sched/sched.h:721
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
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:745
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:745
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:745
Inline: True
```
```
In kernel/sched/stop_task.c (0)
Location: kernel/sched/sched.h:745
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
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:777
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:777
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:777
Inline: True
```
```
In kernel/sched/stop_task.c (0)
Location: kernel/sched/sched.h:777
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
In kernel/sched/fair.c (ffffffff810c2584)
Location: kernel/sched/sched.h:888
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/rt.c (ffffffff810c460e)
Location: kernel/sched/sched.h:888
Inline: True
Inline callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c6b71)
Location: kernel/sched/sched.h:888
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_curr_task_dl
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810cd84c)
Location: kernel/sched/sched.h:888
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:set_curr_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/fair.c (ffffffff810c9bf2)
Location: kernel/sched/sched.h:902
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/rt.c (ffffffff810cbcae)
Location: kernel/sched/sched.h:902
Inline: True
Inline callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810ce3b1)
Location: kernel/sched/sched.h:902
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_curr_task_dl
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810d509c)
Location: kernel/sched/sched.h:902
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:set_curr_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/fair.c (ffffffff810d1c1a)
Location: kernel/sched/sched.h:978
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/rt.c (ffffffff810d2bef)
Location: kernel/sched/sched.h:978
Inline: True
Inline callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810d55af)
Location: kernel/sched/sched.h:978
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_curr_task_dl
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810dd07d)
Location: kernel/sched/sched.h:978
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:set_curr_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/fair.c (ffffffff810db567)
Location: kernel/sched/sched.h:1036
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/rt.c (ffffffff810dc63f)
Location: kernel/sched/sched.h:1036
Inline: True
Inline callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810defdf)
Location: kernel/sched/sched.h:1036
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_curr_task_dl
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810e6cdd)
Location: kernel/sched/sched.h:1036
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:set_curr_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff810cbec5)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff810e24eb)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e35df)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e61b0)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/deadline.c:set_curr_task_dl
  - kernel/sched/deadline.c:pick_next_task_dl
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810ed96d)
Location: kernel/sched/sched.h:1094
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:set_curr_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff810d5a25)
Location: kernel/sched/sched.h:1102
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810ecba4)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810ee18c)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f34a5)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810f962f)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff810e4eb8)
Location: kernel/sched/sched.h:1132
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff810f6a4a)
Location: kernel/sched/sched.h:1132
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f7b4c)
Location: kernel/sched/sched.h:1132
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fcb8d)
Location: kernel/sched/sched.h:1132
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff8110373f)
Location: kernel/sched/sched.h:1132
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff810e298a)
Location: kernel/sched/sched.h:1175
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff810f4c02)
Location: kernel/sched/sched.h:1175
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f5d4c)
Location: kernel/sched/sched.h:1175
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fb09d)
Location: kernel/sched/sched.h:1175
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff81101e5f)
Location: kernel/sched/sched.h:1175
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff810e4760)
Location: kernel/sched/sched.h:1188
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff810f6cf2)
Location: kernel/sched/sched.h:1188
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f80ac)
Location: kernel/sched/sched.h:1188
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810fd2a8)
Location: kernel/sched/sched.h:1188
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff811041cf)
Location: kernel/sched/sched.h:1188
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff810fb51f)
Location: kernel/sched/sched.h:1475
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff81110f4c)
Location: kernel/sched/sched.h:1475
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff81113711)
Location: kernel/sched/sched.h:1475
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff81119678)
Location: kernel/sched/sched.h:1475
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff811212d1)
Location: kernel/sched/sched.h:1475
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff81117a12)
Location: kernel/sched/sched.h:1456
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff81121063)
Location: kernel/sched/sched.h:1456
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81136109)
Location: kernel/sched/sched.h:1456
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff81144003)
Location: kernel/sched/sched.h:1456
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:put_prev_task_stop
  - kernel/sched/build_utility.c:put_prev_task_stop
  - kernel/sched/build_utility.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff8113eff7)
Location: kernel/sched/sched.h:1502
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff81149cd3)
Location: kernel/sched/sched.h:1502
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff811606e9)
Location: kernel/sched/sched.h:1502
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff8116fce3)
Location: kernel/sched/sched.h:1502
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:put_prev_task_stop
  - kernel/sched/build_utility.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff81151f47)
Location: kernel/sched/sched.h:1507
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff81159b81)
Location: kernel/sched/sched.h:1507
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:place_entity
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81170e0f)
Location: kernel/sched/sched.h:1507
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
```
```
In kernel/sched/build_utility.c (ffffffff8117e673)
Location: kernel/sched/sched.h:1507
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:put_prev_task_stop
  - kernel/sched/build_utility.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff81151cc4)
Location: kernel/sched/sched.h:1526
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_tick_remote
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff811661b1)
Location: kernel/sched/sched.h:1526
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr_se
```
```
In kernel/sched/build_policy.c (ffffffff81180b58)
Location: kernel/sched/sched.h:1526
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_rt
```
```
In kernel/sched/build_utility.c (ffffffff8118c459)
Location: kernel/sched/sched.h:1526
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:pick_next_task_stop
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
In kernel/sched/core.c (ffff800010136504)
Location: kernel/sched/sched.h:1102
Inline: True
```
```
In kernel/sched/fair.c (ffff80001014d120)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffff80001014ee40)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffff8000101556b8)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffff80001015dfe4)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (c03853d8)
Location: kernel/sched/sched.h:1102
Inline: True
```
```
In kernel/sched/fair.c (c039ad88)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (c039d2bc)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (c03a2fec)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (c03a9e40)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (c0000000001816f0)
Location: kernel/sched/sched.h:1102
Inline: True
```
```
In kernel/sched/fair.c (c00000000019ff3c)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (c0000000001a3268)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (c0000000001a98c4)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (c0000000001b2c10)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffe0000e7400)
Location: kernel/sched/sched.h:1102
Inline: True
```
```
In kernel/sched/fair.c (ffffffe0000f646c)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffe0000f7d14)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffe0000fd260)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffe0001024e8)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff810cfd25)
Location: kernel/sched/sched.h:1102
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810e6d04)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e7e85)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810ec8a5)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810f2a2f)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff810bfa6a)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_tick_remote
```
```
In kernel/sched/fair.c (ffffffff810d5e9e)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810d74dc)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810dc945)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810e2b3f)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff810ce8b5)
Location: kernel/sched/sched.h:1102
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810e30d4)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810e46bc)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e99d5)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810efb5f)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:pick_next_task_stop
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
In kernel/sched/core.c (ffffffff810d7895)
Location: kernel/sched/sched.h:1102
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810eecaa)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:tg_throttle_down
  - kernel/sched/fair.c:tg_unthrottle_up
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/rt.c (ffffffff810f0b45)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f4985)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/stop_task.c (ffffffff810fabaf)
Location: kernel/sched/sched.h:1102
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:put_prev_task_stop
  - kernel/sched/stop_task.c:pick_next_task_stop
```
</details>
</li>
</ul>

## Differences
