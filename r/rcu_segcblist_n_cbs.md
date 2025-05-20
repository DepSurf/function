# Function: <code>rcu_segcblist_n_cbs</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f69d3)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_dead_cpu
  - kernel/rcu/tree.c:rcutree_dead_cpu
  - kernel/rcu/tree.c:rcutree_dead_cpu
  - kernel/rcu/tree.c:rcutree_dead_cpu
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff810f7245)
Location: kernel/rcu/rcu_segcblist.h:78
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/tree.c (ffffffff81100b10)
Location: kernel/rcu/rcu_segcblist.h:56
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81101145)
Location: kernel/rcu/rcu_segcblist.h:56
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/tree.c (ffffffff811089e7)
Location: kernel/rcu/rcu_segcblist.h:56
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811095c5)
Location: kernel/rcu/rcu_segcblist.h:56
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/tree.c (ffffffff81113df5)
Location: kernel/rcu/rcu_segcblist.h:56
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81114d95)
Location: kernel/rcu/rcu_segcblist.h:56
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffff8111818f)
Location: kernel/rcu/rcu_segcblist.h:43
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff8111de94)
Location: kernel/rcu/rcu_segcblist.h:43
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff8111ebc5)
Location: kernel/rcu/rcu_segcblist.h:43
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffff81124567)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff8112a466)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff8112b275)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffff81131ccb)
Location: kernel/rcu/rcu_segcblist.h:44
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff81138dc1)
Location: kernel/rcu/rcu_segcblist.h:44
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81139805)
Location: kernel/rcu/rcu_segcblist.h:44
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffff8112d4ab)
Location: kernel/rcu/rcu_segcblist.h:44
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff81be2794)
Location: kernel/rcu/rcu_segcblist.h:44
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811342d5)
Location: kernel/rcu/rcu_segcblist.h:44
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffff8112dacb)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff81bd4739)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811350f5)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffff8114edb6)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff81caeb0a)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811578f5)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/update.c (ffffffff811739a2)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
```
```
In kernel/rcu/srcutree.c (ffffffff81175e54)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff81e5f1b7)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81180bb5)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/update.c (ffffffff811a9892)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
```
```
In kernel/rcu/srcutree.c (ffffffff811ad582)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff811b7c1e)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811bb4a5)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/update.c (ffffffff811bb782)
Location: kernel/rcu/rcu_segcblist.h:49
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
```
```
In kernel/rcu/srcutree.c (ffffffff811bf762)
Location: kernel/rcu/rcu_segcblist.h:49
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff811c96de)
Location: kernel/rcu/rcu_segcblist.h:49
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811cde45)
Location: kernel/rcu/rcu_segcblist.h:49
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/update.c (ffffffff811cbc46)
Location: kernel/rcu/rcu_segcblist.h:49
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:call_rcu_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811cfbd2)
Location: kernel/rcu/rcu_segcblist.h:49
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff811d3dff)
Location: kernel/rcu/rcu_segcblist.h:49
Inline: True
Inline callers:
  - kernel/rcu/tree.c:show_rcu_nocb_state
  - kernel/rcu/tree.c:__call_rcu_nocb_wake
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811e2a55)
Location: kernel/rcu/rcu_segcblist.h:49
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffff800010189ab0)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffff800010192a30)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/rcu/rcu_segcblist.c (ffff8000101933d4)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (c03d8528)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
```
```
In kernel/rcu/tree.c (c03dfe1c)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/rcu/rcu_segcblist.c (c03e0700)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (c0000000001e400c)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (c0000000001edaa4)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/rcu/rcu_segcblist.c (c0000000001ee428)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffe00011ec0a)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffe0001251c8)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/rcu/rcu_segcblist.c (ffffffe0001259a4)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffff8111cb47)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff81122a46)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81123855)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffff8110dc07)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff811154ff)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81116305)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffff8111aa37)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff81120936)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81121745)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffff81126317)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff8112cc0b)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff8112dd55)
Location: kernel/rcu/rcu_segcblist.h:53
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_entrain
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
```
</details>
</li>
</ul>

## Differences
