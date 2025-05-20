# Function: <code>find_nth_bit</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81217979)
Location: include/linux/find.h:191
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:node_random
```
```
In mm/memory-tiers.c (ffffffff81437985)
Location: include/linux/find.h:191
Inline: True
Inline callers:
  - mm/memory-tiers.c:next_demotion_node
```
```
In lib/bitmap.c (ffffffff817ce328)
Location: include/linux/find.h:191
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_bitremap
```
```
In lib/cpumask.c (ffffffff8201fa70)
Location: include/linux/find.h:191
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
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
In kernel/cgroup/cpuset.c (ffffffff81234e49)
Location: include/linux/find.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
```
```
In mm/memory-tiers.c (ffffffff8146d645)
Location: include/linux/find.h:226
Inline: True
Inline callers:
  - mm/memory-tiers.c:next_demotion_node
```
```
In lib/bitmap.c (ffffffff8180c7d8)
Location: include/linux/find.h:226
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_bitremap
```
```
In lib/cpumask.c (ffffffff8209f91a)
Location: include/linux/find.h:226
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
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
In kernel/cgroup/cpuset.c (ffffffff8124ea69)
Location: include/linux/find.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
```
```
In kernel/trace/trace_events_filter.c (ffffffff812c6b70)
Location: include/linux/find.h:226
Inline: True
```
```
In mm/memory-tiers.c (ffffffff8149c7b5)
Location: include/linux/find.h:226
Inline: True
Inline callers:
  - mm/memory-tiers.c:next_demotion_node
```
```
In lib/bitmap.c (ffffffff818528e8)
Location: include/linux/find.h:226
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_bitremap
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
