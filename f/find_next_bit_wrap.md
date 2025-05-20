# Function: <code>find_next_bit_wrap</code>

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
In kernel/sched/core.c (ffffffff8113ce72)
Location: include/linux/find.h:360
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
```
```
In kernel/sched/fair.c (ffffffff811455dc)
Location: include/linux/find.h:360
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_utility.c (ffffffff8117222a)
Location: include/linux/find.h:360
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/bpf/percpu_freelist.c (ffffffff812ff967)
Location: include/linux/find.h:360
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
```
```
In lib/cpumask.c (ffffffff8201f865)
Location: include/linux/find.h:360
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
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
In kernel/sched/core.c (ffffffff811519ae)
Location: include/linux/find.h:425
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
```
```
In kernel/sched/fair.c (ffffffff81156371)
Location: include/linux/find.h:425
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_utility.c (ffffffff8118254a)
Location: include/linux/find.h:425
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/bpf/percpu_freelist.c (ffffffff8132e4c7)
Location: include/linux/find.h:425
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
```
```
In lib/cpumask.c (ffffffff8209f875)
Location: include/linux/find.h:425
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
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
In kernel/sched/core.c (ffffffff8115d88e)
Location: include/linux/find.h:425
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
```
```
In kernel/sched/fair.c (ffffffff81162d25)
Location: include/linux/find.h:425
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_utility.c (ffffffff81190daa)
Location: include/linux/find.h:425
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/bpf/percpu_freelist.c (ffffffff813529e7)
Location: include/linux/find.h:425
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
```
```
In lib/cpumask.c (ffffffff821778d5)
Location: include/linux/find.h:425
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_any_distribute
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
