# Function: <code>cpu_util_dl</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810e3e9f)
Location: kernel/sched/sched.h:2180
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810ee353)
Location: kernel/sched/sched.h:2245
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810f50f3)
Location: kernel/sched/sched.h:2351
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
In kernel/sched/cpufreq_schedutil.c (ffffffff81100d73)
Location: kernel/sched/sched.h:2394
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
In kernel/sched/cpufreq_schedutil.c (ffffffff8110b51d)
Location: kernel/sched/sched.h:2467
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
In kernel/sched/cpufreq_schedutil.c (ffffffff811083dd)
Location: kernel/sched/sched.h:2590
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
In kernel/sched/core.c (ffffffff810e5151)
Location: kernel/sched/sched.h:2641
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
In kernel/sched/core.c (ffffffff810fc0dd)
Location: kernel/sched/sched.h:2948
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
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
In kernel/sched/core.c (ffffffff811185fe)
Location: kernel/sched/sched.h:2862
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
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
In kernel/sched/core.c (ffffffff8113fce5)
Location: kernel/sched/sched.h:2953
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114c1dc)
Location: kernel/sched/sched.h:2981
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
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
In kernel/sched/core.c (ffffffff81157e9a)
Location: kernel/sched/sched.h:3037
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
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
In kernel/sched/cpufreq_schedutil.c (ffff800010165608)
Location: kernel/sched/sched.h:2394
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
In kernel/sched/cpufreq_schedutil.c (c03b1b64)
Location: kernel/sched/sched.h:2394
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
In kernel/sched/cpufreq_schedutil.c (c0000000001bc820)
Location: kernel/sched/sched.h:2394
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810fa083)
Location: kernel/sched/sched.h:2394
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810ea263)
Location: kernel/sched/sched.h:2394
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810f724d)
Location: kernel/sched/sched.h:2394
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
In kernel/sched/cpufreq_schedutil.c (ffffffff81102323)
Location: kernel/sched/sched.h:2394
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
</details>
</li>
</ul>

## Differences
