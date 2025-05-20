# Function: <code>cpufreq_update_util</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b9779)
Location: kernel/sched/sched.h:1775
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
```
In kernel/sched/rt.c (ffffffff810c356a)
Location: kernel/sched/sched.h:1775
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c5d0e)
Location: kernel/sched/sched.h:1775
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/fair.c (ffffffff810c0ace)
Location: kernel/sched/sched.h:1801
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810c95d3)
Location: kernel/sched/sched.h:1801
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810cbcce)
Location: kernel/sched/sched.h:1801
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/fair.c (ffffffff810c2856)
Location: kernel/sched/sched.h:2069
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810c4823)
Location: kernel/sched/sched.h:2069
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c7f9e)
Location: kernel/sched/sched.h:2069
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/fair.c (ffffffff810c9f52)
Location: kernel/sched/sched.h:2110
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810cbd96)
Location: kernel/sched/sched.h:2110
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810cf54e)
Location: kernel/sched/sched.h:2110
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/fair.c (ffffffff810d203f)
Location: kernel/sched/sched.h:2158
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810d2d7c)
Location: kernel/sched/sched.h:2158
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810d7b49)
Location: kernel/sched/sched.h:2158
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
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
In kernel/sched/fair.c (ffffffff810db9bb)
Location: kernel/sched/sched.h:2193
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810dccfc)
Location: kernel/sched/sched.h:2193
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810e0779)
Location: kernel/sched/sched.h:2193
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
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
In kernel/sched/fair.c (ffffffff810ddaf1)
Location: kernel/sched/sched.h:2255
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810e3ce5)
Location: kernel/sched/sched.h:2255
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810e73cc)
Location: kernel/sched/sched.h:2255
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_contending
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
In kernel/sched/fair.c (ffffffff810e81b1)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810ef4b6)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810f29ec)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
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
In kernel/sched/fair.c (ffffffff810edc6e)
Location: kernel/sched/sched.h:2338
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810f7a3f)
Location: kernel/sched/sched.h:2338
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
```
```
In kernel/sched/deadline.c (ffffffff810fc02c)
Location: kernel/sched/sched.h:2338
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
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
In kernel/sched/fair.c (ffffffff810eba8d)
Location: kernel/sched/sched.h:2461
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810f5c1f)
Location: kernel/sched/sched.h:2461
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
```
```
In kernel/sched/deadline.c (ffffffff810fa58d)
Location: kernel/sched/sched.h:2461
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
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
In kernel/sched/fair.c (ffffffff810ed3fe)
Location: kernel/sched/sched.h:2508
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810f7f7f)
Location: kernel/sched/sched.h:2508
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
```
```
In kernel/sched/deadline.c (ffffffff810fc4bc)
Location: kernel/sched/sched.h:2508
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
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
In kernel/sched/fair.c (ffffffff8110608b)
Location: kernel/sched/sched.h:2815
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff811135a1)
Location: kernel/sched/sched.h:2815
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
```
```
In kernel/sched/deadline.c (ffffffff8111ab03)
Location: kernel/sched/sched.h:2815
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
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
In kernel/sched/fair.c (ffffffff81121693)
Location: kernel/sched/sched.h:2811
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/build_policy.c (ffffffff8113aaa9)
Location: kernel/sched/sched.h:2811
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:dequeue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
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
In kernel/sched/fair.c (ffffffff81149d8d)
Location: kernel/sched/sched.h:2869
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/build_policy.c (ffffffff81165361)
Location: kernel/sched/sched.h:2869
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:dequeue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
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
In kernel/sched/fair.c (ffffffff81159c37)
Location: kernel/sched/sched.h:2915
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/build_policy.c (ffffffff81175b01)
Location: kernel/sched/sched.h:2915
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:dequeue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
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
In kernel/sched/fair.c (ffffffff81166267)
Location: kernel/sched/sched.h:2986
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/build_policy.c (ffffffff81183da5)
Location: kernel/sched/sched.h:2986
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:migrate_task_rq_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:task_contending
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:enqueue_top_rt_rq
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
In kernel/sched/fair.c (ffff800010145ba8)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffff8000101506fc)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffff800010154bc4)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
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
In kernel/sched/fair.c (c0393808)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (c039e340)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (c03a1d88)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
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
In kernel/sched/fair.c (c000000000199744)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (c0000000001a3644)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_top_rt_rq
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (c0000000001aa180)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
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
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:2308
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: kernel/sched/sched.h:2308
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:2308
Inline: True
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
In kernel/sched/fair.c (ffffffff810e2361)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810e8175)
Location: kernel/sched/sched.h:2298
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810ebdec)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
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
In kernel/sched/fair.c (ffffffff810d1441)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810d8876)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810dbe0c)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
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
In kernel/sched/fair.c (ffffffff810de6e1)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810e59e6)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810e8f1c)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
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
In kernel/sched/fair.c (ffffffff810ea1fa)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/rt.c (ffffffff810f0e35)
Location: kernel/sched/sched.h:2298
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810f3ecc)
Location: kernel/sched/sched.h:2298
Inline: True
Inline callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
</details>
</li>
</ul>

## Differences
