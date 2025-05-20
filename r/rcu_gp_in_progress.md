# Function: <code>rcu_gp_in_progress</code>

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
In kernel/rcu/tree.c (ffffffff810e4635)
Location: kernel/rcu/tree.c:236
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
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
In kernel/rcu/tree.c (ffffffff810ee385)
Location: kernel/rcu/tree.c:236
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (ffffffff810f5465)
Location: kernel/rcu/tree.c:237
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (ffffffff810f6208)
Location: kernel/rcu/tree.c:222
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (ffffffff811000ad)
Location: kernel/rcu/tree.c:219
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (ffffffff81106ab4)
Location: kernel/rcu/tree.c:219
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
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
In kernel/rcu/tree.c (ffffffff81112d4b)
Location: kernel/rcu/tree.c:205
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (ffffffff8111ddde)
Location: kernel/rcu/tree.c:200
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (ffffffff8112a3b7)
Location: kernel/rcu/tree.c:201
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (ffffffff81138d12)
Location: kernel/rcu/tree.c:212
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_start_this_gp
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
In kernel/rcu/tree.c (ffffffff81be26e5)
Location: kernel/rcu/tree.c:217
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_start_this_gp
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
In kernel/rcu/tree.c (ffffffff81bd4688)
Location: kernel/rcu/tree.c:223
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_start_this_gp
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
In kernel/rcu/tree.c (ffffffff81caea3b)
Location: kernel/rcu/tree.c:229
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_start_this_gp
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
In kernel/rcu/tree.c (ffffffff8117c81a)
Location: kernel/rcu/tree.c:240
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_start_this_gp
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
In kernel/rcu/tree.c (ffffffff811b68b5)
Location: kernel/rcu/tree.c:243
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_start_this_gp
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
In kernel/rcu/tree.c (ffffffff811c72e5)
Location: kernel/rcu/tree.c:224
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_start_this_gp
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
In kernel/rcu/tree.c (ffffffff811d7805)
Location: kernel/rcu/tree.c:225
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_start_this_gp
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
In kernel/rcu/tree.c (ffff800010192974)
Location: kernel/rcu/tree.c:201
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (c03dfd5c)
Location: kernel/rcu/tree.c:201
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (c0000000001ed9c0)
Location: kernel/rcu/tree.c:201
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (ffffffe0001250fc)
Location: kernel/rcu/tree.c:201
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (ffffffff81122997)
Location: kernel/rcu/tree.c:201
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (ffffffff81115450)
Location: kernel/rcu/tree.c:201
Inline: True
Inline callers:
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
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (ffffffff81120887)
Location: kernel/rcu/tree.c:201
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/tree.c (ffffffff8112cb47)
Location: kernel/rcu/tree.c:201
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_report_qs_rsp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
</details>
</li>
</ul>

## Differences
