# Function: <code>rcu_seq_current</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f1aaa)
Location: kernel/rcu/rcu.h:122
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
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
In kernel/rcu/srcutree.c (ffffffff810fb81d)
Location: kernel/rcu/rcu.h:122
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
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
In kernel/rcu/srcutree.c (ffffffff81103d30)
Location: kernel/rcu/rcu.h:105
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
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
In kernel/rcu/srcutree.c (ffffffff8110ffe8)
Location: kernel/rcu/rcu.h:115
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcutorture_get_gp_data
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff81113bfc)
Location: kernel/rcu/rcu.h:115
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcutorture_get_gp_data
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
In kernel/rcu/srcutree.c (ffffffff81119735)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcutorture_get_gp_data
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff8111ddde)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcutorture_get_gp_data
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
In kernel/rcu/srcutree.c (ffffffff81125b05)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcutorture_get_gp_data
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff8112a3b7)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcutorture_get_gp_data
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
In kernel/rcu/srcutree.c (ffffffff81133414)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcutorture_get_gp_data
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_might_be_idle
  - kernel/rcu/srcutree.c:srcu_might_be_idle
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff81138d12)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcutorture_get_gp_data
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
In kernel/rcu/srcutree.c (ffffffff81be1f5f)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcutorture_get_gp_data
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_might_be_idle
  - kernel/rcu/srcutree.c:srcu_might_be_idle
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff81be26e5)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcutorture_get_gp_data
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
In kernel/rcu/srcutree.c (ffffffff81bd3fef)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcutorture_get_gp_data
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff81bd4688)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_check_gp_kthread_expired_fqs_timer
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcutorture_get_gp_data
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
In kernel/rcu/srcutree.c (ffffffff81cae15f)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcutorture_get_gp_data
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff81caea3b)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_check_gp_kthread_expired_fqs_timer
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcutorture_get_gp_data
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
In kernel/rcu/update.c (ffffffff81172bb3)
Location: kernel/rcu/rcu.h:99
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_rcu_tasks_generic_gp_kthread
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
```
```
In kernel/rcu/srcutree.c (ffffffff81175a46)
Location: kernel/rcu/rcu.h:99
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcutorture_get_gp_data
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff8117c81a)
Location: kernel/rcu/rcu.h:99
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_check_gp_kthread_expired_fqs_timer
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
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
In kernel/rcu/update.c (ffffffff811aa61d)
Location: kernel/rcu/rcu.h:98
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_rcu_tasks_generic_gp_kthread
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
```
```
In kernel/rcu/srcutree.c (ffffffff811ad76a)
Location: kernel/rcu/rcu.h:98
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcutorture_get_gp_data
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff811b68b5)
Location: kernel/rcu/rcu.h:98
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_check_gp_kthread_expired_fqs_timer
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
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
In kernel/rcu/update.c (ffffffff811bc551)
Location: kernel/rcu/rcu.h:135
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_rcu_tasks_generic_gp_kthread
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
```
```
In kernel/rcu/srcutree.c (ffffffff811bf49d)
Location: kernel/rcu/rcu.h:135
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcutorture_get_gp_data
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff811c72e5)
Location: kernel/rcu/rcu.h:135
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_check_gp_kthread_expired_fqs_timer
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
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
In kernel/rcu/update.c (ffffffff811ccb29)
Location: kernel/rcu/rcu.h:136
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_rcu_tasks_generic_gp_kthread
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
```
```
In kernel/rcu/srcutree.c (ffffffff811cf90d)
Location: kernel/rcu/rcu.h:136
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcutorture_get_gp_data
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff811d7805)
Location: kernel/rcu/rcu.h:136
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_check_gp_kthread_expired_fqs_timer
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcutree_report_cpu_starting
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs_nowake
  - kernel/rcu/tree.c:rcu_advance_cbs_nowake
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
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
In kernel/rcu/srcutree.c (ffff80001018bae8)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcutorture_get_gp_data
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffff800010192974)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcutorture_get_gp_data
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
In kernel/rcu/srcutree.c (c03d9bf8)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcutorture_get_gp_data
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (c03dfd5c)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcutorture_get_gp_data
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
In kernel/rcu/srcutree.c (c0000000001e6280)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcutorture_get_gp_data
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (c0000000001ed9c0)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcutorture_get_gp_data
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
In kernel/rcu/srcutree.c (ffffffe000120246)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcutorture_get_gp_data
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffe0001250fc)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcutorture_get_gp_data
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
In kernel/rcu/srcutree.c (ffffffff8111e0e5)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcutorture_get_gp_data
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff81122997)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcutorture_get_gp_data
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
In kernel/rcu/srcutree.c (ffffffff8110f151)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcutorture_get_gp_data
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff81115450)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs_nowake
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcutorture_get_gp_data
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
In kernel/rcu/srcutree.c (ffffffff8111bfd5)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcutorture_get_gp_data
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff81120887)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcutorture_get_gp_data
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
In kernel/rcu/srcutree.c (ffffffff81127703)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcutorture_get_gp_data
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff8112cb47)
Location: kernel/rcu/rcu.h:97
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rsp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
  - kernel/rcu/tree.c:rcutorture_get_gp_data
```
</details>
</li>
</ul>

## Differences
