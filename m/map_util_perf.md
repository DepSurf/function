# Function: <code>map_util_perf</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff811089b8)
Location: include/linux/sched/cpufreq.h:32
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
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
In kernel/sched/cpufreq_schedutil.c (ffffffff8110a6a9)
Location: include/linux/sched/cpufreq.h:32
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
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
In kernel/sched/fair.c (ffffffff8110131c)
Location: include/linux/sched/cpufreq.h:32
Inline: True
Inline callers:
  - kernel/sched/fair.c:compute_energy
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81128d8b)
Location: include/linux/sched/cpufreq.h:32
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
  - kernel/sched/cpufreq_schedutil.c:get_next_freq
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
In kernel/sched/fair.c (ffffffff8111ca33)
Location: include/linux/sched/cpufreq.h:32
Inline: True
Inline callers:
  - kernel/sched/fair.c:compute_energy
```
```
In kernel/sched/build_utility.c (ffffffff81145d83)
Location: include/linux/sched/cpufreq.h:32
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:get_next_freq
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
In kernel/sched/fair.c (ffffffff811463c4)
Location: include/linux/sched/cpufreq.h:32
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_energy_efficient_cpu
```
```
In kernel/sched/build_utility.c (ffffffff81172f33)
Location: include/linux/sched/cpufreq.h:32
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:get_next_freq
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
In kernel/sched/fair.c (ffffffff811541d8)
Location: include/linux/sched/cpufreq.h:32
Inline: True
Inline callers:
  - kernel/sched/fair.c:compute_energy
```
```
In kernel/sched/build_utility.c (ffffffff81183e88)
Location: include/linux/sched/cpufreq.h:32
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_perf
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
In kernel/sched/build_utility.c (ffffffff81185736)
Location: include/linux/sched/cpufreq.h:32
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_get_util
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
