# Function: <code>cpumask_copy</code>

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
In arch/x86/xen/mmu.c (ffffffff8102073f)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
```
```
In arch/x86/xen/suspend.c (ffffffff8102423d)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
```
In arch/x86/xen/smp.c (ffffffff81f65002)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In arch/x86/kernel/irq.c (ffffffff81030c86)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/smp.c (ffffffff81050833)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff81f6f763)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81054a06)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:noop_vector_allocation_domain
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810553e3)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81059252)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:default_vector_allocation_domain
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810596d2)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:default_vector_allocation_domain
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059c6a)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a4c2)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:default_vector_allocation_domain
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810747ae)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff81081fd5)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_present
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_online
```
```
In kernel/workqueue.c (ffffffff8109760b)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
```
```
In kernel/smpboot.c (ffffffff810a3a24)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
```
```
In kernel/sched/core.c (ffffffff810aafea)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/sched/core.c:set_cpus_allowed_common
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:build_sched_domains
```
```
In kernel/sched/fair.c (ffffffff810bd294)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/irq/irqdesc.c (ffffffff810da243)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff810db5c5)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/proc.c (ffffffff810e1b1d)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
  - kernel/irq/proc.c:default_affinity_write
```
```
In kernel/profile.c (ffffffff810ea0b8)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/tick-broadcast.c (ffffffff810fd7dc)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cpuset.c (ffffffff8111aec1)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/cpuset.c:alloc_trial_cpuset
  - kernel/cpuset.c:alloc_trial_cpuset
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:cpuset_bind
  - kernel/cpuset.c:cpuset_bind
  - kernel/cpuset.c:cpuset_css_online
  - kernel/cpuset.c:cpuset_css_online
  - kernel/cpuset.c:cpuset_css_online
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_init_smp
  - kernel/cpuset.c:cpuset_init_smp
```
```
In kernel/watchdog.c (ffffffff81f8311e)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
```
```
In kernel/trace/ring_buffer.c (ffffffff8114a157)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff8114bc4c)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:trace_init
```
```
In kernel/padata.c (ffffffff8118a4d8)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/padata.c:__padata_set_cpumasks
  - kernel/padata.c:__padata_set_cpumasks
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
```
```
In mm/vmstat.c (ffffffff81f88524)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - mm/vmstat.c:setup_vmstat
```
```
In block/blk-mq.c (ffffffff813c5890)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In lib/nmi_backtrace.c (ffffffff813edb97)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
```
```
In drivers/acpi/processor_throttling.c (ffffffff814ad997)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff814af709)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/xen/events/events_base.c (ffffffff814c7dd1)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816b1ad1)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff816b6777)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff816b8676)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
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
In arch/x86/xen/mmu.c (ffffffff8102072d)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
```
```
In arch/x86/xen/suspend.c (ffffffff8102350d)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
```
In arch/x86/xen/smp.c (ffffffff81f8cbc0)
Location: include/linux/cpumask.h:514
Inline: True
```
```
In arch/x86/kernel/irq.c (ffffffff8102fd32)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/smp.c (ffffffff81050a40)
Location: include/linux/cpumask.h:514
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff81f97e5b)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81054b9b)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:noop_vector_allocation_domain
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055656)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810596cb)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:default_vector_allocation_domain
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105993b)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:default_vector_allocation_domain
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059f3a)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a86b)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:default_vector_allocation_domain
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81075d84)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff810850b5)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff81fa5277)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_workqueue_attrs
```
```
In kernel/smpboot.c (ffffffff810a7147)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
```
```
In kernel/sched/core.c (ffffffff810b1f21)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/fair.c (ffffffff810c0a24)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/irq/irqdesc.c (ffffffff810df9f4)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff810e0c55)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff810e76a2)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff810e8f02)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_mask
```
```
In kernel/profile.c (ffffffff810f0e08)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/tick-broadcast.c (ffffffff81104b4c)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cpuset.c (ffffffff81fab5dc)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_init_smp
  - kernel/cpuset.c:cpuset_init_smp
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_bind
  - kernel/cpuset.c:cpuset_bind
  - kernel/cpuset.c:cpuset_css_online
  - kernel/cpuset.c:cpuset_css_online
  - kernel/cpuset.c:cpuset_css_online
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:alloc_trial_cpuset
  - kernel/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (ffffffff81fac6be)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
```
```
In kernel/trace/ring_buffer.c (ffffffff81152ba8)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff81fad3ff)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:tracing_cpumask_write
```
```
In kernel/padata.c (ffffffff8119d150)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In block/blk-mq.c (ffffffff81408509)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/nmi_backtrace.c (ffffffff81433da6)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
```
```
In drivers/acpi/processor_throttling.c (ffffffff814fd394)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff814ff047)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/xen/events/events_base.c (ffffffff81518841)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81713ae0)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8171823c)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8171a389)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cpumask_copy(struct cpumask *dstp, const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81020f20)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
```
```
In arch/x86/xen/suspend.c (ffffffff81023c5f)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
```
In arch/x86/xen/smp.c (ffffffff81fc800f)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
```
```
In arch/x86/kernel/irq.c (ffffffff8102fce6)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff8104459e)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smp.c (ffffffff81053306)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff81fd32b1)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81057965)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:noop_vector_allocation_domain
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810583ae)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105c460)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:default_vector_allocation_domain
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c6d0)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:default_vector_allocation_domain
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cce1)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d570)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:default_vector_allocation_domain
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107993c)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff8108a035)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff810a4599)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/smpboot.c (ffffffff810ad0cd)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
```
```
In kernel/sched/core.c (ffffffff810b82e2)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/fair.c (ffffffff810c6a1a)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/irq/irqdesc.c (ffffffff810e62d4)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff810e7274)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff810ee413)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff810ef974)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff810f86c2)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/tick-broadcast.c (ffffffff8110c296)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cpuset.c (ffffffff81fe789c)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_init_smp
  - kernel/cpuset.c:cpuset_init_smp
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_bind
  - kernel/cpuset.c:cpuset_bind
  - kernel/cpuset.c:cpuset_css_online
  - kernel/cpuset.c:cpuset_css_online
  - kernel/cpuset.c:cpuset_css_online
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:alloc_trial_cpuset
  - kernel/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (ffffffff81fe89a2)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
```
```
In kernel/trace/trace.c (ffffffff81fe9757)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:tracing_cpumask_write
```
```
In kernel/padata.c (ffffffff811acaf2)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In block/blk-mq.c (ffffffff81424285)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_queue_reinit_prepare
  - block/blk-mq.c:blk_mq_queue_reinit_dead
```
```
In lib/nmi_backtrace.c (ffffffff81450046)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/acpi/processor_throttling.c (ffffffff8151fd35)
Location: include/linux/cpumask.h:514
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff81521c30)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815256fd)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/xen/events/events_base.c (ffffffff81544d51)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8174580e)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81749fd7)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8174c134)
Location: include/linux/cpumask.h:514
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
**Symbols:**

```
ffffffff8151fd35-ffffffff8151fd4f: cpumask_copy (STB_LOCAL)
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
In arch/x86/xen/suspend_pv.c (ffffffff8101d09e)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81022015)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/xen/smp_pv.c (ffffffff820a86aa)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/kernel/irq.c (ffffffff8102e0e0)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810435b5)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smp.c (ffffffff81052eb1)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff820b3f39)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056e71)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:default_cpu_mask_to_apicid
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810570e5)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:noop_vector_allocation_domain
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81057a8b)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105bb60)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:default_vector_allocation_domain
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105be00)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:default_vector_allocation_domain
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c651)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105cc70)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:default_vector_allocation_domain
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810781dc)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff81087125)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff810a16b9)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/smpboot.c (ffffffff810a9b9f)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
```
```
In kernel/sched/core.c (ffffffff810b2d46)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/topology.c (ffffffff810ccbcc)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/irq/irqdesc.c (ffffffff810e5924)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff810e7134)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff810edc5c)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff810ef8d6)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff810fa6e6)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/tick-broadcast.c (ffffffff8110d7b2)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cgroup/cpuset.c (ffffffff820c7edf)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (ffffffff820c9114)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
```
```
In kernel/trace/trace.c (ffffffff820ca14d)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:tracing_cpumask_write
```
```
In kernel/padata.c (ffffffff811b35c8)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In drivers/acpi/processor_throttling.c (ffffffff81531d2b)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff815336fe)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8153817d)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/xen/events/events_base.c (ffffffff81559111)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81763f2f)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81768604)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8176a4c7)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In lib/nmi_backtrace.c (ffffffff818efde3)
Location: include/linux/cpumask.h:542
Inline: True
Inline callers:
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
In arch/x86/xen/suspend_pv.c (ffffffff8101dd6e)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/smp_pv.c (ffffffff826aecab)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81046c0d)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smp.c (ffffffff81056bd4)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff826ba6c2)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105b3bc)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81060380)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107e538)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff8108de95)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff810a7f19)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/smpboot.c (ffffffff810b0776)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
```
```
In kernel/sched/core.c (ffffffff810ba146)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/topology.c (ffffffff810d3d1c)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/debug.c (ffffffff810d83cd)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/irqdesc.c (ffffffff810ed7d4)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff810ef414)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff810f669c)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff810f84c6)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff81105066)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/tick-broadcast.c (ffffffff81118a42)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cgroup/cpuset.c (ffffffff826d05b0)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (ffffffff826d1839)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (ffffffff826d281c)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:tracing_cpumask_write
```
```
In kernel/padata.c (ffffffff811c7238)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In drivers/acpi/processor_throttling.c (ffffffff81593050)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff81594dd8)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81599932)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/xen/events/events_base.c (ffffffff815bd501)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817d9f1f)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817de4f4)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817e0379)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In lib/nmi_backtrace.c (ffffffff81976223)
Location: include/linux/cpumask.h:546
Inline: True
Inline callers:
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
In arch/x86/xen/suspend_pv.c (ffffffff8101e817)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/smp_pv.c (ffffffff826d7f56)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102c031)
Location: include/linux/cpumask.h:548
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81049224)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smp.c (ffffffff81059a44)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff826e4489)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105e2f5)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81063481)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff8106ca05)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810815a8)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff81091725)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff810aead3)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/smpboot.c (ffffffff810b7593)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_update_cpumask_percpu_thread
  - kernel/smpboot.c:smpboot_register_percpu_thread_cpumask
```
```
In kernel/sched/core.c (ffffffff810c171b)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/topology.c (ffffffff810db7ef)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/debug.c (ffffffff810df845)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/irqdesc.c (ffffffff810f5ba4)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff810f77e3)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff810fe9bc)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff81100cc2)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff8110fe03)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/tick-broadcast.c (ffffffff811255cc)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cgroup/cpuset.c (ffffffff826facf1)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (ffffffff826fbfe2)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (ffffffff826fd005)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:tracing_cpumask_write
```
```
In kernel/padata.c (ffffffff811e8002)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In drivers/acpi/processor_throttling.c (ffffffff815ca41d)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff815cc1f1)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d1192)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/xen/events/events_base.c (ffffffff815f5ba7)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81822a30)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818271e5)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81828fc0)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In lib/nmi_backtrace.c (ffffffff819d29a3)
Location: include/linux/cpumask.h:548
Inline: True
Inline callers:
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
In arch/x86/xen/suspend_pv.c (ffffffff8101e0c6)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/smp_pv.c (ffffffff8288df76)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102d02b)
Location: include/linux/cpumask.h:560
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059225)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smp.c (ffffffff8105f6c4)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff8289af4e)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81063f85)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81069178)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff81072899)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810881b8)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff81099a05)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff810b7c33)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff810caa4b)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/topology.c (ffffffff810e53ea)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/debug.c (ffffffff810e9fc5)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/irqdesc.c (ffffffff81101334)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff81103072)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff8110a18c)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff8110c433)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff8111ad63)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/tick-broadcast.c (ffffffff81130cbc)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cgroup/cpuset.c (ffffffff828b1c24)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (ffffffff828b2ee4)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (ffffffff828b3f1f)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace.c:tracing_cpumask_write
```
```
In kernel/padata.c (ffffffff811f81e2)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In drivers/acpi/processor_throttling.c (ffffffff815e39fd)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff815e57d1)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815ea7c2)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81609c9e)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/events/events_base.c (ffffffff81610c67)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8184e910)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818530e5)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81855050)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/powercap/idle_inject.c (ffffffff81883f1b)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
```
```
In lib/nmi_backtrace.c (ffffffff81a0c023)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
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
In arch/x86/xen/suspend_pv.c (ffffffff8101fbed)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/smp_pv.c (ffffffff828a5513)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102ee11)
Location: include/linux/cpumask.h:560
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c7c5)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smp.c (ffffffff81062b56)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b2d0b)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81067646)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106c9c9)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff810763c9)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108be06)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff8109dfd5)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff810ba7ee)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff810d272e)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/topology.c (ffffffff810ec3af)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/debug.c (ffffffff810f0d73)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/irqdesc.c (ffffffff81109b35)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff8110b706)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff8111387b)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff81115ad8)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff81125447)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/tick-broadcast.c (ffffffff8113b81b)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cgroup/cpuset.c (ffffffff828ca966)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (ffffffff828cbc31)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (ffffffff828cca93)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_cpumask_write
```
```
In kernel/padata.c (ffffffff81210544)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In drivers/acpi/processor_throttling.c (ffffffff81615593)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff816173bc)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161c544)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8163da7f)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/events/events_base.c (ffffffff81644940)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816d0408)
Location: include/linux/cpumask.h:560
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81891c2b)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818966b3)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81897c89)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/powercap/idle_inject.c (ffffffff818ce62d)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
```
```
In lib/nmi_backtrace.c (ffffffff81a7b97d)
Location: include/linux/cpumask.h:560
Inline: True
Inline callers:
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
In arch/x86/xen/suspend_pv.c (ffffffff8102054d)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/smp_pv.c (ffffffff828a85a3)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f721)
Location: include/linux/cpumask.h:590
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d0cb)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b615e)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81067f86)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e169)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff810773d9)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108ca76)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109944f)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810a4525)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff810c3c9e)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff810dcb9e)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/topology.c (ffffffff810f7e5f)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/debug.c (ffffffff810fca23)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/irqdesc.c (ffffffff81115f05)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff81117a06)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff8111f9eb)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff81121ee8)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff81131407)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/tick-broadcast.c (ffffffff8114742b)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cgroup/cpuset.c (ffffffff828d2e48)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (ffffffff828d4113)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (ffffffff828d4fd2)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_cpumask_write
```
```
In kernel/padata.c (ffffffff8121dc6c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In drivers/acpi/processor_throttling.c (ffffffff81636a83)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff8163891c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163dfe4)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8165ff5f)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/events/events_base.c (ffffffff81666ef0)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816f4228)
Location: include/linux/cpumask.h:590
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c3c4a)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818c86c3)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818c9aca)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/powercap/idle_inject.c (ffffffff81900a1d)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
```
```
In lib/nmi_backtrace.c (ffffffff81ab2cdd)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
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
In arch/x86/xen/suspend_pv.c (ffffffff81022bb0)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/smp_pv.c (ffffffff82ccdef7)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81031b91)
Location: include/linux/cpumask.h:597
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061601)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff82cdb36d)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106f090)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810757e9)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e729)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093c9e)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109eb1f)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810ab7f5)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff810cba14)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff810e5718)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/topology.c (ffffffff81101533)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:init_overlap_sched_group
  - kernel/sched/topology.c:build_group_from_child_sched_domain
  - kernel/sched/topology.c:build_group_from_child_sched_domain
```
```
In kernel/sched/debug.c (ffffffff8110719c)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/power/energy_model.c (ffffffff8111cb83)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/irq/irqdesc.c (ffffffff81121bb5)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:desc_set_defaults
```
```
In kernel/irq/manage.c (ffffffff811234bf)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff8112bf2b)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff8112e720)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff81140f17)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/tick-broadcast.c (ffffffff8115759e)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cgroup/cpuset.c (ffffffff82cf3813)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/watchdog.c (ffffffff82cf4a42)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (ffffffff811bef7e)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_set_cpumask
```
```
In kernel/padata.c (ffffffff81249d8f)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - kernel/padata.c:__padata_set_cpumasks
  - kernel/padata.c:__padata_set_cpumasks
  - kernel/padata.c:__padata_set_cpumasks
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In lib/nmi_backtrace.c (ffffffff815ed57d)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e3c8b)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff816e5678)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816eb32f)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8170f14f)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/events/events_base.c (ffffffff81716d00)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff817ac918)
Location: include/linux/cpumask.h:597
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8199608b)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199ab11)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199cb4a)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/powercap/idle_inject.c (ffffffff819d7a21)
Location: include/linux/cpumask.h:597
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
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
In arch/x86/xen/suspend_pv.c (ffffffff81023180)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/smp_pv.c (ffffffff82fb9d27)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81032871)
Location: include/linux/cpumask.h:603
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fa11)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff82fc77c1)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107061e)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075e2c)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e359)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810931ee)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a67f)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810a7075)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff810c6c74)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff810e3a1d)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/topology.c (ffffffff81100093)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:init_overlap_sched_group
  - kernel/sched/topology.c:build_group_from_child_sched_domain
  - kernel/sched/topology.c:build_group_from_child_sched_domain
```
```
In kernel/sched/debug.c (ffffffff811059ac)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/power/energy_model.c (ffffffff8111771d)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/irq/irqdesc.c (ffffffff8111dc15)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:desc_set_defaults
```
```
In kernel/irq/manage.c (ffffffff8111f30f)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff8112794b)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff8112a310)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff8113d247)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/tick-broadcast.c (ffffffff8115366e)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cgroup/cpuset.c (ffffffff82fe02ed)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/watchdog.c (ffffffff82fe1521)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (ffffffff811bcc06)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_set_cpumask
```
```
In kernel/padata.c (ffffffff81254456)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:__padata_set_cpumasks
  - kernel/padata.c:__padata_set_cpumasks
  - kernel/padata.c:__padata_set_cpumasks
```
```
In lib/nmi_backtrace.c (ffffffff81611d3d)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/acpi/processor_throttling.c (ffffffff8170191a)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff817030d8)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8172bf1f)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/events/events_base.c (ffffffff81734220)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff817c150c)
Location: include/linux/cpumask.h:603
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8199919b)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199da62)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199fbda)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/powercap/idle_inject.c (ffffffff819d6b6b)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
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
In arch/x86/xen/suspend_pv.c (ffffffff81025490)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/smp_pv.c (ffffffff831c43cd)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81033cd1)
Location: include/linux/cpumask.h:574
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fa81)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff831d1fe5)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81070e0e)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810768ac)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f469)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093bee)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ae3f)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810a8115)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff810c9291)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:copy_workqueue_attrs
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff831e5745)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/topology.c (ffffffff81102168)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/debug.c (ffffffff811079cc)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/sched/debug.c:update_sched_domain_debugfs
```
```
In kernel/power/energy_model.c (ffffffff81117cdd)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/irq/irqdesc.c (ffffffff8111dcf5)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff8111f42f)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff81127aeb)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff8112a590)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff8113e497)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/tick-broadcast.c (ffffffff811547f2)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cgroup/cpuset.c (ffffffff831eaecd)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/watchdog.c (ffffffff831ebadd)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (ffffffff811bc706)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_set_cpumask
```
```
In kernel/padata.c (ffffffff812589ca)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_setup_cpumasks
```
```
In mm/percpu.c (ffffffff831f0333)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In lib/nmi_backtrace.c (ffffffff815f541d)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e2f81)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff816e493c)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8170fc6f)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/events/events_base.c (ffffffff81717d34)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff817a4a6c)
Location: include/linux/cpumask.h:574
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197d9ff)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81982624)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81984618)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/powercap/idle_inject.c (ffffffff819bcceb)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
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
In arch/x86/xen/suspend_pv.c (ffffffff810299a0)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/smp_pv.c (ffffffff832a4ff3)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810690e1)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff832b4785)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8107cae6)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8108401c)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e1cd)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810a39ce)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ab11f)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810b9bc5)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff810dbf8f)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:copy_workqueue_attrs
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff832c9697)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:dup_user_cpus_ptr
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:__sched_core_flip
```
```
In kernel/sched/topology.c (ffffffff8111e6eb)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/debug.c (ffffffff81125aab)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/sched/debug.c:update_sched_domain_debugfs
```
```
In kernel/power/energy_model.c (ffffffff8113803d)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/irq/irqdesc.c (ffffffff8113e135)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff8113f8bf)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff8114805b)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff8114af20)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff81161927)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/clocksource.c (ffffffff8116d874)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff81179242)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cgroup/cpuset.c (ffffffff832cf83f)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/watchdog.c (ffffffff832d04e0)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (ffffffff811e7168)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_set_cpumask
```
```
In kernel/padata.c (ffffffff812945ea)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_setup_cpumasks
```
```
In mm/percpu.c (ffffffff832d5b4b)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In fs/io-wq.c (ffffffff813f325f)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_cpu_affinity
  - fs/io-wq.c:io_wq_cpu_affinity
  - fs/io-wq.c:io_wq_create
```
```
In lib/nmi_backtrace.c (ffffffff8166288d)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/acpi/processor_throttling.c (ffffffff8175b38d)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff8175d690)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8178c61f)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/events/events_base.c (ffffffff81795603)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff8182e27c)
Location: include/linux/cpumask.h:574
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a26ab0)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81a2bab8)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81a2dc89)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/powercap/idle_inject.c (ffffffff81a6c223)
Location: include/linux/cpumask.h:574
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
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
In arch/x86/xen/suspend_pv.c (ffffffff8102e25a)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/smp_pv.c (ffffffff8345404d)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8107635d)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff83466059)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8108c105)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81094119)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff8109eb8d)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810b80ad)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c0b36)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810d06b5)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff810f56c3)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:copy_workqueue_attrs
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff8347c913)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:dup_user_cpus_ptr
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:__sched_core_flip
```
```
In kernel/sched/build_utility.c (ffffffff8347d559)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup_type
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
```
```
In kernel/power/energy_model.c (ffffffff8115a7a3)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/irq/irqdesc.c (ffffffff8116196f)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff8116322f)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff8116cbf0)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff81170593)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff811947a7)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/clocksource.c (ffffffff811a1973)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff811aeb97)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cgroup/cpuset.c (ffffffff834835c7)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/watchdog.c (ffffffff83484356)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (ffffffff8121f0ee)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_set_cpumask
```
```
In kernel/padata.c (ffffffff812ea8ed)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/percpu.c (ffffffff8348a3e0)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In io_uring/io-wq.c (ffffffff816dbde4)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_cpu_affinity
  - io_uring/io-wq.c:io_wq_cpu_affinity
  - io_uring/io-wq.c:io_wq_create
```
```
In lib/nmi_backtrace.c (ffffffff8177c6ef)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/acpi/processor_throttling.c (ffffffff8188df68)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff818906ea)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff818c428c)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/events/events_base.c (ffffffff818ce33e)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff8196ee4e)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b90bf0)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81b9607f)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81b99610)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/powercap/idle_inject.c (ffffffff81bdcd25)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
```
```
In net/core/dev.c (ffffffff81c0f9f1)
Location: include/linux/cpumask.h:609
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In arch/x86/xen/suspend_pv.c (ffffffff8103567a)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/smp_pv.c (ffffffff83e71899)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810868fd)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff83e8991f)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a0865)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a974c)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff810b6a9f)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d379f)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dcda2)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810eef85)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff81116b08)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff81140386)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:dup_user_cpus_ptr
  - kernel/sched/core.c:__sched_core_flip
```
```
In kernel/sched/build_utility.c (ffffffff83ea91bc)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
```
```
In kernel/power/energy_model.c (ffffffff8118cbc7)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/irq/irqdesc.c (ffffffff8119502f)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff81196e54)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff811a1ce5)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff811a6a13)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff811d19dc)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/clocksource.c (ffffffff811e0b23)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff811eed48)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cgroup/cpuset.c (ffffffff8121e849)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/watchdog.c (ffffffff83eb26b9)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (ffffffff81269b23)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_set_cpumask
```
```
In kernel/padata.c (ffffffff81354807)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/percpu.c (ffffffff83ebae70)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In io_uring/io-wq.c (ffffffff817a7ef4)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_cpu_affinity
  - io_uring/io-wq.c:io_wq_cpu_affinity
  - io_uring/io-wq.c:io_wq_create
```
```
In drivers/acpi/processor_throttling.c (ffffffff819d672f)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff819d829c)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81a1497c)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/events/events_base.c (ffffffff81a1f95f)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81ad9a8e)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d30da7)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d36c34)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81d3a570)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/powercap/idle_inject.c (ffffffff81d87e95)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
```
```
In net/core/dev.c (ffffffff81dc21f4)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In lib/nmi_backtrace.c (ffffffff820391bf)
Location: include/linux/cpumask.h:685
Inline: True
Inline callers:
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
In arch/x86/xen/suspend_pv.c (ffffffff810355fa)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/smp_pv.c (ffffffff8369276f)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089389)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/smp.c (ffffffff8109b8a8)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810a37e7)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810ac95c)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff810b9be4)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d6b7f)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e8382)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810faf35)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff81123a18)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_store
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_nice_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff8114f6ea)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:dup_user_cpus_ptr
  - kernel/sched/core.c:__sched_core_flip
```
```
In kernel/sched/build_utility.c (ffffffff836cdca1)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/power/energy_model.c (ffffffff8119e302)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/irq/irqdesc.c (ffffffff811a6974)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff811a891f)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff811b3985)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff811b847a)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff811e5c73)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/clocksource.c (ffffffff811f5083)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff81203a8b)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cgroup/cpuset.c (ffffffff81234939)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/watchdog.c (ffffffff836d77e9)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (ffffffff81280cce)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_set_cpumask
```
```
In kernel/trace/trace_osnoise.c (ffffffff836da5df)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:init_osnoise_tracer
  - kernel/trace/trace_osnoise.c:osnoise_cpus_write
```
```
In kernel/bpf/cpumask.c (ffffffff8135db2c)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_copy
```
```
In kernel/padata.c (ffffffff81385b3f)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/percpu.c (ffffffff836e3495)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In io_uring/io-wq.c (ffffffff817e8d2f)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_cpu_affinity
  - io_uring/io-wq.c:io_wq_cpu_affinity
  - io_uring/io-wq.c:io_wq_create
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a1e0a3)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a1fd08)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81a5d9e0)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/events/events_base.c (ffffffff81a68cb1)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81b27c0e)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d9a027)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d9ffd0)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81da5000)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/powercap/idle_inject.c (ffffffff81df63fb)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register_full
```
```
In net/core/dev.c (ffffffff81e31754)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In lib/nmi_backtrace.c (ffffffff820b74cf)
Location: include/linux/cpumask.h:737
Inline: True
Inline callers:
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
In arch/x86/xen/suspend_pv.c (ffffffff8103b7fa)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/smp_pv.c (ffffffff838c22bd)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81090379)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/smp.c (ffffffff810a2e48)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In arch/x86/kernel/apic/apic.c (ffffffff838e05f6)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_init_primary_thread_mask
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810aa805)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b35dc)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff810c0e34)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810df3af)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f0912)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff811043d5)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff8112dc2d)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_unbound_exclude_cpumask
  - kernel/workqueue.c:workqueue_unbound_exclude_cpumask
  - kernel/workqueue.c:workqueue_apply_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_pod_cpumask
  - kernel/workqueue.c:wqattrs_actualize_cpumask
  - kernel/workqueue.c:copy_workqueue_attrs
  - kernel/workqueue.c:copy_workqueue_attrs
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff8115b58a)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:__sched_setaffinity
  - kernel/sched/core.c:dup_user_cpus_ptr
  - kernel/sched/core.c:__sched_core_flip
```
```
In kernel/sched/fair.c (ffffffff81163058)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/sched/fair.c:should_we_balance
```
```
In kernel/sched/build_utility.c (ffffffff838ff0e2)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:housekeeping_setup
  - kernel/sched/build_utility.c:init_sched_groups_capacity
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
```
```
In kernel/power/energy_model.c (ffffffff811ad4a5)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/irq/irqdesc.c (ffffffff811b6494)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff811b847f)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff811c3805)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff811c833a)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff811fb9c3)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/clocksource.c (ffffffff8120b223)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff8121a04b)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/time/tick-sched.c (ffffffff8390572f)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_full_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff8124e559)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_cpus_allowed
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:update_exclusive_cpumask
  - kernel/cgroup/cpuset.c:update_exclusive_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_effective_cpumask
  - kernel/cgroup/cpuset.c:reset_partition_data
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:guarantee_online_cpus
```
```
In kernel/watchdog.c (ffffffff83909caf)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (ffffffff8129af22)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create_systems
  - kernel/trace/trace.c:tracing_set_cpumask
```
```
In kernel/trace/trace_osnoise.c (ffffffff8390cb4f)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:init_osnoise_tracer
  - kernel/trace/trace_osnoise.c:osnoise_cpus_write
```
```
In kernel/bpf/cpumask.c (ffffffff813868cc)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_copy
```
```
In kernel/padata.c (ffffffff813aeffe)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/percpu.c (ffffffff83915d25)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In io_uring/io-wq.c (ffffffff8182eadf)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_cpu_affinity
  - io_uring/io-wq.c:io_wq_cpu_affinity
  - io_uring/io-wq.c:io_wq_create
```
```
In lib/group_cpus.c (ffffffff8192e28a)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - lib/group_cpus.c:group_cpus_evenly
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a693b3)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a6b028)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81aaf990)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/events/events_base.c (ffffffff81abb906)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81b7eace)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e51cd7)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e57e4f)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5cfbf)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/powercap/idle_inject.c (ffffffff81eacaf1)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register_full
```
```
In net/core/dev.c (ffffffff81eefed4)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In lib/nmi_backtrace.c (ffffffff8219167f)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
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
In arch/arm64/kernel/smp.c (ffff80001009d324)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:crash_smp_send_stop
  - arch/arm64/kernel/smp.c:smp_send_stop
```
```
In kernel/cpu.c (ffff8000100fa1a8)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffff800010121a44)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffff80001013c6ec)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/topology.c (ffff80001015c2ac)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/debug.c (ffff800010161e20)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/irqdesc.c (ffff80001017764c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffff80001017ae48)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffff8000101855d8)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffff800010188140)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffff800010198bc8)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/tick-broadcast.c (ffff8000101b25e0)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cgroup/cpuset.c (ffff80001144b42c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (ffff80001144c848)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (ffff80001144d874)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_cpumask_write
```
```
In kernel/padata.c (ffff8000102a9488)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_setup_cpumasks
```
```
In drivers/irqchip/irq-gic.c (ffff80001066c3c0)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_set_affinity
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066f270)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010671c5c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_set_affinity
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff8000106771f8)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_set_affinity
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b690)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_set_affinity
```
```
In drivers/acpi/processor_perflib.c (ffff8000107a3d74)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a8eb4)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/virtio/virtio_pci_common.c (ffff800010828e84)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/events/events_base.c (ffff800010830bb4)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/base/arch_topology.c (ffff800011497f6c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:register_cpufreq_notifier
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b217dc)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/powercap/idle_inject.c (ffff800010b90308)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
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
In arch/arm/kernel/smp.c (c03138e0)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:smp_send_stop
```
```
In arch/arm/common/bL_switcher.c (c03276e0)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus
```
```
In kernel/cpu.c (c0358378)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (c03754b4)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (c038ca98)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/topology.c (c03a8cb4)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/debug.c (c03ae5f4)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/irqdesc.c (c03c9534)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (c03cbfbc)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (c03d477c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (c03d6b30)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (c03e4030)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/tick-broadcast.c (c03fcd4c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cgroup/cpuset.c (c15258c8)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (c1526dd0)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (c1527e14)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_cpumask_write
```
```
In kernel/padata.c (c04d8778)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_setup_cpumasks
```
```
In drivers/irqchip/irq-hip04.c (c0813fdc)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/irqchip/irq-hip04.c:hip04_irq_set_affinity
```
```
In drivers/irqchip/irq-gic.c (c0815750)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_set_affinity
```
```
In drivers/irqchip/irq-gic-v3.c (c0818040)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
```
```
In drivers/irqchip/irq-gic-v3-its.c (c081b1d8)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_activate
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_set_affinity
```
```
In drivers/irqchip/irq-armada-370-xp.c (c081ebec)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_xp_set_affinity
```
```
In drivers/virtio/virtio_pci_common.c (c0946b1c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/base/arch_topology.c (c1598c80)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:register_cpufreq_notifier
```
```
In drivers/cpufreq/cpufreq.c (c0bfbe1c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/powercap/idle_inject.c (c0c7a338)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
```
```
In lib/nmi_backtrace.c (c0e874d0)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
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
In arch/powerpc/kernel/rtas.c (c00000000003e314)
Location: include/linux/cpumask.h:590
Inline: True
```
```
In arch/powerpc/kernel/smp.c (c000000000054c30)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi
```
```
In arch/powerpc/platforms/pseries/smp.c (c000000001363900)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/smp.c:smp_init_pseries
```
```
In kernel/cpu.c (c00000000014139c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (c00000000016b23c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:wq_calc_node_cpumask
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (c00000000018ad9c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/topology.c (c0000000001b0a5c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/debug.c (c0000000001b8080)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/irqdesc.c (c0000000001d1290)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (c0000000001d5420)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (c0000000001dfad4)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (c0000000001e2260)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (c0000000001f9490)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/tick-broadcast.c (c000000000217d1c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cgroup/cpuset.c (c000000001370ddc)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (c000000001372828)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (c000000001373e30)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_cpumask_write
```
```
In kernel/padata.c (c00000000035d8c0)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_setup_cpumasks
```
```
In drivers/virtio/virtio_pci_common.c (c0000000008d55a4)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/cpufreq/cpufreq.c (c000000000c157a8)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/powernv-cpufreq.c (c0000000013b88a0)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init
```
```
In drivers/powercap/idle_inject.c (c000000000c6f5ac)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
```
```
In lib/nmi_backtrace.c (c000000000ecf140)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
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
In arch/riscv/kernel/smp.c (ffffffe0000b8060)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/riscv/kernel/smp.c:smp_send_stop
```
```
In kernel/cpu.c (ffffffe0000c4300)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffe0000da690)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffe0000ebec2)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/topology.c (ffffffe000101222)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
```
In kernel/sched/debug.c (ffffffe000105bc0)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/irqdesc.c (ffffffe0001122f0)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
```
```
In kernel/irq/manage.c (ffffffe000114aca)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffe00011c112)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffe00011d914)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffe00012954e)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/cgroup/cpuset.c (ffffffe00000c7b2)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (ffffffe00000d05a)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (ffffffe00000de86)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_cpumask_write
```
```
In kernel/padata.c (ffffffe0001d2c96)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_setup_cpumasks
```
```
In drivers/virtio/virtio_pci_common.c (ffffffe00051f1de)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
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
In arch/x86/xen/suspend_pv.c (ffffffff810206ad)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/smp_pv.c (ffffffff828965b3)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f881)
Location: include/linux/cpumask.h:590
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105cc4b)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff828a416a)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81067a76)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d109)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff810763d9)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108ba36)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff8109de45)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff810be00e)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff810d6dae)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/topology.c (ffffffff810f125f)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/debug.c (ffffffff810f5d53)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/irqdesc.c (ffffffff8110e4e5)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff8110ffe6)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff81117fcb)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff8111a4c8)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff81129bb7)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/tick-broadcast.c (ffffffff8113fa4b)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cgroup/cpuset.c (ffffffff828bbcf9)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (ffffffff828bcfc4)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (ffffffff828bde83)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_cpumask_write
```
```
In kernel/padata.c (ffffffff812162bc)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In drivers/acpi/processor_throttling.c (ffffffff81605f63)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff816079cc)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81609a14)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81625dcf)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/events/events_base.c (ffffffff8162cc20)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816b9a18)
Location: include/linux/cpumask.h:590
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8186836a)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8186cde3)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8186e1ea)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In lib/nmi_backtrace.c (ffffffff81a51b2d)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
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
In arch/x86/hyperv/hv_apic.c (ffffffff8101f091)
Location: include/linux/cpumask.h:590
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104ce1b)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff8289c2ac)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81057de6)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d4fc)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff81066349)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107a556)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff8108c865)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff810ac83e)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff810c569e)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/topology.c (ffffffff810e12cf)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/debug.c (ffffffff810e5f13)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/irqdesc.c (ffffffff810ff245)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff81100d16)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff8110903b)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff8110b538)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff8111c447)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/tick-broadcast.c (ffffffff811327cb)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/time/tick-sched.c (ffffffff828b257a)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_full_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff828b438c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (ffffffff828b567c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (ffffffff828b6523)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_cpumask_write
```
```
In kernel/padata.c (ffffffff8120901c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In drivers/acpi/processor_throttling.c (ffffffff815f1033)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff815f2acc)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fb654)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8161a44f)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81697658)
Location: include/linux/cpumask.h:590
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8183101a)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81835b63)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8183780a)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/hv/channel_mgmt.c (ffffffff81852b5c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:init_vp_index
```
```
In lib/nmi_backtrace.c (ffffffff81a0ec2d)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
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
In arch/x86/xen/suspend_pv.c (ffffffff8102050d)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/smp_pv.c (ffffffff828a95a3)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f6e1)
Location: include/linux/cpumask.h:590
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d07b)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b707a)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81067f26)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d5b9)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff81076389)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108b9e6)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff8109ddf5)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff810bd56e)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff810d39ee)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/topology.c (ffffffff810ee38f)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/debug.c (ffffffff810f2f53)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/irqdesc.c (ffffffff8110c3d5)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff8110ded6)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff81115ebb)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff811183b8)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff811278d7)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/tick-broadcast.c (ffffffff8113d8fb)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cgroup/cpuset.c (ffffffff828cea7c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (ffffffff828cfd47)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (ffffffff828d0c06)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_cpumask_write
```
```
In kernel/padata.c (ffffffff8121405c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In drivers/acpi/processor_throttling.c (ffffffff8162ad63)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff8162cbfc)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81631e24)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81653d9f)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/events/events_base.c (ffffffff8165ad30)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816e7ee8)
Location: include/linux/cpumask.h:590
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b90fa)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818bdb73)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818bef7a)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/powercap/idle_inject.c (ffffffff818f143d)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
```
```
In lib/nmi_backtrace.c (ffffffff81abdf1d)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
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
In arch/x86/xen/suspend_pv.c (ffffffff8102075d)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/xen/suspend_pv.c:xen_pv_post_suspend
```
```
In arch/x86/xen/smp_pv.c (ffffffff828a95b3)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81030531)
Location: include/linux/cpumask.h:590
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e59b)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b7161)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810695e6)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f839)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff810783d9)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108dd46)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a91f)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810a5ce5)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/cpu.c:init_cpu_online
  - kernel/cpu.c:init_cpu_possible
  - kernel/cpu.c:init_cpu_present
```
```
In kernel/workqueue.c (ffffffff810c58ee)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_sysfs_prep_attrs
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff810de929)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/topology.c (ffffffff810f93cf)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
```
```
In kernel/sched/debug.c (ffffffff810fdf53)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/irq/irqdesc.c (ffffffff81117b05)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff8111941f)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/proc.c (ffffffff811214eb)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/proc.c:default_affinity_write
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffffffff81123a48)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff81133f17)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/profile.c:prof_cpu_mask_proc_write
  - kernel/profile.c:profile_init
```
```
In kernel/time/tick-broadcast.c (ffffffff8114a40b)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
```
```
In kernel/cgroup/cpuset.c (ffffffff828d3e76)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_bind
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_css_online
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (ffffffff828d5141)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/trace.c (ffffffff828d6027)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_cpumask_write
```
```
In kernel/padata.c (ffffffff8122329c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_replace
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
```
```
In drivers/acpi/processor_throttling.c (ffffffff81644c03)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81646a9c)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164c154)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8166e42f)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/events/events_base.c (ffffffff81675320)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:xen_irq_init
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff817025e8)
Location: include/linux/cpumask.h:590
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d53da)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818d9e83)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818db28a)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/powercap/idle_inject.c (ffffffff819124bd)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - drivers/powercap/idle_inject.c:idle_inject_register
```
```
In lib/nmi_backtrace.c (ffffffff81aca3b1)
Location: include/linux/cpumask.h:590
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
