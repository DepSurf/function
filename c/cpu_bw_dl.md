# Function: <code>cpu_bw_dl</code>

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
In kernel/sched/cpufreq_schedutil.c (ffffffff810ee61b)
Location: kernel/sched/sched.h:2240
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810f540b)
Location: kernel/sched/sched.h:2346
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (ffffffff811010bb)
Location: kernel/sched/sched.h:2389
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (ffffffff8110b9d8)
Location: kernel/sched/sched.h:2462
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (ffffffff81108726)
Location: kernel/sched/sched.h:2585
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff810e4ffb)
Location: kernel/sched/sched.h:2636
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110a786)
Location: kernel/sched/sched.h:2636
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff810fbeee)
Location: kernel/sched/sched.h:2943
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81128e93)
Location: kernel/sched/sched.h:2943
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_perf
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff81118381)
Location: kernel/sched/sched.h:2857
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff81145641)
Location: kernel/sched/sched.h:2857
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
  - kernel/sched/build_utility.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff8113fac2)
Location: kernel/sched/sched.h:2948
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff811727c1)
Location: kernel/sched/sched.h:2948
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
  - kernel/sched/build_utility.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff8114bf71)
Location: kernel/sched/sched.h:2976
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff81183871)
Location: kernel/sched/sched.h:2976
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
  - kernel/sched/build_utility.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff81157d91)
Location: kernel/sched/sched.h:3032
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff81191fad)
Location: kernel/sched/sched.h:3032
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_update_shared
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
In kernel/sched/cpufreq_schedutil.c (ffff800010165a28)
Location: kernel/sched/sched.h:2389
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (c03b1f64)
Location: kernel/sched/sched.h:2389
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (c0000000001bcdf8)
Location: kernel/sched/sched.h:2389
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810fa3cb)
Location: kernel/sched/sched.h:2389
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810ea5ab)
Location: kernel/sched/sched.h:2389
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810f758b)
Location: kernel/sched/sched.h:2389
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (ffffffff8110266b)
Location: kernel/sched/sched.h:2389
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
</details>
</li>
</ul>

## Differences
