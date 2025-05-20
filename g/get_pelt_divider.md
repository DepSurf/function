# Function: <code>get_pelt_divider</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eb27a)
Location: kernel/sched/pelt.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff81102cdd)
Location: kernel/sched/pelt.h:40
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffff810ed269)
Location: kernel/sched/pelt.h:40
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff81105022)
Location: kernel/sched/pelt.h:40
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffff81105f1d)
Location: kernel/sched/pelt.h:42
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/pelt.c (ffffffff81122a45)
Location: kernel/sched/pelt.h:42
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffff81120c4c)
Location: kernel/sched/pelt.h:42
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/build_policy.c (ffffffff811387f1)
Location: kernel/sched/pelt.h:42
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffff8114989a)
Location: kernel/sched/pelt.h:42
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/build_policy.c (ffffffff81162e81)
Location: kernel/sched/pelt.h:42
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffff8115974a)
Location: kernel/sched/pelt.h:42
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/build_policy.c (ffffffff8117351c)
Location: kernel/sched/pelt.h:42
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
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
In kernel/sched/fair.c (ffffffff81165d2a)
Location: kernel/sched/pelt.h:42
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_blocked_fair
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:reweight_entity
```
```
In kernel/sched/build_policy.c (ffffffff81180e4c)
Location: kernel/sched/pelt.h:42
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
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
