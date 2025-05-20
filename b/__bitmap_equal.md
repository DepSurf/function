# Function: <code>__bitmap_equal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff813f8dd0)
Location: lib/bitmap.c:45
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:partition_sched_domains
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cpuset.c:rebuild_sched_domains_locked
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff813f8dd0-ffffffff813f8e39: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8143fc80)
Location: lib/bitmap.c:47
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:rebuild_sched_domains_locked
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff8143fc80-ffffffff8143fcf1: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8145cd80)
Location: lib/bitmap.c:47
Inline: False
Direct callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
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
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - mm/mempolicy.c:mpol_rebind_policy
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff8145cd80-ffffffff8145cdf1: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81461fd0)
Location: lib/bitmap.c:47
Inline: False
Direct callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff81461fd0-ffffffff81462040: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8148deb0)
Location: lib/bitmap.c:49
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff8148deb0-ffffffff8148df20: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814c2c30)
Location: lib/bitmap.c:49
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/time/tick-common.c:tick_check_preferred
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff814c2c30-ffffffff814c2c9a: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d72e0)
Location: lib/bitmap.c:46
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/time/tick-common.c:tick_check_preferred
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff814d72e0-ffffffff814d734a: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81503140)
Location: lib/bitmap.c:46
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/time/tick-common.c:tick_check_preferred
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/net/phy/phy.c:phy_speed_up
```
**Symbols:**

```
ffffffff81503140-ffffffff815031a3: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815210e0)
Location: lib/bitmap.c:46
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/time/tick-common.c:tick_check_preferred
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff815210e0-ffffffff81521143: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815842e0)
Location: lib/bitmap.c:46
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:init_overlap_sched_group
  - kernel/sched/topology.c:build_balance_mask
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/time/tick-common.c:tick_check_preferred
  - kernel/time/tick-common.c:tick_check_percpu
  - kernel/time/tick-common.c:tick_check_percpu
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
**Symbols:**

```
ffffffff815842e0-ffffffff81584339: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a13f0)
Location: lib/bitmap.c:46
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:init_overlap_sched_group
  - kernel/sched/topology.c:build_balance_mask
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/time/tick-common.c:tick_check_preferred
  - kernel/time/tick-common.c:tick_check_percpu
  - kernel/time/tick-common.c:tick_check_percpu
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
**Symbols:**

```
ffffffff815a13f0-ffffffff815a1449: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a82a0)
Location: lib/bitmap.c:48
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
**Symbols:**

```
ffffffff815a82a0-ffffffff815a82ff: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81611260)
Location: lib/bitmap.c:48
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
**Symbols:**

```
ffffffff81611260-ffffffff816112bf: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816dd2a0)
Location: lib/bitmap.c:48
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_down
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
**Symbols:**

```
ffffffff816dd2a0-ffffffff816dd321: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817cd120)
Location: lib/bitmap.c:48
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
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
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_down
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
**Symbols:**

```
ffffffff817cd120-ffffffff817cd1a1: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180b530)
Location: lib/bitmap.c:48
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:get_unbound_pool
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
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
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/bpf/cpumask.c:bpf_cpumask_equal
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_down
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
**Symbols:**

```
ffffffff8180b530-ffffffff8180b5b1: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81851d10)
Location: lib/bitmap.c:37
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_unbound_exclude_cpumask
  - kernel/workqueue.c:wqattrs_equal
  - kernel/workqueue.c:wqattrs_equal
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
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
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_check_replacement
  - kernel/time/tick-common.c:tick_setup_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_exclusive_cpumask
  - kernel/cgroup/cpuset.c:update_exclusive_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/trace/trace_events_filter.c:filter_pred_fn_call
  - kernel/trace/trace_events_filter.c:filter_pred_fn_call
  - kernel/bpf/cpumask.c:bpf_cpumask_equal
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_speed_down
  - net/ethtool/linkmodes.c:ethnl_auto_linkmodes
```
**Symbols:**

```
ffffffff81851d10-ffffffff81851d91: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062a778)
Location: lib/bitmap.c:46
Inline: False
```
**Symbols:**

```
ffff80001062a778-ffff80001062a7f0: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c07d1940)
Location: lib/bitmap.c:46
Inline: False
```
**Symbols:**

```
c07d1940-c07d19c0: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007cc760)
Location: lib/bitmap.c:46
Inline: False
```
**Symbols:**

```
c0000000007cc760-c0000000007cc7ec: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffe00045b0b8)
Location: lib/bitmap.c:46
Inline: False
```
**Symbols:**

```
ffffffe00045b0b8-ffffffe00045b122: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815196c0)
Location: lib/bitmap.c:46
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/time/tick-common.c:tick_check_preferred
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff815196c0-ffffffff81519723: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815099b0)
Location: lib/bitmap.c:46
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/time/tick-common.c:tick_check_preferred
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - drivers/hv/channel_mgmt.c:init_vp_index
```
**Symbols:**

```
ffffffff815099b0-ffffffff81509a13: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81515750)
Location: lib/bitmap.c:46
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/time/tick-common.c:tick_check_preferred
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff81515750-ffffffff815157b3: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __bitmap_equal(const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152eee0)
Location: lib/bitmap.c:46
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/time/tick-common.c:tick_check_preferred
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
```
**Symbols:**

```
ffffffff8152eee0-ffffffff8152ef43: __bitmap_equal (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
