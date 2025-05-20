# Function: <code>arch_atomic_and</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c01e3)
Location: arch/x86/include/asm/atomic.h:205
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810d0c0f)
Location: arch/x86/include/asm/atomic.h:205
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff81104697)
Location: arch/x86/include/asm/atomic.h:205
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
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
In kernel/sched/core.c (ffffffff810c9553)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810da44f)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff8111011a)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81551cd6)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
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
In kernel/sched/core.c (ffffffff810d1183)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810e1767)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff811198ca)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8158074e)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81581cc1)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
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
In kernel/sched/core.c (ffffffff810db133)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810ebe07)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff81125c5a)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815a2218)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a3751)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
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
In kernel/rcu/tree.c (ffffffff81bbf891)
Location: arch/x86/include/asm/atomic.h:214
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8164acf6)
Location: arch/x86/include/asm/atomic.h:214
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164c2b1)
Location: arch/x86/include/asm/atomic.h:214
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
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
In kernel/rcu/tree.c (ffffffff81c38671)
Location: arch/x86/include/asm/atomic.h:212
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8166f446)
Location: arch/x86/include/asm/atomic.h:212
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81670601)
Location: arch/x86/include/asm/atomic.h:212
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
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
In kernel/rcu/tree.c (ffffffff81c2aa81)
Location: arch/x86/include/asm/atomic.h:212
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81651966)
Location: arch/x86/include/asm/atomic.h:212
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816531b5)
Location: arch/x86/include/asm/atomic.h:212
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff816c36e6)
Location: arch/x86/include/asm/atomic.h:212
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c4f1e)
Location: arch/x86/include/asm/atomic.h:212
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
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
In io_uring/io_uring.c (ffffffff816d942a)
Location: arch/x86/include/asm/atomic.h:212
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:__io_cqring_overflow_flush
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff817e9150)
Location: arch/x86/include/asm/atomic.h:212
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817eac14)
Location: arch/x86/include/asm/atomic.h:212
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
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
In io_uring/io_uring.c (ffffffff8178f08b)
Location: arch/x86/include/asm/atomic.h:212
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:__io_cqring_overflow_flush
```
```
In io_uring/sqpoll.c (ffffffff8179a8da)
Location: arch/x86/include/asm/atomic.h:212
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/poll.c (ffffffff8179cee9)
Location: arch/x86/include/asm/atomic.h:212
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_check_events
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8190ecf0)
Location: arch/x86/include/asm/atomic.h:212
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81910ede)
Location: arch/x86/include/asm/atomic.h:212
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
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
In io_uring/io_uring.c (ffffffff817d047d)
Location: arch/x86/include/asm/atomic.h:125
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:__io_cqring_overflow_flush
```
```
In io_uring/sqpoll.c (ffffffff817db980)
Location: arch/x86/include/asm/atomic.h:125
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/poll.c (ffffffff817de113)
Location: arch/x86/include/asm/atomic.h:125
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_check_events
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8195236d)
Location: arch/x86/include/asm/atomic.h:125
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819545d9)
Location: arch/x86/include/asm/atomic.h:125
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
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
In kernel/time/tick-sched.c (ffffffff8121c9ac)
Location: arch/x86/include/asm/atomic.h:125
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_dep_clear_signal
  - kernel/time/tick-sched.c:tick_nohz_dep_clear_task
  - kernel/time/tick-sched.c:tick_nohz_dep_clear_cpu
  - kernel/time/tick-sched.c:tick_nohz_dep_clear
```
```
In io_uring/io_uring.c (ffffffff818136bd)
Location: arch/x86/include/asm/atomic.h:125
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:ctx_flush_and_put
  - io_uring/io_uring.c:__io_cqring_overflow_flush
```
```
In io_uring/sqpoll.c (ffffffff8181fcf6)
Location: arch/x86/include/asm/atomic.h:125
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/poll.c (ffffffff818224b4)
Location: arch/x86/include/asm/atomic.h:125
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_check_events
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199b7fd)
Location: arch/x86/include/asm/atomic.h:125
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199da69)
Location: arch/x86/include/asm/atomic.h:125
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffff80001070aa90)
Location: arch/arm64/include/asm/atomic.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070c1c0)
Location: arch/arm64/include/asm/atomic.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
</details>
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d55e3)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810e5f67)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff8111e23a)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81595a28)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81596f61)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
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
In kernel/sched/core.c (ffffffff810c3c33)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810d5107)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff8110f29a)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In kernel/time/tick-sched.c (ffffffff811348c5)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_dep_clear_signal
  - kernel/time/tick-sched.c:tick_nohz_dep_clear_task
  - kernel/time/tick-sched.c:tick_nohz_dep_clear_cpu
  - kernel/time/tick-sched.c:tick_nohz_dep_clear
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81584bb8)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815860f1)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
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
In kernel/sched/core.c (ffffffff810d2423)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810e2337)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff8111c12a)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81595f68)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815974a1)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
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
In kernel/sched/core.c (ffffffff810dceb3)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810eded7)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff8112785a)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815b03e8)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b18e1)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
</details>
</li>
</ul>

## Differences
