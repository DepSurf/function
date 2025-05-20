# Function: <code>atomic_and</code>

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
In kernel/rcu/tree.c (ffffffff810f2337)
Location: arch/x86/include/asm/atomic.h:222
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
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
In kernel/rcu/tree.c (ffffffff810fc0b7)
Location: arch/x86/include/asm/atomic.h:201
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
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
In kernel/sched/core.c (ffffffff810c01e3)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810d0c0f)
Location: include/asm-generic/atomic-instrumented.h:148
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff81104697)
Location: include/asm-generic/atomic-instrumented.h:148
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
Location: include/asm-generic/atomic-instrumented.h:165
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810da44f)
Location: include/asm-generic/atomic-instrumented.h:165
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff8111011a)
Location: include/asm-generic/atomic-instrumented.h:165
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81551cd6)
Location: include/asm-generic/atomic-instrumented.h:165
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
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810e1767)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff811198ca)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8158074e)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81581cc1)
Location: include/asm-generic/atomic-instrumented.h:416
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
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810ebe07)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff81125c5a)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815a2218)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a3751)
Location: include/asm-generic/atomic-instrumented.h:416
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8164acf6)
Location: include/asm-generic/atomic-instrumented.h:417
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164c2b1)
Location: include/asm-generic/atomic-instrumented.h:417
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8166f446)
Location: include/asm-generic/atomic-instrumented.h:417
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81670601)
Location: include/asm-generic/atomic-instrumented.h:417
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81651966)
Location: include/asm-generic/atomic-instrumented.h:417
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816531b5)
Location: include/asm-generic/atomic-instrumented.h:417
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
Location: include/linux/atomic/atomic-instrumented.h:305
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c4f1e)
Location: include/linux/atomic/atomic-instrumented.h:305
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff817e9150)
Location: include/linux/atomic/atomic-instrumented.h:322
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817eac14)
Location: include/linux/atomic/atomic-instrumented.h:322
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8190ecf0)
Location: include/linux/atomic/atomic-instrumented.h:322
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81910ede)
Location: include/linux/atomic/atomic-instrumented.h:322
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8195236d)
Location: include/linux/atomic/atomic-instrumented.h:748
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819545d9)
Location: include/linux/atomic/atomic-instrumented.h:748
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199b7fd)
Location: include/linux/atomic/atomic-instrumented.h:748
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199da69)
Location: include/linux/atomic/atomic-instrumented.h:748
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
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070c1c0)
Location: include/asm-generic/atomic-instrumented.h:416
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018895c)
Location: arch/powerpc/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (c00000000019ea20)
Location: arch/powerpc/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (c0000000001e63e8)
Location: arch/powerpc/include/asm/atomic.h:113
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
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
In kernel/sched/core.c (ffffffe0000ea50a)
Location: arch/riscv/include/asm/atomic.h:78
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffe0000f573a)
Location: arch/riscv/include/asm/atomic.h:78
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffe000124180)
Location: arch/riscv/include/asm/atomic.h:78
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_idle_exit
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffe0004d77ee)
Location: arch/riscv/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d8b16)
Location: arch/riscv/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
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
In kernel/sched/core.c (ffffffff810d55e3)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810e5f67)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff8111e23a)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81595a28)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81596f61)
Location: include/asm-generic/atomic-instrumented.h:416
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
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810d5107)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff8110f29a)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In kernel/time/tick-sched.c (ffffffff811348c5)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_dep_clear_signal
  - kernel/time/tick-sched.c:tick_nohz_dep_clear_task
  - kernel/time/tick-sched.c:tick_nohz_dep_clear_cpu
  - kernel/time/tick-sched.c:tick_nohz_dep_clear
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81584bb8)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815860f1)
Location: include/asm-generic/atomic-instrumented.h:416
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
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810e2337)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff8111c12a)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81595f68)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815974a1)
Location: include/asm-generic/atomic-instrumented.h:416
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
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/fair.c (ffffffff810eded7)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
```
In kernel/rcu/tree.c (ffffffff8112785a)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_dynticks_eqs_exit
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815b03e8)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b18e1)
Location: include/asm-generic/atomic-instrumented.h:416
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
</details>
</li>
</ul>

## Differences
