# Function: <code>cfs_rq_load_avg</code>

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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:2877
Inline: True
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3145
Inline: True
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3422
Inline: True
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3527
Inline: True
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3869
Inline: True
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3927
Inline: True
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3601
Inline: True
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3687
Inline: True
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3688
Inline: True
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
In kernel/sched/fair.c (ffffffff810eec5a)
Location: kernel/sched/fair.c:3875
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_cfs_rq_h_load
  - kernel/sched/fair.c:update_cfs_rq_h_load
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:wake_affine_weight
  - kernel/sched/fair.c:wake_affine_weight
  - kernel/sched/fair.c:wake_affine_weight
  - kernel/sched/fair.c:wake_affine_weight
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (ffffffff810ecaa6)
Location: kernel/sched/fair.c:3892
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_cfs_rq_h_load
  - kernel/sched/fair.c:update_cfs_rq_h_load
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:wake_affine_weight
  - kernel/sched/fair.c:wake_affine_weight
  - kernel/sched/fair.c:wake_affine_weight
  - kernel/sched/fair.c:wake_affine_weight
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (ffffffff810ea4aa)
Location: kernel/sched/fair.c:3940
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (ffffffff8110c24d)
Location: kernel/sched/fair.c:3952
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (ffffffff81127c25)
Location: kernel/sched/fair.c:4001
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (ffffffff8115102f)
Location: kernel/sched/fair.c:4270
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (ffffffff811614b2)
Location: kernel/sched/fair.c:4327
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (ffffffff8116b822)
Location: kernel/sched/fair.c:4814
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:update_numa_stats
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3688
Inline: True
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
In kernel/sched/fair.c (c0395ec8)
Location: kernel/sched/fair.c:3688
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:task_h_load
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
In kernel/sched/fair.c (c00000000019814c)
Location: kernel/sched/fair.c:3688
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_cfs_rq_h_load
  - kernel/sched/fair.c:update_cfs_rq_h_load
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffe0000f1eac)
Location: kernel/sched/fair.c:3688
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_cfs_rq_h_load
  - kernel/sched/fair.c:update_cfs_rq_h_load
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3688
Inline: True
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3688
Inline: True
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3688
Inline: True
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3688
Inline: True
```
</details>
</li>
</ul>

## Differences
