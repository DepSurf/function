# Function: <code>trace_pelt_cfs_tp</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dda43)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/pelt.c (ffffffff810ee260)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffff810e8103)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/pelt.c (ffffffff810f9e40)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffff810edbc0)
Location: include/trace/events/sched.h:609
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/pelt.c (ffffffff81103fb3)
Location: include/trace/events/sched.h:609
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffff810eb9f0)
Location: include/trace/events/sched.h:693
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/pelt.c (ffffffff8110265e)
Location: include/trace/events/sched.h:693
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffff810ed34e)
Location: include/trace/events/sched.h:693
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/pelt.c (ffffffff811049dc)
Location: include/trace/events/sched.h:693
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffff81105fdd)
Location: include/trace/events/sched.h:691
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/pelt.c (ffffffff81121ef2)
Location: include/trace/events/sched.h:691
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffff8112159b)
Location: include/trace/events/sched.h:694
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/build_policy.c (ffffffff81137405)
Location: include/trace/events/sched.h:694
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffff81148ac1)
Location: include/trace/events/sched.h:694
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/build_policy.c (ffffffff81161a95)
Location: include/trace/events/sched.h:694
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffff8115b2a6)
Location: include/trace/events/sched.h:694
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/build_policy.c (ffffffff811721ae)
Location: include/trace/events/sched.h:694
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffff8116c4c3)
Location: include/trace/events/sched.h:743
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/sched/build_policy.c (ffffffff8117fabe)
Location: include/trace/events/sched.h:743
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffff800010145ad0)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/pelt.c (ffff80001015e790)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (c0393790)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/pelt.c (c03aaab8)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (c000000000199698)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/pelt.c (c0000000001b37c8)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffe0000f0804)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
```
In kernel/sched/pelt.c (ffffffe000102bdc)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffff810e22b3)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/pelt.c (ffffffff810f3240)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffff810d1393)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/pelt.c (ffffffff810e3350)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffff810de633)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/pelt.c (ffffffff810f0370)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffff810ea133)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
```
```
In kernel/sched/pelt.c (ffffffff810fb3f0)
Location: include/trace/events/sched.h:604
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
```
</details>
</li>
</ul>

## Differences
