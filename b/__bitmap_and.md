# Function: <code>__bitmap_and</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff813f8e80)
Location: lib/bitmap.c:153
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:workqueue_cpu_up_callback
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:setup_affinity
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:guarantee_online_cpus
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/watchdog.c:proc_watchdog_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff813f8e80-ffffffff813f8edf: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8143fd40)
Location: lib/bitmap.c:155
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:setup_affinity
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:proc_watchdog_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff8143fd40-ffffffff8143fd9f: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8145ce40)
Location: lib/bitmap.c:155
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:guarantee_online_mems
  - kernel/watchdog.c:proc_watchdog_cpumask
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_set_nodemask
  - mm/mempolicy.c:mpol_set_nodemask
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff8145ce40-ffffffff8145ce9f: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81462090)
Location: lib/bitmap.c:155
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/fair.c:load_balance
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:build_sched_domain
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - kernel/watchdog.c:proc_watchdog_cpumask
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/mempolicy.c:mpol_rebind_nodemask
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81462090-ffffffff814620fb: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8148df70)
Location: lib/bitmap.c:157
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/fair.c:load_balance
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/mempolicy.c:mpol_rebind_nodemask
  - drivers/base/node.c:node_read_cpumap
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff8148df70-ffffffff8148dfdb: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814c2cd0)
Location: lib/bitmap.c:154
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/fair.c:load_balance
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - drivers/base/node.c:node_read_cpumap
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff814c2cd0-ffffffff814c2d33: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d7380)
Location: lib/bitmap.c:151
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/fair.c:load_balance
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - drivers/base/node.c:node_read_cpumap
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff814d7380-ffffffff814d73e3: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815031e0)
Location: lib/bitmap.c:151
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/fair.c:load_balance
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - drivers/base/node.c:node_read_cpumap
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_speed_up
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/net/phy/phy_device.c:genphy_config_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff815031e0-ffffffff81503241: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81521180)
Location: lib/bitmap.c:171
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/fair.c:load_balance
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - drivers/base/node.c:node_read_cpumap
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81521180-ffffffff815211e1: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81584370)
Location: lib/bitmap.c:238
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sd_init
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many_cond
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
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - drivers/base/node.c:node_read_cpumap
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81584370-ffffffff815843d1: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a1480)
Location: lib/bitmap.c:238
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sd_init
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many_cond
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
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - drivers/base/node.c:node_read_cpumap
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff815a1480-ffffffff815a14e1: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a8330)
Location: lib/bitmap.c:240
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sd_init
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many_cond
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
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - drivers/base/node.c:node_read_cpumap
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/powercap/dtpm_cpu.c:get_pd_power_uw
  - drivers/powercap/dtpm_cpu.c:set_pd_power_limit
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff815a8330-ffffffff815a8391: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816112f0)
Location: lib/bitmap.c:240
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sd_init
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many_cond
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
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/powercap/dtpm_cpu.c:get_pd_power_uw
  - drivers/powercap/dtpm_cpu.c:set_pd_power_limit
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff816112f0-ffffffff81611351: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816dd370)
Location: lib/bitmap.c:240
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many_cond
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
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff816dd370-ffffffff816dd3ed: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817cd210)
Location: lib/bitmap.c:240
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many_cond
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
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/memory-tiers.c:establish_demotion_targets
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff817cd210-ffffffff817cd28b: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180b620)
Location: lib/bitmap.c:240
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many_cond
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
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/trace/trace_osnoise.c:start_per_cpu_kthreads
  - kernel/bpf/cpumask.c:bpf_cpumask_and
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/memory-tiers.c:establish_demotion_targets
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:alloc_nodes_groups
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
```
**Symbols:**

```
ffffffff8180b620-ffffffff8180b69b: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81851e00)
Location: lib/bitmap.c:229
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/kernel/cpu/mce/core.c:mce_timed_out
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:activate_managed
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - arch/x86/kernel/apic/vector.c:assign_irq_vector_any_locked
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
  - kernel/workqueue.c:restrict_unbound_cpumask
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_pod_cpumask
  - kernel/workqueue.c:wq_calc_pod_cpumask
  - kernel/workqueue.c:wq_calc_pod_cpumask
  - kernel/workqueue.c:wqattrs_actualize_cpumask
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/rcu/tree.c:rcu_init_nohz
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many_cond
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
  - kernel/cgroup/cpuset.c:partition_xcpus_del
  - kernel/cgroup/cpuset.c:reset_partition_data
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/trace/trace_osnoise.c:start_per_cpu_kthreads
  - kernel/bpf/cpumask.c:bpf_cpumask_and
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/memory-tiers.c:establish_demotion_targets
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:alloc_nodes_groups
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/base/node.c:cpulist_read
  - drivers/base/node.c:cpumap_read
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
  - drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:genphy_config_advert
  - drivers/net/phy/linkmode.c:linkmode_resolve_pause
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
```
**Symbols:**

```
ffffffff81851e00-ffffffff81851e7b: __bitmap_and (STB_GLOBAL)
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
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062a828)
Location: lib/bitmap.c:171
Inline: False
Direct callers:
  - arch/arm64/kernel/fpsimd.c:sve_update_vq_map
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/fair.c:load_balance
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - mm/sparse.c:section_deactivate
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_offline_cpu
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu
```
**Symbols:**

```
ffff80001062a828-ffff80001062a8a0: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c07d19f8)
Location: lib/bitmap.c:171
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
**Symbols:**

```
c07d19f8-c07d1a7c: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007cc850)
Location: lib/bitmap.c:171
Inline: False
Direct callers:
  - arch/powerpc/mm/numa.c:mem_topology_setup
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_online
  - arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_online
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/fair.c:load_balance
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
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
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - drivers/base/node.c:node_read_cpumap
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_work_fn
```
**Symbols:**

```
c0000000007cc850-c0000000007cc8e8: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffe00045b15c)
Location: lib/bitmap.c:171
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
```
**Symbols:**

```
ffffffe00045b15c-ffffffe00045b1d8: __bitmap_and (STB_GLOBAL)
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
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81519760)
Location: lib/bitmap.c:171
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/fair.c:load_balance
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - drivers/base/node.c:node_read_cpumap
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81519760-ffffffff815197c1: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81509a50)
Location: lib/bitmap.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/fair.c:load_balance
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/rcu/tree.c:rcu_init_nohz
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - drivers/base/node.c:node_read_cpumap
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81509a50-ffffffff81509ab1: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815157f0)
Location: lib/bitmap.c:171
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/fair.c:load_balance
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - drivers/base/node.c:node_read_cpumap
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff815157f0-ffffffff81515851: __bitmap_and (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __bitmap_and(long unsigned int *dst, const long unsigned int *bitmap1, const long unsigned int *bitmap2, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152ef80)
Location: lib/bitmap.c:171
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/apic/vector.c:apic_set_affinity
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/sched/core.c:sched_getaffinity
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/fair.c:load_balance
  - kernel/sched/cpupri.c:cpupri_find
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/smp.c:smp_call_function_many
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:guarantee_online_mems
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - drivers/base/node.c:node_read_cpumap
  - drivers/net/phy/phy.c:phy_init_eee
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_ethtool_sset
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_resolve_aneg_linkmode
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff8152ef80-ffffffff8152efe1: __bitmap_and (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
