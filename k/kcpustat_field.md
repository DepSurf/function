# Function: <code>kcpustat_field</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_governor.c (ffffffff819995a1)
Location: include/linux/kernel_stat.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
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
In drivers/cpufreq/cpufreq_governor.c (ffffffff8199c681)
Location: include/linux/kernel_stat.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
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
In drivers/cpufreq/cpufreq_governor.c (ffffffff81981351)
Location: include/linux/kernel_stat.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
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
In drivers/cpufreq/cpufreq_governor.c (ffffffff81a2a5db)
Location: include/linux/kernel_stat.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
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
In drivers/cpufreq/cpufreq_governor.c (ffffffff81b94903)
Location: include/linux/kernel_stat.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
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
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d3568a)
Location: include/linux/kernel_stat.h:88
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
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
In kernel/rcu/tree.c (ffffffff811c49e6)
Location: include/linux/kernel_stat.h:100
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d9e9fa)
Location: include/linux/kernel_stat.h:100
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 kcpustat_field(struct kernel_cpustat *kcpustat, enum cpu_usage_stat usage, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/cputime.c:980
Inline: False
Direct callers:
  - kernel/rcu/tree.c:print_cpu_stat_info
  - kernel/rcu/tree.c:print_cpu_stat_info
  - kernel/rcu/tree.c:print_cpu_stat_info
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
```
**Symbols:**

```
ffffffff821b0b67-ffffffff821b0b8c: kcpustat_field.cold (STB_LOCAL)
ffffffff811764d0-ffffffff81176627: kcpustat_field (STB_GLOBAL)
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
<b>Regular</b>
<ul>
</ul>
