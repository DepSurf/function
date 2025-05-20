# Function: <code>topology_get_cpu_scale</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/sched/core.c (ffff800010136484)
Location: include/linux/arch_topology.h:21
Inline: True
```
```
In kernel/sched/fair.c (ffff80001014a218)
Location: include/linux/arch_topology.h:21
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/deadline.c (ffff80001015575c)
Location: include/linux/arch_topology.h:21
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/topology.c (ffff80001015b9a0)
Location: include/linux/arch_topology.h:21
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/cpufreq_schedutil.c (ffff8000101656d4)
Location: include/linux/arch_topology.h:21
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
```
In drivers/base/arch_topology.c (ffff8000109202bc)
Location: include/linux/arch_topology.h:21
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:topology_normalize_cpu_scale
  - drivers/base/arch_topology.c:cpu_capacity_show
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
In arch/arm/kernel/topology.c (c0319ad4)
Location: include/linux/arch_topology.h:21
Inline: True
Inline callers:
  - arch/arm/kernel/topology.c:store_cpu_topology
```
```
In kernel/sched/core.c (c0385328)
Location: include/linux/arch_topology.h:21
Inline: True
```
```
In kernel/sched/fair.c (c0397e60)
Location: include/linux/arch_topology.h:21
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:post_init_entity_util_avg
```
```
In kernel/sched/deadline.c (c03a30ec)
Location: include/linux/arch_topology.h:21
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
```
```
In kernel/sched/topology.c (c03a83f4)
Location: include/linux/arch_topology.h:21
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/cpufreq_schedutil.c (c03b1c1c)
Location: include/linux/arch_topology.h:21
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
```
In drivers/base/arch_topology.c (c0a05240)
Location: include/linux/arch_topology.h:21
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:topology_normalize_cpu_scale
  - drivers/base/arch_topology.c:cpu_capacity_show
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/arch_topology.c (ffffffe00059ef88)
Location: include/linux/arch_topology.h:21
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:topology_normalize_cpu_scale
  - drivers/base/arch_topology.c:cpu_capacity_show
```
</details>
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
