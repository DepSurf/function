# Function: <code>__for_each_wrap</code>

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
In kernel/sched/core.c (ffffffff8113cef1)
Location: include/linux/find.h:377
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:pick_next_task
```
```
In kernel/sched/fair.c (ffffffff81145668)
Location: include/linux/find.h:377
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_utility.c (ffffffff811722e4)
Location: include/linux/find.h:377
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/bpf/percpu_freelist.c (ffffffff812ffa21)
Location: include/linux/find.h:377
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
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
In kernel/sched/core.c (ffffffff81151a4f)
Location: include/linux/find.h:442
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:pick_next_task
```
```
In kernel/sched/fair.c (ffffffff81156403)
Location: include/linux/find.h:442
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_utility.c (ffffffff81182604)
Location: include/linux/find.h:442
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/bpf/percpu_freelist.c (ffffffff8132e581)
Location: include/linux/find.h:442
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
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
In kernel/sched/core.c (ffffffff8115d92f)
Location: include/linux/find.h:442
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:pick_next_task
```
```
In kernel/sched/fair.c (ffffffff81162ddf)
Location: include/linux/find.h:442
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_utility.c (ffffffff81190e64)
Location: include/linux/find.h:442
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/bpf/percpu_freelist.c (ffffffff81352aa1)
Location: include/linux/find.h:442
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
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
