# Function: <code>__cpumask_clear_cpu</code>

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
In kernel/smp.c (ffffffff81113f75)
Location: include/linux/cpumask.h:312
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
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
In kernel/sched/debug.c (ffffffff810d82c7)
Location: include/linux/cpumask.h:316
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/smp.c (ffffffff8111f505)
Location: include/linux/cpumask.h:316
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
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
In arch/x86/kernel/kvm.c (ffffffff8106ca49)
Location: include/linux/cpumask.h:318
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In kernel/sched/debug.c (ffffffff810df744)
Location: include/linux/cpumask.h:318
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/smp.c (ffffffff8112c838)
Location: include/linux/cpumask.h:318
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
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
In arch/x86/kernel/kvm.c (ffffffff810728f9)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In kernel/sched/debug.c (ffffffff810e9ec4)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/smp.c (ffffffff81138108)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
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
In arch/x86/kernel/smp.c (ffffffff81062b92)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106c9f6)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff81076426)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In kernel/sched/fair.c (ffffffff810e0b73)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/debug.c (ffffffff810f0cd1)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff828c55b3)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff811432bb)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e196)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff81077436)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In kernel/sched/fair.c (ffffffff810eb203)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/debug.c (ffffffff810fc981)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff828cdc1c)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff8114edfb)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075816)
Location: include/linux/cpumask.h:353
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e786)
Location: include/linux/cpumask.h:353
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In kernel/sched/fair.c (ffffffff810f503d)
Location: include/linux/cpumask.h:353
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/debug.c (ffffffff811070dc)
Location: include/linux/cpumask.h:353
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff82ceefe0)
Location: include/linux/cpumask.h:353
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff8115f76b)
Location: include/linux/cpumask.h:353
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075e59)
Location: include/linux/cpumask.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e3b6)
Location: include/linux/cpumask.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In kernel/sched/fair.c (ffffffff810f30cf)
Location: include/linux/cpumask.h:359
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/debug.c (ffffffff811058ec)
Location: include/linux/cpumask.h:359
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff82fdb6f7)
Location: include/linux/cpumask.h:359
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff8115b70b)
Location: include/linux/cpumask.h:359
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810768d9)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f4c6)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
```
In kernel/sched/fair.c (ffffffff810f529f)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/debug.c (ffffffff81107986)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/debug.c:update_sched_domain_debugfs
```
```
In kernel/sched/isolation.c (ffffffff831e6451)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff8115c7f1)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81084049)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e238)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
```
In kernel/sched/fair.c (ffffffff8110edae)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/debug.c (ffffffff81125a61)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/debug.c:update_sched_domain_debugfs
```
```
In kernel/sched/isolation.c (ffffffff832ca54d)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff81181947)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81094149)
Location: include/linux/cpumask.h:365
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff8109ebf9)
Location: include/linux/cpumask.h:365
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
```
In kernel/sched/fair.c (ffffffff8112acfe)
Location: include/linux/cpumask.h:365
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_utility.c (ffffffff8347d6f0)
Location: include/linux/cpumask.h:365
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
```
```
In kernel/smp.c (ffffffff811b7f94)
Location: include/linux/cpumask.h:365
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a977c)
Location: include/linux/cpumask.h:430
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff810b6af7)
Location: include/linux/cpumask.h:430
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
```
In kernel/sched/fair.c (ffffffff811546d3)
Location: include/linux/cpumask.h:430
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_utility.c (ffffffff83ea8fd9)
Location: include/linux/cpumask.h:430
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
```
```
In kernel/smp.c (ffffffff811f9230)
Location: include/linux/cpumask.h:430
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810ac99c)
Location: include/linux/cpumask.h:490
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff810b9c50)
Location: include/linux/cpumask.h:490
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
```
In kernel/sched/fair.c (ffffffff8116482d)
Location: include/linux/cpumask.h:490
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_utility.c (ffffffff836cda99)
Location: include/linux/cpumask.h:490
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff8120df25)
Location: include/linux/cpumask.h:490
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b361c)
Location: include/linux/cpumask.h:490
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff810c0ea0)
Location: include/linux/cpumask.h:490
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
```
In kernel/sched/fair.c (ffffffff8117157f)
Location: include/linux/cpumask.h:490
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/build_utility.c (ffffffff838feed7)
Location: include/linux/cpumask.h:490
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff812256b5)
Location: include/linux/cpumask.h:490
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
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
In kernel/sched/fair.c (ffff80001014b358)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/debug.c (ffff800010161d54)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffff800011445520)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffff8000101bd340)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
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
In kernel/sched/fair.c (c0399060)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/debug.c (c03ae548)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (c151f640)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (c0405518)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
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
In kernel/sched/fair.c (c00000000019d89c)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/debug.c (c0000000001b7f18)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (c000000001369f84)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (c000000000223720)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
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
In kernel/sched/fair.c (ffffffe0000f4be2)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/debug.c (ffffffe000105b0a)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffe0000072ac)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffe0001409b4)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d136)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff81076436)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In kernel/sched/fair.c (ffffffff810e5363)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/debug.c (ffffffff810f5cb1)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff828b69ac)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff8114741b)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d529)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff810663a6)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In kernel/sched/fair.c (ffffffff810d450c)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/debug.c (ffffffff810e5e71)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff828aeba2)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff8113a6f6)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d5e6)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff810763e6)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In kernel/sched/fair.c (ffffffff810e1733)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/debug.c (ffffffff810f2eb1)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff828c9850)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff811452cb)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f866)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff81078436)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In kernel/sched/fair.c (ffffffff810ed39e)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/debug.c (ffffffff810fdeb1)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/isolation.c (ffffffff828cec02)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff81151eab)
Location: include/linux/cpumask.h:346
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
</details>
</li>
</ul>

## Differences
