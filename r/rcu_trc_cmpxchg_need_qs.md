# Function: <code>rcu_trc_cmpxchg_need_qs</code>

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
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u8 rcu_trc_cmpxchg_need_qs(struct task_struct *t, u8 old, u8 new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811abdaa)
Location: kernel/rcu/tasks.h:1255
Inline: True
Inline callers:
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:rcu_read_unlock_trace_special
Direct callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:trc_read_check_handler
  - kernel/rcu/update.c:trc_read_check_handler
  - kernel/rcu/update.c:exit_tasks_rcu_finish
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_softirq_qs
```
**Symbols:**

```
ffffffff811a8c30-ffffffff811a8c7a: rcu_trc_cmpxchg_need_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u8 rcu_trc_cmpxchg_need_qs(struct task_struct *t, u8 old, u8 new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811bdcca)
Location: kernel/rcu/tasks.h:1292
Inline: True
Inline callers:
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:rcu_read_unlock_trace_special
Direct callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:trc_read_check_handler
  - kernel/rcu/update.c:trc_read_check_handler
  - kernel/rcu/update.c:exit_tasks_rcu_finish
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:kvfree_rcu_list
  - kernel/rcu/tree.c:kvfree_rcu_bulk
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_softirq_qs
  - kernel/trace/trace_osnoise.c:osnoise_sleep
```
**Symbols:**

```
ffffffff811ba980-ffffffff811ba9ca: rcu_trc_cmpxchg_need_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u8 rcu_trc_cmpxchg_need_qs(struct task_struct *t, u8 old, u8 new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811ce1ea)
Location: kernel/rcu/tasks.h:1408
Inline: True
Inline callers:
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:rcu_read_unlock_trace_special
Direct callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:trc_read_check_handler
  - kernel/rcu/update.c:trc_read_check_handler
  - kernel/rcu/update.c:exit_tasks_rcu_finish
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_nocb_cb_kthread
  - kernel/rcu/tree.c:rcu_nocb_gp_kthread
  - kernel/rcu/tree.c:kvfree_rcu_list
  - kernel/rcu/tree.c:kvfree_rcu_bulk
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_softirq_qs
  - kernel/trace/trace_osnoise.c:osnoise_sleep
```
**Symbols:**

```
ffffffff811ca910-ffffffff811ca95a: rcu_trc_cmpxchg_need_qs (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
