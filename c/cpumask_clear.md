# Function: <code>cpumask_clear</code>

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
In init/main.c (ffffffff81f59c74)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/apic.c (ffffffff81025b11)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:flat_vector_allocation_domain
```
```
In arch/x86/xen/smp.c (ffffffff81f64fa3)
Location: include/linux/cpumask.h:338
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81f69630)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:init_amd_e400_c1e_mask
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81f6af01)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
```
```
In arch/x86/kernel/smpboot.c (ffffffff81f6f7c0)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81054e9f)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059e38)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
  - arch/x86/kernel/apic/x2apic_cluster.c:update_clusterinfo
  - arch/x86/kernel/apic/x2apic_cluster.c:update_clusterinfo
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a431)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_vector_allocation_domain
```
```
In kernel/fork.c (ffffffff8107db12)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff81081b82)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (ffffffff8109d176)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:init_workqueues
```
```
In kernel/sched/core.c (ffffffff810a5d72)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/sched/core.c:init_rootdomain
  - kernel/sched/core.c:init_rootdomain
  - kernel/sched/core.c:init_rootdomain
  - kernel/sched/core.c:init_rootdomain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:SyS_sched_setaffinity
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff81f7e4a7)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
```
```
In kernel/sched/rt.c (ffffffff81f7e4d2)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffff81f7e525)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/cpupri.c (ffffffff810c428d)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810c48af)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/irq/irqdesc.c (ffffffff810da26f)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/proc.c (ffffffff810e1ae9)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/migration.c (ffffffff810e2621)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff810fcee3)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
```
```
In kernel/smp.c (ffffffff811037c9)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/smp.c:hotplug_cfd
  - kernel/smp.c:on_each_cpu_cond
```
```
In kernel/cpuset.c (ffffffff8111aa9d)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (ffffffff811501de)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In mm/swap.c (ffffffff8119e257)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/rmap.c (ffffffff811ca674)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush
```
```
In mm/slub.c (ffffffff811e9435)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff813c4273)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-tag.c (ffffffff813c7845)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/blk-mq-cpumap.c (ffffffff813c85f7)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
```
```
In lib/cpu_rmap.c (ffffffff81415dc6)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/acpi_processor.c (ffffffff81482192)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/processor_throttling.c (ffffffff814ada1b)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff814af34a)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff814c2fd1)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81fa56e5)
Location: include/linux/cpumask.h:338
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816b1cdc)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff816b3b96)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81fb3ee7)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff816b87ba)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff816b978d)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/sysctl_net_core.c (ffffffff817132ef)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/flow.c (ffffffff81735189)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/core/net-sysfs.c (ffffffff817363be)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_xps_map
  - net/core/net-sysfs.c:show_rps_map
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
In init/main.c (ffffffff81f81c3d)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/apic.c (ffffffff81024f11)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:flat_vector_allocation_domain
```
```
In arch/x86/xen/smp.c (ffffffff81f8cb64)
Location: include/linux/cpumask.h:342
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81f9151f)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:init_amd_e400_c1e_mask
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81f931fe)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
```
```
In arch/x86/kernel/smpboot.c (ffffffff81052688)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055e53)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a0da)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a7e1)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_vector_allocation_domain
```
```
In kernel/fork.c (ffffffff8107f70d)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff8108500c)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:disable_nonboot_cpus
```
```
In kernel/workqueue.c (ffffffff81fa5111)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
```
```
In kernel/sched/core.c (ffffffff81fa72d6)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:SyS_sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff81fa7378)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
```
```
In kernel/sched/rt.c (ffffffff81fa7397)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffff81fa73ea)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/cpupri.c (ffffffff810c7f7d)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810c855d)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/irq/irqdesc.c (ffffffff810df76e)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/proc.c (ffffffff810e7589)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/migration.c (ffffffff810e80b1)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff81fa9a15)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff8110b3bf)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/cpuset.c (ffffffff8112336a)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:generate_sched_domains
```
```
In kernel/trace/trace.c (ffffffff8115a928)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:__tracing_open
```
```
In mm/swap.c (ffffffff811b3c05)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/rmap.c (ffffffff811e7032)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush
```
```
In mm/slub.c (ffffffff81207cca)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff814079e0)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In block/blk-mq-tag.c (ffffffff8140ba80)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/blk-mq-cpumap.c (ffffffff8140c857)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
```
```
In lib/cpu_rmap.c (ffffffff8145dc06)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/acpi_processor.c (ffffffff814d0c9b)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/processor_throttling.c (ffffffff814fd41e)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff814fecb6)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81513541)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81fd1b6a)
Location: include/linux/cpumask.h:342
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81713e76)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81715bbb)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817181ad)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8171a516)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff8171b18d)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/sysctl_net_core.c (ffffffff8177af57)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/flow.c (ffffffff817a1320)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/core/net-sysfs.c (ffffffff817a2564)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_xps_map
  - net/core/net-sysfs.c:show_rps_map
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
In init/main.c (ffffffff81fbdc45)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/apic.c (ffffffff810255f0)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:flat_vector_allocation_domain
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054f9d)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058c0a)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d500)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_vector_allocation_domain
```
```
In kernel/fork.c (ffffffff81083d42)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff81089fa8)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810b81b9)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:SyS_sched_setaffinity
```
```
In kernel/irq/irqdesc.c (ffffffff810e5e7d)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff810eeaf6)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff8110ba25)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cpuset.c (ffffffff8112ba01)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:generate_sched_domains
```
```
In kernel/trace/trace.c (ffffffff8116513c)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff8116d812)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/swap.c (ffffffff811c4278)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/rmap.c (ffffffff811f83d4)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush
```
```
In mm/slub.c (ffffffff81219cc3)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff81422e1e)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In block/blk-mq-cpumap.c (ffffffff81427bc9)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In drivers/acpi/processor_throttling.c (ffffffff815202f5)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff81521caa)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81525721)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8153f95d)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81745d4e)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81747906)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8174a04e)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff817a85a1)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/flow.c (ffffffff817cfc30)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
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
In init/main.c (ffffffff8209dcf4)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/apic.c (ffffffff8101bfa0)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:flat_vector_allocation_domain
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810437ad)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff810548b5)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058263)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c832)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105cc00)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_vector_allocation_domain
```
```
In arch/x86/mm/tlb.c (ffffffff81074d84)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In kernel/fork.c (ffffffff81080c72)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff81086e6e)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810b2eb5)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setaffinity
```
```
In kernel/sched/topology.c (ffffffff810ccbed)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (ffffffff810e54d2)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff810ee63b)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff8110da65)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff81113f94)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff8112f2a9)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/trace/trace.c (ffffffff81168486)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811709ce)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/swap.c (ffffffff811cc67a)
Location: include/linux/cpumask.h:370
Inline: True
```
```
In mm/slub.c (ffffffff81225a2b)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff814329f6)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In drivers/acpi/processor_throttling.c (ffffffff81531b66)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff81533649)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81538013)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815536fe)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81765f9a)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8176866d)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff817c6bef)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/flow.c (ffffffff817ef030)
Location: include/linux/cpumask.h:370
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
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
In init/main.c (ffffffff826a3c95)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81022afa)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81046e21)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105868f)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
```
In arch/x86/mm/tlb.c (ffffffff8107af1c)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In kernel/fork.c (ffffffff810875e2)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff8108dc03)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810ba2b5)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setaffinity
```
```
In kernel/sched/topology.c (ffffffff810d3a33)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (ffffffff810ed721)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff810f706b)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff81118cf5)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff8111f524)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff8113c155)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff8115b783)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff8115bed5)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff81175415)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff8117db96)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/swap.c (ffffffff811e16ac)
Location: include/linux/cpumask.h:374
Inline: True
```
```
In mm/slub.c (ffffffff812410bb)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff8145e5c7)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In drivers/acpi/processor_throttling.c (ffffffff81592e99)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff81594c95)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815997dd)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815b707e)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/opp/cpu.c (ffffffff817d5fcd)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817dbf7a)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817de55d)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff818407ef)
Location: include/linux/cpumask.h:374
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
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
In init/main.c (ffffffff826ccd86)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810233e9)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff8104927e)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105b308)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
```
In arch/x86/mm/tlb.c (ffffffff8107dcdc)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826f2131)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8108aba2)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff8109194a)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810bc8ae)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff810db70a)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (ffffffff810f5af1)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff810ff3b8)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff8112587f)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff8112c85b)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff8114aa0a)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/watchdog.c (ffffffff8116a2e3)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff8116aa45)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff811843cb)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff8118c9dc)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/swap.c (ffffffff81202ddc)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/slub.c (ffffffff812640bd)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff81491f05)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In drivers/acpi/processor_throttling.c (ffffffff815ca2a7)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff815cc13b)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d103d)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815ef57d)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/opp/cpu.c (ffffffff8181ecad)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81824c30)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818272da)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff8188ae4a)
Location: include/linux/cpumask.h:376
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
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
In init/main.c (ffffffff82882da1)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81022e90)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105927f)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff81060f88)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
```
In arch/x86/mm/tlb.c (ffffffff81084854)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828a9156)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81092b9f)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff81099c2a)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810c372e)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff810e5309)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (ffffffff81101281)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff8110ab98)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff81130f6f)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff8113812b)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff8115866c)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/watchdog.c (ffffffff811772f5)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff81177a55)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff81191d3b)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119a4ec)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/swap.c (ffffffff8121577c)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/slub.c (ffffffff8127882d)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff814ab969)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In drivers/acpi/processor_throttling.c (ffffffff815e3887)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff815e571b)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815ea66d)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/opp/cpu.c (ffffffff8184ab2d)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81850bc0)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818531da)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff818abe8a)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
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
In init/main.c (ffffffff82899cfd)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025559)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c820)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff810645f3)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
```
In arch/x86/mm/tlb.c (ffffffff810884c1)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c193d)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096b87)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff8109e23a)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810cb700)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff810ec2a0)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/irqdesc.c (ffffffff81109a7e)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff8111424c)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff8113bacf)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff811432d8)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff81164e38)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff811840d6)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff811848b9)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff8119f757)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811a8154)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/swap.c (ffffffff81225178)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/slub.c (ffffffff8129492a)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff814d9b5a)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In drivers/acpi/processor_throttling.c (ffffffff81615416)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81617316)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161c3f0)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/opp/cpu.c (ffffffff8188dc9d)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818940fe)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818967b0)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff818f774a)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
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
In arch/x86/xen/mmu_pv.c (ffffffff81025b39)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d126)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064c73)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
```
In arch/x86/mm/tlb.c (ffffffff81089171)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c7db6)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81095949)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:reset_with_ipi
```
```
In kernel/fork.c (ffffffff8109d3c7)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff810a4797)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810d3930)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff810f7d4d)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (ffffffff81115e4e)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff811203bc)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff811476df)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff8114ee18)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff81170d18)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff8118ff56)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff81190739)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff811ab117)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b3954)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/swap.c (ffffffff81232ff8)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/slub.c (ffffffff812a46fa)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff814f2f07)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In drivers/acpi/processor_throttling.c (ffffffff81636906)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81638876)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163de90)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/opp/cpu.c (ffffffff818bfe2d)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818c611e)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818c87c0)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff819294ca)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
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
In arch/x86/xen/mmu_pv.c (ffffffff81025edf)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061658)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106a0c1)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
```
```
In arch/x86/mm/tlb.c (ffffffff8108ba7a)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82ceabfc)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109aa47)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:reset_with_ipi
```
```
In kernel/fork.c (ffffffff810a4227)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff810aba9f)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810ddce2)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff81101619)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_balance_mask
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/irqdesc.c (ffffffff8112166d)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:desc_set_defaults
```
```
In kernel/irq/migration.c (ffffffff8112c8fc)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff811573ef)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff8115f788)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff81182959)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff811a4ad6)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff811a52e3)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff811c33dc)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811cc3e0)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In mm/swap.c (ffffffff81260633)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/slub.c (ffffffff812d8e8a)
Location: include/linux/cpumask.h:411
Inline: True
```
```
In block/blk-mq.c (ffffffff8155351e)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e3b16)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff816e55d2)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816eb287)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/opp/cpu.c (ffffffff81991b8d)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8199819e)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199aa10)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff819fd45a)
Location: include/linux/cpumask.h:411
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
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
In arch/x86/xen/mmu_pv.c (ffffffff8102671f)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fa68)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068032)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106bd91)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
```
```
In arch/x86/mm/tlb.c (ffffffff8108baca)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82fd8447)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8109fe37)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff81bdb6e1)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810da2be)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff81100179)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_balance_mask
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/irqdesc.c (ffffffff8111d79d)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:desc_set_defaults
```
```
In kernel/irq/migration.c (ffffffff8112832c)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff811534bf)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff8115b728)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff8117f891)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff811a1b76)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff811a22d3)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff811c0fec)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811c9a3b)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In mm/swap.c (ffffffff8126a6e3)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/slub.c (ffffffff812e447a)
Location: include/linux/cpumask.h:417
Inline: True
```
```
In block/blk-mq.c (ffffffff8156fbce)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In drivers/acpi/processor_throttling.c (ffffffff81701776)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81703032)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8170898f)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/opp/cpu.c (ffffffff81994e6d)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8199b2be)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199daf3)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff819fd0a2)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81a046f4)
Location: include/linux/cpumask.h:417
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
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
In arch/x86/xen/mmu_pv.c (ffffffff8102839f)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fad8)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810685a2)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106c6ee)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
```
```
In arch/x86/mm/tlb.c (ffffffff8108c6fa)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff831e2e3d)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810a0b4a)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff81bcd7d3)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810dc3ab)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff81102e44)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/irqdesc.c (ffffffff8111dc41)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff811285f2)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/clocksource.c (ffffffff811496e5)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_percpu
  - kernel/time/clocksource.c:clocksource_verify_percpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8115497f)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff8115c7f9)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff8117fed1)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff811a2867)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff811a2f93)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff811c1f38)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811cae1d)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In mm/swap.c (ffffffff8126f82b)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/percpu.c (ffffffff831f0286)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/slub.c (ffffffff812eb67c)
Location: include/linux/cpumask.h:388
Inline: True
```
```
In block/blk-mq.c (ffffffff81577a8a)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e2dbb)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff816e47a3)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816e9fa4)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/opp/cpu.c (ffffffff81979dad)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8197ff9e)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff819826b5)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff819e3912)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff819ebf04)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
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
In arch/x86/xen/mmu_pv.c (ffffffff8102ca0b)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81069138)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072d21)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
```
In arch/x86/kernel/smpboot.c (ffffffff8107751f)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
```
```
In arch/x86/mm/tlb.c (ffffffff8109bf3a)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff832c67e0)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810b1fb1)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff81ca4114)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810ef1eb)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff8111fa22)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:asym_cpu_capacity_scan
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/irqdesc.c (ffffffff8113e063)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff81148bc2)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/clocksource.c (ffffffff8116d786)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff811795d3)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff8118194f)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff811a8111)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff811cc033)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff811cc7d5)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff811ecb18)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811f6e37)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In mm/swap.c (ffffffff812ac97b)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/percpu.c (ffffffff832d5a9e)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/slub.c (ffffffff81333d4c)
Location: include/linux/cpumask.h:388
Inline: True
```
```
In fs/io_uring.c (ffffffff813decf4)
Location: include/linux/cpumask.h:388
Inline: True
```
```
In block/blk-mq.c (ffffffff815dc7aa)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In drivers/acpi/processor_throttling.c (ffffffff8175b19b)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff8175d4db)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8176389e)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/opp/cpu.c (ffffffff81a22dbd)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81a2913e)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81a2bb52)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff81a93eb2)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81a9ce94)
Location: include/linux/cpumask.h:388
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
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
In arch/x86/xen/mmu_pv.c (ffffffff810317bd)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810763b8)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080f82)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
```
```
In arch/x86/kernel/smpboot.c (ffffffff8108659a)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
```
```
In arch/x86/mm/tlb.c (ffffffff810af4b7)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83479578)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810c8918)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff81e539b1)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff8110aba5)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/build_utility.c (ffffffff81149a5e)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/irqdesc.c (ffffffff8116167b)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff8116d6f8)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/clocksource.c (ffffffff811a1873)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff811ae993)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff811b7f9d)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff811d90d1)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff811ffdf1)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff812006e5)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff81224cc5)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff8123062f)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In mm/swap.c (ffffffff81302df8)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/percpu.c (ffffffff8348a330)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/slub.c (ffffffff813a501d)
Location: include/linux/cpumask.h:423
Inline: True
```
```
In block/blk-mq.c (ffffffff8168a37f)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In io_uring/io_uring.c (ffffffff81e8f64e)
Location: include/linux/cpumask.h:423
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff8188dd69)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff8189062b)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81896d75)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/opp/cpu.c (ffffffff81b8bd39)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b9108a)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81b9319e)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81b96117)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff81c0a281)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81c0f624)
Location: include/linux/cpumask.h:423
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
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
In arch/x86/xen/mmu_pv.c (ffffffff81038fd6)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81086958)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108fd02)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/smpboot.c (ffffffff81099b02)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
```
```
In arch/x86/mm/tlb.c (ffffffff810c9939)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83ea36c3)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810e5c65)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff810ee8c6)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff81132195)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/build_utility.c (ffffffff8116f709)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/irqdesc.c (ffffffff81194d02)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff811a2898)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/clocksource.c (ffffffff811e0a21)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff811ef2f3)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff811f9239)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff8121e1ec)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff812478b9)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff812483e1)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff8126fe25)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff8127cca6)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In mm/swap.c (ffffffff8136ddc8)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/percpu.c (ffffffff83ebadbb)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/slub.c (ffffffff81425a6a)
Location: include/linux/cpumask.h:488
Inline: True
```
```
In block/blk-mq.c (ffffffff8174897f)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In io_uring/io_uring.c (ffffffff81788ecf)
Location: include/linux/cpumask.h:488
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff819d67d7)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff819d835f)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819df8ff)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/opp/cpu.c (ffffffff81d2b489)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d310a6)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d3381c)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d36ccc)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff81dba326)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81dc1f88)
Location: include/linux/cpumask.h:488
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
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
In arch/x86/xen/mmu_pv.c (ffffffff81038f09)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089406)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092c12)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/smp.c (ffffffff8109b93f)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109cf82)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
```
```
In arch/x86/mm/tlb.c (ffffffff810ccfb4)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff836c7953)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810f13db)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff810fa8a6)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff81140405)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/build_utility.c (ffffffff8117f569)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/irqdesc.c (ffffffff811a6497)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff811b4798)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/clocksource.c (ffffffff811f4f81)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff81203853)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff8120dee3)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff812342ec)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff8125ecd9)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
```
In kernel/watchdog_perf.c (ffffffff8125f701)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/watchdog_perf.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff81287083)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:close_pipe_on_cpu
```
```
In kernel/trace/trace_hwlat.c (ffffffff81294986)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/cpumask.c (ffffffff8135d8e5)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_clear
```
```
In mm/swap.c (ffffffff8139ffe8)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/percpu.c (ffffffff836e33eb)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/slub.c (ffffffff8145acfa)
Location: include/linux/cpumask.h:552
Inline: True
```
```
In fs/exec.c (ffffffff814b889c)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - fs/exec.c:mm_init_cid
```
```
In block/blk-mq.c (ffffffff8178508f)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In io_uring/io_uring.c (ffffffff817cad9e)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_iowq_aff
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a1e130)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a1fdb7)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a2760f)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/net/virtio_net.c (ffffffff81c4ced0)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
```
In drivers/opp/cpu.c (ffffffff81d94759)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d9a358)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d9cbac)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81da0081)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff81e2accd)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81e314e8)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
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
In arch/x86/xen/mmu_pv.c (ffffffff8103f3b9)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810903f6)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a052)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/smp.c (ffffffff810a2f49)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a44c2)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
```
```
In arch/x86/mm/tlb.c (ffffffff810d5684)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff838f8553)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810fa7ab)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff81103cc6)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/workqueue.c (ffffffff838fba40)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_unbound_cpus_setup
```
```
In kernel/sched/core.c (ffffffff8114b4b5)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/build_utility.c (ffffffff8118ce69)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/irqdesc.c (ffffffff811b5fb6)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff811c4618)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/clocksource.c (ffffffff8120b121)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff81219e13)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/time/tick-sched.c (ffffffff839058de)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_init
```
```
In kernel/smp.c (ffffffff81225673)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff8124e090)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:update_exclusive_cpumask
  - kernel/cgroup/cpuset.c:update_exclusive_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:reset_partition_data
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff81278ce9)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
```
In kernel/watchdog_perf.c (ffffffff81279711)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/watchdog_perf.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff812a214c)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:close_pipe_on_cpu
```
```
In kernel/trace/trace_hwlat.c (ffffffff812affe6)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/cpumask.c (ffffffff81386685)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_clear
```
```
In mm/swap.c (ffffffff813c9c68)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/percpu.c (ffffffff83915c7b)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/slub.c (ffffffff8145605a)
Location: include/linux/cpumask.h:552
Inline: True
```
```
In fs/exec.c (ffffffff814eadac)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - fs/exec.c:mm_init_cid
```
```
In block/blk-mq.c (ffffffff817c761f)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In io_uring/register.c (ffffffff8182b36e)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - io_uring/register.c:io_register_iowq_aff
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a69440)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a6b0d7)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a7277f)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/net/virtio_net.c (ffffffff81d02773)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
```
In drivers/opp/cpu.c (ffffffff81e4c269)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e52087)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81e5486c)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e57f00)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff81ee8add)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81eefc68)
Location: include/linux/cpumask.h:552
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
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
In arch/arm64/mm/numa.c (ffff800011439010)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:numa_init
```
```
In virt/kvm/kvm_main.c (ffff8000100b6ae0)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_init
  - virt/kvm/kvm_main.c:kvm_make_all_cpus_request
```
```
In kernel/fork.c (ffff8000100f1c1c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffff8000100f9eb4)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/workqueue.c (ffff800011442fa0)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
```
```
In kernel/sched/core.c (ffff80001013c7e8)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/core.c:__arm64_sys_sched_setaffinity
```
```
In kernel/sched/fair.c (ffff800011445088)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
```
```
In kernel/sched/rt.c (ffff8000114450cc)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffff800011445140)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/cpupri.c (ffff80001015a044)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffff80001015a898)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/topology.c (ffff80001015d224)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/membarrier.c (ffff800010166268)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
```
```
In kernel/irq/irqdesc.c (ffff8000101774c0)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/proc.c (ffff800010185788)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffff8000101881d8)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffff800011449108)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffff8000101bd7b8)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/cgroup/cpuset.c (ffff8000101e3f08)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (ffff800010207804)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/ring_buffer.c (ffff80001021a130)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffff800010227e9c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/trace_hwlat.c (ffff800010231f88)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (ffff800011451240)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_all_cpus
```
```
In mm/swap.c (ffff8000102c317c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/slub.c (ffff800010344c78)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffff8000105f20d0)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/cpu_rmap.c (ffff80001066286c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff80001067722c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff800010725790)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_hwirq_alloc
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff8000107262a4)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
```
```
In drivers/acpi/acpi_processor.c (ffff80001076f648)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/processor_perflib.c (ffff8000107a3a18)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a8cbc)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/base/power/domain.c (ffff800010907f80)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/arch_topology.c (ffff800010920008)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
```
```
In drivers/opp/cpu.c (ffff800010b1aec0)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b216b8)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffff800010b24180)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/firmware/efi/arm-runtime.c (ffff8000114a78cc)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b99068)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe
```
```
In net/core/sysctl_net_core.c (ffff800010bc59a0)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/net-sysfs.c (ffff800010c0b96c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
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
In arch/arm/mm/context.c (c03224f4)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
```
```
In arch/arm/common/bL_switcher.c (c03277a8)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus
```
```
In kernel/fork.c (c0350b1c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (c0358104)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In kernel/sched/rt.c (c151f234)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (c151f290)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/cpupri.c (c03a6dfc)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (c03a7534)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/topology.c (c03a7ab8)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In kernel/irq/irqdesc.c (c03c93c0)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/proc.c (0)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In kernel/irq/affinity.c (c03d6c04)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/time/tick-broadcast.c (c15231ec)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
```
```
In kernel/smp.c (c0405538)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/cgroup/cpuset.c (c04251d0)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (c04465f8)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/ring_buffer.c (c04575e8)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (c0465504)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/trace_hwlat.c (c046d604)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (c152bd34)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/swap.c (c04ee20c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/slub.c (c054a164)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (c079e224)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/cpu_rmap.c (c080b4dc)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/soc/qcom/spm.c (0)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In drivers/base/power/domain.c (c09f2454)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/arch_topology.c (c0a05058)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
```
```
In drivers/opp/cpu.c (c0bf5944)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (c0bfbcf8)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In drivers/firmware/efi/arm-runtime.c (c15aa044)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:404
Inline: True
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
In arch/powerpc/kernel/setup-common.c (c00000000134a4f4)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
```
```
In arch/powerpc/kernel/smp.c (c000000001350750)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi
```
```
In arch/powerpc/mm/book3s64/radix_tlb.c (c000000000095e3c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:exit_flush_lazy_tlbs
```
```
In arch/powerpc/mm/numa.c (c0000000000a34c4)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000be434)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_pick_irq_target
```
```
In arch/powerpc/platforms/powernv/idle.c (c0000000000c78c0)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (c0000000000dfd20)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000f9f3c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
```
```
In kernel/fork.c (c00000000013736c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (c000000000140fa0)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/workqueue.c (c00000000016d1d4)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/core.c (c00000000018aee4)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/core.c:__do_sys_sched_setaffinity
```
```
In kernel/sched/fair.c (c0000000013699a0)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
```
```
In kernel/sched/rt.c (c000000001369a0c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (c000000001369abc)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/cpupri.c (c0000000001ae2e4)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (c0000000001aeb6c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/topology.c (c0000000001b1d68)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/membarrier.c (c0000000001bd270)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/irq/irqdesc.c (c0000000001d107c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/proc.c (c0000000001dfc28)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (c0000000001e1f24)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (c00000000136e56c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (c000000000223c2c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/cgroup/cpuset.c (c00000000025438c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (c000000000283fc4)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/ring_buffer.c (c00000000029d434)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (c0000000002ae598)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/trace_hwlat.c (c0000000002bc434)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (c000000001378cb4)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/swap.c (c00000000037d4ac)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/slub.c (c000000000422da8)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (c0000000007891fc)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/cpu_rmap.c (c0000000008169dc)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/base/power/domain.c (c0000000009a7b00)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/opp/cpu.c (c000000000c0cf50)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (c000000000c15634)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (c000000000c189e4)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In net/core/sysctl_net_core.c (c000000000ca0574)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/net-sysfs.c (c000000000cf6a04)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
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
In arch/riscv/kernel/smp.c (ffffffe0000b7c48)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/riscv/kernel/smp.c:riscv_cpuid_to_hartid_mask
```
```
In kernel/fork.c (ffffffe0000bec4c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In kernel/sched/core.c (ffffffe0000ebf8c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setaffinity
```
```
In kernel/sched/fair.c (0)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In kernel/sched/rt.c (ffffffe000006eee)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffe000006f70)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/cpupri.c (ffffffe0000ffa98)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffe00010010c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/topology.c (ffffffe000100214)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In kernel/irq/irqdesc.c (ffffffe0001124f0)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In kernel/irq/affinity.c (ffffffe00011d99c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/smp.c (ffffffe000140a04)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/cgroup/cpuset.c (ffffffe00015a40a)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
```
```
In kernel/watchdog.c (ffffffe000169f98)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/ring_buffer.c (ffffffe000177e3a)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffe0001827f2)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In mm/slub.c (ffffffe000238b00)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffe000430a16)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In drivers/base/power/domain.c (ffffffe00058daf8)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/arch_topology.c (ffffffe00059ed4a)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
```
```
In drivers/opp/cpu.c (ffffffe0007032b8)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/cpumask.h:404
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/cpumask.h:404
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
In arch/x86/xen/mmu_pv.c (ffffffff81025c99)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105cca6)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064763)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
```
In arch/x86/mm/tlb.c (ffffffff81088131)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828b2d4e)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096ce7)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff8109e0b7)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810cdc20)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff810f114d)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (ffffffff8110e42e)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff8111899c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff8113fcff)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff81147438)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff81169338)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff81188576)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff81188d59)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff811a3737)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811abf74)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/swap.c (ffffffff8122b648)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/slub.c (ffffffff8129ccda)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff814eb4e7)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In drivers/acpi/processor_throttling.c (ffffffff81605de6)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81607926)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816098c0)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/opp/cpu.c (ffffffff8186454d)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8186a83e)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8186cee0)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff818c94ca)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104ce76)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054a53)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
```
In arch/x86/mm/tlb.c (ffffffff81076d91)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828aaecf)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81085767)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff8108cad7)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810bc4b0)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff810e11bd)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (ffffffff810ff18e)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff81109a0c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff81132a7f)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/time/tick-sched.c (ffffffff828b25da)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_init
```
```
In kernel/smp.c (ffffffff8113a713)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff8115c53c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff8117b6b6)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff8117be99)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff81196707)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119ee64)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/swap.c (ffffffff8121e738)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/slub.c (ffffffff8128e86a)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff814dba37)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In drivers/acpi/processor_throttling.c (ffffffff815f0eb6)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff815f2a26)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fb500)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/opp/cpu.c (ffffffff8182d1fd)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818334ee)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81835c60)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/hv/channel_mgmt.c (ffffffff81852bfe)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:init_vp_index
  - drivers/hv/channel_mgmt.c:init_vp_index
```
```
In net/core/sysctl_net_core.c (ffffffff8188340a)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
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
In arch/x86/xen/mmu_pv.c (ffffffff81025af9)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d0d6)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064c13)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
```
In arch/x86/mm/tlb.c (ffffffff810880e1)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c5c4d)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096c97)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff8109e067)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810cd090)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff810ee27d)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (ffffffff8110c31e)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff8111688c)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff8113dbaf)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff811452e8)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff81167108)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff81186346)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff81186b29)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff811a1507)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811a9d44)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/swap.c (ffffffff812293e8)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/slub.c (ffffffff8129aaea)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff814e7577)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In drivers/acpi/processor_throttling.c (ffffffff8162abe6)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff8162cb56)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81631cd0)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/opp/cpu.c (ffffffff818b52dd)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818bb5ce)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818bdc70)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff8191a4ca)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
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
In arch/x86/xen/mmu_pv.c (ffffffff810265eb)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e5f6)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff810661f3)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
```
In arch/x86/mm/tlb.c (ffffffff8108a368)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c8df3)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81096ed9)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:reset_with_ipi
```
```
In kernel/fork.c (ffffffff8109eb37)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff810a5f88)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810d5a20)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/topology.c (ffffffff810f92bd)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (ffffffff81117a4e)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff81121ecc)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff8114a6bf)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff81151ec8)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff811746e9)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff81193c96)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff81194479)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff811af297)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b7b84)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/swap.c (ffffffff812387f8)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/slub.c (ffffffff812aa9ca)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff81500517)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In drivers/acpi/processor_throttling.c (ffffffff81644a86)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff816469f6)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164c000)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/opp/cpu.c (ffffffff818d158d)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818d78be)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818d9f80)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff8193b70a)
Location: include/linux/cpumask.h:404
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
</details>
</li>
</ul>

## Differences
