# Function: <code>bitmap_and</code>

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
In arch/x86/xen/mmu.c (ffffffff81021c0c)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81054fe0)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059fda)
Location: include/linux/bitmap.h:212
Inline: True
```
```
In kernel/workqueue.c (ffffffff81097640)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:workqueue_cpu_up_callback
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
```
```
In kernel/sched/core.c (ffffffff810adee8)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:build_sched_domain
```
```
In kernel/sched/cpupri.c (ffffffff810c414c)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (ffffffff810c457b)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/irq/manage.c (ffffffff810dbffb)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:setup_affinity
```
```
In kernel/time/tick-broadcast.c (ffffffff810fd050)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff81103c95)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cpuset.c (ffffffff8111ab33)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:guarantee_online_cpus
  - kernel/cpuset.c:guarantee_online_mems
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
```
```
In kernel/watchdog.c (ffffffff8113b3b6)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_cpumask
```
```
In kernel/padata.c (ffffffff8118a2d5)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In mm/mempolicy.c (ffffffff811e095e)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_nodemask
  - mm/mempolicy.c:mpol_set_nodemask
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In drivers/dma/dmaengine.c (ffffffff814bd5a3)
Location: include/linux/bitmap.h:212
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816b1b5d)
Location: include/linux/bitmap.h:212
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In arch/x86/xen/mmu.c (ffffffff81020f33)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055dd9)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a2aa)
Location: include/linux/bitmap.h:222
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a07b6)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (ffffffff810b17b6)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/cpupri.c (ffffffff810c7e18)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (ffffffff810c825b)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/irq/manage.c (ffffffff810e1788)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:setup_affinity
```
```
In kernel/time/tick-broadcast.c (ffffffff81104396)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff8110b0b2)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cpuset.c (ffffffff81125122)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:guarantee_online_mems
```
```
In kernel/watchdog.c (ffffffff81143916)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_cpumask
```
```
In kernel/padata.c (ffffffff8119c99e)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In mm/mempolicy.c (ffffffff811ff52c)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_set_nodemask
  - mm/mempolicy.c:mpol_set_nodemask
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:222
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81713bd2)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In arch/x86/xen/mmu.c (ffffffff810216df)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058b88)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d06b)
Location: include/linux/bitmap.h:222
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a58ce)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/sched/core.c (ffffffff810b79f4)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff810bd5a7)
Location: include/linux/bitmap.h:222
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810cde0a)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (ffffffff810ce277)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/irq/manage.c (ffffffff810e80e9)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:setup_affinity
```
```
In kernel/irq/affinity.c (ffffffff810efbf6)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8110bba3)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff81112a8c)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cpuset.c (ffffffff8112e53b)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:guarantee_online_mems
```
```
In kernel/watchdog.c (ffffffff8114d516)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_cpumask
```
```
In kernel/trace/trace_hwlat.c (ffffffff8116d4a3)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff811abedb)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In mm/mempolicy.c (ffffffff8120fcf7)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_set_nodemask
  - mm/mempolicy.c:mpol_set_nodemask
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:222
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8174598c)
Location: include/linux/bitmap.h:222
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In arch/x86/xen/mmu_pv.c (ffffffff81023c99)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810436b9)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810581e6)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c470)
Location: include/linux/bitmap.h:221
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a294c)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/sched/core.c (ffffffff810b2f32)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff810c05f9)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/cpupri.c (ffffffff810ca779)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (ffffffff810cabb3)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810cc329)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domain
```
```
In kernel/irq/manage.c (ffffffff810e7815)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/affinity.c (ffffffff810efba4)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8110dbd9)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff81113f62)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff8112fbd8)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/watchdog.c (ffffffff8114f4df)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_cpumask
```
```
In kernel/trace/trace_hwlat.c (ffffffff81170979)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff811b333b)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In mm/mempolicy.c (ffffffff8121b32f)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:221
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81764079)
Location: include/linux/bitmap.h:221
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In arch/x86/xen/mmu_pv.c (ffffffff8102481d)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81046d2c)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105bf48)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff810a927c)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/sched/core.c (ffffffff810ba332)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff810c7d09)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/cpupri.c (ffffffff810d1f89)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (ffffffff810d2363)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810d4f4d)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (ffffffff810efb95)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/affinity.c (ffffffff810f877d)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff81118e5b)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff8111f4f2)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff8113cd71)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/watchdog.c (ffffffff8115b886)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_update
```
```
In kernel/trace/trace_hwlat.c (ffffffff8117db4b)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff811c6f90)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In mm/mempolicy.c (ffffffff8123654f)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:231
Inline: True
```
```
In drivers/base/node.c (ffffffff81660e87)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817da06f)
Location: include/linux/bitmap.h:231
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In arch/x86/xen/mmu_pv.c (ffffffff81025757)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810491a8)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105edab)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/workqueue.c (ffffffff810af9ac)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/sched/core.c (ffffffff810c1945)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff810cfd6a)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/cpupri.c (ffffffff810da01a)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (ffffffff810da443)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810dcad7)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (ffffffff810f7fb7)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/affinity.c (ffffffff81100897)
Location: include/linux/bitmap.h:262
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff811259db)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff8112c825)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff8114b393)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/watchdog.c (ffffffff8116a3d5)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_update
```
```
In kernel/trace/trace_hwlat.c (ffffffff8118c994)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff811e71e0)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In mm/mempolicy.c (ffffffff8125a266)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In drivers/dma/dmaengine.c (ffffffff815e7b14)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/base/node.c (ffffffff8169c640)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81822b92)
Location: include/linux/bitmap.h:262
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In arch/x86/xen/mmu_pv.c (ffffffff81024df7)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810591a9)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81064d0b)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
```
In kernel/workqueue.c (ffffffff810b8b1c)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/sched/core.c (ffffffff810cac75)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff810d953a)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/cpupri.c (ffffffff810e3b6a)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (ffffffff810e3f93)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810e6737)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (ffffffff81103729)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/affinity.c (ffffffff8110c051)
Location: include/linux/bitmap.h:263
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff811310cb)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff811380f5)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff81157c6b)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/watchdog.c (ffffffff811773e5)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_update
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119a4a4)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff811f7f30)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In mm/mempolicy.c (ffffffff8126e0f6)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In drivers/dma/dmaengine.c (ffffffff81602f84)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/base/node.c (ffffffff816bcfd0)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In drivers/net/phy/phy.c (ffffffff81758d88)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-core.c (ffffffff8175984a)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff8175a7b0)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8184ea72)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In arch/x86/xen/mmu_pv.c (ffffffff8102700e)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c745)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81068412)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
```
In kernel/workqueue.c (ffffffff810be61c)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/sched/core.c (ffffffff810d2935)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff810e07a3)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/cpupri.c (ffffffff810ea77a)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (ffffffff810eab7e)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810ed37a)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (ffffffff8110c153)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/affinity.c (ffffffff811157d0)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8113bc26)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff811432a8)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff811621f3)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/watchdog.c (ffffffff811841c5)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_update
```
```
In kernel/trace/trace_hwlat.c (ffffffff811a810c)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff8120fdbc)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In mm/mempolicy.c (ffffffff81289703)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/sparse.c (ffffffff8128dab5)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/dma/dmaengine.c (ffffffff81635654)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/base/node.c (ffffffff816f7800)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In drivers/net/phy/phy.c (ffffffff81794a45)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817962cc)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81796da7)
Location: include/linux/bitmap.h:263
Inline: True
```
```
In drivers/net/phy/phy_device.c (ffffffff817983ab)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81891c54)
Location: include/linux/bitmap.h:263
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In arch/x86/xen/mmu_pv.c (ffffffff810275ee)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d04b)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81068d52)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
```
In kernel/workqueue.c (ffffffff810c4bcc)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/sched/core.c (ffffffff810dcda5)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff810eae33)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/cpupri.c (ffffffff810f614a)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (ffffffff810f654c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810f8f27)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (ffffffff81118583)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/affinity.c (ffffffff81121c0c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff81147836)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff8114ede8)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff8116ded3)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/watchdog.c (ffffffff81190045)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_update
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b390c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff8121dab2)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/mempolicy.c (ffffffff81299299)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/sparse.c (ffffffff8129d6fb)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/dma/dmaengine.c (ffffffff81657374)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/base/node.c (ffffffff8171bc60)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In drivers/net/phy/phy.c (ffffffff817b85e5)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817b9c8c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff817bada7)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff817bc74b)
Location: include/linux/bitmap.h:267
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c3c73)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In arch/x86/xen/mmu_pv.c (ffffffff810289c5)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810615c8)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106f9aa)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/workqueue.c (ffffffff810cc6da)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (ffffffff810e5985)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff810f4ecd)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
```
```
In kernel/sched/cpupri.c (ffffffff810ffa0c)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
```
In kernel/sched/cpudeadline.c (ffffffff810ffedc)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff81102f77)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sd_init
```
```
In kernel/irq/manage.c (ffffffff81123e73)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/affinity.c (ffffffff8112e273)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In kernel/time/tick-broadcast.c (ffffffff81157546)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff8115f758)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff81182c8d)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/watchdog.c (ffffffff811a4bc5)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_update
```
```
In kernel/trace/trace_hwlat.c (ffffffff811cc37d)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/padata.c (ffffffff81249b01)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/mempolicy.c (ffffffff812cd410)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/sparse.c (ffffffff812d1304)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - mm/sparse.c:clear_subsection_map
```
```
In drivers/dma/dmaengine.c (ffffffff81706ca0)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:private_candidate
```
```
In drivers/base/node.c (ffffffff817d7cb0)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In drivers/net/phy/phy.c (ffffffff8187fe83)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff8188137c)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81882657)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81883f9c)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff8188608e)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
```
```
In drivers/cpufreq/cpufreq.c (ffffffff819961f0)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In net/ethtool/features.c (ffffffff81a8a1ee)
Location: include/linux/bitmap.h:283
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
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
In arch/x86/xen/mmu_pv.c (ffffffff81029545)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f9d8)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81070e8a)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/workqueue.c (ffffffff810c785a)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (ffffffff810e35ae)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff810f2f3d)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
```
```
In kernel/sched/cpupri.c (ffffffff810fe509)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
```
In kernel/sched/cpudeadline.c (ffffffff810fe997)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff81101ba0)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sd_init
```
```
In kernel/irq/manage.c (ffffffff8111fcd3)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/affinity.c (ffffffff81129e63)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In kernel/time/tick-broadcast.c (ffffffff81153616)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff8115b6f8)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff8117fbdd)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/watchdog.c (ffffffff811a1c65)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_update
```
```
In kernel/trace/trace_hwlat.c (ffffffff811c99d8)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/padata.c (ffffffff81253b42)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In mm/mempolicy.c (ffffffff812d9c75)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/sparse.c (ffffffff812dce24)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - mm/sparse.c:clear_subsection_map
```
```
In drivers/dma/dmaengine.c (ffffffff817240e0)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:private_candidate
```
```
In drivers/base/node.c (ffffffff817ec6c0)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In drivers/net/phy/phy.c (ffffffff8188e733)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff8188faac)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81890d87)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff818926cc)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff818944ee)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81999300)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In net/core/net-sysfs.c (ffffffff81a3a744)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ethtool/features.c (ffffffff81a93a75)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
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
In arch/x86/xen/mmu_pv.c (ffffffff81029593)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105296f)
Location: include/linux/bitmap.h:281
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fa48)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107166a)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/workqueue.c (ffffffff810c921c)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (ffffffff810e573e)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff810f5111)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_cpu
```
```
In kernel/sched/cpupri.c (ffffffff811008ec)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
```
In kernel/sched/cpudeadline.c (ffffffff81100d5b)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff81103f15)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sd_init
```
```
In kernel/irq/manage.c (ffffffff8111ff83)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/affinity.c (ffffffff8112a0dd)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In kernel/time/tick-broadcast.c (ffffffff81154ad6)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff8115c7ec)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff811806bd)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/watchdog.c (ffffffff811a2955)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_update
```
```
In kernel/trace/trace_hwlat.c (ffffffff811cadba)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/padata.c (ffffffff812581d2)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In mm/mempolicy.c (ffffffff812e14f1)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/sparse.c (ffffffff812e46d2)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/dma/dmaengine.c (ffffffff81705350)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:private_candidate
```
```
In drivers/base/node.c (ffffffff817d0f30)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In drivers/net/phy/phy.c (ffffffff81870ff4)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff8187234c)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81873667)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81874e8c)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff81876dee)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197dbd6)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/powercap/dtpm_cpu.c (ffffffff819baf8b)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - drivers/powercap/dtpm_cpu.c:get_pd_power_uw
  - drivers/powercap/dtpm_cpu.c:set_pd_power_limit
```
```
In net/core/net-sysfs.c (ffffffff81a218c3)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ethtool/features.c (ffffffff81a7d4ad)
Location: include/linux/bitmap.h:281
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
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
In arch/x86/xen/mmu_pv.c (ffffffff8102dd33)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105af2f)
Location: include/linux/bitmap.h:287
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810690a8)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107de8a)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/workqueue.c (ffffffff810dbef6)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (ffffffff810fc81e)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff8110ec11)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_cpu
```
```
In kernel/sched/cpupri.c (ffffffff8111c954)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
```
In kernel/sched/cpudeadline.c (ffffffff8111cecb)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff81120f92)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sd_init
```
```
In kernel/irq/manage.c (ffffffff8114049c)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/affinity.c (ffffffff8114aa3b)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In kernel/time/tick-broadcast.c (ffffffff81179740)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff81181942)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff811a84ad)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/watchdog.c (ffffffff811cc125)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_update
```
```
In kernel/trace/trace_hwlat.c (ffffffff811f6db6)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/padata.c (ffffffff81293d48)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In mm/mempolicy.c (ffffffff813287c1)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/sparse.c (ffffffff8132b9e2)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/dma/dmaengine.c (ffffffff81780b30)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:private_candidate
```
```
In drivers/base/node.c (ffffffff8185b902)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
```
```
In drivers/net/phy/phy.c (ffffffff819016d4)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81902a5c)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81903f10)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff8190595c)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff819079fe)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a26c87)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/powercap/dtpm_cpu.c (ffffffff81a6a08b)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - drivers/powercap/dtpm_cpu.c:get_pd_power_uw
  - drivers/powercap/dtpm_cpu.c:set_pd_power_limit
```
```
In net/core/net-sysfs.c (ffffffff81ad5e4b)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ethtool/features.c (ffffffff81b376af)
Location: include/linux/bitmap.h:287
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81032d34)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f1599e)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810762cb)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8108cb49)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/workqueue.c (ffffffff810f561e)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff81118e61)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff8112ab41)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_cpu
```
```
In kernel/sched/build_policy.c (ffffffff81133c6b)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_find
```
```
In kernel/sched/build_utility.c (ffffffff8114b391)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
```
In kernel/irq/manage.c (ffffffff81163e21)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/affinity.c (ffffffff81170034)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In kernel/time/tick-broadcast.c (ffffffff811aeb11)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff811b7f8f)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9616)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/watchdog.c (ffffffff811ffef5)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_update
```
```
In kernel/trace/trace_hwlat.c (ffffffff812305eb)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/padata.c (ffffffff812e9d88)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In mm/mempolicy.c (ffffffff81397a16)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/sparse.c (ffffffff8139b640)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/pci/pci-driver.c (ffffffff817c8d6d)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/dma/dmaengine.c (ffffffff818b6aa0)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:private_candidate
```
```
In drivers/base/node.c (ffffffff819a290b)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
```
```
In drivers/net/phy/phy.c (ffffffff81a53025)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81a5505f)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81a569a0)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81a5a6ab)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
```
In drivers/net/phy/linkmode.c (ffffffff81a5aa9e)
Location: include/linux/bitmap.h:306
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b90c15)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In net/core/net-sysfs.c (ffffffff81c5663c)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ethtool/features.c (ffffffff81cc3107)
Location: include/linux/bitmap.h:306
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81e54961-ffffffff81e5497a: bitmap_and.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool bitmap_and(long unsigned int *dst, const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103a69f)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820bd0c2)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108686b)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a1159)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/workqueue.c (ffffffff81117b78)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff81140661)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
Direct callers:
  - kernel/sched/core.c:__sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff8115450d)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
```
```
In kernel/sched/build_policy.c (ffffffff8115e16b)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_find
```
```
In kernel/sched/build_utility.c (ffffffff81179db2)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
```
In kernel/irq/manage.c (ffffffff81197b41)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/affinity.c (ffffffff811a648c)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In kernel/time/tick-broadcast.c (ffffffff811ef47a)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff811f922b)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff8121ea16)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/watchdog.c (ffffffff812479e5)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_update
```
```
In kernel/trace/trace_hwlat.c (ffffffff8127cc52)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/padata.c (ffffffff81353cde)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In mm/mempolicy.c (ffffffff814175f6)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/sparse.c (ffffffff8141b680)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-tiers.c (ffffffff81436f67)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - mm/memory-tiers.c:establish_demotion_targets
```
```
In drivers/pci/pci-driver.c (ffffffff818e6672)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/dma/dmaengine.c (ffffffff81a05620)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:private_candidate
```
```
In drivers/char/random.c (ffffffff81a94eb0)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/base/node.c (ffffffff81b148c0)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
```
```
In drivers/net/phy/phy.c (ffffffff81bdc185)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81bde3df)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81be0702)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81be460b)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff81be533e)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d30de7)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In net/core/net-sysfs.c (ffffffff81e0c0f1)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ethtool/features.c (ffffffff81e82407)
Location: include/linux/bitmap.h:320
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff8112f570-ffffffff8112f587: bitmap_and (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool bitmap_and(long unsigned int *dst, const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103a76f)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213ead2)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810892e9)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a4149)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/cpu.c (ffffffff836c9d03)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
```
```
In kernel/workqueue.c (ffffffff81124d48)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff8114c521)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
Direct callers:
  - kernel/sched/core.c:__sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff81164675)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
```
```
In kernel/sched/build_policy.c (ffffffff8116e844)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_find
```
```
In kernel/sched/build_utility.c (ffffffff8118a8ce)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
```
In kernel/irq/manage.c (ffffffff811a9801)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/time/tick-broadcast.c (ffffffff812039da)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff8120ded5)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff81234b06)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_fork
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/watchdog.c (ffffffff8125ee05)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_update
```
```
In kernel/trace/trace_hwlat.c (ffffffff81294932)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/trace/trace_osnoise.c (ffffffff81297282)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:start_per_cpu_kthreads
```
```
In kernel/bpf/cpumask.c (ffffffff8135d935)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_and
```
```
In kernel/padata.c (ffffffff81384ede)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In mm/mempolicy.c (ffffffff8144ab86)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/sparse.c (ffffffff8144ec20)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-tiers.c (ffffffff8146cc27)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - mm/memory-tiers.c:establish_demotion_targets
```
```
In lib/group_cpus.c (ffffffff818e6ecf)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:alloc_nodes_groups
```
```
In drivers/pci/pci-driver.c (ffffffff81929cb2)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/dma/dmaengine.c (ffffffff81a4e0c0)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:private_candidate
```
```
In drivers/char/random.c (ffffffff81ae06d0)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/base/node.c (ffffffff81b63630)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
```
```
In drivers/net/phy/phy.c (ffffffff81c332d6)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81c3620c)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81c38012)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3c848)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff81c3cdce)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d9a07d)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In net/core/net-sysfs.c (ffffffff81e8166f)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
```
```
In net/ethtool/features.c (ffffffff81edea67)
Location: include/linux/bitmap.h:318
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff8113cff0-ffffffff8113d007: bitmap_and (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool bitmap_and(long unsigned int *dst, const long unsigned int *src1, const long unsigned int *src2, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81040c2f)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82220af2)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810902d9)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810ab179)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
```
```
In kernel/cpu.c (ffffffff838fa973)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
```
```
In kernel/workqueue.c (ffffffff838fbadf)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/workqueue.c:restrict_unbound_cpumask
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_pod_cpumask
  - kernel/workqueue.c:wq_calc_pod_cpumask
  - kernel/workqueue.c:wq_calc_pod_cpumask
  - kernel/workqueue.c:wqattrs_actualize_cpumask
```
```
In kernel/sched/core.c (ffffffff811581e1)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
Direct callers:
  - kernel/sched/core.c:__sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff8117141f)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
```
```
In kernel/sched/build_policy.c (ffffffff8117be0e)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_find
```
```
In kernel/sched/build_utility.c (ffffffff811991e4)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
```
In kernel/irq/manage.c (ffffffff811b9361)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/rcu/tree.c (ffffffff83903ba3)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_nohz
```
```
In kernel/time/tick-broadcast.c (ffffffff81219f9a)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff81225665)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff8124e726)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_fork
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_sibling_cpumasks
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:compute_partition_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:partition_xcpus_del
  - kernel/cgroup/cpuset.c:reset_partition_data
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/watchdog.c (ffffffff81278e15)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_update
```
```
In kernel/trace/trace_hwlat.c (ffffffff812aff92)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b28d2)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:start_per_cpu_kthreads
```
```
In kernel/bpf/cpumask.c (ffffffff813866d5)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_and
```
```
In kernel/padata.c (ffffffff813ae24d)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In mm/mempolicy.c (ffffffff814845c5)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/sparse.c (ffffffff814887c4)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In mm/memory-tiers.c (ffffffff8149bd77)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - mm/memory-tiers.c:establish_demotion_targets
```
```
In lib/group_cpus.c (ffffffff8192deef)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:alloc_nodes_groups
```
```
In drivers/pci/pci-driver.c (ffffffff819724b2)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/dma/dmaengine.c (ffffffff81a99d60)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:private_candidate
```
```
In drivers/char/random.c (ffffffff81b33ad0)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/base/node.c (ffffffff81bb7140)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
```
```
In drivers/net/phy/phy.c (ffffffff81ce7fc6)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
```
```
In drivers/net/phy/phy-c45.c (ffffffff81ceb18c)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff81ced3a2)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81cf1c48)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/linkmode.c (ffffffff81cf21ce)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e51d2d)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In net/core/net-sysfs.c (ffffffff81f4264f)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
```
```
In net/ethtool/features.c (ffffffff81fa2899)
Location: include/linux/bitmap.h:295
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81148160-ffffffff81148177: bitmap_and (STB_LOCAL)
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
In arch/arm64/kernel/fpsimd.c (ffff800010087a3c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:sve_update_vq_map
```
```
In arch/arm64/kernel/alternative.c (ffff80001009b5a8)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - arch/arm64/kernel/alternative.c:__apply_alternatives
```
```
In kernel/workqueue.c (ffff80001012310c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (ffff80001013c870)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/fair.c (ffff80001014af34)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/cpupri.c (ffff800010159de8)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (ffff80001015a3d0)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffff80001015d618)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (ffff80001017ae5c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/affinity.c (ffff800010187dc4)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffff8000101b2a5c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffff8000101bd334)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffff8000101e2700)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/watchdog.c (ffff8000102078e8)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_update
```
```
In kernel/trace/trace_hwlat.c (ffff800010231f40)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffff8000102a9220)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/mempolicy.c (ffff800010337d24)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/sparse.c (ffff80001033c7d8)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/dma/dmaengine.c (ffff8000107fda08)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/base/node.c (ffff80001090f59c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
```
In drivers/net/phy/phy.c (ffff8000109d1a14)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffff8000109d1e04)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffff8000109d38b4)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffff8000109d5790)
Location: include/linux/bitmap.h:267
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b218e0)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b96bac)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_offline_cpu
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b99bbc)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu
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
In kernel/workqueue.c (c0376a34)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/sched/core.c (c038cc60)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/fair.c (c0398c84)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/cpupri.c (c03a6c54)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (c03a7198)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (c03a9704)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (c03cbf68)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/affinity.c (c03d6838)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (c03fd19c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (c0405508)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (c0424a8c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/watchdog.c (c0446bdc)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_cpumask
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
```
```
In kernel/trace/trace_hwlat.c (c046d5a4)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (c04d85f0)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In drivers/dma/dmaengine.c (c091ed9c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/net/phy/phy.c (c0ab9bf8)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (c0ab9fdc)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (c0abb71c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (c0abd280)
Location: include/linux/bitmap.h:267
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (c0bfbeb0)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpuidle/coupled.c (c0c05088)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:coupled_cpu_online
  - drivers/cpuidle/coupled.c:cpuidle_coupled_register_device
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
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
In arch/powerpc/mm/numa.c (c000000001357770)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:mem_topology_setup
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012c4b4)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_online
  - arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_online
```
```
In kernel/workqueue.c (c00000000016cf50)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (c00000000018afd0)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/fair.c (c00000000019d480)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/cpupri.c (c0000000001ae060)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (c0000000001ae680)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (c0000000001b2258)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (c0000000001d53bc)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/affinity.c (c0000000001e1af8)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (c0000000002184b4)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (c000000000223714)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (c000000000250e2c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/watchdog.c (c00000000028412c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_update
```
```
In kernel/trace/trace_hwlat.c (c0000000002bc3e0)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (c00000000035d5f4)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/mempolicy.c (c000000000412bc8)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/sparse.c (c0000000004178d0)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/dma/dmaengine.c (c0000000008c6b40)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/base/node.c (c0000000009b03b4)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In drivers/net/phy/phy.c (c000000000a90c78)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (c000000000a91afc)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (c000000000a93db0)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (c000000000a966bc)
Location: include/linux/bitmap.h:267
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (c000000000c15928)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/powernv-cpufreq.c (c000000000c1c8f8)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_work_fn
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
In kernel/workqueue.c (ffffffe0000db942)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/sched/core.c (ffffffe0000ebfec)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffe0000f480c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:select_task_rq_fair
```
```
In kernel/sched/cpupri.c (ffffffe0000ff900)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (ffffffe0000ffd9c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffe000101e22)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (ffffffe000114a54)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/affinity.c (ffffffe00011d734)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/smp.c (ffffffe0001409a6)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffe0001592a4)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/watchdog.c (ffffffe00016a5a8)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_cpumask
  - kernel/watchdog.c:proc_watchdog_thresh
  - kernel/watchdog.c:proc_watchdog_common
```
```
In kernel/trace/trace_hwlat.c (ffffffe0001893e0)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffe0001d2c9a)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In drivers/dma/dmaengine.c (ffffffe000515d5c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/net/phy/phy.c (ffffffe00061e3f0)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffe00061e852)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffe00061ff62)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffe000621920)
Location: include/linux/bitmap.h:267
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff8102774e)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105cbcb)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81068842)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
```
In kernel/workqueue.c (ffffffff810bef3c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/sched/core.c (ffffffff810d6fb5)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff810e4f93)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/cpupri.c (ffffffff810ef54a)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (ffffffff810ef94c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810f2327)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (ffffffff81110b63)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/affinity.c (ffffffff8111a1ec)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8113fe56)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff81147408)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff811664f3)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/watchdog.c (ffffffff81188665)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_update
```
```
In kernel/trace/trace_hwlat.c (ffffffff811abf2c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff81216102)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/mempolicy.c (ffffffff81291879)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/sparse.c (ffffffff81295cdb)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/dma/dmaengine.c (ffffffff8161d214)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/base/node.c (ffffffff816e1f90)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In drivers/net/phy/phy.c (ffffffff8177d0b5)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff8177e75c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff8177f877)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff8178121b)
Location: include/linux/bitmap.h:267
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81868393)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104cd9b)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058bb2)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
```
In kernel/workqueue.c (ffffffff810ad75c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/sched/core.c (ffffffff810c58a5)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff810d4143)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/cpupri.c (ffffffff810df5ba)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (ffffffff810df9bc)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810e2397)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (ffffffff81101893)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/affinity.c (ffffffff8110b25c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff828b0ee4)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_nohz
```
```
In kernel/time/tick-broadcast.c (ffffffff81132bd6)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff8113a6e3)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff81159733)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/watchdog.c (ffffffff8117b7a5)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_update
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119ee1c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff81208e62)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/mempolicy.c (ffffffff812834f9)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/sparse.c (ffffffff812878eb)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/dma/dmaengine.c (ffffffff81611904)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/base/node.c (ffffffff816bc5d0)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In drivers/net/phy/phy.c (ffffffff8175ce65)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff8175e4fc)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff8175f617)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff81760fab)
Location: include/linux/bitmap.h:267
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81831043)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In arch/x86/xen/mmu_pv.c (ffffffff810275ae)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105cffb)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81068cf2)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
```
In kernel/workqueue.c (ffffffff810be49c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/sched/core.c (ffffffff810d3bf5)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff810e1363)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/cpupri.c (ffffffff810ec67a)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (ffffffff810eca7c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810ef457)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (ffffffff8110ea53)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/affinity.c (ffffffff811180dc)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8113dd06)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff811452b8)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff811642c3)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/watchdog.c (ffffffff81186435)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_update
```
```
In kernel/trace/trace_hwlat.c (ffffffff811a9cfc)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff81213ea2)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/mempolicy.c (ffffffff8128f689)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/sparse.c (ffffffff81293aeb)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/dma/dmaengine.c (ffffffff8164b1b4)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/base/node.c (ffffffff8170f4c0)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In drivers/net/phy/phy.c (ffffffff817ad465)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817aeb0c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff817afc27)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff817b15cb)
Location: include/linux/bitmap.h:267
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b9123)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
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
In arch/x86/xen/mmu_pv.c (ffffffff8102812e)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e51b)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106a4a4)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
```
```
In kernel/workqueue.c (ffffffff810c680c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
```
```
In kernel/sched/core.c (ffffffff810deba7)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff810ecf03)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/cpupri.c (ffffffff810f76ba)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find
```
```
In kernel/sched/cpudeadline.c (ffffffff810f7abc)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810fa4a1)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/manage.c (ffffffff81119f81)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/irq/affinity.c (ffffffff8112376c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffffffff8114a814)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
```
In kernel/smp.c (ffffffff81151e98)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff8117176e)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In kernel/watchdog.c (ffffffff81193d85)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/watchdog.c:proc_watchdog_update
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b7b3c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/padata.c (ffffffff812230e2)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
```
```
In mm/mempolicy.c (ffffffff8129faf3)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/sparse.c (ffffffff812a394b)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
```
```
In drivers/dma/dmaengine.c (ffffffff81665754)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:find_candidate
```
```
In drivers/base/node.c (ffffffff8172a280)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
```
In drivers/net/phy/phy.c (ffffffff817c73f5)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
```
```
In drivers/net/phy/phy-c45.c (ffffffff817c8a9c)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy-core.c (ffffffff817c9bb7)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
```
In drivers/net/phy/phy_device.c (ffffffff817cb55b)
Location: include/linux/bitmap.h:267
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d5403)
Location: include/linux/bitmap.h:267
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
