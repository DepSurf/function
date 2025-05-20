# Function: <code>rcu_seq_state</code>

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
In kernel/rcu/srcutree.c (ffffffff810f199b)
Location: kernel/rcu/rcu.h:80
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff810f451b)
Location: kernel/rcu/rcu.h:80
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
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
In kernel/rcu/srcutree.c (ffffffff810fb70b)
Location: kernel/rcu/rcu.h:80
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff810fe3f1)
Location: kernel/rcu/rcu.h:80
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
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
In kernel/rcu/srcutree.c (ffffffff81103b87)
Location: kernel/rcu/rcu.h:57
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:_cleanup_srcu_struct
  - kernel/rcu/srcutree.c:_cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff81106794)
Location: kernel/rcu/rcu.h:57
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:_rcu_barrier
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
In kernel/rcu/srcutree.c (ffffffff828ae3c6)
Location: kernel/rcu/rcu.h:57
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:_cleanup_srcu_struct
  - kernel/rcu/srcutree.c:_cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff8111168a)
Location: kernel/rcu/rcu.h:57
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffffffff828c6da6)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff8111b490)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffffffff828cf3bb)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff8112783b)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffffffff81132c55)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff811378f1)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
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
In kernel/rcu/srcutree.c (ffffffff8112e435)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff81132f31)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
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
In kernel/rcu/srcutree.c (ffffffff8112ea55)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff811324a1)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
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
In kernel/rcu/srcutree.c (ffffffff8114ff35)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff81154883)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
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
In kernel/rcu/update.c (ffffffff8117425c)
Location: kernel/rcu/rcu.h:41
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff81176a60)
Location: kernel/rcu/rcu.h:41
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_funnel_exp_start
  - kernel/rcu/srcutree.c:srcu_funnel_exp_start
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:srcu_get_delay
```
```
In kernel/rcu/tree.c (ffffffff8117c821)
Location: kernel/rcu/rcu.h:41
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
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
In kernel/rcu/update.c (ffffffff811a9c11)
Location: kernel/rcu/rcu.h:40
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_one_gp
  - kernel/rcu/update.c:rcu_tasks_one_gp
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811ace40)
Location: kernel/rcu/rcu.h:40
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_funnel_exp_start
  - kernel/rcu/srcutree.c:srcu_funnel_exp_start
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:srcu_get_delay
```
```
In kernel/rcu/tree.c (ffffffff811b68bc)
Location: kernel/rcu/rcu.h:40
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_poll_gp_seq_end_unlocked
  - kernel/rcu/tree.c:rcu_poll_gp_seq_start_unlocked
  - kernel/rcu/tree.c:rcu_poll_gp_seq_start_unlocked
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
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
In kernel/rcu/update.c (ffffffff811bbb01)
Location: kernel/rcu/rcu.h:77
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_one_gp
  - kernel/rcu/update.c:rcu_tasks_one_gp
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811bf8e8)
Location: kernel/rcu/rcu.h:77
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_module_notify
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff811c72ec)
Location: kernel/rcu/rcu.h:77
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_poll_gp_seq_end_unlocked
  - kernel/rcu/tree.c:rcu_poll_gp_seq_start_unlocked
  - kernel/rcu/tree.c:rcu_poll_gp_seq_start_unlocked
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
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
In kernel/rcu/update.c (ffffffff811cbffd)
Location: kernel/rcu/rcu.h:78
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_one_gp
  - kernel/rcu/update.c:rcu_tasks_one_gp
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811cfd58)
Location: kernel/rcu/rcu.h:78
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_module_notify
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_advance_state
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff811d780c)
Location: kernel/rcu/rcu.h:78
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_poll_gp_seq_end_unlocked
  - kernel/rcu/tree.c:rcu_poll_gp_seq_start_unlocked
  - kernel/rcu/tree.c:rcu_poll_gp_seq_start_unlocked
  - kernel/rcu/tree.c:rcu_advance_cbs_nowake
  - kernel/rcu/tree.c:rcu_advance_cbs_nowake
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
  - kernel/rcu/tree.c:rcu_start_this_gp
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
In kernel/rcu/srcutree.c (ffff800011446ad8)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffff80001018fd90)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (c152117c)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (c03dbcf0)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (c00000000136ba1c)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (c0000000001e8ea4)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffffffe000008586)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffe0001223e8)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffffffff828b80b3)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff8111fe1b)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffffffff828b0333)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff8111181b)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_advance_cbs_nowake
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffffffff828cafef)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff8111dd0b)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffffffff828d03e8)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
```
In kernel/rcu/tree.c (ffffffff81128c6f)
Location: kernel/rcu/rcu.h:39
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rsp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
</details>
</li>
</ul>

## Differences
