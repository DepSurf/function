# Function: <code>uclamp_eff_value</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int uclamp_eff_value(struct task_struct *p, unsigned int clamp_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ce6f0)
Location: kernel/sched/core.c:883
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
**Symbols:**

```
ffffffff810ce6f0-ffffffff810ce738: uclamp_eff_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int uclamp_eff_value(struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d82f0)
Location: kernel/sched/core.c:921
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
**Symbols:**

```
ffffffff810d82f0-ffffffff810d8376: uclamp_eff_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int uclamp_eff_value(struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e2160)
Location: kernel/sched/core.c:941
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
**Symbols:**

```
ffffffff810e2160-ffffffff810e21e1: uclamp_eff_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int uclamp_eff_value(struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df500)
Location: kernel/sched/core.c:1100
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
**Symbols:**

```
ffffffff810df500-ffffffff810df589: uclamp_eff_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int uclamp_eff_value(struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1190)
Location: kernel/sched/core.c:1113
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
**Symbols:**

```
ffffffff810e1190-ffffffff810e121d: uclamp_eff_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int uclamp_eff_value(struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f71e0)
Location: kernel/sched/core.c:1467
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
**Symbols:**

```
ffffffff810f71e0-ffffffff810f7302: uclamp_eff_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int uclamp_eff_value(struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811136b0)
Location: kernel/sched/core.c:1510
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
```
**Symbols:**

```
ffffffff811136b0-ffffffff811137e6: uclamp_eff_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int uclamp_eff_value(struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113a810)
Location: kernel/sched/core.c:1498
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
```
**Symbols:**

```
ffffffff8113a810-ffffffff8113a946: uclamp_eff_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int uclamp_eff_value(struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81149bb0)
Location: kernel/sched/core.c:1520
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
```
**Symbols:**

```
ffffffff81149bb0-ffffffff81149ce6: uclamp_eff_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int uclamp_eff_value(struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811556b0)
Location: kernel/sched/core.c:1561
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
```
**Symbols:**

```
ffffffff811556b0-ffffffff811557e6: uclamp_eff_value (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
unsigned int uclamp_eff_value(struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010138b30)
Location: kernel/sched/core.c:921
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
**Symbols:**

```
ffff800010138b30-ffff800010138bf4: uclamp_eff_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int uclamp_eff_value(struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c03878b0)
Location: kernel/sched/core.c:921
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
**Symbols:**

```
c03878b0-c0387968: uclamp_eff_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int uclamp_eff_value(struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0000000001848b0)
Location: kernel/sched/core.c:921
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
**Symbols:**

```
c0000000001848b0-c000000000184968: uclamp_eff_value (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
unsigned int uclamp_eff_value(struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d27c0)
Location: kernel/sched/core.c:921
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
**Symbols:**

```
ffffffff810d27c0-ffffffff810d283e: uclamp_eff_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int uclamp_eff_value(struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c0df0)
Location: kernel/sched/core.c:921
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
**Symbols:**

```
ffffffff810c0df0-ffffffff810c0e76: uclamp_eff_value (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int uclamp_eff_value(struct task_struct *p, enum uclamp_id clamp_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d9f00)
Location: kernel/sched/core.c:921
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
  - kernel/sched/cpufreq_schedutil.c:schedutil_cpu_util
```
**Symbols:**

```
ffffffff810d9f00-ffffffff810d9f7e: uclamp_eff_value (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int clamp_id</code> ➡️ <code>enum uclamp_id clamp_id</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>long unsigned int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
