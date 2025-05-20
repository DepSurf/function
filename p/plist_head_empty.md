# Function: <code>plist_head_empty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810bef45)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff810cbf8a)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_dbg_show_requests
  - kernel/power/qos.c:pm_qos_dbg_show_requests
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
```
```
In lib/plist.c (ffffffff813ede42)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - lib/plist.c:plist_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c2c1a)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff810d0c73)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_dbg_show_requests
  - kernel/power/qos.c:pm_qos_dbg_show_requests
```
```
In lib/plist.c (ffffffff814340b0)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c8c6a)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff810d76e3)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_dbg_show_requests
  - kernel/power/qos.c:pm_qos_dbg_show_requests
```
```
In lib/plist.c (ffffffff81450340)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c4647)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff810d6733)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_dbg_show_requests
  - kernel/power/qos.c:pm_qos_dbg_show_requests
```
```
In mm/swapfile.c (ffffffff8120fe35)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffffffff818f00a0)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810cbce7)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff810de6c3)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_dbg_show_requests
  - kernel/power/qos.c:pm_qos_dbg_show_requests
```
```
In mm/swapfile.c (ffffffff8122bde5)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffffffff819764f0)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d2c17)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff810e6d12)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_dbg_show_requests
  - kernel/power/qos.c:pm_qos_dbg_show_requests
```
```
In mm/swapfile.c (ffffffff8124d0a5)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffffffff819d2cb0)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810dc667)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff810f2312)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In mm/swapfile.c (ffffffff812614a5)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffffffff81a0c330)
Location: include/linux/plist.h:212
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810e3607)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:set_curr_task_rt
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff810fa7c5)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In mm/swapfile.c (ffffffff8127c415)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffffffff81a7bc90)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810efc5c)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff81106665)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In mm/swapfile.c (ffffffff8128bef5)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffffffff81ab2ff0)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810f95a9)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff81111365)
Location: include/linux/plist.h:210
Inline: True
```
```
In mm/swapfile.c (ffffffff812bedf5)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffffffff815ed880)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810f789e)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff8110e4e5)
Location: include/linux/plist.h:210
Inline: True
```
```
In mm/swapfile.c (ffffffff812caa15)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffffffff81611fb0)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810f9643)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff8110efc5)
Location: include/linux/plist.h:210
Inline: True
```
```
In mm/swapfile.c (ffffffff812d14f5)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffffffff815f56a0)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff81112e31)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff8112e8b8)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
```
```
In mm/swapfile.c (ffffffff81316bf5)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffffffff81662b00)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/sched/build_policy.c (ffffffff81130110)
Location: include/linux/plist.h:213
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff8114fcee)
Location: include/linux/plist.h:213
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
```
```
In mm/swapfile.c (ffffffff81382216)
Location: include/linux/plist.h:213
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffffffff8177c9e0)
Location: include/linux/plist.h:213
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/sched/build_policy.c (ffffffff8115a381)
Location: include/linux/plist.h:213
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff8117e59e)
Location: include/linux/plist.h:213
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
```
```
In mm/swapfile.c (ffffffff81400a26)
Location: include/linux/plist.h:213
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffffffff82039430)
Location: include/linux/plist.h:213
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/sched/build_policy.c (ffffffff8116a591)
Location: include/linux/plist.h:213
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff8118f1fe)
Location: include/linux/plist.h:213
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
```
```
In mm/swapfile.c (ffffffff814338c6)
Location: include/linux/plist.h:213
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffffffff820b7750)
Location: include/linux/plist.h:213
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/sched/build_policy.c (ffffffff81177c51)
Location: include/linux/plist.h:203
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
  - kernel/sched/build_policy.c:pick_next_pushable_task
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff8119dbae)
Location: include/linux/plist.h:203
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
```
```
In mm/swapfile.c (ffffffff8146ccb6)
Location: include/linux/plist.h:203
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffffffff82192060)
Location: include/linux/plist.h:203
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffff800010151084)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffff80001016cdb8)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In mm/swapfile.c (ffff800010327600)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffff800010d8d2a0)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039c324)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (c03b818c)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In mm/swapfile.c (c053ea68)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (c0e877a4)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a1f64)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (c0000000001c4740)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In mm/swapfile.c (c0000000003fe24c)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (c000000000ecf530)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f9b4e)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffe00010ca5c)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In mm/swapfile.c (ffffffe0002274d2)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffffffe0008b5f2c)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
```
</details>
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
In kernel/sched/rt.c (ffffffff810e954c)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff810ff975)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In mm/swapfile.c (ffffffff812844d5)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffffffff81a51e40)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810d9017)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff810efb65)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In mm/swapfile.c (ffffffff81276365)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffffffff81a0ef40)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810e618c)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff810fcb35)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In mm/swapfile.c (ffffffff812822e5)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffffffff81abe230)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
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
In kernel/sched/rt.c (ffffffff810efe85)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:pick_next_pushable_task
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:dequeue_task_rt
```
```
In kernel/power/qos.c (ffffffff81107d65)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_read
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_update_target
  - kernel/power/qos.c:pm_qos_debug_show
  - kernel/power/qos.c:pm_qos_debug_show
```
```
In mm/swapfile.c (ffffffff81291fd6)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - mm/swapfile.c:has_usable_swap
```
```
In lib/plist.c (ffffffff81aca6d0)
Location: include/linux/plist.h:210
Inline: True
Inline callers:
  - lib/plist.c:plist_requeue
  - lib/plist.c:plist_add
```
</details>
</li>
</ul>

## Differences
