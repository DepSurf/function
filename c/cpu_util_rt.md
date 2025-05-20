# Function: <code>cpu_util_rt</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810ee342)
Location: kernel/sched/sched.h:2262
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_freq_util
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f507b)
Location: kernel/sched/sched.h:2368
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff81100cfb)
Location: kernel/sched/sched.h:2411
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110b49c)
Location: kernel/sched/sched.h:2484
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
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
In kernel/sched/cpufreq_schedutil.c (ffffffff8110835c)
Location: kernel/sched/sched.h:2607
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
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
In kernel/sched/core.c (ffffffff810e514a)
Location: kernel/sched/sched.h:2658
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
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
In kernel/sched/core.c (ffffffff810fc0d6)
Location: kernel/sched/sched.h:2965
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
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
In kernel/sched/core.c (ffffffff811185f7)
Location: kernel/sched/sched.h:2915
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
```
```
In kernel/sched/build_utility.c (ffffffff81145d4a)
Location: kernel/sched/sched.h:2915
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
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
In kernel/sched/core.c (ffffffff8113fcde)
Location: kernel/sched/sched.h:3006
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
```
```
In kernel/sched/build_utility.c (ffffffff81172efa)
Location: kernel/sched/sched.h:3006
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
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
In kernel/sched/core.c (ffffffff8114c1d4)
Location: kernel/sched/sched.h:2990
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
```
```
In kernel/sched/build_utility.c (ffffffff81183e5d)
Location: kernel/sched/sched.h:2990
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
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
In kernel/sched/core.c (ffffffff81157e92)
Location: kernel/sched/sched.h:3046
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
```
```
In kernel/sched/build_utility.c (ffffffff81192562)
Location: kernel/sched/sched.h:3046
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffff8000101655a4)
Location: kernel/sched/sched.h:2411
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (c03b1af4)
Location: kernel/sched/sched.h:2411
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (c0000000001bc810)
Location: kernel/sched/sched.h:2411
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810fa00b)
Location: kernel/sched/sched.h:2411
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810ea1eb)
Location: kernel/sched/sched.h:2411
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f723d)
Location: kernel/sched/sched.h:2411
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff811022ab)
Location: kernel/sched/sched.h:2411
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
</details>
</li>
</ul>

## Differences
