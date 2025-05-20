# Function: <code>uclamp_rq_util_with</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eaade)
Location: kernel/sched/sched.h:2372
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_energy_efficient_cpu
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110b4af)
Location: kernel/sched/sched.h:2372
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
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
In kernel/sched/fair.c (ffffffff810e868e)
Location: kernel/sched/sched.h:2495
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_energy_efficient_cpu
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110836f)
Location: kernel/sched/sched.h:2495
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
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
In kernel/sched/core.c (ffffffff810e4ee6)
Location: kernel/sched/sched.h:2542
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810e9c60)
Location: kernel/sched/sched.h:2542
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_energy_efficient_cpu
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
In kernel/sched/core.c (ffffffff810fbe3b)
Location: kernel/sched/sched.h:2849
Inline: True
```
```
In kernel/sched/fair.c (ffffffff8110151e)
Location: kernel/sched/sched.h:2849
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_energy_efficient_cpu
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
In kernel/sched/core.c (ffffffff811182ed)
Location: kernel/sched/sched.h:2942
Inline: True
```
```
In kernel/sched/fair.c (ffffffff8111cc64)
Location: kernel/sched/sched.h:2942
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_energy_efficient_cpu
```
```
In kernel/sched/build_utility.c (ffffffff8113ea66)
Location: kernel/sched/sched.h:2942
Inline: True
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
In kernel/sched/core.c (ffffffff8113f985)
Location: kernel/sched/sched.h:3050
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff81169046)
Location: kernel/sched/sched.h:3050
Inline: True
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
In kernel/sched/core.c (ffffffff8114bed4)
Location: kernel/sched/sched.h:3034
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff811797cc)
Location: kernel/sched/sched.h:3034
Inline: True
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
