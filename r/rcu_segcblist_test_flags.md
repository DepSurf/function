# Function: <code>rcu_segcblist_test_flags</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81bd4712)
Location: kernel/rcu/rcu_segcblist.h:68
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81135405)
Location: kernel/rcu/rcu_segcblist.h:68
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_pend_cb
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_cb
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
In kernel/rcu/tree.c (ffffffff81caeae3)
Location: kernel/rcu/rcu_segcblist.h:68
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81157da5)
Location: kernel/rcu/rcu_segcblist.h:68
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_pend_cb
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_cb
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
In kernel/rcu/update.c (ffffffff811736d1)
Location: kernel/rcu/rcu_segcblist.h:68
Inline: True
Inline callers:
  - kernel/rcu/update.c:call_rcu_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff81e5f18c)
Location: kernel/rcu/rcu_segcblist.h:68
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811810f5)
Location: kernel/rcu/rcu_segcblist.h:68
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_pend_cb
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_cb
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
In kernel/rcu/update.c (ffffffff811aab09)
Location: kernel/rcu/rcu_segcblist.h:68
Inline: True
Inline callers:
  - kernel/rcu/update.c:call_rcu_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff811b7c12)
Location: kernel/rcu/rcu_segcblist.h:68
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811bba55)
Location: kernel/rcu/rcu_segcblist.h:68
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_pend_cb
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_cb
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
In kernel/rcu/update.c (ffffffff811bca39)
Location: kernel/rcu/rcu_segcblist.h:70
Inline: True
Inline callers:
  - kernel/rcu/update.c:call_rcu_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff811c96d2)
Location: kernel/rcu/rcu_segcblist.h:70
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811ce3f5)
Location: kernel/rcu/rcu_segcblist.h:70
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_pend_cb
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_cb
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
In kernel/rcu/update.c (ffffffff811cb86e)
Location: kernel/rcu/rcu_segcblist.h:70
Inline: True
Inline callers:
  - kernel/rcu/update.c:call_rcu_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff811def82)
Location: kernel/rcu/rcu_segcblist.h:70
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_spawn_cpu_nocb_kthread
  - kernel/rcu/tree.c:rcu_nocb_cpu_offload
  - kernel/rcu/tree.c:rcu_nocb_rdp_offload
  - kernel/rcu/tree.c:rcu_nocb_rdp_offload
  - kernel/rcu/tree.c:rcu_nocb_rdp_offload
  - kernel/rcu/tree.c:rcu_nocb_rdp_offload
  - kernel/rcu/tree.c:rcu_nocb_rdp_offload
  - kernel/rcu/tree.c:rcu_nocb_rdp_offload
  - kernel/rcu/tree.c:rcu_nocb_cpu_deoffload
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:rdp_offload_toggle
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:__call_rcu_nocb_wake
  - kernel/rcu/tree.c:__call_rcu_nocb_wake
  - kernel/rcu/tree.c:__call_rcu_nocb_wake
  - kernel/rcu/tree.c:__call_rcu_nocb_wake
  - kernel/rcu/tree.c:__call_rcu_nocb_wake
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_do_flush_bypass
  - kernel/rcu/tree.c:rcu_nocb_do_flush_bypass
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_report_qs_rdp
  - kernel/rcu/tree.c:rcu_report_qs_rdp
  - kernel/rcu/tree.c:rcu_report_qs_rdp
  - kernel/rcu/tree.c:rcu_report_qs_rdp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs_nowake
  - kernel/rcu/tree.c:rcu_advance_cbs_nowake
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_needs_cpu
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811e2fe5)
Location: kernel/rcu/rcu_segcblist.h:70
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_nextgp
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_pend_cb
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_first_cb
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
