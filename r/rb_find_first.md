# Function: <code>rb_find_first</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81240350)
Location: include/linux/rbtree.h:311
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_first
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
In kernel/sched/core.c (ffffffff810ee965)
Location: include/linux/rbtree.h:284
Inline: True
```
```
In kernel/events/core.c (ffffffff8127ad20)
Location: include/linux/rbtree.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_first
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
In kernel/sched/core.c (ffffffff8110b1f5)
Location: include/linux/rbtree.h:284
Inline: True
```
```
In kernel/events/core.c (ffffffff812ce9f5)
Location: include/linux/rbtree.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_groups_first
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
In kernel/sched/core.c (ffffffff811315c5)
Location: include/linux/rbtree.h:284
Inline: True
```
```
In kernel/events/core.c (ffffffff81336e7b)
Location: include/linux/rbtree.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_event_to_rotate
  - kernel/events/core.c:ctx_event_to_rotate
  - kernel/events/core.c:ctx_event_to_rotate
  - kernel/events/core.c:perf_event_groups_first
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
In kernel/sched/core.c (ffffffff8113d2b5)
Location: include/linux/rbtree.h:284
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_find
```
```
In kernel/events/core.c (ffffffff81367beb)
Location: include/linux/rbtree.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_event_to_rotate
  - kernel/events/core.c:ctx_event_to_rotate
  - kernel/events/core.c:ctx_event_to_rotate
  - kernel/events/core.c:perf_event_groups_first
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
In kernel/sched/core.c (ffffffff81148425)
Location: include/linux/rbtree.h:284
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_find
```
```
In kernel/events/core.c (ffffffff81390b0b)
Location: include/linux/rbtree.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:ctx_event_to_rotate
  - kernel/events/core.c:ctx_event_to_rotate
  - kernel/events/core.c:ctx_event_to_rotate
  - kernel/events/core.c:perf_event_groups_first
```
```
In drivers/base/regmap/regcache.c (ffffffff81bc3aa6)
Location: include/linux/rbtree.h:284
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_sync
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
