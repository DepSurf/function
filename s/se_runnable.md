# Function: <code>se_runnable</code>

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
In kernel/sched/fair.c (ffffffff810c9eb4)
Location: kernel/sched/fair.c:2734
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff810d1ee2)
Location: kernel/sched/fair.c:2762
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff810db846)
Location: kernel/sched/sched.h:703
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_group_set_shares
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_blocked_averages
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff810e71c6)
Location: kernel/sched/sched.h:703
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
In kernel/sched/fair.c (ffffffff810dbf0f)
Location: kernel/sched/sched.h:697
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff810edf23)
Location: kernel/sched/sched.h:697
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
In kernel/sched/fair.c (ffffffff810e634f)
Location: kernel/sched/sched.h:704
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff810f9b03)
Location: kernel/sched/sched.h:704
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
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
In kernel/sched/pelt.c (ffffffff81103a65)
Location: kernel/sched/sched.h:707
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
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
In kernel/sched/pelt.c (ffffffff8110216e)
Location: kernel/sched/sched.h:719
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
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
In kernel/sched/pelt.c (ffffffff811044e3)
Location: kernel/sched/sched.h:728
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
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
In kernel/sched/pelt.c (ffffffff81121715)
Location: kernel/sched/sched.h:745
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
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
In kernel/sched/build_policy.c (ffffffff81136ba5)
Location: kernel/sched/sched.h:740
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_se
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
In kernel/sched/build_policy.c (ffffffff81161225)
Location: kernel/sched/sched.h:770
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_se
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
In kernel/sched/build_policy.c (ffffffff81171979)
Location: kernel/sched/sched.h:773
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_se
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
In kernel/sched/build_policy.c (ffffffff8117f289)
Location: kernel/sched/sched.h:799
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_se
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
In kernel/sched/fair.c (ffff800010146264)
Location: kernel/sched/sched.h:704
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffff80001015e4b4)
Location: kernel/sched/sched.h:704
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
In kernel/sched/fair.c (c0394668)
Location: kernel/sched/sched.h:704
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (c03aa5b4)
Location: kernel/sched/sched.h:704
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
In kernel/sched/fair.c (c000000000197414)
Location: kernel/sched/sched.h:704
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (c0000000001b32f8)
Location: kernel/sched/sched.h:704
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
In kernel/sched/fair.c (ffffffe0000f1f2a)
Location: kernel/sched/sched.h:704
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffe000102958)
Location: kernel/sched/sched.h:704
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
In kernel/sched/fair.c (ffffffff810e04ff)
Location: kernel/sched/sched.h:704
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff810f2f03)
Location: kernel/sched/sched.h:704
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
In kernel/sched/fair.c (ffffffff810cf4ff)
Location: kernel/sched/sched.h:704
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff810e3013)
Location: kernel/sched/sched.h:704
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
In kernel/sched/fair.c (ffffffff810dc87f)
Location: kernel/sched/sched.h:704
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff810f0033)
Location: kernel/sched/sched.h:704
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
In kernel/sched/fair.c (ffffffff810e85df)
Location: kernel/sched/sched.h:704
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff810fb0a3)
Location: kernel/sched/sched.h:704
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
</details>
</li>
</ul>

## Differences
