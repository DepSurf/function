# Function: <code>__cpumask_set_cpu</code>

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
In kernel/smp.c (ffffffff8111403a)
Location: include/linux/cpumask.h:296
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
In kernel/sched/debug.c (ffffffff810d84c2)
Location: include/linux/cpumask.h:300
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff810dbf3a)
Location: include/linux/cpumask.h:300
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:SyS_membarrier
```
```
In kernel/smp.c (ffffffff8111f5b4)
Location: include/linux/cpumask.h:300
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
In kernel/sched/debug.c (ffffffff810df931)
Location: include/linux/cpumask.h:302
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff810e4234)
Location: include/linux/cpumask.h:302
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/smp.c (ffffffff8112c8e3)
Location: include/linux/cpumask.h:302
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
In kernel/sched/debug.c (ffffffff810ea0b1)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff810eeb54)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/smp.c (ffffffff8113842a)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
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
In kernel/sched/debug.c (ffffffff810f0ea5)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff810f5965)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff828c55a6)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff811435e8)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
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
In kernel/sched/debug.c (ffffffff810fcb55)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff811014b9)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff828cdc0f)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff8114f128)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
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
In kernel/sched/debug.c (ffffffff811072e5)
Location: include/linux/cpumask.h:337
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff8110bcf0)
Location: include/linux/cpumask.h:337
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff82ceefd3)
Location: include/linux/cpumask.h:337
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff8115f84c)
Location: include/linux/cpumask.h:337
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
In kernel/sched/debug.c (ffffffff81105af5)
Location: include/linux/cpumask.h:343
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff81108f36)
Location: include/linux/cpumask.h:343
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff82fdb6ea)
Location: include/linux/cpumask.h:343
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff8115b7ec)
Location: include/linux/cpumask.h:343
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In mm/swap.c (ffffffff8126a7c1)
Location: include/linux/cpumask.h:343
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
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
In arch/x86/mm/tlb.c (ffffffff8108c1de)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
```
```
In kernel/sched/debug.c (ffffffff81107a45)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff8110aec6)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff831e6444)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff8115c8cd)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In mm/swap.c (ffffffff8126f902)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
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
In arch/x86/mm/tlb.c (ffffffff8109b9ea)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
```
```
In kernel/sched/topology.c (ffffffff8111eb44)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - kernel/sched/topology.c:asym_cpu_capacity_scan
```
```
In kernel/sched/debug.c (ffffffff81125b35)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff811296f4)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff832ca540)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff81181a43)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In mm/swap.c (ffffffff812aca92)
Location: include/linux/cpumask.h:314
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
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
In kernel/sched/build_utility.c (ffffffff8347d6df)
Location: include/linux/cpumask.h:349
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:cpu_attach_domain
```
```
In kernel/smp.c (ffffffff811b80a0)
Location: include/linux/cpumask.h:349
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In mm/swap.c (ffffffff81302f24)
Location: include/linux/cpumask.h:349
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
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
In kernel/sched/build_utility.c (ffffffff83ea8fc8)
Location: include/linux/cpumask.h:414
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:cpu_attach_domain
```
```
In kernel/smp.c (ffffffff811f933d)
Location: include/linux/cpumask.h:414
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In mm/swap.c (ffffffff8136debd)
Location: include/linux/cpumask.h:414
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
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
In kernel/sched/build_utility.c (ffffffff836cda88)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:cpu_attach_domain
```
```
In kernel/smp.c (ffffffff8120dffc)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In mm/swap.c (ffffffff813a00dd)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
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
In kernel/sched/build_utility.c (ffffffff838feec6)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:cpu_attach_domain
```
```
In kernel/smp.c (ffffffff8122578c)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In mm/swap.c (ffffffff813c9d5d)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
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
In virt/kvm/kvm_main.c (ffff8000100bc77c)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_make_vcpus_request_mask
```
```
In kernel/sched/debug.c (ffff800010161f30)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffff8000101662ec)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
```
```
In kernel/sched/isolation.c (ffff8000114454f0)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffff8000101bd804)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
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
In kernel/sched/debug.c (c03ae740)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (c03b280c)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
```
```
In kernel/sched/isolation.c (c151f60c)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (c0405ad8)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
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
In kernel/sched/debug.c (c0000000001b8230)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (c0000000001bd30c)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (c000000001369f68)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (c000000000223ca0)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
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
In kernel/sched/debug.c (ffffffe000105ca4)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffe000108684)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
```
```
In kernel/sched/isolation.c (ffffffe00000728c)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffe000140cdc)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
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
In kernel/sched/debug.c (ffffffff810f5e85)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff810fa7c9)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff828b699f)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff81147748)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
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
In kernel/sched/debug.c (ffffffff810e6045)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff810ea9a9)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff828aeb95)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff8113a9f8)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
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
In kernel/sched/debug.c (ffffffff810f3085)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff810f7989)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff828c9843)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff811455f8)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
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
In kernel/sched/debug.c (ffffffff810fe085)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/debug.c:dirty_sched_domain_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff81102a96)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/sched/isolation.c (ffffffff828cebf5)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/smp.c (ffffffff811521ef)
Location: include/linux/cpumask.h:330
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
```
</details>
</li>
</ul>

## Differences
