# Function: <code>se_weight</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c9e2b)
Location: kernel/sched/fair.c:2729
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
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
In kernel/sched/fair.c (ffffffff810d1e61)
Location: kernel/sched/fair.c:2757
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
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
In kernel/sched/fair.c (ffffffff810db7c5)
Location: kernel/sched/sched.h:698
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff810e71e5)
Location: kernel/sched/sched.h:698
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
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
In kernel/sched/fair.c (ffffffff810dd9b2)
Location: kernel/sched/sched.h:692
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff810edf43)
Location: kernel/sched/sched.h:692
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
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
In kernel/sched/fair.c (ffffffff810e8072)
Location: kernel/sched/sched.h:699
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff810f9b23)
Location: kernel/sched/sched.h:699
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
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
In kernel/sched/fair.c (ffffffff810edae5)
Location: kernel/sched/sched.h:730
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff81103b56)
Location: kernel/sched/sched.h:730
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
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
In kernel/sched/fair.c (ffffffff810eb915)
Location: kernel/sched/sched.h:742
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff81102253)
Location: kernel/sched/sched.h:742
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
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
In kernel/sched/fair.c (ffffffff810ed291)
Location: kernel/sched/sched.h:751
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff811045c8)
Location: kernel/sched/sched.h:751
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
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
In kernel/sched/fair.c (ffffffff81103dfc)
Location: kernel/sched/sched.h:768
Inline: True
Inline callers:
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff811217f4)
Location: kernel/sched/sched.h:768
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
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
In kernel/sched/fair.c (ffffffff8112148c)
Location: kernel/sched/sched.h:763
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/build_policy.c (ffffffff81136c7c)
Location: kernel/sched/sched.h:763
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
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
In kernel/sched/fair.c (ffffffff811489b9)
Location: kernel/sched/sched.h:793
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/build_policy.c (ffffffff811612fc)
Location: kernel/sched/sched.h:793
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
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
In kernel/sched/fair.c (ffffffff81158869)
Location: kernel/sched/sched.h:796
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/build_policy.c (ffffffff81171b38)
Location: kernel/sched/sched.h:796
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
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
In kernel/sched/fair.c (ffffffff81164e09)
Location: kernel/sched/sched.h:822
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/build_policy.c (ffffffff8117f448)
Location: kernel/sched/sched.h:822
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
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
In kernel/sched/fair.c (ffff800010145a60)
Location: kernel/sched/sched.h:699
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffff80001015e4b4)
Location: kernel/sched/sched.h:699
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
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
In kernel/sched/fair.c (c03936f8)
Location: kernel/sched/sched.h:699
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (c03aa5b4)
Location: kernel/sched/sched.h:699
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
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
In kernel/sched/fair.c (c000000000199610)
Location: kernel/sched/sched.h:699
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (c0000000001b32f8)
Location: kernel/sched/sched.h:699
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
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
In kernel/sched/fair.c (ffffffe0000f07aa)
Location: kernel/sched/sched.h:699
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffe000102958)
Location: kernel/sched/sched.h:699
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
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
In kernel/sched/fair.c (ffffffff810e2222)
Location: kernel/sched/sched.h:699
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff810f2f23)
Location: kernel/sched/sched.h:699
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
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
In kernel/sched/fair.c (ffffffff810d1302)
Location: kernel/sched/sched.h:699
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff810e3033)
Location: kernel/sched/sched.h:699
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
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
In kernel/sched/fair.c (ffffffff810de5a2)
Location: kernel/sched/sched.h:699
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff810f0053)
Location: kernel/sched/sched.h:699
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
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
In kernel/sched/fair.c (ffffffff810ea0a2)
Location: kernel/sched/sched.h:699
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff810fb0c3)
Location: kernel/sched/sched.h:699
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
</details>
</li>
</ul>

## Differences
