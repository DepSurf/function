# Function: <code>task_cfs_rq</code>

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
In kernel/sched/fair.c (ffffffff810b4d1c)
Location: kernel/sched/fair.c:269
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810b7864)
Location: kernel/sched/fair.c:269
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810bfb74)
Location: kernel/sched/fair.c:282
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810bb558)
Location: kernel/sched/fair.c:284
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810c32b8)
Location: kernel/sched/fair.c:286
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810c97b8)
Location: kernel/sched/fair.c:271
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810d3b9b)
Location: kernel/sched/fair.c:268
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810db09d)
Location: kernel/sched/fair.c:261
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810e4fad)
Location: kernel/sched/fair.c:261
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810ee51d)
Location: kernel/sched/fair.c:273
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:wake_affine_weight
  - kernel/sched/fair.c:wake_affine_weight
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
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
In kernel/sched/fair.c (ffffffff810ec33f)
Location: kernel/sched/fair.c:271
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:detach_tasks
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:wake_affine_weight
  - kernel/sched/fair.c:wake_affine_weight
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
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
In kernel/sched/fair.c (ffffffff810eecdf)
Location: kernel/sched/fair.c:281
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
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
In kernel/sched/fair.c (ffffffff811075b0)
Location: kernel/sched/sched.h:1380
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
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
In kernel/sched/fair.c (ffffffff811247ed)
Location: kernel/sched/sched.h:1366
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
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
In kernel/sched/fair.c (ffffffff8114c80d)
Location: kernel/sched/sched.h:1412
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
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
In kernel/sched/fair.c (ffffffff8115c7dd)
Location: kernel/sched/sched.h:1420
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
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
In kernel/sched/fair.c (ffffffff8116bd42)
Location: kernel/sched/sched.h:1439
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
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
In kernel/sched/fair.c (ffff800010144f50)
Location: kernel/sched/fair.c:261
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (c0392840)
Location: kernel/sched/fair.c:261
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_h_load
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
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
In kernel/sched/fair.c (c00000000019607c)
Location: kernel/sched/fair.c:261
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffe0000f18da)
Location: kernel/sched/fair.c:261
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff810df15d)
Location: kernel/sched/fair.c:261
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810ce16d)
Location: kernel/sched/fair.c:261
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810db4dd)
Location: kernel/sched/fair.c:261
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810e71cd)
Location: kernel/sched/fair.c:261
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:yield_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:check_preempt_wakeup
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
</details>
</li>
</ul>

## Differences
