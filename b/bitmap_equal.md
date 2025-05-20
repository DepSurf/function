# Function: <code>bitmap_equal</code>

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
In arch/x86/kernel/smp.c (ffffffff81050877)
Location: include/linux/bitmap.h:255
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105541f)
Location: include/linux/bitmap.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a7a6)
Location: include/linux/bitmap.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
```
In kernel/workqueue.c (ffffffff8109769b)
Location: include/linux/bitmap.h:255
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:wq_update_unbound_numa
```
```
In kernel/sched/core.c (ffffffff810a8376)
Location: include/linux/bitmap.h:255
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:partition_sched_domains
```
```
In kernel/time/tick-common.c (ffffffff810fc5a0)
Location: include/linux/bitmap.h:255
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff810fcd7b)
Location: include/linux/bitmap.h:255
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cpuset.c (ffffffff8111ad31)
Location: include/linux/bitmap.h:255
Inline: True
Inline callers:
  - kernel/cpuset.c:rebuild_sched_domains_locked
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
```
```
In kernel/padata.c (ffffffff81189f93)
Location: include/linux/bitmap.h:255
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/frontswap.c (0)
Location: include/linux/bitmap.h:255
Inline: True
```
```
In mm/mempolicy.c (ffffffff811e2474)
Location: include/linux/bitmap.h:255
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:255
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff814d64de)
Location: include/linux/bitmap.h:255
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
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
In arch/x86/kernel/smp.c (ffffffff81050a7b)
Location: include/linux/bitmap.h:265
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105568e)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a656)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
```
In kernel/workqueue.c (ffffffff8109f239)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810b2589)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/time/tick-common.c (ffffffff81103b14)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff811040db)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cpuset.c (ffffffff8112514c)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/padata.c (ffffffff8119c693)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/frontswap.c (ffffffff811f585d)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/mempolicy.c (ffffffff81200e60)
Location: include/linux/bitmap.h:265
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff8150cb54)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81527279)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int bitmap_equal(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff8105333a)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810583dd)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d6ce)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
```
In kernel/workqueue.c (ffffffff810a416b)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810b8b68)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:__set_cpus_allowed_ptr
Direct callers:
  - kernel/sched/core.c:cpu_attach_domain
```
```
In kernel/time/tick-common.c (ffffffff8110b204)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff8110b7db)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cpuset.c (ffffffff8112e581)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffffffff8116d799)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff811ac4aa)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/frontswap.c (ffffffff8120638d)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/mempolicy.c (ffffffff8120f4ec)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_policy
```
```
In drivers/dma/dmaengine.c (ffffffff81538c64)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff815537d5)
Location: include/linux/bitmap.h:265
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff810afe60-ffffffff810afe6b: bitmap_equal (STB_LOCAL)
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
In arch/x86/kernel/smp.c (ffffffff81052ef4)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81057aba)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105cdce)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
```
In kernel/workqueue.c (ffffffff810a12c9)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810b0340)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/topology.c (ffffffff810cd557)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/time/tick-common.c (ffffffff8110d0f4)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff8110d6cb)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (ffffffff8112fc21)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffffffff8117094b)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff811b39fa)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/frontswap.c (ffffffff81211b08)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/mempolicy.c (ffffffff8121c4ba)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_policy
```
```
In drivers/dma/dmaengine.c (ffffffff8154c424)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8156815c)
Location: include/linux/bitmap.h:264
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
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
In arch/x86/hyperv/mmu.c (ffffffff8102a5fe)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/kernel/smp.c (ffffffff81056c17)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81060a8e)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
```
In kernel/workqueue.c (ffffffff810a7b2f)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810b7770)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/topology.c (ffffffff810d4d66)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/isolation.c (ffffffff826cbc9f)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/time/tick-common.c (ffffffff81118374)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff8111895b)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (ffffffff8113cdba)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffffffff8117db14)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff811c768a)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/frontswap.c (ffffffff8122c4d4)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/mempolicy.c (ffffffff81237670)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_policy
```
```
In drivers/dma/dmaengine.c (ffffffff815af764)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff815cc30d)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int bitmap_equal(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102b240)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102bdac)
Location: include/linux/bitmap.h:312
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81059a87)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81063bb6)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
```
In kernel/workqueue.c (ffffffff810ae68f)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810bf2fc)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/topology.c (ffffffff810dc908)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/isolation.c (ffffffff826f5e08)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/time/tick-common.c (ffffffff81124d8d)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_preferred
```
```
In kernel/time/tick-broadcast.c (ffffffff81125514)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (ffffffff8114b3e3)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffffffff8118c97b)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff811e78da)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/frontswap.c (ffffffff8124f3b4)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/mempolicy.c (ffffffff81259d9e)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_policy
```
```
In drivers/dma/dmaengine.c (ffffffff815e7b17)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81604c19)
Location: include/linux/bitmap.h:312
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff810da960-ffffffff810da96b: bitmap_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int bitmap_equal(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102bd86)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102cdb4)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/smp.c (ffffffff8105f707)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810698a9)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
```
In kernel/workqueue.c (ffffffff810b77ef)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810c85fc)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/topology.c (ffffffff810e6568)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/isolation.c (ffffffff828acc52)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/time/tick-common.c (ffffffff8113048d)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_preferred
```
```
In kernel/time/tick-broadcast.c (ffffffff81130c04)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (ffffffff81157cfe)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119a48b)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff811f882a)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/frontswap.c (ffffffff8126383e)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/mempolicy.c (ffffffff8126ddae)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_policy
```
```
In drivers/dma/dmaengine.c (ffffffff81602f87)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8161fcf9)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
```
In drivers/net/phy/phy.c (ffffffff81758750)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_speed_up
```
```
In drivers/net/phy/phy_device.c (ffffffff8175c516)
Location: include/linux/bitmap.h:313
Inline: True
```
**Symbols:**

```
ffffffff810e44b0-ffffffff810e44bb: bitmap_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int bitmap_equal(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102de54)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102e9f2)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/smp.c (ffffffff81062b98)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d096)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
```
In kernel/workqueue.c (ffffffff810bcb97)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810cfffc)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/topology.c (ffffffff810ed198)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
Direct callers:
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/sched/isolation.c (ffffffff828c561a)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/time/tick-common.c (ffffffff8113afdd)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_preferred
```
```
In kernel/time/tick-broadcast.c (ffffffff8113b764)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (ffffffff811649c7)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffffffff811a80e2)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff812102ca)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/frontswap.c (ffffffff8127e921)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/mempolicy.c (ffffffff81289141)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_policy
```
```
In mm/sparse.c (0)
Location: include/linux/bitmap.h:313
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81635657)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff816532bc)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
```
In drivers/net/phy/phy.c (ffffffff817954ef)
Location: include/linux/bitmap.h:313
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_speed_up
```
```
In drivers/net/phy/phy_device.c (ffffffff817999ac)
Location: include/linux/bitmap.h:313
Inline: True
```
**Symbols:**

```
ffffffff810eb0c0-ffffffff810eb0cb: bitmap_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int bitmap_equal(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102e764)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f302)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8106788c)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In kernel/workqueue.c (ffffffff810c38ef)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810d9f7e)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/topology.c (ffffffff810f8cd2)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/isolation.c (ffffffff828cdc83)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/time/tick-common.c (ffffffff81146bed)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_preferred
```
```
In kernel/time/tick-broadcast.c (ffffffff81147374)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (ffffffff811708a7)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b38e2)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff8121dacc)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/frontswap.c (ffffffff8128e380)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/mempolicy.c (ffffffff81298cd1)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_policy
```
```
In mm/sparse.c (0)
Location: include/linux/bitmap.h:317
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81657377)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81675864)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
```
In drivers/net/phy/phy.c (ffffffff817b8f17)
Location: include/linux/bitmap.h:317
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff817bd4cc)
Location: include/linux/bitmap.h:317
Inline: True
```
**Symbols:**

```
ffffffff810f6a60-ffffffff810f6a6b: bitmap_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int bitmap_equal(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff810310de)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81031822)
Location: include/linux/bitmap.h:333
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8106e5dc)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In kernel/workqueue.c (ffffffff810cb13e)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/core.c (ffffffff810e2c3e)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/topology.c (ffffffff81102bb4)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:init_overlap_sched_group
  - kernel/sched/topology.c:build_balance_mask
  - kernel/sched/topology.c:cpu_attach_domain
Direct callers:
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/sched/isolation.c (ffffffff82cef047)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/time/tick-common.c (ffffffff81156abb)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_preferred
  - kernel/time/tick-common.c:tick_check_percpu
  - kernel/time/tick-common.c:tick_check_percpu
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff811571f1)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (ffffffff81182488)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffffffff811cbf73)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In mm/frontswap.c (ffffffff812c0e80)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/mempolicy.c (ffffffff812ce647)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_mm
```
```
In mm/sparse.c (0)
Location: include/linux/bitmap.h:333
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81706ca3)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:private_candidate
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8172627a)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/net/phy/phy.c (ffffffff8187f471)
Location: include/linux/bitmap.h:333
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81884fe9)
Location: include/linux/bitmap.h:333
Inline: True
```
```
In net/ethtool/linkmodes.c (ffffffff81a88d43)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
```
In net/ethtool/features.c (ffffffff81a8a164)
Location: include/linux/bitmap.h:333
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff811006f0-ffffffff811006fb: bitmap_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int bitmap_equal(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81031e39)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81032522)
Location: include/linux/bitmap.h:331
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8106fa5c)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In kernel/workqueue.c (ffffffff810c626e)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/core.c (ffffffff810e03aa)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/topology.c (ffffffff811017d4)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:init_overlap_sched_group
  - kernel/sched/topology.c:build_balance_mask
  - kernel/sched/topology.c:cpu_attach_domain
Direct callers:
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/sched/isolation.c (ffffffff82fdb75e)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/time/tick-common.c (ffffffff81152bdb)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_preferred
  - kernel/time/tick-common.c:tick_check_percpu
  - kernel/time/tick-common.c:tick_check_percpu
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff811532c1)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (ffffffff8117f3a8)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffffffff811c95c3)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In mm/frontswap.c (ffffffff812cc8a0)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/mempolicy.c (ffffffff812d83bf)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_policy
```
```
In mm/sparse.c (0)
Location: include/linux/bitmap.h:331
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff817240e3)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:private_candidate
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81c063d7)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/net/phy/phy.c (ffffffff8188dd21)
Location: include/linux/bitmap.h:331
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81893a69)
Location: include/linux/bitmap.h:331
Inline: True
```
```
In net/ethtool/linkmodes.c (ffffffff81a92623)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
```
In net/ethtool/features.c (ffffffff81a939f1)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff810ff240-ffffffff810ff24b: bitmap_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int bitmap_equal(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8103295e)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81033962)
Location: include/linux/bitmap.h:331
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8107058c)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In kernel/workqueue.c (ffffffff810c7bac)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/core.c (ffffffff810e21ca)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/topology.c (ffffffff81103b50)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
Direct callers:
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/sched/isolation.c (ffffffff831e64b8)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/time/tick-common.c (ffffffff811541ca)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff811546c1)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (ffffffff8117f9e8)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffffffff811ca9c4)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In mm/frontswap.c (ffffffff812d346d)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/mempolicy.c (ffffffff812dfd5f)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_policy
```
```
In mm/sparse.c (0)
Location: include/linux/bitmap.h:331
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81705353)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:private_candidate
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81bf8069)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/net/phy/phy.c (ffffffff8187066b)
Location: include/linux/bitmap.h:331
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81876639)
Location: include/linux/bitmap.h:331
Inline: True
```
```
In net/ethtool/linkmodes.c (ffffffff81a7bea5)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
```
In net/ethtool/features.c (ffffffff81a7d417)
Location: include/linux/bitmap.h:331
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81101430-ffffffff8110143b: bitmap_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int bitmap_equal(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81037ac7)
Location: include/linux/bitmap.h:337
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81038c2b)
Location: include/linux/bitmap.h:337
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8107c12c)
Location: include/linux/bitmap.h:337
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In kernel/workqueue.c (ffffffff810dbf26)
Location: include/linux/bitmap.h:337
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/core.c (ffffffff810f8436)
Location: include/linux/bitmap.h:337
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
```
In kernel/sched/topology.c (ffffffff81120b79)
Location: include/linux/bitmap.h:337
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
Direct callers:
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/sched/topology.c:sched_domain_debug_one
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/sched/isolation.c (ffffffff832ca5b4)
Location: include/linux/bitmap.h:337
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/time/tick-common.c (ffffffff81178928)
Location: include/linux/bitmap.h:337
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff811790ef)
Location: include/linux/bitmap.h:337
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (ffffffff811a7c07)
Location: include/linux/bitmap.h:337
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffffffff811f6b49)
Location: include/linux/bitmap.h:337
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In mm/frontswap.c (ffffffff81318eed)
Location: include/linux/bitmap.h:337
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/mempolicy.c (ffffffff813280d1)
Location: include/linux/bitmap.h:337
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_mm
  - mm/mempolicy.c:mpol_rebind_task
```
```
In mm/sparse.c (0)
Location: include/linux/bitmap.h:337
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81780b33)
Location: include/linux/bitmap.h:337
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:private_candidate
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81cf71a1)
Location: include/linux/bitmap.h:337
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/net/phy/phy.c (ffffffff81900c8b)
Location: include/linux/bitmap.h:337
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81907249)
Location: include/linux/bitmap.h:337
Inline: True
```
```
In net/ethtool/linkmodes.c (ffffffff81b36225)
Location: include/linux/bitmap.h:337
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
```
In net/ethtool/features.c (ffffffff81b37607)
Location: include/linux/bitmap.h:337
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff8111d650-ffffffff8111d65b: bitmap_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool bitmap_equal(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8103dce7)
Location: include/linux/bitmap.h:356
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103f9b0)
Location: include/linux/bitmap.h:356
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8108b448)
Location: include/linux/bitmap.h:356
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In kernel/workqueue.c (ffffffff810f5652)
Location: include/linux/bitmap.h:356
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/core.c (ffffffff811146ec)
Location: include/linux/bitmap.h:356
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
```
In kernel/sched/build_utility.c (ffffffff8114af6b)
Location: include/linux/bitmap.h:356
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:cpu_attach_domain
Direct callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/time/tick-common.c (ffffffff811adb76)
Location: include/linux/bitmap.h:356
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff811ae54b)
Location: include/linux/bitmap.h:356
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (ffffffff811d8cda)
Location: include/linux/bitmap.h:356
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffffffff812305d9)
Location: include/linux/bitmap.h:356
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In mm/mempolicy.c (ffffffff81399769)
Location: include/linux/bitmap.h:356
Inline: True
Inline callers:
  - mm/mempolicy.c:__mpol_equal
  - mm/mempolicy.c:__mpol_equal
```
```
In mm/sparse.c (0)
Location: include/linux/bitmap.h:356
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff818b6aa3)
Location: include/linux/bitmap.h:356
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:private_candidate
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81ebf279)
Location: include/linux/bitmap.h:356
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/net/phy/phy.c (ffffffff81a53a6f)
Location: include/linux/bitmap.h:356
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_down
```
```
In drivers/net/phy/phy_device.c (ffffffff81a5a120)
Location: include/linux/bitmap.h:356
Inline: True
```
```
In net/ethtool/linkmodes.c (ffffffff81cc1b37)
Location: include/linux/bitmap.h:356
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
```
In net/ethtool/features.c (ffffffff81cc3041)
Location: include/linux/bitmap.h:356
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81e56b7d-ffffffff81e56b92: bitmap_equal (STB_LOCAL)
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
In arch/x86/hyperv/mmu.c (ffffffff81046b27)
Location: include/linux/bitmap.h:370
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048a85)
Location: include/linux/bitmap.h:370
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8109f7e8)
Location: include/linux/bitmap.h:370
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In kernel/workqueue.c (ffffffff81117baa)
Location: include/linux/bitmap.h:370
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/core.c (ffffffff8113ba35)
Location: include/linux/bitmap.h:370
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
```
In kernel/sched/build_utility.c (ffffffff83ea901b)
Location: include/linux/bitmap.h:370
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/time/tick-common.c (ffffffff811ee196)
Location: include/linux/bitmap.h:370
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff811eec9b)
Location: include/linux/bitmap.h:370
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (ffffffff8121dee9)
Location: include/linux/bitmap.h:370
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffffffff8127cc1b)
Location: include/linux/bitmap.h:370
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In mm/mempolicy.c (ffffffff814195e9)
Location: include/linux/bitmap.h:370
Inline: True
Inline callers:
  - mm/mempolicy.c:__mpol_equal
  - mm/mempolicy.c:__mpol_equal
  - mm/mempolicy.c:mpol_rebind_task
```
```
In mm/sparse.c (0)
Location: include/linux/bitmap.h:370
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81a05623)
Location: include/linux/bitmap.h:370
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:private_candidate
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81a330a6)
Location: include/linux/bitmap.h:370
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/net/phy/phy.c (ffffffff81bdd13b)
Location: include/linux/bitmap.h:370
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_down
```
```
In drivers/net/phy/phy_device.c (ffffffff81be4ea0)
Location: include/linux/bitmap.h:370
Inline: True
```
```
In net/ethtool/linkmodes.c (ffffffff81e80908)
Location: include/linux/bitmap.h:370
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
```
In net/ethtool/features.c (ffffffff81e82341)
Location: include/linux/bitmap.h:370
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
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
In arch/x86/hyperv/mmu.c (ffffffff81046d7d)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048d15)
Location: include/linux/bitmap.h:368
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a2778)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In kernel/workqueue.c (ffffffff81124d7a)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/core.c (ffffffff8114ef44)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
```
In kernel/sched/build_utility.c (ffffffff836cdadb)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/time/tick-common.c (ffffffff812028c6)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff812033cb)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (ffffffff81233fe9)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffffffff812948fb)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/cpumask.c (ffffffff8135d9f5)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_equal
```
```
In mm/mempolicy.c (ffffffff8144cbed)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - mm/mempolicy.c:__mpol_equal
  - mm/mempolicy.c:__mpol_equal
  - mm/mempolicy.c:mpol_rebind_task
```
```
In mm/sparse.c (0)
Location: include/linux/bitmap.h:368
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81a4e0c3)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:private_candidate
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81a7c996)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/net/phy/phy.c (ffffffff81c3292e)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_down
```
```
In drivers/net/phy/phy_device.c (ffffffff81c39e5d)
Location: include/linux/bitmap.h:368
Inline: True
```
```
In net/ethtool/linkmodes.c (ffffffff81edd144)
Location: include/linux/bitmap.h:368
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
```
In net/ethtool/features.c (0)
Location: include/linux/bitmap.h:368
Inline: True
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
In arch/x86/hyperv/mmu.c (ffffffff8104d4ff)
Location: include/linux/bitmap.h:345
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8104ffd5)
Location: include/linux/bitmap.h:345
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a9468)
Location: include/linux/bitmap.h:345
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In kernel/workqueue.c (ffffffff8112dc65)
Location: include/linux/bitmap.h:345
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_unbound_exclude_cpumask
  - kernel/workqueue.c:wqattrs_equal
  - kernel/workqueue.c:wqattrs_equal
```
```
In kernel/sched/core.c (ffffffff8115ade4)
Location: include/linux/bitmap.h:345
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
```
In kernel/sched/build_utility.c (ffffffff838fef19)
Location: include/linux/bitmap.h:345
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/time/tick-common.c (ffffffff81218e86)
Location: include/linux/bitmap.h:345
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (ffffffff8121998b)
Location: include/linux/bitmap.h:345
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (ffffffff8124dc39)
Location: include/linux/bitmap.h:345
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_exclusive_cpumask
  - kernel/cgroup/cpuset.c:update_exclusive_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffffffff812aff5b)
Location: include/linux/bitmap.h:345
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/trace/trace_events_filter.c (ffffffff812c6fbd)
Location: include/linux/bitmap.h:345
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:filter_pred_fn_call
  - kernel/trace/trace_events_filter.c:filter_pred_fn_call
```
```
In kernel/bpf/cpumask.c (ffffffff81386795)
Location: include/linux/bitmap.h:345
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_equal
```
```
In mm/mempolicy.c (ffffffff814864ed)
Location: include/linux/bitmap.h:345
Inline: True
Inline callers:
  - mm/mempolicy.c:__mpol_equal
  - mm/mempolicy.c:__mpol_equal
  - mm/mempolicy.c:mpol_rebind_task
```
```
In mm/sparse.c (0)
Location: include/linux/bitmap.h:345
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81a99d63)
Location: include/linux/bitmap.h:345
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:private_candidate
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81acee46)
Location: include/linux/bitmap.h:345
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
```
```
In drivers/net/phy/phy.c (ffffffff81ce761e)
Location: include/linux/bitmap.h:345
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_down
```
```
In drivers/net/phy/phy_device.c (ffffffff81cef1dd)
Location: include/linux/bitmap.h:345
Inline: True
```
```
In net/ethtool/linkmodes.c (ffffffff81fa0f14)
Location: include/linux/bitmap.h:345
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
```
In net/ethtool/features.c (0)
Location: include/linux/bitmap.h:345
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffff800010121620)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffff800010139958)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/topology.c (ffff80001015d380)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/isolation.c (ffff8000114455cc)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/time/tick-common.c (ffff8000101b1788)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_preferred
```
```
In kernel/time/tick-broadcast.c (ffff8000101b2484)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (ffff8000101e3f68)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffff800010231c90)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffff8000102a922c)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/frontswap.c (ffff80001032a70c)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/mempolicy.c (ffff800010337574)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_policy
```
```
In mm/sparse.c (ffff80001033c7ec)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/dma/dmaengine.c (ffff8000107fda0c)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/soc/fsl/qbman/qman_portal.c (ffff80001081164c)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
```
```
In drivers/net/phy/phy.c (ffff8000109d13cc)
Location: include/linux/bitmap.h:317
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffff8000109d64f8)
Location: include/linux/bitmap.h:317
Inline: True
```
**Symbols:**

```
ffff80001015d9c0-ffff80001015d9e0: bitmap_equal.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm/mach-tegra/pm.c (c034a970)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/arm/mach-tegra/pm.c:tegra_set_cpu_in_lp2
```
```
In kernel/workqueue.c (c037517c)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (c0389738)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/topology.c (c03a947c)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/isolation.c (c151f6b8)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/time/tick-common.c (c03fc1f8)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_preferred
  - kernel/time/tick-common.c:tick_check_percpu
  - kernel/time/tick-common.c:tick_check_percpu
  - kernel/time/tick-common.c:tick_setup_device
```
```
In kernel/time/tick-broadcast.c (c03fccc8)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (c0424fd8)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/trace/trace_hwlat.c (c046d7ac)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (c04d85f0)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/frontswap.c (c0540ef4)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In drivers/dma/dmaengine.c (c091eda0)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/net/phy/phy.c (c0ab9584)
Location: include/linux/bitmap.h:317
Inline: True
```
```
In drivers/net/phy/phy_device.c (c0abde04)
Location: include/linux/bitmap.h:317
Inline: True
```
```
In drivers/cpuidle/coupled.c (c0c056c8)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:cpuidle_coupled_register_device
```
**Symbols:**

```
c03a7850-c03a7878: bitmap_equal.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/powerpc/kernel/irq.c (c00000000001c218)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/powerpc/kernel/irq.c:irq_choose_cpu
```
```
In arch/powerpc/kernel/rtas.c (c00000000003ee40)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas.c:rtas_ibm_suspend_me
```
```
In arch/powerpc/kernel/smp.c (c00000000005636c)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:start_secondary
```
```
In arch/powerpc/sysdev/xics/xics-common.c (c0000000000ba804)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/xics-common.c:xics_get_irq_server
```
```
In kernel/workqueue.c (c00000000016ac80)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (c000000000186dbc)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/topology.c (c0000000001b1f74)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/isolation.c (c00000000136a00c)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/time/tick-common.c (c000000000216b20)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_preferred
```
```
In kernel/time/tick-broadcast.c (c000000000217c44)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (c000000000254444)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (c0000000002bc3bc)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (c00000000035d614)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/frontswap.c (c000000000401ad0)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/mempolicy.c (c000000000412ff0)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_policy
```
```
In mm/sparse.c (c0000000004178d8)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/dma/dmaengine.c (c0000000008c6b44)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/net/phy/phy.c (c000000000a910f8)
Location: include/linux/bitmap.h:317
Inline: True
```
```
In drivers/net/phy/phy_device.c (c000000000a97c30)
Location: include/linux/bitmap.h:317
Inline: True
```
**Symbols:**

```
c0000000001b24b4-c0000000001b24ec: bitmap_equal.constprop.0 (STB_LOCAL)
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
In kernel/workqueue.c (ffffffe0000da17c)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffe0000e953a)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/topology.c (ffffffe000101c0a)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/isolation.c (ffffffe0000072f6)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/time/tick-common.c (ffffffe000139fcc)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_preferred
```
```
In kernel/cgroup/cpuset.c (ffffffe00015a390)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/trace/trace_hwlat.c (ffffffe00018939a)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffe0001d284e)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/frontswap.c (ffffffe000229aee)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In drivers/dma/dmaengine.c (ffffffe000515d60)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/net/phy/phy.c (ffffffe00061d9c8)
Location: include/linux/bitmap.h:317
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffe000621f22)
Location: include/linux/bitmap.h:317
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int bitmap_equal(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102e8c4)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f462)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8106737c)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In kernel/workqueue.c (ffffffff810bdc5f)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810d442e)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/topology.c (ffffffff810f20d2)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/isolation.c (ffffffff828b6a13)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/time/tick-common.c (ffffffff8113f39d)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_preferred
```
```
In kernel/time/tick-broadcast.c (ffffffff8113f994)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (ffffffff81168ec7)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffffffff811abf02)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff8121611c)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/frontswap.c (ffffffff81286960)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/mempolicy.c (ffffffff812912b1)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_policy
```
```
In mm/sparse.c (0)
Location: include/linux/bitmap.h:317
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff8161d217)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8163b554)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
```
In drivers/net/phy/phy.c (ffffffff8177d9e7)
Location: include/linux/bitmap.h:317
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81781f9c)
Location: include/linux/bitmap.h:317
Inline: True
```
**Symbols:**

```
ffffffff810efe60-ffffffff810efe6b: bitmap_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int bitmap_equal(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8101e26c)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101edec)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8105773c)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In kernel/workqueue.c (ffffffff810ac489)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810c2a7e)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/topology.c (ffffffff810e2142)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/isolation.c (ffffffff828aec09)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/time/tick-common.c (ffffffff81131ecd)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_preferred
```
```
In kernel/time/tick-broadcast.c (ffffffff81132714)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (ffffffff8115c0d7)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119edf2)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff81208e7c)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/frontswap.c (ffffffff812787c0)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/mempolicy.c (ffffffff81282f31)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_policy
```
```
In mm/sparse.c (0)
Location: include/linux/bitmap.h:317
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81611907)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/net/phy/phy.c (ffffffff8175d7a7)
Location: include/linux/bitmap.h:317
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff81761d2c)
Location: include/linux/bitmap.h:317
Inline: True
```
```
In drivers/hv/channel_mgmt.c (ffffffff81852be0)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:init_vp_index
```
**Symbols:**

```
ffffffff810dfed0-ffffffff810dfedb: bitmap_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int bitmap_equal(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102e724)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f2c2)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8106782c)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In kernel/workqueue.c (ffffffff810bd1bf)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810d126e)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/topology.c (ffffffff810ef202)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/isolation.c (ffffffff828c98b7)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/time/tick-common.c (ffffffff8113d0bd)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_preferred
```
```
In kernel/time/tick-broadcast.c (ffffffff8113d844)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (ffffffff81166c97)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffffffff811a9cd2)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff81213ebc)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/frontswap.c (ffffffff81284770)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/mempolicy.c (ffffffff8128f0c1)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_policy
```
```
In mm/sparse.c (0)
Location: include/linux/bitmap.h:317
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff8164b1b7)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff816696a4)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
```
In drivers/net/phy/phy.c (ffffffff817add97)
Location: include/linux/bitmap.h:317
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff817b234c)
Location: include/linux/bitmap.h:317
Inline: True
```
**Symbols:**

```
ffffffff810ecf90-ffffffff810ecf9b: bitmap_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int bitmap_equal(const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102f514)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81030102)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81068e0c)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In kernel/workqueue.c (ffffffff810c5536)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff810dbbde)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
```
In kernel/sched/topology.c (ffffffff810fa242)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/isolation.c (ffffffff828cec69)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/time/tick-common.c (ffffffff81149bad)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_check_preferred
```
```
In kernel/time/tick-broadcast.c (ffffffff8114a354)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
```
```
In kernel/cgroup/cpuset.c (ffffffff81174345)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b7b12)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff812230fc)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/frontswap.c (ffffffff8129429c)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/mempolicy.c (ffffffff8129efc1)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_policy
```
```
In mm/sparse.c (0)
Location: include/linux/bitmap.h:317
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81665757)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81683c64)
Location: include/linux/bitmap.h:317
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
```
In drivers/net/phy/phy.c (ffffffff817c7d27)
Location: include/linux/bitmap.h:317
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff817cc2dc)
Location: include/linux/bitmap.h:317
Inline: True
```
**Symbols:**

```
ffffffff810f7fd0-ffffffff810f7fdb: bitmap_equal (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
