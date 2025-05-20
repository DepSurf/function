# Function: <code>uclamp_is_used</code>

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
In kernel/sched/cpufreq_schedutil.c (ffffffff8110b48e)
Location: kernel/sched/sched.h:2408
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
In kernel/sched/cpufreq_schedutil.c (ffffffff8110834e)
Location: kernel/sched/sched.h:2531
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
In kernel/sched/core.c (ffffffff810e5140)
Location: kernel/sched/sched.h:2585
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
In kernel/sched/core.c (ffffffff810fc0cf)
Location: kernel/sched/sched.h:2892
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
In kernel/sched/core.c (ffffffff811185f0)
Location: kernel/sched/sched.h:3000
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
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
In kernel/sched/core.c (ffffffff8113fcdc)
Location: kernel/sched/sched.h:3108
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
```
```
In kernel/sched/fair.c (ffffffff8114cb53)
Location: kernel/sched/sched.h:3108
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:enqueue_task_fair
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
In kernel/sched/core.c (ffffffff8114c1d2)
Location: kernel/sched/sched.h:3092
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_util
```
```
In kernel/sched/fair.c (ffffffff8115b09f)
Location: kernel/sched/sched.h:3092
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:enqueue_task_fair
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
In kernel/sched/core.c (ffffffff81157db0)
Location: kernel/sched/sched.h:3095
Inline: True
```
```
In kernel/sched/fair.c (ffffffff8116c33e)
Location: kernel/sched/sched.h:3095
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:enqueue_task_fair
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
