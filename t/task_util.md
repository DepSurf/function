# Function: <code>task_util</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c4e32)
Location: kernel/sched/fair.c:5856
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff810b7d6d)
Location: kernel/sched/fair.c:5812
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff810bf46f)
Location: kernel/sched/fair.c:6258
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff810c732f)
Location: kernel/sched/fair.c:3934
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffff810d77a8)
Location: kernel/sched/fair.c:3608
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffff810dc8cf)
Location: kernel/sched/fair.c:3694
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffff810e6cf5)
Location: kernel/sched/fair.c:3693
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffff810eeaff)
Location: kernel/sched/fair.c:3882
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffff810ec958)
Location: kernel/sched/fair.c:3899
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffff810ef2f5)
Location: kernel/sched/fair.c:3947
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffff811078fe)
Location: kernel/sched/fair.c:3959
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffff81124b6a)
Location: kernel/sched/fair.c:4008
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffff8114cafd)
Location: kernel/sched/fair.c:4277
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:cpu_util_next
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffff8115b04f)
Location: kernel/sched/fair.c:4334
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffff8116c2f8)
Location: kernel/sched/fair.c:4821
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffff800010146c08)
Location: kernel/sched/fair.c:3693
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (c0396d28)
Location: kernel/sched/fair.c:3693
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (c0000000001980f8)
Location: kernel/sched/fair.c:3693
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffe0000f1e36)
Location: kernel/sched/fair.c:3693
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffff810e0ea5)
Location: kernel/sched/fair.c:3693
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffff810cff85)
Location: kernel/sched/fair.c:3693
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffff810dd225)
Location: kernel/sched/fair.c:3693
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffff810e8f92)
Location: kernel/sched/fair.c:3693
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
```
</details>
</li>
</ul>

## Differences
