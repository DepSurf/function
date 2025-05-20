# Function: <code>static_branch_UTIL_EST</code>

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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cf399)
Location: kernel/sched/features.h:92
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810e331a)
Location: kernel/sched/features.h:92
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d7853)
Location: kernel/sched/features.h:92
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/sched/pelt.c (ffffffff810e7217)
Location: kernel/sched/features.h:92
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810ee3b8)
Location: kernel/sched/features.h:92
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dc959)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/sched/pelt.c (ffffffff810edf75)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f5175)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e6d80)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/sched/pelt.c (ffffffff810f9b55)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81100df5)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eeba7)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/pelt.c (ffffffff81103bae)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110b605)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
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
In kernel/sched/fair.c (ffffffff810eca00)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/pelt.c (ffffffff811022aa)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff811084e4)
Location: kernel/sched/features.h:91
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
In kernel/sched/core.c (ffffffff810e512b)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
```
```
In kernel/sched/fair.c (ffffffff810ef396)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/pelt.c (ffffffff8110461e)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81109c94)
Location: kernel/sched/features.h:91
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
In kernel/sched/core.c (ffffffff810fc0b2)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
```
```
In kernel/sched/fair.c (ffffffff811079b7)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/pelt.c (ffffffff81121853)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81128066)
Location: kernel/sched/features.h:91
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
In kernel/sched/core.c (ffffffff811185b5)
Location: kernel/sched/features.h:97
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
```
```
In kernel/sched/fair.c (ffffffff81124c14)
Location: kernel/sched/features.h:97
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/build_policy.c (ffffffff81136cd3)
Location: kernel/sched/features.h:97
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_se
```
```
In kernel/sched/build_utility.c (ffffffff81145d2d)
Location: kernel/sched/features.h:97
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
In kernel/sched/core.c (ffffffff8113fca2)
Location: kernel/sched/features.h:97
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
```
```
In kernel/sched/fair.c (ffffffff8114cd15)
Location: kernel/sched/features.h:97
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/build_policy.c (ffffffff81161353)
Location: kernel/sched/features.h:97
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_se
```
```
In kernel/sched/build_utility.c (ffffffff81172edd)
Location: kernel/sched/features.h:97
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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8115e719)
Location: kernel/sched/features.h:97
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/sched/build_policy.c (ffffffff81171b8f)
Location: kernel/sched/features.h:97
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_se
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
In kernel/sched/fair.c (ffffffff8116cd09)
Location: kernel/sched/features.h:85
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/sched/build_policy.c (ffffffff8117f49f)
Location: kernel/sched/features.h:85
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:__update_load_avg_se
```
</details>
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
In kernel/sched/fair.c (ffff800010146c6c)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/sched/pelt.c (ffff80001015e4f0)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffff8000101656c0)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0000000001981b8)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/sched/pelt.c (c0000000001b3344)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (c0000000001bca08)
Location: kernel/sched/features.h:91
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e0f30)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/sched/pelt.c (ffffffff810f2f55)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810fa105)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d0010)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/sched/pelt.c (ffffffff810e3065)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810ea2e5)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dd2b0)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/sched/pelt.c (ffffffff810f0085)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f72c5)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e901d)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
```
```
In kernel/sched/pelt.c (ffffffff810fb0f5)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/pelt.c:__update_load_avg_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff811023a5)
Location: kernel/sched/features.h:91
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_get_util
```
</details>
</li>
</ul>

## Differences
