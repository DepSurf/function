# Function: <code>effective_cpu_util</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int effective_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum cpu_util_type type, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e513d)
Location: kernel/sched/core.c:5911
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
Direct callers:
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
**Symbols:**

```
ffffffff810e4ea0-ffffffff810e50f5: effective_cpu_util (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int effective_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum cpu_util_type type, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fc0c3)
Location: kernel/sched/core.c:7074
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
Direct callers:
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
**Symbols:**

```
ffffffff810fbde0-ffffffff810fc061: effective_cpu_util (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int effective_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int max, enum cpu_util_type type, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811185e4)
Location: kernel/sched/core.c:7166
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
Direct callers:
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/build_utility.c:sugov_get_util
```
**Symbols:**

```
ffffffff81118290-ffffffff81118565: effective_cpu_util (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int effective_cpu_util(int cpu, long unsigned int util_cfs, enum cpu_util_type type, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113fcd0)
Location: kernel/sched/core.c:7307
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
Direct callers:
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/build_utility.c:sugov_get_util
```
**Symbols:**

```
ffffffff8113f930-ffffffff8113fc44: effective_cpu_util (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int effective_cpu_util(int cpu, long unsigned int util_cfs, enum cpu_util_type type, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114c1c1)
Location: kernel/sched/core.c:7408
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
Direct callers:
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/build_utility.c:sugov_get_util
```
**Symbols:**

```
ffffffff8114be80-ffffffff8114c185: effective_cpu_util (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int effective_cpu_util(int cpu, long unsigned int util_cfs, long unsigned int *min, long unsigned int *max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81157e81)
Location: kernel/sched/core.c:7471
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
Direct callers:
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/build_utility.c:sugov_get_util
```
**Symbols:**

```
ffffffff81157d50-ffffffff81157e47: effective_cpu_util (STB_GLOBAL)
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
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int max</code>
</li>
<li>
<b>Param reordered. </b>
<code>cpu, util_cfs, max, type, p</code> ➡️ <code>cpu, util_cfs, type, p</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int *min</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int *max</code>
</li>
<li>
<b>Param removed. </b>
<code>enum cpu_util_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *p</code>
</li>
</ul>
</details>
</li>
</ul>
