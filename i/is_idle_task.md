# Function: <code>is_idle_task</code>

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
In arch/x86/kernel/kvm.c (0)
Location: include/linux/sched.h:2395
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/sched.h:2395
Inline: True
```
```
In kernel/sched/core.c (ffffffff810ac70a)
Location: include/linux/sched.h:2395
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:2395
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:2395
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/sched.h:2395
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/sched.h:2395
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/sched.h:2395
Inline: True
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
In arch/x86/kernel/kvm.c (0)
Location: include/linux/sched.h:2566
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/sched.h:2566
Inline: True
```
```
In kernel/sched/core.c (ffffffff810af02a)
Location: include/linux/sched.h:2566
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:2566
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/sched.h:2566
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:2566
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/sched.h:2566
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/sched.h:2566
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/sched.h:2566
Inline: True
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
In arch/x86/kernel/kvm.c (0)
Location: include/linux/sched.h:2664
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/sched.h:2664
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b516d)
Location: include/linux/sched.h:2664
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:2664
Inline: True
```
```
In kernel/rcu/update.c (ffffffff810f04b5)
Location: include/linux/sched.h:2664
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:2664
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/sched.h:2664
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/sched.h:2664
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/sched.h:2664
Inline: True
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
In arch/x86/kernel/kvm.c (0)
Location: include/linux/sched.h:1408
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/sched.h:1408
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b13ee)
Location: include/linux/sched.h:1408
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1408
Inline: True
```
```
In kernel/rcu/update.c (ffffffff810f04dc)
Location: include/linux/sched.h:1408
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1408
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/sched.h:1408
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/sched.h:1408
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/sched.h:1408
Inline: True
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
In arch/x86/kernel/kvm.c (ffffffff8106a364)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/softirq.c (0)
Location: include/linux/sched.h:1438
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b881e)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1438
Inline: True
```
```
In kernel/rcu/update.c (ffffffff810fa1a0)
Location: include/linux/sched.h:1438
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/sched.h:1438
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/sched.h:1438
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/sched.h:1438
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/sched.h:1438
Inline: True
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
In arch/x86/kernel/kvm.c (ffffffff8106cfdd)
Location: include/linux/sched.h:1540
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/softirq.c (ffffffff81095127)
Location: include/linux/sched.h:1540
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (ffffffff810c02c8)
Location: include/linux/sched.h:1540
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
```
```
In kernel/sched/fair.c (ffffffff810c80a9)
Location: include/linux/sched.h:1540
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/rcu/update.c (ffffffff811029bc)
Location: include/linux/sched.h:1540
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff81106c18)
Location: include/linux/sched.h:1540
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
```
In kernel/time/tick-sched.c (ffffffff81126cb9)
Location: include/linux/sched.h:1540
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_handle
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/sched.h:1540
Inline: True
```
```
In kernel/events/core.c (ffffffff811d6af9)
Location: include/linux/sched.h:1540
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
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
In arch/x86/kernel/kvm.c (ffffffff810731a9)
Location: include/linux/sched.h:1553
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/softirq.c (ffffffff8109d497)
Location: include/linux/sched.h:1553
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (ffffffff810c9638)
Location: include/linux/sched.h:1553
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
```
```
In kernel/sched/fair.c (ffffffff810d1271)
Location: include/linux/sched.h:1553
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/rcu/update.c (ffffffff8110e37d)
Location: include/linux/sched.h:1553
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff81112f3d)
Location: include/linux/sched.h:1553
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
```
In kernel/time/tick-sched.c (ffffffff81132399)
Location: include/linux/sched.h:1553
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_handle
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/sched.h:1553
Inline: True
```
```
In kernel/events/core.c (ffffffff811e7139)
Location: include/linux/sched.h:1553
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
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
In arch/x86/kernel/kvm.c (ffffffff81076cdb)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/softirq.c (ffffffff810a1a77)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (ffffffff810d126c)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff810d91bb)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/rcu/update.c (ffffffff81117a58)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff8111c90e)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/time/tick-sched.c (ffffffff8113ccf9)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_handle
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/sched.h:1626
Inline: True
```
```
In kernel/events/core.c (ffffffff811fe767)
Location: include/linux/sched.h:1626
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
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
In arch/x86/kernel/kvm.c (ffffffff81077d2b)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/softirq.c (ffffffff810a8037)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (ffffffff810db21c)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
```
```
In kernel/sched/fair.c (ffffffff810e391f)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/rcu/update.c (ffffffff81123e25)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff81127c51)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/tick-sched.c (ffffffff81148a99)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_handle
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/sched.h:1619
Inline: True
```
```
In kernel/events/core.c (ffffffff8120b8f7)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
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
In arch/x86/entry/common.c (ffffffff81bbc894)
Location: include/linux/sched.h:1661
Inline: True
Inline callers:
  - arch/x86/entry/common.c:idtentry_enter_cond_rcu
```
```
In kernel/softirq.c (ffffffff810af847)
Location: include/linux/sched.h:1661
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (ffffffff810e3f7b)
Location: include/linux/sched.h:1661
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff810ef427)
Location: include/linux/sched.h:1661
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_compare
```
```
In kernel/rcu/update.c (ffffffff8113147d)
Location: include/linux/sched.h:1661
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/rcu/tree.c (ffffffff81136436)
Location: include/linux/sched.h:1661
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_is_cpu_rrupt_from_idle
```
```
In kernel/time/tick-sched.c (ffffffff811586d9)
Location: include/linux/sched.h:1661
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_handle
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811a14e5)
Location: include/linux/sched.h:1661
Inline: True
```
```
In kernel/events/core.c (ffffffff812370cd)
Location: include/linux/sched.h:1661
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
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
In kernel/softirq.c (ffffffff810aafe2)
Location: include/linux/sched.h:1722
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (ffffffff810e198b)
Location: include/linux/sched.h:1722
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff810ed407)
Location: include/linux/sched.h:1722
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_compare
```
```
In kernel/rcu/update.c (ffffffff81be1e51)
Location: include/linux/sched.h:1722
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/update.c:trc_inspect_reader
```
```
In kernel/rcu/tree.c (ffffffff81131c7b)
Location: include/linux/sched.h:1722
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_is_cpu_rrupt_from_idle
```
```
In kernel/entry/common.c (ffffffff81c389f8)
Location: include/linux/sched.h:1722
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_enter
```
```
In kernel/time/tick-sched.c (ffffffff811546f9)
Location: include/linux/sched.h:1722
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_handle
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119e635)
Location: include/linux/sched.h:1722
Inline: True
```
```
In kernel/events/core.c (ffffffff81240d26)
Location: include/linux/sched.h:1722
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
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
In kernel/softirq.c (ffffffff810ac1d2)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (ffffffff810e379b)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff810ef4d7)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_compare
```
```
In kernel/rcu/update.c (ffffffff81bd3edd)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/update.c:trc_inspect_reader
```
```
In kernel/rcu/tree.c (ffffffff81132c26)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_is_cpu_rrupt_from_idle
```
```
In kernel/entry/common.c (ffffffff81c2adf8)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_enter
```
```
In kernel/time/tick-sched.c (ffffffff81155b79)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_handle
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119fde7)
Location: include/linux/sched.h:1744
Inline: True
```
```
In kernel/events/core.c (ffffffff81244ad2)
Location: include/linux/sched.h:1744
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
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
In kernel/softirq.c (ffffffff810bd852)
Location: include/linux/sched.h:1861
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (ffffffff810fa339)
Location: include/linux/sched.h:1861
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff81107e63)
Location: include/linux/sched.h:1861
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_compare
```
```
In kernel/rcu/update.c (ffffffff8114cfd1)
Location: include/linux/sched.h:1861
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/update.c:trc_inspect_reader
```
```
In kernel/rcu/tree.c (ffffffff81156855)
Location: include/linux/sched.h:1861
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/entry/common.c (ffffffff81d49388)
Location: include/linux/sched.h:1861
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_enter
```
```
In kernel/time/tick-sched.c (ffffffff8117a7e9)
Location: include/linux/sched.h:1861
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_handle
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811c9cb5)
Location: include/linux/sched.h:1861
Inline: True
```
```
In kernel/events/core.c (ffffffff8127fa72)
Location: include/linux/sched.h:1861
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
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
In kernel/softirq.c (ffffffff810d4982)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (ffffffff81116949)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (0)
Location: include/linux/sched.h:1886
Inline: True
```
```
In kernel/rcu/update.c (ffffffff81173bc1)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/rcu/tree.c (ffffffff8117dc97)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_flavor_sched_clock_irq
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:invoke_rcu_core_kthread
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/entry/common.c (ffffffff81f186a2)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_enter
```
```
In kernel/time/tick-sched.c (ffffffff811afcf3)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_handle
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fd897)
Location: include/linux/sched.h:1886
Inline: True
```
```
In kernel/events/core.c (ffffffff812d4ad2)
Location: include/linux/sched.h:1886
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
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
In kernel/softirq.c (ffffffff810f38e2)
Location: include/linux/sched.h:1913
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (ffffffff8113de79)
Location: include/linux/sched.h:1913
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff81143cad)
Location: include/linux/sched.h:1913
Inline: True
Inline callers:
  - kernel/sched/fair.c:migrate_task_rq_fair
```
```
In kernel/rcu/update.c (ffffffff811ab524)
Location: include/linux/sched.h:1913
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/rcu/tree.c (ffffffff811b86e0)
Location: include/linux/sched.h:1913
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:invoke_rcu_core_kthread
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/entry/common.c (ffffffff820bfc32)
Location: include/linux/sched.h:1913
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_enter
```
```
In kernel/time/tick-sched.c (ffffffff811f0723)
Location: include/linux/sched.h:1913
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_handle
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81245067)
Location: include/linux/sched.h:1913
Inline: True
```
```
In kernel/events/core.c (ffffffff8133d091)
Location: include/linux/sched.h:1913
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
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
In kernel/softirq.c (ffffffff810ffc32)
Location: include/linux/sched.h:1924
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (ffffffff8114a989)
Location: include/linux/sched.h:1924
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff81153c62)
Location: include/linux/sched.h:1924
Inline: True
Inline callers:
  - kernel/sched/fair.c:migrate_task_rq_fair
```
```
In kernel/rcu/update.c (ffffffff811bd444)
Location: include/linux/sched.h:1924
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:check_all_holdout_tasks
```
```
In kernel/rcu/tree.c (ffffffff811cac30)
Location: include/linux/sched.h:1924
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:invoke_rcu_core_kthread
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/entry/common.c (ffffffff82141a12)
Location: include/linux/sched.h:1924
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_enter
```
```
In kernel/time/tick-sched.c (ffffffff81204f42)
Location: include/linux/sched.h:1924
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_handle
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8125c0f7)
Location: include/linux/sched.h:1924
Inline: True
```
```
In kernel/events/core.c (ffffffff8136e20a)
Location: include/linux/sched.h:1924
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
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
In kernel/softirq.c (ffffffff811092e0)
Location: include/linux/sched.h:1828
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter_rcu
```
```
In kernel/sched/core.c (ffffffff81151c5b)
Location: include/linux/sched.h:1828
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_tick_remote
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:update_rq_clock
```
```
In kernel/sched/fair.c (ffffffff8115fdb6)
Location: include/linux/sched.h:1828
Inline: True
Inline callers:
  - kernel/sched/fair.c:migrate_task_rq_fair
```
```
In kernel/sched/build_policy.c (ffffffff811826ba)
Location: include/linux/sched.h:1828
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:vtime_task_switch_generic
```
```
In kernel/rcu/update.c (ffffffff811cc6b3)
Location: include/linux/sched.h:1828
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_stalled_task_trace
  - kernel/rcu/update.c:check_holdout_task
  - kernel/rcu/update.c:check_holdout_task
  - kernel/rcu/update.c:check_holdout_task
```
```
In kernel/rcu/tree.c (ffffffff811d93a0)
Location: include/linux/sched.h:1828
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:invoke_rcu_core_kthread
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/entry/common.c (ffffffff82223db6)
Location: include/linux/sched.h:1828
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_enter
```
```
In kernel/time/tick-sched.c (ffffffff8121b612)
Location: include/linux/sched.h:1828
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_handle
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81276039)
Location: include/linux/sched.h:1828
Inline: True
```
```
In kernel/events/core.c (ffffffff8139733a)
Location: include/linux/sched.h:1828
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
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
In kernel/softirq.c (ffff8000100ff108)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (ffff80001013af14)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
```
```
In kernel/sched/fair.c (ffff8000101439c4)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/rcu/update.c (ffff800010188f78)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffff80001018f304)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/tick-sched.c (ffff8000101b4b30)
Location: include/linux/sched.h:1619
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/sched.h:1619
Inline: True
```
```
In kernel/events/core.c (ffff80001029aa84)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
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
In kernel/softirq.c (c035be0c)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (c038a920)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
```
```
In kernel/rcu/update.c (c03d778c)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (c03ddc24)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/time/tick-sched.c (c03fe8d8)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_handle
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/sched.h:1619
Inline: True
```
```
In kernel/events/core.c (c04c5064)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
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
In arch/powerpc/kernel/stacktrace.c (c000000000069780)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - arch/powerpc/kernel/stacktrace.c:save_stack_trace_tsk_reliable
```
```
In kernel/softirq.c (c0000000001463f8)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (c000000000188aa8)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
```
```
In kernel/sched/fair.c (c000000000193018)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/rcu/update.c (c0000000001e3270)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (c0000000001eb328)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/time/tick-sched.c (c00000000021a304)
Location: include/linux/sched.h:1619
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/sched.h:1619
Inline: True
```
```
In kernel/events/core.c (c000000000342b70)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
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
In kernel/softirq.c (ffffffe0000c7022)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (ffffffe0000ea5ec)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
```
```
In kernel/rcu/update.c (ffffffe00011e2e4)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffe000122cd6)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/time/tick-sched.c (ffffffe00013b09a)
Location: include/linux/sched.h:1619
Inline: True
```
```
In kernel/events/core.c (ffffffe0001c689a)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
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
In arch/x86/kernel/kvm.c (ffffffff81076d2b)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/softirq.c (ffffffff810a1957)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (ffffffff810d56cc)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
```
```
In kernel/sched/fair.c (ffffffff810ddacf)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/rcu/update.c (ffffffff8111c405)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff81120231)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/tick-sched.c (ffffffff811410b9)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_handle
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/sched.h:1619
Inline: True
```
```
In kernel/events/core.c (ffffffff81203f17)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
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
In arch/x86/kernel/kvm.c (ffffffff81066d8b)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/softirq.c (ffffffff81090317)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (ffffffff810bfa63)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_tick_remote
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
```
```
In kernel/sched/cputime.c (ffffffff810c8995)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/cputime.c:vtime_common_task_switch
```
```
In kernel/sched/fair.c (ffffffff810ccadf)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/rcu/update.c (ffffffff8110d21d)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff8111039b)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/tick-sched.c (ffffffff81133e59)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_handle
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/sched.h:1619
Inline: True
```
```
In kernel/events/core.c (ffffffff811f6ca7)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
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
In arch/x86/kernel/kvm.c (ffffffff81076cdb)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/softirq.c (ffffffff810a1907)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (ffffffff810d250c)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
```
```
In kernel/sched/fair.c (ffffffff810d9e4f)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/rcu/update.c (ffffffff8111a2f5)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff8111e121)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/tick-sched.c (ffffffff8113ef69)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_handle
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/sched.h:1619
Inline: True
```
```
In kernel/events/core.c (ffffffff81201ce7)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
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
In arch/x86/kernel/kvm.c (ffffffff81078d18)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/softirq.c (ffffffff810a98f7)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (ffffffff810dcfa0)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_if_idle
```
```
In kernel/sched/fair.c (ffffffff810e587e)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/rcu/update.c (ffffffff81125a75)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/tree.c (ffffffff8112b181)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/tick-sched.c (ffffffff8114bad9)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_sched_handle
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/sched.h:1619
Inline: True
```
```
In kernel/events/core.c (ffffffff812113b7)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_hrtimer
```
</details>
</li>
</ul>

## Differences
