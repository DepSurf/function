# Function: <code>cpu_runnable_load</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e08ec)
Location: kernel/sched/fair.c:5428
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (ffffffff810eaf7c)
Location: kernel/sched/fair.c:5374
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:update_numa_stats
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/sched/fair.c (ffff80001014b0b8)
Location: kernel/sched/fair.c:5374
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (c0398e00)
Location: kernel/sched/fair.c:5374
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (c00000000019d654)
Location: kernel/sched/fair.c:5374
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:update_numa_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f49c6)
Location: kernel/sched/fair.c:5374
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
```
</details>
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
In kernel/sched/fair.c (ffffffff810e50dc)
Location: kernel/sched/fair.c:5374
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (ffffffff810d428c)
Location: kernel/sched/fair.c:5374
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (ffffffff810e14ac)
Location: kernel/sched/fair.c:5374
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (ffffffff810ed04c)
Location: kernel/sched/fair.c:5374
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:update_numa_stats
```
</details>
</li>
</ul>

## Differences
