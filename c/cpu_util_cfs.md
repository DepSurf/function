# Function: <code>cpu_util_cfs</code>

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
In kernel/sched/cpufreq_schedutil.c (ffffffff810e3310)
Location: kernel/sched/sched.h:2185
Inline: True
Inline callers:
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810ee3ab)
Location: kernel/sched/sched.h:2250
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810f5168)
Location: kernel/sched/sched.h:2356
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (ffffffff81100de8)
Location: kernel/sched/sched.h:2399
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (ffffffff8110b5f8)
Location: kernel/sched/sched.h:2472
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (ffffffff811084dd)
Location: kernel/sched/sched.h:2595
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/core.c (ffffffff810e5121)
Location: kernel/sched/sched.h:2646
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81109c8d)
Location: kernel/sched/sched.h:2646
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff810fc0aa)
Location: kernel/sched/sched.h:2953
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff8112805f)
Location: kernel/sched/sched.h:2953
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff81118575)
Location: kernel/sched/sched.h:2899
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
```
```
In kernel/sched/fair.c (ffffffff81124be9)
Location: kernel/sched/sched.h:2899
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/build_utility.c (ffffffff81145d04)
Location: kernel/sched/sched.h:2899
Inline: True
Inline callers:
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
In kernel/sched/core.c (ffffffff8113fc65)
Location: kernel/sched/sched.h:2990
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
```
```
In kernel/sched/fair.c (ffffffff8114ccfb)
Location: kernel/sched/sched.h:2990
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/build_utility.c (ffffffff81172eb4)
Location: kernel/sched/sched.h:2990
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
  - kernel/sched/build_utility.c:sugov_get_util
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int cpu_util_cfs(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8115b19d)
Location: kernel/sched/fair.c:7329
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:update_numa_stats
Direct callers:
  - kernel/sched/core.c:sched_cpu_util
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff81163b20-ffffffff81163bfd: cpu_util_cfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int cpu_util_cfs(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8116c3e3)
Location: kernel/sched/fair.c:7724
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:update_numa_stats
Direct callers:
  - kernel/sched/core.c:sched_cpu_util
  - kernel/sched/build_utility.c:sugov_update_single_perf
  - kernel/sched/build_utility.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff811708d0-ffffffff8117095a: cpu_util_cfs (STB_GLOBAL)
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
In kernel/sched/cpufreq_schedutil.c (ffff8000101656bc)
Location: kernel/sched/sched.h:2399
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (c03b1c08)
Location: kernel/sched/sched.h:2399
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (c0000000001bca04)
Location: kernel/sched/sched.h:2399
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810fa0f8)
Location: kernel/sched/sched.h:2399
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810ea2d8)
Location: kernel/sched/sched.h:2399
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (ffffffff810f72b8)
Location: kernel/sched/sched.h:2399
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/cpufreq_schedutil.c (ffffffff81102398)
Location: kernel/sched/sched.h:2399
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
