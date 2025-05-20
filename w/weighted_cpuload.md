# Function: <code>weighted_cpuload</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b342a)
Location: kernel/sched/fair.c:4362
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:update_cpu_load_active
  - kernel/sched/fair.c:run_rebalance_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c1bf9)
Location: kernel/sched/fair.c:4755
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:cpu_load_update_active
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:cpu_load_update_nohz_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c7c49)
Location: kernel/sched/fair.c:4985
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:cpu_load_update_active
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:cpu_load_update_nohz_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c190d)
Location: kernel/sched/fair.c:5128
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:cpu_load_update_active
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:cpu_load_update_nohz_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c7e6b)
Location: kernel/sched/fair.c:5467
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:cpu_load_update_active
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d0a5f)
Location: kernel/sched/fair.c:5663
Inline: True
Inline callers:
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:cpu_load_update_active
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:cpu_load_update_nohz_start
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
In kernel/sched/fair.c (ffffffff810da29f)
Location: kernel/sched/fair.c:5403
Inline: True
Inline callers:
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:cpu_load_update_active
  - kernel/sched/fair.c:cpu_load_update_nohz_stop
  - kernel/sched/fair.c:cpu_load_update_nohz_start
```
</details>
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
