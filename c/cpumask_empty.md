# Function: <code>cpumask_empty</code>

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
In arch/x86/events/intel/cstate.c (ffffffff8100f2d4)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
```
```
In arch/x86/events/intel/rapl.c (ffffffff81014f87)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - arch/x86/events/intel/rapl.c:rapl_cpu_notifier
```
```
In arch/x86/events/intel/uncore.c (ffffffff81f60302)
Location: include/linux/cpumask.h:456
Inline: True
```
```
In arch/x86/xen/mmu.c (ffffffff810207e7)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff81030d80)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81054ec9)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
```
```
In kernel/cpu.c (ffffffff81081d57)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (ffffffff81097668)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
```
```
In kernel/sched/core.c (ffffffff81f7dfa1)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/sched/fair.c (ffffffff810bd947)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/irq/manage.c (ffffffff810db33c)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/migration.c (ffffffff810e25d8)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff810fce25)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/cpuset.c (ffffffff8111a793)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - kernel/cpuset.c:update_domain_attr_tree
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:cpuset_write_s64
  - kernel/cpuset.c:cpuset_can_attach
  - kernel/cpuset.c:update_flag
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
```
```
In mm/page_alloc.c (ffffffff8119204a)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/vmscan.c (ffffffff811a5816)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/slub.c (ffffffff811ecccc)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In lib/nmi_backtrace.c (ffffffff813edc77)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
```
```
In drivers/base/cacheinfo.c (ffffffff81552020)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:detect_cache_attributes
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816ae824)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_frequency_get_table
  - drivers/cpufreq/cpufreq.c:first_policy
  - drivers/cpufreq/cpufreq.c:first_policy
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_offline_finish
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_offline_prepare
  - drivers/cpufreq/cpufreq.c:cpufreq_offline_prepare
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff816b5eff)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
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
In arch/x86/xen/mmu.c (ffffffff81020ece)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_exit_mmap
```
```
In arch/x86/kernel/irq.c (ffffffff8102fe2f)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055e8f)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/cpu.c (ffffffff81084ea7)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (ffffffff810a080a)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/core.c (ffffffff81fa6e57)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/sched/fair.c (ffffffff810c11ad)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/irq/irqdesc.c (ffffffff81892b16)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/manage.c (ffffffff810e09d0)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/migration.c (ffffffff810e8068)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff81104bcf)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cpuset.c (ffffffff81125041)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_s64
  - kernel/cpuset.c:cpuset_can_attach
  - kernel/cpuset.c:update_flag
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:update_domain_attr_tree
```
```
In mm/page_alloc.c (ffffffff811a6b12)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/vmscan.c (ffffffff811bc2a6)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff811d1db6)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/slub.c (ffffffff8120c422)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In lib/nmi_backtrace.c (ffffffff81433ded)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
```
```
In drivers/base/cacheinfo.c (ffffffff815a3fc7)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:detect_cache_attributes
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817114ee)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81717a5f)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
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
In arch/x86/xen/mmu.c (ffffffff8102162e)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
  - arch/x86/xen/mmu.c:xen_exit_mmap
```
```
In arch/x86/kernel/irq.c (ffffffff8102fde4)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81043128)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058c3f)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/cpu.c (ffffffff81089e53)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (ffffffff810a58ec)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/core.c (ffffffff81fe29f5)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/sched/fair.c (ffffffff810c7123)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/irq/irqdesc.c (ffffffff818c7436)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/manage.c (ffffffff810e73ed)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/migration.c (ffffffff810eeaa8)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff8110c309)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cpuset.c (ffffffff8112e5bd)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_s64
  - kernel/cpuset.c:cpuset_can_attach
  - kernel/cpuset.c:update_flag
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:update_domain_attr_tree
```
```
In mm/page_alloc.c (ffffffff811b6e9c)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/vmscan.c (ffffffff811cc98c)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff811e1cf0)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/slub.c (ffffffff8121e442)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In lib/nmi_backtrace.c (ffffffff81450083)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/base/cacheinfo.c (ffffffff815d2c16)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817445de)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817496f8)
Location: include/linux/cpumask.h:460
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
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
In arch/x86/xen/mmu_pv.c (ffffffff81023bdc)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff8102e147)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff8104128d)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff81044df6)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058294)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:__send_cleanup_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In kernel/cpu.c (ffffffff81086d13)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (ffffffff810a296a)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/core.c (ffffffff820c32bf)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/sched/topology.c (ffffffff810ccc97)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/irqdesc.c (ffffffff818feb79)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/manage.c (ffffffff810e69b5)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/irq/migration.c (ffffffff810ee5ec)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff8110d838)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff8112fc5d)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
```
In mm/page_alloc.c (ffffffff811beda0)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/vmscan.c (ffffffff811d561c)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff811ebaf0)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/slub.c (ffffffff8122a0ab)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/cacheinfo.c (ffffffff815e779f)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81762d6e)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81767d78)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In lib/nmi_backtrace.c (ffffffff818efe2b)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/xen/mmu_pv.c (ffffffff81024758)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102a57d)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff8104467d)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff810486c9)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105c336)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/cpu.c (ffffffff8108dab3)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (ffffffff810a929a)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/topology.c (ffffffff810d3bf5)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/isolation.c (ffffffff826cbc56)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (ffffffff81988e02)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/manage.c (ffffffff810eebe1)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/migration.c (ffffffff810f701c)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff810f7237)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff81118ac8)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff8113cc78)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
```
In mm/page_alloc.c (ffffffff811d3a5a)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/vmscan.c (ffffffff811eab59)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff81201e70)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/slub.c (ffffffff81245261)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In block/blk-mq.c (ffffffff8145b142)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/cacheinfo.c (ffffffff8164eb4f)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/opp/cpu.c (ffffffff817d603b)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817d8c0e)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817ddc58)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In lib/nmi_backtrace.c (ffffffff8197626b)
Location: include/linux/cpumask.h:492
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/xen/mmu_pv.c (ffffffff81025675)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102b16b)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102bc35)
Location: include/linux/cpumask.h:494
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810468c2)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff8104af97)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105f302)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In kernel/cpu.c (ffffffff810914ef)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (ffffffff810af9ca)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/topology.c (ffffffff810db89e)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/isolation.c (ffffffff826f5dbf)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (ffffffff819e56f1)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/manage.c (ffffffff810f6fd1)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/migration.c (ffffffff810ff34c)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff810ff4fe)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff81125648)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff8114b41f)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
```
In mm/page_alloc.c (ffffffff811f4cd2)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/vmscan.c (ffffffff8120c6c5)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff81223267)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/slub.c (ffffffff81269378)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In block/blk-mq.c (ffffffff8148e0ec)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/cacheinfo.c (ffffffff8168a2ae)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/opp/cpu.c (ffffffff8181ed15)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8182186a)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81826a3d)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In lib/nmi_backtrace.c (ffffffff819d29dc)
Location: include/linux/cpumask.h:494
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/xen/mmu_pv.c (ffffffff81024d15)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102bcbf)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102cc30)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81055853)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105b3ad)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105d086)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81064f72)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/kernel/kvm.c (ffffffff81072968)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In kernel/cpu.c (ffffffff810997cf)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (ffffffff810b8b3a)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/topology.c (ffffffff810e5499)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/isolation.c (ffffffff828acc09)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (ffffffff81a208e1)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/manage.c (ffffffff81102741)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/migration.c (ffffffff8110ab2c)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff8110acd7)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In kernel/irq/matrix.c (ffffffff8110d425)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
```
```
In kernel/time/tick-broadcast.c (ffffffff81130d38)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff81157d3a)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
```
```
In mm/page_alloc.c (ffffffff812070b2)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/vmscan.c (ffffffff8121f555)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff812362b7)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/slub.c (ffffffff81278d90)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In block/blk-mq.c (ffffffff814a798c)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/cacheinfo.c (ffffffff816a97ae)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/opp/cpu.c (ffffffff8184abb5)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8184d71a)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8185292d)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In lib/nmi_backtrace.c (ffffffff81a0c05c)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/xen/mmu_pv.c (ffffffff81026f3a)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102dd9f)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102eb7c)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058aa5)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105e71d)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060408)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106868e)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/kernel/kvm.c (ffffffff810767d8)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In kernel/cpu.c (ffffffff8109db4f)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (ffffffff810be63a)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/topology.c (ffffffff810eb464)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/isolation.c (ffffffff828c556e)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (ffffffff81a90e11)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/manage.c (ffffffff8110af42)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/migration.c (ffffffff811141dc)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff811143a1)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In kernel/irq/matrix.c (ffffffff81116b25)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
```
```
In kernel/time/tick-broadcast.c (ffffffff8113b897)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff811622ac)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/vmscan.c (ffffffff8122ed3e)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff81247799)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff8126d10c)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/slub.c (ffffffff81294e86)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In block/blk-mq.c (ffffffff814d59f8)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/cacheinfo.c (ffffffff816e2dbb)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/opp/cpu.c (ffffffff8188dd25)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8189080a)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81895ebe)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In lib/nmi_backtrace.c (ffffffff81a7b9bc)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/xen/mmu_pv.c (ffffffff8102751a)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e6af)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f48c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059375)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105ef9d)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060cb8)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810690b3)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/kernel/kvm.c (ffffffff81077868)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In kernel/cpu.c (ffffffff810a409f)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (ffffffff810c4bea)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/topology.c (ffffffff810f7465)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/isolation.c (ffffffff828cdbd7)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (ffffffff81ac8151)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/manage.c (ffffffff811174a2)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/migration.c (ffffffff8112034c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff81120501)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In kernel/irq/matrix.c (ffffffff81122ef5)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
```
```
In kernel/time/tick-broadcast.c (ffffffff811474a7)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff8116df8c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/vmscan.c (ffffffff8123cece)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff81255bf9)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff8127c18c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/slub.c (ffffffff812a4c6a)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In block/blk-mq.c (ffffffff814eed28)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/cacheinfo.c (ffffffff81706f6b)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/opp/cpu.c (ffffffff818bfeb5)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c2a0a)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818c7ece)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In lib/nmi_backtrace.c (ffffffff81ab2d1c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/xen/mmu_pv.c (ffffffff8102896a)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/hyperv/mmu.c (ffffffff81031035)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810319cc)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105e58e)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81064afd)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81066958)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106f4f0)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:activate_managed
```
```
In arch/x86/kernel/kvm.c (ffffffff8107eb58)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In kernel/cpu.c (ffffffff810ab30f)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
```
```
In kernel/workqueue.c (ffffffff810cc6f8)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_select_unbound_cpu
```
```
In kernel/sched/cpupri.c (ffffffff810ffa1f)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
```
In kernel/sched/topology.c (ffffffff81101d25)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_balance_mask
```
```
In kernel/sched/isolation.c (ffffffff82ceef9b)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (ffffffff81121a01)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/irq/manage.c (ffffffff81122a42)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/migration.c (ffffffff8112c88c)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112ca1b)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In kernel/irq/matrix.c (ffffffff8112f835)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
```
```
In kernel/time/tick-broadcast.c (ffffffff81157627)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff81182172)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_root_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/vmscan.c (ffffffff81269cec)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff812842e9)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff812ae4b6)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/slub.c (ffffffff812d943e)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In block/blk-mq.c (ffffffff8154ffcc)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In lib/nmi_backtrace.c (ffffffff815ed5bc)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/base/cacheinfo.c (ffffffff817c1d05)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
```
```
In drivers/opp/cpu.c (ffffffff81991c15)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81995d6b)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81999fce)
Location: include/linux/cpumask.h:543
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
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
In arch/x86/xen/mmu_pv.c (ffffffff810294d4)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/hyperv/mmu.c (ffffffff81031da1)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810326cc)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105cabb)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81062ceb)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064ba8)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81070a10)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:activate_managed
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e788)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In kernel/cpu.c (ffffffff810a6b8f)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
```
```
In kernel/workqueue.c (ffffffff810c7878)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_select_unbound_cpu
```
```
In kernel/sched/cpupri.c (ffffffff810fe519)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
```
In kernel/sched/cpudeadline.c (ffffffff810fea8b)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff81100915)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_balance_mask
```
```
In kernel/sched/isolation.c (ffffffff82fdb6b2)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (ffffffff8111da61)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/irq/manage.c (ffffffff8111e872)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/migration.c (ffffffff811282bc)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112844b)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In kernel/irq/matrix.c (ffffffff8112b6eb)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
```
```
In kernel/time/tick-broadcast.c (ffffffff811536f7)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff8117f092)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_root_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/vmscan.c (ffffffff8127481b)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff8128e459)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff812ba0d6)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/slub.c (ffffffff812e49cb)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In lib/nmi_backtrace.c (ffffffff81611d7c)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/base/cacheinfo.c (ffffffff817d6f25)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
```
```
In drivers/opp/cpu.c (ffffffff81994f16)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81998c04)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:handle_update
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199d03e)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In net/core/net-sysfs.c (ffffffff81a3a5f3)
Location: include/linux/cpumask.h:549
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:store_rps_map
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
In arch/x86/events/core.c (ffffffff810064db)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
```
```
In arch/x86/events/intel/core.c (ffffffff8100dff8)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81029542)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/hyperv/mmu.c (ffffffff810328b0)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81033b1c)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d41a)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff810633bb)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065149)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81071230)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:activate_managed
```
```
In arch/x86/kernel/kvm.c (ffffffff8107fc48)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In kernel/cpu.c (ffffffff810a7c4f)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
```
```
In kernel/workqueue.c (ffffffff810c923a)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/cpupri.c (ffffffff811008fb)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
```
In kernel/sched/cpudeadline.c (ffffffff81100e65)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff81102a55)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/isolation.c (ffffffff831e640c)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (ffffffff831e77f4)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/manage.c (ffffffff8111ed02)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/migration.c (ffffffff8112857c)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112870b)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In kernel/irq/matrix.c (ffffffff8112b9b8)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
```
```
In kernel/time/clocksource.c (ffffffff8114984d)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_percpu
  - kernel/time/clocksource.c:clocksource_verify_percpu
  - kernel/time/clocksource.c:clocksource_verify_percpu
  - kernel/time/clocksource.c:clocksource_verify_percpu
```
```
In kernel/time/tick-broadcast.c (ffffffff81154882)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff8117f054)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/vmscan.c (ffffffff81279b2b)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/percpu.c (ffffffff831f035f)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/compaction.c (ffffffff81293ae9)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff812bf080)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/slub.c (ffffffff812ec22f)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In lib/nmi_backtrace.c (ffffffff815f545c)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/base/cacheinfo.c (ffffffff817ba945)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
```
```
In drivers/opp/cpu.c (ffffffff81979e56)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197d15e)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81981c6e)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In net/core/net-sysfs.c (ffffffff81a21766)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:store_rps_map
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
In arch/x86/events/core.c (ffffffff81006858)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
```
```
In arch/x86/events/intel/core.c (ffffffff8100e785)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102dce2)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81066b1a)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8106d2d4)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106f201)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107cfc0)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:activate_managed
```
```
In arch/x86/kernel/kvm.c (ffffffff8108ea28)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In kernel/cpu.c (ffffffff810b96af)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
```
```
In kernel/workqueue.c (ffffffff810dbefb)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/cpupri.c (ffffffff8111c963)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_find_fitness
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
```
In kernel/sched/cpudeadline.c (ffffffff8111cfe3)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff8111f645)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:asym_cpu_capacity_scan
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/isolation.c (ffffffff832ca508)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (ffffffff832cb8e6)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/manage.c (ffffffff8113f2d2)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/migration.c (ffffffff81148b4c)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff81148cdb)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
```
In kernel/irq/matrix.c (ffffffff8114c488)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
```
```
In kernel/time/clocksource.c (ffffffff81cb19b3)
Location: include/linux/cpumask.h:520
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff811792d2)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff811a7214)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/vmscan.c (ffffffff812b7ad2)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/percpu.c (ffffffff832d5b65)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/compaction.c (ffffffff812d3f2d)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff81308da8)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/slub.c (ffffffff813334d3)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In lib/nmi_backtrace.c (ffffffff816628cc)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/base/cacheinfo.c (ffffffff818447f5)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
```
```
In drivers/opp/cpu.c (ffffffff81a22e66)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a261cd)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81a2af0f)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In net/core/net-sysfs.c (ffffffff81ad5ce6)
Location: include/linux/cpumask.h:520
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:store_rps_map
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
In arch/x86/events/core.c (ffffffff81005cba)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
```
```
In arch/x86/events/intel/core.c (ffffffff8100ea8f)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81032c7f)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8107384a)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810785f0)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8107a7c4)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107ca5f)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8108c650)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:activate_managed
```
```
In arch/x86/kernel/kvm.c (ffffffff8109f4dd)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810b8642)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c11f3)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/cpu.c (ffffffff810d00cd)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
```
```
In kernel/workqueue.c (ffffffff810f5623)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_select_unbound_cpu
```
```
In kernel/sched/core.c (ffffffff8111953e)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
```
```
In kernel/sched/build_policy.c (ffffffff81133d8f)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_find
```
```
In kernel/sched/build_utility.c (ffffffff81149696)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (ffffffff8347f090)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
```
```
In kernel/irq/manage.c (ffffffff81162d61)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/migration.c (ffffffff8116d688)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff8116d7d7)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In kernel/irq/affinity.c (ffffffff8116fe5b)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff81171ef8)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
```
```
In kernel/time/clocksource.c (ffffffff811a1a3f)
Location: include/linux/cpumask.h:555
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff811aec39)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff811d82f0)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/padata.c (ffffffff812ea4ef)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmscan.c (ffffffff813128ae)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff83489f5a)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/percpu.c (ffffffff8348a3fe)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/compaction.c (ffffffff81332e2d)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff8137129c)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/slub.c (ffffffff813a4cbb)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In lib/nmi_backtrace.c (ffffffff8177c737)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/base/cacheinfo.c (ffffffff81988a3d)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
```
```
In drivers/nvdimm/nd_perf.c (ffffffff819d926e)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
```
```
In drivers/opp/cpu.c (ffffffff81b8bf7f)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b914eb)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/cpufreq.c:store
  - drivers/cpufreq/cpufreq.c:show
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81b9531f)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In net/core/net-sysfs.c (ffffffff81c5650f)
Location: include/linux/cpumask.h:555
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:store_rps_map
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
In arch/x86/events/core.c (ffffffff8100761a)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
```
```
In arch/x86/events/intel/core.c (ffffffff8101212b)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103a5fb)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81083c5a)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108928f)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108ba27)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108ddaf)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a0bd0)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:activate_managed
```
```
In arch/x86/kernel/kvm.c (ffffffff810b6d4d)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d38f5)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:leave_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dd9cd)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/cpu.c (ffffffff810ee75f)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
```
```
In kernel/workqueue.c (ffffffff81117b7d)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_select_unbound_cpu
```
```
In kernel/sched/core.c (ffffffff81140e0e)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
```
```
In kernel/sched/fair.c (ffffffff81145fb1)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_energy_efficient_cpu
```
```
In kernel/sched/build_policy.c (ffffffff8115e273)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_find
```
```
In kernel/sched/build_utility.c (ffffffff81178005)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (ffffffff81194e01)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/irq/manage.c (ffffffff81196941)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/migration.c (ffffffff811a2828)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff811a2993)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In kernel/irq/affinity.c (ffffffff811a62bb)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/irq/matrix.c (ffffffff811a85e8)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
```
```
In kernel/time/clocksource.c (ffffffff811e0c1f)
Location: include/linux/cpumask.h:620
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff811eedec)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff8121e7d4)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/padata.c (ffffffff813543c1)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmscan.c (ffffffff81385cf2)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff83eba8af)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/percpu.c (ffffffff83ebae8d)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/compaction.c (ffffffff813a9b5d)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff813ee904)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/slub.c (ffffffff81424f78)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In drivers/base/cacheinfo.c (ffffffff81af761d)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81b542de)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
```
```
In drivers/opp/cpu.c (ffffffff81d2b805)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d317eb)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/cpufreq.c:store
  - drivers/cpufreq/cpufreq.c:show
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d35baf)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In net/core/net-sysfs.c (ffffffff81e0bfc2)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:store_rps_map
```
```
In lib/nmi_backtrace.c (ffffffff82039207)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/events/core.c (ffffffff81006e24)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
```
```
In arch/x86/events/intel/core.c (ffffffff810131c2)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103a6cb)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810861fa)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089b1c)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108e977)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81090c36)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
```
In arch/x86/kernel/smp.c (ffffffff8109b8e7)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a3bc0)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:activate_managed
```
```
In arch/x86/kernel/kvm.c (ffffffff810b9eed)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d6cd5)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:leave_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e9043)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/cpu.c (ffffffff810fa73f)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
```
```
In kernel/workqueue.c (ffffffff81124d4d)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_select_unbound_cpu
```
```
In kernel/sched/core.c (ffffffff8114cb2e)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
```
```
In kernel/sched/fair.c (ffffffff81155c8a)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_energy_efficient_cpu
```
```
In kernel/sched/build_policy.c (ffffffff8116e956)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_find
```
```
In kernel/sched/build_utility.c (ffffffff81188ca8)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (ffffffff811a65f8)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/irq/manage.c (ffffffff811a8301)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/migration.c (ffffffff811b4728)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff811b4897)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In kernel/irq/matrix.c (ffffffff811ba2b8)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
```
```
In kernel/time/clocksource.c (ffffffff811f517f)
Location: include/linux/cpumask.h:672
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff81203b8d)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff812348c4)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach_check
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/trace/trace.c (ffffffff8127eac6)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In kernel/bpf/cpumask.c (ffffffff8135da85)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_empty
```
```
In kernel/padata.c (ffffffff813855c1)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmscan.c (ffffffff813b8fb2)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff836dfebf)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/percpu.c (ffffffff836e34b2)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/compaction.c (ffffffff813dce0d)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff814226d4)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/slub.c (ffffffff8145a328)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In lib/group_cpus.c (ffffffff818e6cee)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1b613)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_online
```
```
In drivers/base/cacheinfo.c (ffffffff81b4585d)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81ba782e)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
```
```
In drivers/opp/cpu.c (ffffffff81d94ab5)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d9abab)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:store
  - drivers/cpufreq/cpufreq.c:show
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d9ef1f)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In net/core/net-sysfs.c (ffffffff81e81837)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
```
```
In lib/nmi_backtrace.c (ffffffff820b7518)
Location: include/linux/cpumask.h:672
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/events/core.c (ffffffff8100c553)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
```
```
In arch/x86/events/intel/core.c (ffffffff8101a44c)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81040b8b)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d0da)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81090c35)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81095d07)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81097fc6)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
```
In arch/x86/kernel/smp.c (ffffffff810a2e87)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810aabf0)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:activate_managed
```
```
In arch/x86/kernel/kvm.c (ffffffff810c12ad)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810df505)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:leave_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f13f7)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In kernel/cpu.c (ffffffff81103b5f)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
```
```
In kernel/workqueue.c (ffffffff8112dc01)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_calc_pod_cpumask
  - kernel/workqueue.c:wq_calc_pod_cpumask
  - kernel/workqueue.c:wqattrs_actualize_cpumask
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff811587ee)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
```
```
In kernel/sched/fair.c (ffffffff81161149)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_energy_efficient_cpu
```
```
In kernel/sched/build_policy.c (ffffffff8117bef9)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_find
```
```
In kernel/sched/build_utility.c (ffffffff81197579)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (ffffffff811b6118)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/irq/manage.c (ffffffff811b7d81)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/migration.c (ffffffff811c45a8)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff811c4717)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
```
```
In kernel/irq/matrix.c (ffffffff811ca178)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
```
```
In kernel/rcu/tree.c (ffffffff839039ca)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_nohz
  - kernel/rcu/tree.c:rcu_init_nohz
```
```
In kernel/time/clocksource.c (ffffffff8120b31f)
Location: include/linux/cpumask.h:682
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff8121a14d)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff8124e4e4)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach_check
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_exclusive_cpumask
  - kernel/cgroup/cpuset.c:update_exclusive_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:remote_cpus_update
  - kernel/cgroup/cpuset.c:reset_partition_data
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In kernel/trace/trace.c (ffffffff8129958d)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In kernel/bpf/cpumask.c (ffffffff81386825)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_empty
```
```
In kernel/padata.c (ffffffff813ae961)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmscan.c (ffffffff813e1fb2)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/vmstat.c (ffffffff8391276f)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/percpu.c (ffffffff83915d42)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/compaction.c (ffffffff81406d6d)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff8144f4c4)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/slub.c (ffffffff814553f8)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In lib/group_cpus.c (ffffffff8192dd0e)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b71143)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_online
```
```
In drivers/base/cacheinfo.c (ffffffff81b9d8dd)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81bfbb0d)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
```
```
In drivers/opp/cpu.c (ffffffff81e4c5c5)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e52921)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_trigger_state
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_unregister_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:store
  - drivers/cpufreq/cpufreq.c:show
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e56d2f)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In net/core/net-sysfs.c (ffffffff81f42817)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
```
```
In lib/nmi_backtrace.c (ffffffff821916c8)
Location: include/linux/cpumask.h:682
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In virt/kvm/kvm_main.c (ffff8000100bc7d4)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_make_vcpus_request_mask
```
```
In kernel/cpu.c (ffff8000100f9de4)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (ffff800010123110)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/topology.c (ffff80001015b7c4)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/isolation.c (ffff8000114454a8)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (ffff800010d9bfd4)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/manage.c (ffff80001017a29c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/cpuhotplug.c (ffff8000101862bc)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In kernel/time/tick-broadcast.c (ffff8000101b2620)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffff8000101e279c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/vmscan.c (ffff8000102ce1cc)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffff8000102ed160)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffff80001031376c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/slub.c (ffff800010345588)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In block/blk-mq.c (ffff8000105ee41c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/cacheinfo.c (ffff8000108f3ca4)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/arch_topology.c (ffff8000109203d8)
Location: include/linux/cpumask.h:536
Inline: True
```
```
In drivers/opp/cpu.c (ffff800010b1af94)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/opp/of.c (ffff800010b1c67c)
Location: include/linux/cpumask.h:536
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b1d8e8)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a9c8)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_online_cpu
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c6dc)
Location: include/linux/cpumask.h:536
Inline: True
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
In arch/arm/kernel/smp.c (c03138f0)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:smp_send_stop
```
```
In arch/arm/kernel/hw_breakpoint.c (c150676c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/arm/kernel/hw_breakpoint.c:arch_hw_breakpoint_init
```
```
In kernel/cpu.c (c0358044)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (c037213c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/topology.c (c03a8210)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/isolation.c (c151f8cc)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (c0e98660)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/manage.c (c03cad10)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/cpuhotplug.c (c03d50fc)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In kernel/time/tick-broadcast.c (c03fcda0)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (c0424b0c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/vmscan.c (c04f7ff8)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (c0511060)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/slub.c (c054a494)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In block/blk-mq.c (c079a1e8)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/cacheinfo.c (c09e0308)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/base/arch_topology.c (c0a0537c)
Location: include/linux/cpumask.h:536
Inline: True
```
```
In drivers/opp/cpu.c (c0bf59c4)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/opp/of.c (c0bf6ea0)
Location: include/linux/cpumask.h:536
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (c0bf8744)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_update_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:handle_update
  - drivers/cpufreq/cpufreq.c:show_cpuinfo_cur_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
```
In drivers/cpuidle/coupled.c (c0c057ac)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:cpuidle_coupled_unregister_device
  - drivers/cpuidle/coupled.c:cpuidle_coupled_register_device
```
```
In drivers/firmware/qcom_scm-32.c (c0c365b8)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_set_cold_boot_addr
```
```
In lib/nmi_backtrace.c (c0e8750c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/powerpc/kernel/cacheinfo.c (c00000000002b288)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_offline
```
```
In arch/powerpc/kernel/watchdog.c (c0000000000371dc)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
```
```
In arch/powerpc/kernel/rtas.c (c00000000003cce0)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas.c:rtas_cpu_state_change_mask
```
```
In arch/powerpc/kernel/smp.c (c000000000054a94)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi
  - arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi
  - arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000be4f0)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_pick_irq_target
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000fa018)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
```
```
In arch/powerpc/xmon/xmon.c (c00000000010c424)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:cpus_are_in_xmon
```
```
In kernel/cpu.c (c000000000140e94)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (c00000000016cf6c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/topology.c (c0000000001afe4c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/isolation.c (c000000001369f30)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (c0000000001d1ff4)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/manage.c (c0000000001d38bc)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
```
```
In kernel/time/tick-broadcast.c (c000000000217df0)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (c000000000250f0c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/vmscan.c (c00000000038beb8)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (c0000000003b0d54)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (c0000000003e4bb0)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/slub.c (c00000000042345c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In block/blk-mq.c (c000000000783b98)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/cacheinfo.c (c00000000098db5c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/opp/cpu.c (c000000000c0d074)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/opp/of.c (c000000000c0eeb4)
Location: include/linux/cpumask.h:536
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (c000000000c10970)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
```
In lib/nmi_backtrace.c (c000000000ecf18c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/riscv/mm/cacheflush.c (ffffffe0000ba0b2)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/riscv/mm/cacheflush.c:flush_icache_mm
```
```
In arch/riscv/mm/tlbflush.c (ffffffe0000ba5a2)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/riscv/mm/tlbflush.c:flush_tlb_range
  - arch/riscv/mm/tlbflush.c:flush_tlb_page
  - arch/riscv/mm/tlbflush.c:flush_tlb_mm
```
```
In kernel/workqueue.c (ffffffe0000d84de)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/topology.c (ffffffe000100a5c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/isolation.c (ffffffe0000074a6)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (ffffffe0008c432a)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/manage.c (ffffffe000113c8e)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
```
```
In kernel/cgroup/cpuset.c (ffffffe00015930a)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/vmscan.c (ffffffe0001ec440)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffe0002017f6)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/slub.c (ffffffe000238e64)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In block/blk-mq.c (ffffffe00042d31a)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/cacheinfo.c (ffffffe0005851ac)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/opp/cpu.c (ffffffe000703384)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/opp/of.c (ffffffe000704706)
Location: include/linux/cpumask.h:536
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
In arch/x86/xen/mmu_pv.c (ffffffff8102767a)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e80f)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f5ec)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058ef5)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105eb1d)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060838)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81068ba3)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/kernel/kvm.c (ffffffff81076868)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In kernel/cpu.c (ffffffff8109d9bf)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (ffffffff810bef5a)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/topology.c (ffffffff810f0865)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/isolation.c (ffffffff828b6967)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (ffffffff81a66fc1)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/manage.c (ffffffff8110fa82)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/migration.c (ffffffff8111892c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff81118ae1)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In kernel/irq/matrix.c (ffffffff8111b4d5)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
```
```
In kernel/time/tick-broadcast.c (ffffffff8113fac7)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff811665ac)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/vmscan.c (ffffffff8123551e)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff8124e249)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff812747dc)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/slub.c (ffffffff8129d24a)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In block/blk-mq.c (ffffffff814e7308)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/cacheinfo.c (ffffffff816cc6bb)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/opp/cpu.c (ffffffff818645d5)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8186712a)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8186c5ee)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In lib/nmi_backtrace.c (ffffffff81a51b6c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/hyperv/mmu.c (ffffffff8101e1cf)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101ec70)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810490f5)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8104ee4d)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81050c98)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058f13)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/kernel/kvm.c (ffffffff81066868)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In kernel/cpu.c (ffffffff8108c3df)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (ffffffff810ad77a)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/topology.c (ffffffff810e08d5)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/isolation.c (ffffffff828aeb5d)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (ffffffff81a23a81)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/manage.c (ffffffff811007c2)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/migration.c (ffffffff8110999c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff81109b51)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In kernel/irq/matrix.c (ffffffff8110c545)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
```
```
In kernel/rcu/tree.c (ffffffff828b0ef9)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_nohz
```
```
In kernel/time/tick-broadcast.c (ffffffff81132847)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff811597ec)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/vmscan.c (ffffffff8122858e)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff812411e9)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff8126674c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/slub.c (ffffffff8128edda)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In block/blk-mq.c (ffffffff814d7878)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/cacheinfo.c (ffffffff816a79eb)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/opp/cpu.c (ffffffff8182d285)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8182fdda)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8183510e)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In drivers/hv/channel_mgmt.c (ffffffff81852b35)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:init_vp_index
```
```
In lib/nmi_backtrace.c (ffffffff81a0ec6c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/xen/mmu_pv.c (ffffffff810274da)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e66f)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f44c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059325)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105ef4d)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060c68)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81069053)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/kernel/kvm.c (ffffffff81076818)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In kernel/cpu.c (ffffffff8109d96f)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (ffffffff810be4ba)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/topology.c (ffffffff810ed995)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/isolation.c (ffffffff828c980b)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (ffffffff81ad33d1)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/manage.c (ffffffff8110d972)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/migration.c (ffffffff8111681c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff811169d1)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In kernel/irq/matrix.c (ffffffff811193c5)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
```
```
In kernel/time/tick-broadcast.c (ffffffff8113d977)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff8116437c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/vmscan.c (ffffffff812332be)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff8124bfe9)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff8127257c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/slub.c (ffffffff8129b05a)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In block/blk-mq.c (ffffffff814e3398)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/cacheinfo.c (ffffffff816fac2b)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/opp/cpu.c (ffffffff818b5365)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b7eba)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818bd37e)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In lib/nmi_backtrace.c (ffffffff81abdf5c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
In arch/x86/xen/mmu_pv.c (ffffffff8102803a)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102f45f)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103028c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105a7c5)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8106048d)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81062228)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106a757)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
```
In arch/x86/kernel/kvm.c (ffffffff81078978)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In kernel/cpu.c (ffffffff810a57ff)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (ffffffff810c682a)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:__queue_work
```
```
In kernel/sched/topology.c (ffffffff810f89d5)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/isolation.c (ffffffff828cebbd)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_setup
  - kernel/sched/isolation.c:housekeeping_init
```
```
In kernel/irq/irqdesc.c (ffffffff81adf8d1)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/manage.c (ffffffff81119132)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/migration.c (ffffffff81121e5c)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/irq/cpuhotplug.c (ffffffff8112200f)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
```
In kernel/irq/matrix.c (ffffffff81124ac5)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
```
```
In kernel/time/tick-broadcast.c (ffffffff8114a487)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
```
In kernel/cgroup/cpuset.c (ffffffff81171827)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_s64
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:update_domain_attr_tree
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/vmscan.c (ffffffff812427ce)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff8125b939)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/page_alloc.c (ffffffff81281eac)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/slub.c (ffffffff812aaf3a)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In block/blk-mq.c (ffffffff814fc281)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_run_hw_queue
```
```
In drivers/base/cacheinfo.c (ffffffff817154cb)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
  - drivers/base/cacheinfo.c:cache_default_attrs_is_visible
```
```
In drivers/opp/cpu.c (ffffffff818d1615)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d417a)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
  - drivers/cpufreq/cpufreq.c:cpufreq_suspend
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_cpu_acquire
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818d966e)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:get_cur_val
```
```
In lib/nmi_backtrace.c (ffffffff81aca3f0)
Location: include/linux/cpumask.h:536
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
</details>
</li>
</ul>

## Differences
