# Function: <code>cpumask_set_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cpumask_set_cpu(unsigned int cpu, struct cpumask *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff8100864b)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/events/amd/iommu.c (ffffffff81f5dcb0)
Location: include/linux/cpumask.h:270
Inline: True
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100ec14)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_cpu_notifier
  - arch/x86/events/intel/cqm.c:intel_cqm_cpu_notifier
```
```
In arch/x86/events/intel/cstate.c (ffffffff8100f172)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
  - arch/x86/events/intel/cstate.c:cstate_cpu_notifier
```
```
In arch/x86/events/intel/rapl.c (ffffffff81014f29)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - arch/x86/events/intel/rapl.c:rapl_cpu_init
  - arch/x86/events/intel/rapl.c:rapl_cpu_notifier
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015e29)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_cpu_notifier
```
```
In arch/x86/xen/mmu.c (ffffffff810207d5)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
```
```
In arch/x86/xen/smp.c (ffffffff8102b74f)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In arch/x86/kernel/process.c (ffffffff81038f76)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:amd_e400_idle
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f54c)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810463d3)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create
```
```
In arch/x86/kernel/smpboot.c (ffffffff81050e80)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:native_cpu_up
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059e9f)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/numa.c (ffffffff81074c0f)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In kernel/cpu.c (ffffffff81081c04)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:set_cpu_possible
  - kernel/cpu.c:set_cpu_present
  - kernel/cpu.c:set_cpu_online
  - kernel/cpu.c:set_cpu_online
  - kernel/cpu.c:set_cpu_active
```
```
In kernel/workqueue.c (ffffffff81f7c730)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
```
```
In kernel/sched/core.c (ffffffff810a4e30)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_domains_numa_masks_update
  - kernel/sched/core.c:rq_attach_root
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/sched/fair.c (ffffffff810be5a6)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810bf404)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffffffff810c1aec)
Location: include/linux/cpumask.h:270
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810c41ed)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810c45b7)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
```
```
In kernel/irq/chip.c (ffffffff810de2e4)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/profile.c (ffffffff810ea7be)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - kernel/profile.c:profile_cpu_callback
```
```
In kernel/time/tick-broadcast.c (ffffffff810fcf62)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/smp.c (ffffffff8110400b)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond
```
```
In kernel/trace/ring_buffer.c (ffffffff8114a07f)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_cpu_notify
```
```
In kernel/trace/trace.c (ffffffff81150f23)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/padata.c (ffffffff8118a96e)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - kernel/padata.c:padata_add_cpu
  - kernel/padata.c:padata_add_cpu
```
```
In mm/page_alloc.c (ffffffff81192bf0)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/swap.c (ffffffff8119e2f0)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/vmstat.c (ffffffff811ad8d6)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpuup_callback
  - mm/vmstat.c:vmstat_cpuup_callback
```
```
In mm/mmu_context.c (ffffffff811afc6a)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/slub.c (ffffffff811e9459)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In fs/exec.c (ffffffff8121378a)
Location: include/linux/cpumask.h:270
Inline: True
```
```
In block/blk-mq.c (ffffffff813c4301)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In block/blk-mq-cpumap.c (ffffffff813c8663)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
```
```
In lib/percpu_ida.c (ffffffff813ff7e6)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_free
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/cpu_rmap.c (ffffffff81415e28)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/processor_throttling.c (ffffffff814ad757)
Location: include/linux/cpumask.h:270
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
```
```
In drivers/acpi/processor_perflib.c (ffffffff814aebb7)
Location: include/linux/cpumask.h:270
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff814c2ff0)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/base/cacheinfo.c (ffffffff815526ea)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:detect_cache_attributes
  - drivers/base/cacheinfo.c:detect_cache_attributes
  - drivers/base/cacheinfo.c:detect_cache_attributes
  - drivers/base/cacheinfo.c:cache_add_dev
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816b18d5)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff816b6a81)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff816b9840)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff816baab6)
Location: include/linux/cpumask.h:270
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff81713361)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/flow.c (ffffffff81735238)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/core/net-sysfs.c (ffffffff81736486)
Location: include/linux/cpumask.h:270
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_xps_map
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff81050e80-ffffffff81050e8d: cpumask_set_cpu (STB_LOCAL)
ffffffff810a4e30-ffffffff810a4e3d: cpumask_set_cpu (STB_LOCAL)
ffffffff814ad757-ffffffff814ad764: cpumask_set_cpu (STB_LOCAL)
ffffffff814aebb7-ffffffff814aebc4: cpumask_set_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cpumask_set_cpu(unsigned int cpu, struct cpumask *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff810085a6)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/events/amd/iommu.c (ffffffff81f85b7e)
Location: include/linux/cpumask.h:274
Inline: True
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100eeeb)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_cpu_starting
```
```
In arch/x86/events/intel/uncore.c (ffffffff810153fe)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/xen/mmu.c (ffffffff810207c0)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
```
```
In arch/x86/xen/smp.c (ffffffff8102aa5f)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/xen/smp.c:cpu_bringup
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_init
```
```
In arch/x86/kernel/process.c (ffffffff81037fb0)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:amd_e400_idle
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f356)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104641e)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:274
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff81f97c2a)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:start_secondary
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81054709)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a180)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/tlb.c (ffffffff8107244c)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff8107620f)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In kernel/cpu.c (ffffffff81084d5b)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/cpu.c:disable_nonboot_cpus
Direct callers:
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/workqueue.c (ffffffff81fa54f7)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
```
```
In kernel/sched/core.c (ffffffff81fa6e74)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:rq_attach_root
```
```
In kernel/sched/fair.c (ffffffff810c1d8f)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810c2d0e)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffffffff810c564c)
Location: include/linux/cpumask.h:274
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810c7ed8)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810c84b6)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/irq/irqdesc.c (ffffffff81fa7f54)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff810e3c34)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffffffff810e8ece)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_mask
```
```
In kernel/profile.c (ffffffff810f1526)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff811049ab)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/smp.c (ffffffff8110b41b)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond
```
```
In kernel/trace/ring_buffer.c (ffffffff81150a71)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_cpu_notify
```
```
In kernel/trace/trace.c (ffffffff81159f80)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
```
```
In mm/page_alloc.c (ffffffff811a8ab0)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/swap.c (ffffffff811b3cce)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/slub.c (ffffffff81207cee)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff8140842a)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In block/blk-mq-cpumap.c (ffffffff8140c8c3)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
```
```
In lib/percpu_ida.c (ffffffff81446ed6)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_free
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/cpu_rmap.c (ffffffff8145dc68)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/processor_throttling.c (ffffffff814fd0a6)
Location: include/linux/cpumask.h:274
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff814fe580)
Location: include/linux/cpumask.h:274
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81513560)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81514d52)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cacheinfo.c (ffffffff815a4860)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/cacheinfo.c:detect_cache_attributes
  - drivers/base/cacheinfo.c:detect_cache_attributes
  - drivers/base/cacheinfo.c:detect_cache_attributes
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81713a61)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8171835e)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff8171b20a)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8171c8ea)
Location: include/linux/cpumask.h:274
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff8177afcd)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/flow.c (ffffffff817a13c1)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/core/net-sysfs.c (ffffffff817a2634)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_xps_map
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff8102a020-ffffffff8102a02d: cpumask_set_cpu (STB_LOCAL)
ffffffff81051030-ffffffff8105103d: cpumask_set_cpu (STB_LOCAL)
ffffffff81082fb0-ffffffff81082fbd: cpumask_set_cpu (STB_LOCAL)
ffffffff814fd0a6-ffffffff814fd0b3: cpumask_set_cpu (STB_LOCAL)
ffffffff814fe580-ffffffff814fe58d: cpumask_set_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cpumask_set_cpu(unsigned int cpu, struct cpumask *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff810085cd)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/events/amd/iommu.c (ffffffff81fc0fbb)
Location: include/linux/cpumask.h:274
Inline: True
```
```
In arch/x86/events/intel/cqm.c (ffffffff8100efaf)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_cpu_starting
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101590f)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/xen/mmu.c (ffffffff81020fb3)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
```
```
In arch/x86/xen/smp.c (ffffffff8102abf1)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/xen/smp.c:cpu_bringup
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_init
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:274
Inline: False
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103ed62)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81043276)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043e78)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
```
```
In arch/x86/kernel/cpu/intel_rdt_schemata.c (ffffffff81044d2f)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_write
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81048163)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:274
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff81fd313c)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:start_secondary
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810573f1)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__generic_processor_info
  - arch/x86/kernel/apic/apic.c:__generic_processor_info
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105ced3)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/tlb.c (ffffffff81075fda)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff81079dff)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In kernel/cpu.c (ffffffff81089ce0)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/workqueue.c (ffffffff81fe0cf3)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/core.c (ffffffff81fe2a13)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:rq_attach_root
```
```
In kernel/sched/fair.c (ffffffff810c7d9f)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810c8d62)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffffffff810cb638)
Location: include/linux/cpumask.h:274
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810cdec8)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810ce4b6)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/irq/irqdesc.c (ffffffff81fe3cc2)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff810ea764)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffffffff810efcb8)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff810f7eb5)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8110c0f4)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/smp.c (ffffffff81112dab)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond
```
```
In kernel/trace/ring_buffer.c (ffffffff8115d1f9)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff8116479e)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_hwlat.c (ffffffff8116d831)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/page_alloc.c (ffffffff811b9052)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/swap.c (ffffffff811c4357)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/slub.c (ffffffff81219d23)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff814242b1)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_queue_reinit_prepare
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In block/blk-mq-cpumap.c (ffffffff81427c0b)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In lib/percpu_ida.c (ffffffff814656d9)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_free
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/cpu_rmap.c (ffffffff8147c724)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/processor_throttling.c (ffffffff8151fd28)
Location: include/linux/cpumask.h:274
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff81521274)
Location: include/linux/cpumask.h:274
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81525146)
Location: include/linux/cpumask.h:274
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8153f979)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/cpu_hotplug.c (ffffffff815411e2)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cacheinfo.c (ffffffff815d2edd)
Location: include/linux/cpumask.h:274
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817458f0)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8174a076)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff8174cffa)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8174f0b0)
Location: include/linux/cpumask.h:274
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff817a860f)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/flow.c (ffffffff817cfce4)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/core/net-sysfs.c (ffffffff817d1021)
Location: include/linux/cpumask.h:274
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_xps_map
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff8102a770-ffffffff8102a77d: cpumask_set_cpu (STB_LOCAL)
ffffffff81053940-ffffffff8105394d: cpumask_set_cpu (STB_LOCAL)
ffffffff81087a40-ffffffff81087a4d: cpumask_set_cpu (STB_LOCAL)
ffffffff8151fd28-ffffffff8151fd35: cpumask_set_cpu (STB_LOCAL)
ffffffff81521274-ffffffff81521281: cpumask_set_cpu (STB_LOCAL)
ffffffff81525146-ffffffff81525153: cpumask_set_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cpumask_set_cpu(unsigned int cpu, struct cpumask *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff81008287)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/events/amd/iommu.c (ffffffff820a1341)
Location: include/linux/cpumask.h:291
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81013df5)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810220a2)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/xen/smp_pv.c (ffffffff810294b1)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:cpu_bringup
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:291
Inline: False
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103cd2f)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81041585)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81042e40)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
```
```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff81044dbe)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81047a44)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:291
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff820b3dca)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:start_secondary
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056b36)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c363)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid
```
```
In arch/x86/mm/tlb.c (ffffffff810746e0)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff810786af)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In kernel/cpu.c (ffffffff81086b9c)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/workqueue.c (ffffffff820c197a)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/core.c (ffffffff810b3bc6)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/sched/fair.c (ffffffff810c1a3f)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810c2e28)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffffffff810c57a1)
Location: include/linux/cpumask.h:291
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810ca83a)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810cadb6)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810ccc87)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/irqdesc.c (ffffffff820c47bb)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff810e9e54)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffffffff810efc92)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff810f9ef5)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8110e4a4)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/smp.c (ffffffff811142ba)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond
```
```
In kernel/trace/ring_buffer.c (ffffffff811601f9)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff81167ada)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_hwlat.c (ffffffff811709f8)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (ffffffff811ae084)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/page_alloc.c (ffffffff811c0fa6)
Location: include/linux/cpumask.h:291
Inline: True
```
```
In mm/swap.c (ffffffff811cc753)
Location: include/linux/cpumask.h:291
Inline: True
```
```
In mm/slub.c (ffffffff81225a8b)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff81432a85)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/percpu_ida.c (ffffffff8146aa79)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_free
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/cpu_rmap.c (ffffffff81485a84)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/processor_throttling.c (ffffffff81532015)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff815333a2)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81537f70)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8155371a)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81555068)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cacheinfo.c (ffffffff815e7a54)
Location: include/linux/cpumask.h:291
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81763fe7)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81768696)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff8176b678)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8176d5c5)
Location: include/linux/cpumask.h:291
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff817c6c51)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/flow.c (ffffffff817ef0e3)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/core/net-sysfs.c (ffffffff817f01ec)
Location: include/linux/cpumask.h:291
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_xps_map
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff81029150-ffffffff8102915d: cpumask_set_cpu (STB_LOCAL)
ffffffff810532a0-ffffffff810532ad: cpumask_set_cpu (STB_LOCAL)
ffffffff810849f0-ffffffff810849fd: cpumask_set_cpu (STB_LOCAL)
ffffffff810aad50-ffffffff810aad5d: cpumask_set_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cpumask_set_cpu(unsigned int cpu, struct cpumask *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff810088f5)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/events/amd/iommu.c (ffffffff826a747b)
Location: include/linux/cpumask.h:295
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014740)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81022b76)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/xen/smp_pv.c (ffffffff810296d1)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:cpu_bringup
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:295
Inline: False
```
```
In arch/x86/kernel/cpu/intel_cacheinfo.c (ffffffff8103f6dc)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810449e5)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810462e0)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
```
```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff81048691)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104b50a)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:295
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff826ba607)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:start_secondary
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105a89f)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810602b6)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/tlb.c (ffffffff8107a45c)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff8107ea0f)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In kernel/cpu.c (ffffffff8108d943)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/workqueue.c (ffffffff826c9b62)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/core.c (ffffffff810bae66)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810c91aa)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810ca5bb)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffffffff810cced1)
Location: include/linux/cpumask.h:295
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810d204a)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810d2556)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810d3be7)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/sched/isolation.c (ffffffff826cbc73)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff826cca54)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff810f23ab)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffffffff810f886b)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff81104872)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff81119724)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/smp.c (ffffffff8111f81f)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond
```
```
In kernel/watchdog_hld.c (ffffffff8115be5a)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ring_buffer.c (ffffffff8116d2be)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff81174a5d)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_hwlat.c (ffffffff8117dbc0)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (ffffffff811c1be4)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/page_alloc.c (ffffffff811d5591)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/swap.c (ffffffff811e1787)
Location: include/linux/cpumask.h:295
Inline: True
```
```
In mm/slub.c (ffffffff8124111b)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff8145e654)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/percpu_ida.c (ffffffff81496d59)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_free
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/cpu_rmap.c (ffffffff814c1ba3)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/processor_throttling.c (ffffffff81593738)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff81594aaf)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81599743)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815b709a)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/cpu_hotplug.c (ffffffff815b8bd8)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cacheinfo.c (ffffffff8164edac)
Location: include/linux/cpumask.h:295
Inline: True
```
```
In drivers/opp/cpu.c (ffffffff817d6003)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817d9fdd)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817de586)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff817e1556)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/sysctl_net_core.c (ffffffff81840843)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/net-sysfs.c (ffffffff8186b7ff)
Location: include/linux/cpumask.h:295
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff81029360-ffffffff8102936d: cpumask_set_cpu (STB_LOCAL)
ffffffff81057050-ffffffff8105705d: cpumask_set_cpu (STB_LOCAL)
ffffffff8108b4b0-ffffffff8108b4bd: cpumask_set_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cpumask_set_cpu(unsigned int cpu, struct cpumask *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff810097e0)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/events/amd/iommu.c (ffffffff826d061a)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015202)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023465)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a151)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:cpu_bringup
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102bf40)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:297
Inline: False
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81040cdf)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81046c61)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81048237)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff8104af6b)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_write
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104de4c)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:297
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff826e43cd)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:start_secondary
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105d794)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81063396)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/tlb.c (ffffffff8107d1fc)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff81081b4c)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In kernel/cpu.c (ffffffff810917a4)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/workqueue.c (ffffffff826f3d47)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/core.c (ffffffff810c2346)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810d139f)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810d2d24)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffffffff810d4e04)
Location: include/linux/cpumask.h:297
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810da0d4)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810da635)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810db894)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/sched/isolation.c (ffffffff826f5ddc)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff826f6c43)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff810fa7f7)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffffffff81100d00)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff8110f5f1)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff811263b7)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/smp.c (ffffffff8112cb5f)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond
```
```
In kernel/watchdog_hld.c (ffffffff8116a9ca)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ring_buffer.c (ffffffff8117c30e)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff81183abc)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_hwlat.c (ffffffff8118ca0a)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (ffffffff811e1f74)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/page_alloc.c (ffffffff811f69e1)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/swap.c (ffffffff81202ebe)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/slub.c (ffffffff812640c2)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff81491f74)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/percpu_ida.c (ffffffff814cbf55)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_free
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/cpu_rmap.c (ffffffff814f2ae3)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/processor_throttling.c (ffffffff815caa02)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff815cbf81)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d0fa3)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815ef599)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/cpu_hotplug.c (ffffffff815f1168)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cacheinfo.c (ffffffff8168a547)
Location: include/linux/cpumask.h:297
Inline: True
```
```
In drivers/opp/cpu.c (ffffffff8181ecdf)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81822b2b)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818272eb)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff8182a256)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/sysctl_net_core.c (ffffffff8188aea2)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/net-sysfs.c (ffffffff818bbf6d)
Location: include/linux/cpumask.h:297
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff81029dc0-ffffffff81029dcd: cpumask_set_cpu (STB_LOCAL)
ffffffff81059ec0-ffffffff81059ecd: cpumask_set_cpu (STB_LOCAL)
ffffffff8108ed20-ffffffff8108ed2d: cpumask_set_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cpumask_set_cpu(unsigned int cpu, struct cpumask *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff81008f30)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/events/amd/iommu.c (ffffffff828866d9)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015802)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81022f0c)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a7a1)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
  - arch/x86/xen/smp_pv.c:cpu_bringup
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102cf40)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:309
Inline: False
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810422f5)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104b537)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81055c6a)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81057c17)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105b376)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:309
Inline: False
```
```
In arch/x86/kernel/smpboot.c (ffffffff8289ae92)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:start_secondary
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81063424)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81069096)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/tlb.c (ffffffff81083c27)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff8108875c)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In kernel/cpu.c (ffffffff81099a84)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/workqueue.c (ffffffff828aab2f)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/core.c (ffffffff810cb65c)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810dacbf)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810dc5f4)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffffffff810de7b4)
Location: include/linux/cpumask.h:309
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810e3c24)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810e4185)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810e548f)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/sched/isolation.c (ffffffff828acc26)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff828adb68)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff81105fb7)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffffffff8110c4d6)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff8111ac31)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff81131a97)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/watchdog_hld.c (ffffffff811779da)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ring_buffer.c (ffffffff81189b0e)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff81191417)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119a51a)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (ffffffff811f23e4)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/page_alloc.c (ffffffff81208d75)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/swap.c (ffffffff8121585e)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/slub.c (ffffffff81278832)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff814aba48)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/cpu_rmap.c (ffffffff81506e13)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/processor_throttling.c (ffffffff815e3fe2)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff815e5561)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815ea5d3)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8160bd8e)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cacheinfo.c (ffffffff816a9a47)
Location: include/linux/cpumask.h:309
Inline: True
```
```
In drivers/opp/cpu.c (ffffffff8184ab52)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8184ea0b)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818531eb)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81856126)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/sysctl_net_core.c (ffffffff818abee2)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/net-sysfs.c (ffffffff818e32ff)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
```
**Symbols:**

```
ffffffff8102a3a0-ffffffff8102a3ad: cpumask_set_cpu (STB_LOCAL)
ffffffff8105fb40-ffffffff8105fb4d: cpumask_set_cpu (STB_LOCAL)
ffffffff81097020-ffffffff8109702d: cpumask_set_cpu (STB_LOCAL)
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
In arch/x86/events/amd/uncore.c (ffffffff810093ce)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/events/amd/iommu.c (ffffffff8289d655)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016ab9)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810255d3)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/xen/smp_pv.c (ffffffff828a5689)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102ecf1)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/cpumask.h:309
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81044950)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e45f)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058edd)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ae8e)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105e6e6)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:309
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b321c)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066abd)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106c8b6)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/tlb.c (ffffffff810878d3)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff8108c38c)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In kernel/cpu.c (ffffffff828c2739)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/workqueue.c (ffffffff828c3326)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/core.c (ffffffff810d366d)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810e2088)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810e3594)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffffffff810e5884)
Location: include/linux/cpumask.h:309
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810ea83b)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810ead85)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810ec467)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/irqdesc.c (ffffffff828c65be)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff8110f457)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffffffff81115c64)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff81125325)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8113c61a)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/watchdog_hld.c (ffffffff8118483a)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ring_buffer.c (ffffffff811970e8)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff8119edd6)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_hwlat.c (ffffffff811a817f)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (ffffffff81209fd1)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/swap.c (ffffffff81225252)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (ffffffff812700c0)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/slub.c (ffffffff8129492f)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff814d9c1c)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/cpu_rmap.c (ffffffff81535030)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/processor_throttling.c (ffffffff81615b8d)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81617158)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161c35c)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8163fc60)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff828fef48)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/base/cacheinfo.c (ffffffff816e3085)
Location: include/linux/cpumask.h:309
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff816f1c86)
Location: include/linux/cpumask.h:309
Inline: True
```
```
In drivers/opp/cpu.c (ffffffff8188dcc4)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81891bda)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818967c1)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff818997bb)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/sysctl_net_core.c (ffffffff818f77a0)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/net-sysfs.c (ffffffff81933661)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
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
In arch/x86/events/amd/uncore.c (ffffffff810097ce)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/events/amd/iommu.c (ffffffff828a06c4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017469)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025bb3)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/xen/smp_pv.c (ffffffff828a871c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f601)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff810450a0)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104edff)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810597ad)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b77e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105ef66)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b6673)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106712d)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e006)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/tlb.c (ffffffff810885c3)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff8108cfec)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff810959a2)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:reset_with_ipi
```
```
In kernel/cpu.c (ffffffff828cad8c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:notify_cpu_starting
```
```
In kernel/workqueue.c (ffffffff828cb909)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/core.c (ffffffff810ddbdd)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810ebf88)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810edf6c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffffffff810f0ca4)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810f620b)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810f6755)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810f7f2a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/irqdesc.c (ffffffff828cebeb)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff8111b717)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffffffff81122052)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff811312e5)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8114822a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/watchdog_hld.c (ffffffff811906ba)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ring_buffer.c (ffffffff811a2ae8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff811aa796)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b397f)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (ffffffff81217341)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/swap.c (ffffffff812330d6)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (ffffffff8127ef00)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/slub.c (ffffffff812a46ff)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff814f2fcb)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/cpu_rmap.c (ffffffff81555e40)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/processor_throttling.c (ffffffff8163707d)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff816386b8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163ddfc)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81662220)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff829080eb)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/base/cacheinfo.c (ffffffff81707235)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff81716406)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/opp/cpu.c (ffffffff818bfe54)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c3bf9)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818c87d1)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff818cb7ab)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/sysctl_net_core.c (ffffffff81929520)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/net-sysfs.c (ffffffff819661a1)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
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
In arch/x86/events/amd/uncore.c (ffffffff8100a87e)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/events/amd/iommu.c (ffffffff82cc6947)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff810188ab)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025f55)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ee25)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:set_cpu_possible
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048c6e)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105303e)
Location: include/linux/cpumask.h:332
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105ee26)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810604f9)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81064ac6)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:332
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff82cdb75b)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:smp_callin
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106dd00)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810754b6)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/tlb.c (ffffffff8108afd5)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff8109462c)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109aaa0)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:reset_with_ipi
```
```
In kernel/cpu.c (ffffffff82ced1a9)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:notify_cpu_starting
```
```
In kernel/workqueue.c (ffffffff82ced8be)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/core.c (ffffffff810e639d)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810f6798)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810f81e4)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffffffff810f9ea8)
Location: include/linux/cpumask.h:332
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810ffb5b)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff811000e5)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff81102831)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_balance_mask
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/irqdesc.c (ffffffff82cf009d)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff811279c7)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffffffff8112e549)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_spread_init_one
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/profile.c (ffffffff811406b5)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8115806a)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/watchdog_hld.c (ffffffff811a525a)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ring_buffer.c (ffffffff811b96c8)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff811baf85)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_fmt
```
```
In kernel/trace/trace_hwlat.c (ffffffff811cc411)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/events/core.c (ffffffff81242d52)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/swap.c (ffffffff81260710)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (ffffffff812b10d0)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/slub.c (ffffffff812d8e8f)
Location: include/linux/cpumask.h:332
Inline: True
```
```
In block/blk-mq.c (ffffffff81553667)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/cpu_rmap.c (ffffffff815df7b4)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e3fc1)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff816e5418)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816eb1af)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81711626)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:enable_hotplug_cpu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff82d1e8c0)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/base/cacheinfo.c (ffffffff817c215e)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
```
```
In drivers/base/power/domain.c (ffffffff817d2036)
Location: include/linux/cpumask.h:332
Inline: True
```
```
In drivers/opp/cpu.c (ffffffff81991bb4)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81994ff2)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_policy_cpu
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199aa21)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff8199db4b)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/sysctl_net_core.c (ffffffff819fd4b0)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/net-sysfs.c (ffffffff81a38b30)
Location: include/linux/cpumask.h:332
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
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
In arch/x86/events/amd/uncore.c (ffffffff810096de)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/events/amd/iommu.c (ffffffff82fb2364)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff81018f7b)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026795)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102fc42)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:set_cpu_possible
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81048158)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105218e)
Location: include/linux/cpumask.h:338
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d366)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ed59)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81062cce)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:338
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff82fc7bb1)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:smp_callin
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106f4a0)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075b38)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/tlb.c (ffffffff8108b0e3)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff81093a2c)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In kernel/cpu.c (ffffffff82fd9803)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:notify_cpu_starting
```
```
In kernel/workqueue.c (ffffffff82fd9f18)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/core.c (ffffffff810e4205)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810f4928)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810f63f4)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffffffff810f8268)
Location: include/linux/cpumask.h:338
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810fe634)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810fec45)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff81101451)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_balance_mask
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/irqdesc.c (ffffffff82fdca88)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff811235c7)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffffffff8112a139)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_spread_init_one
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/profile.c (ffffffff8113ca25)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8115415a)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/watchdog_hld.c (ffffffff811a2250)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ring_buffer.c (ffffffff811b71b8)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff811b8b28)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_fmt
```
```
In kernel/trace/trace_hwlat.c (ffffffff811c9a6c)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/events/core.c (ffffffff8124d4a2)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/page_alloc.c (ffffffff812b9d92)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - mm/page_alloc.c:__drain_all_pages
```
```
In mm/slub.c (ffffffff812e447f)
Location: include/linux/cpumask.h:338
Inline: True
```
```
In block/blk-mq.c (ffffffff8156fd1a)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/cpu_rmap.c (ffffffff815fcf54)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/processor_throttling.c (ffffffff81701c11)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81702efd)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff817088bf)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8172e356)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:enable_hotplug_cpu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff8300c6c1)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/base/cacheinfo.c (ffffffff817d737e)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
```
```
In drivers/base/power/domain.c (ffffffff817e6846)
Location: include/linux/cpumask.h:338
Inline: True
```
```
In drivers/opp/cpu.c (ffffffff81994e94)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff819990c2)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_policy_cpu
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199db04)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff819a073b)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/sysctl_net_core.c (ffffffff819fd0f4)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81a047c0)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/net-sysfs.c (ffffffff81a3b258)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
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
In arch/x86/events/amd/uncore.c (ffffffff8100a0b6)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/events/amd/iommu.c (ffffffff831bc53b)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/core.c (ffffffff8100e017)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101a29b)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028415)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/xen/smp_pv.c (ffffffff81030752)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:set_cpu_possible
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81049c79)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105384e)
Location: include/linux/cpumask.h:309
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105dc96)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f5d8)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8106339e)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:309
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff831d2511)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106ffd0)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810765db)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/tlb.c (ffffffff8108bc50)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff810943ec)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In kernel/cpu.c (ffffffff831e4157)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
```
```
In kernel/workqueue.c (ffffffff831e48b8)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/core.c (ffffffff810e61dd)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810f699a)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810f8414)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffffffff810fa3d8)
Location: include/linux/cpumask.h:309
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff81100a19)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff81101025)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff811037e1)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/irqdesc.c (ffffffff831e7799)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff81123927)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffffffff8112a3b9)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_spread_init_one
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/profile.c (ffffffff8113dc75)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/clocksource.c (ffffffff81149819)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_percpu
  - kernel/time/clocksource.c:clocksource_verify_percpu
```
```
In kernel/time/tick-broadcast.c (ffffffff811555ce)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/watchdog_hld.c (ffffffff811a2f10)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ring_buffer.c (ffffffff811b7c6b)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff811b93d8)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_fmt
```
```
In kernel/trace/trace_hwlat.c (ffffffff811cae53)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/events/core.c (ffffffff81251da1)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/page_alloc.c (ffffffff812bee08)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - mm/page_alloc.c:__drain_all_pages
```
```
In mm/slub.c (ffffffff812eb684)
Location: include/linux/cpumask.h:309
Inline: True
```
```
In block/blk-mq.c (ffffffff81577bd5)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/cpu_rmap.c (ffffffff815dfcc8)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e34a6)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff816e47b4)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816e9ebe)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81712183)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff832174a5)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/base/cacheinfo.c (ffffffff817bada6)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
```
```
In drivers/base/power/domain.c (ffffffff817cac45)
Location: include/linux/cpumask.h:309
Inline: True
```
```
In drivers/opp/cpu.c (ffffffff81979dd4)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197db73)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff819826c6)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff8198536f)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/sysctl_net_core.c (ffffffff819e3964)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff819ebfd7)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/net-sysfs.c (ffffffff81a21a2b)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_rps_map
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
In arch/x86/events/amd/iommu.c (ffffffff8329c839)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/core.c (ffffffff8100e7a4)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101cb87)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102ca8e)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/xen/smp_pv.c (ffffffff81035622)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:set_cpu_possible
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81050312)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105bfaa)
Location: include/linux/cpumask.h:309
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810673b6)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81069e28)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8106d335)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:309
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff832b4d4d)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107ba40)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81083c62)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/tlb.c (ffffffff8109b243)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff810a42e1)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In kernel/cpu.c (ffffffff832c7d34)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/workqueue.c (ffffffff832c85f4)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/core.c (ffffffff810fd5d5)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff811108c6)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff81113974)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffffffff81115247)
Location: include/linux/cpumask.h:309
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff8111cab8)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff8111d1c5)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff811207bf)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/irqdesc.c (ffffffff832cb88b)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff81143ef7)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffffffff8114ad29)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_spread_init_one
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/profile.c (ffffffff81160e45)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/hrtimer.c (ffffffff81167e98)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/clocksource.c (ffffffff8116d7ec)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff81179646)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/watchdog_hld.c (ffffffff811cc740)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ring_buffer.c (ffffffff811e1eab)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff811e3c71)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_fmt
```
```
In kernel/trace/trace_hwlat.c (ffffffff811f6e65)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/events/core.c (ffffffff8128d5d4)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/page_alloc.c (ffffffff81301965)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - mm/page_alloc.c:__drain_all_pages
```
```
In mm/slub.c (ffffffff81333d54)
Location: include/linux/cpumask.h:309
Inline: True
```
```
In fs/io-wq.c (ffffffff81cc5f58)
Location: include/linux/cpumask.h:309
Inline: True
```
```
In block/blk-mq.c (ffffffff815dc94b)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/cpu_rmap.c (ffffffff8164b909)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/processor_throttling.c (ffffffff8175bf1b)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff8175d4f4)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff817637af)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8178ebf3)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff83300eb7)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/base/cacheinfo.c (ffffffff81844dd9)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
```
```
In drivers/base/power/domain.c (ffffffff81854d15)
Location: include/linux/cpumask.h:309
Inline: True
```
```
In drivers/opp/cpu.c (ffffffff81a22de4)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a26c20)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81a2bb63)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81a2ee4f)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/sysctl_net_core.c (ffffffff81a93f15)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81a9cf84)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/net-sysfs.c (ffffffff81ad5f0c)
Location: include/linux/cpumask.h:309
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_rps_map
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
In arch/x86/events/amd/iommu.c (ffffffff8344b2e8)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/core.c (ffffffff8100eaad)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101ee08)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81031842)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103b454)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8105afbe)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810685a7)
Location: include/linux/cpumask.h:344
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81074036)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81074e34)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8107a878)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:344
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff8346661c)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8108ac20)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81093cb8)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/tlb.c (ffffffff810ae3fc)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff810b8aa1)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In kernel/cpu.c (ffffffff8347ad49)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/workqueue.c (ffffffff8347b6f2)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/core.c (ffffffff81119e91)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff8112ca63)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/build_policy.c (ffffffff81134f14)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_clear
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:rq_online_rt
```
```
In kernel/sched/build_utility.c (ffffffff8114aa89)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_domains_numa_masks_set
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:cpupri_set
```
```
In kernel/irq/irqdesc.c (ffffffff8347ef65)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff81167997)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffffffff8117039a)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_spread_init_one
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/profile.c (ffffffff81193bf5)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/hrtimer.c (ffffffff8119b879)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/clocksource.c (ffffffff811a18d1)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff811ae9f9)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/watchdog_hld.c (ffffffff81200648)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ring_buffer.c (ffffffff81218c0f)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff81219d16)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_fmt
```
```
In kernel/trace/trace_hwlat.c (ffffffff81230658)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/events/core.c (ffffffff812e2339)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/page_alloc.c (ffffffff813689c9)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - mm/page_alloc.c:__drain_all_pages
```
```
In mm/slub.c (ffffffff813a503b)
Location: include/linux/cpumask.h:344
Inline: True
```
```
In block/blk-mq.c (ffffffff8168a4a1)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In io_uring/io-wq.c (ffffffff816d96f7)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_affinity
```
```
In lib/cpu_rmap.c (ffffffff8176240f)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/processor_throttling.c (ffffffff8188f4d7)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff818904c0)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81896c7f)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/xen/cpu_hotplug.c (ffffffff818c6c25)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff834b9bf6)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/base/cacheinfo.c (ffffffff81989007)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
```
```
In drivers/base/power/domain.c (ffffffff8199b424)
Location: include/linux/cpumask.h:344
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81b529bb)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/opp/cpu.c (ffffffff81b8bd62)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b90eda)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81b9612c)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81b9a921)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9c914)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
```
```
In net/core/sysctl_net_core.c (ffffffff81c0a2ec)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81c0f698)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/net-sysfs.c (ffffffff81c557fa)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_rps_map
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
In arch/x86/events/amd/iommu.c (ffffffff83e65ea9)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/core.c (ffffffff81012149)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/events/intel/uncore.c (ffffffff810234f8)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81039048)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043c24)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81069680)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81078157)
Location: include/linux/cpumask.h:409
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810842a6)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81084f9a)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108bad5)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:409
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff83e8a007)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109ed36)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a99c8)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/tlb.c (ffffffff810c86ec)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff810d4341)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In kernel/cpu.c (ffffffff83ea589d)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/workqueue.c (ffffffff83ea658d)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/core.c (ffffffff81141745)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff81156753)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/build_policy.c (ffffffff8115f444)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_clear
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:rq_online_rt
```
```
In kernel/sched/build_utility.c (ffffffff81179409)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_domains_numa_masks_set
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:cpupri_set
```
```
In kernel/irq/irqdesc.c (ffffffff83eab13c)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff8119bd97)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffffffff811a6806)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_spread_init_one
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/profile.c (ffffffff811d1515)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/hrtimer.c (ffffffff811da123)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/clocksource.c (ffffffff811e0a7e)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff811ef31d)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/watchdog_hld.c (ffffffff81248328)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ring_buffer.c (ffffffff81262bb4)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff81263926)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_fmt
```
```
In kernel/trace/trace_hwlat.c (ffffffff8127cccd)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/events/core.c (ffffffff8134a8d5)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/page_alloc.c (ffffffff813e5d7a)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - mm/page_alloc.c:__drain_all_pages
```
```
In mm/slub.c (ffffffff81425a8b)
Location: include/linux/cpumask.h:409
Inline: True
```
```
In block/blk-mq.c (ffffffff81748a9f)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In io_uring/io-wq.c (ffffffff817a55c7)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_affinity
```
```
In lib/cpu_rmap.c (ffffffff818912ef)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/processor_throttling.c (ffffffff819d7197)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff819d813b)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819df7fb)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81a175d3)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff83ef6f58)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/base/cacheinfo.c (ffffffff81af8379)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
```
```
In drivers/base/power/domain.c (ffffffff81b0c5d4)
Location: include/linux/cpumask.h:409
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81ceabfb)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/opp/cpu.c (ffffffff81d2b4b2)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d3112d)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d36ce1)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81d3bde3)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3e460)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
```
```
In net/core/sysctl_net_core.c (ffffffff81dba37a)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81dc1ffd)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/net-sysfs.c (ffffffff81e0b18f)
Location: include/linux/cpumask.h:409
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_rps_map
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
In arch/x86/events/amd/iommu.c (ffffffff8368652c)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/core.c (ffffffff81013267)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/events/intel/uncore.c (ffffffff810231f0)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81038f7e)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/xen/smp_pv.c (ffffffff836927ea)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8369dddd)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_online
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107a407)
Location: include/linux/cpumask.h:469
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81086856)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108ac55)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108e9ff)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:469
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff836ad6ad)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a1cad)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810ac5ad)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/tlb.c (ffffffff810cbcc1)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff810d7881)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In kernel/cpu.c (ffffffff836c9f5d)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/workqueue.c (ffffffff836cad4d)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/core.c (ffffffff8114d3f0)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff811667d3)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/build_policy.c (ffffffff8116fb34)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpudl_clear
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:rq_online_rt
```
```
In kernel/sched/build_utility.c (ffffffff81189ff3)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_domains_numa_masks_set
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:cpupri_set
```
```
In kernel/irq/irqdesc.c (ffffffff836d00fc)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff811adbf7)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/profile.c (ffffffff811e5785)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/hrtimer.c (ffffffff811ee639)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/clocksource.c (ffffffff811f4fde)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff8120387d)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/watchdog_perf.c (ffffffff8125f643)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/watchdog_perf.c:watchdog_hardlockup_disable
```
```
In kernel/trace/ring_buffer.c (ffffffff81279b94)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff8127e911)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:print_trace_fmt
```
```
In kernel/trace/trace_hwlat.c (ffffffff812949ad)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/cpumask.c (ffffffff8135d761)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_set_cpu
```
```
In kernel/events/core.c (ffffffff8137b915)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/page_alloc.c (ffffffff8141aaaa)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - mm/page_alloc.c:__drain_all_pages
```
```
In mm/slub.c (ffffffff8145ad1b)
Location: include/linux/cpumask.h:469
Inline: True
```
```
In block/blk-mq.c (ffffffff817851b1)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In io_uring/io-wq.c (ffffffff817e65a7)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_affinity
```
```
In lib/cpu_rmap.c (ffffffff818d35ff)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In lib/group_cpus.c (ffffffff818e7236)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - lib/group_cpus.c:group_cpus_evenly
  - lib/group_cpus.c:grp_spread_init_one
  - lib/group_cpus.c:grp_spread_init_one
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a1eb57)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a1fb55)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a2750b)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81a60663)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1af93)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_online
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff8371ca08)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/base/cacheinfo.c (ffffffff81b468aa)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
```
```
In drivers/base/power/domain.c (ffffffff81b5a614)
Location: include/linux/cpumask.h:469
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81c4ce2f)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81d5380b)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/opp/cpu.c (ffffffff81d94782)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d9a3e2)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81da0096)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81da6943)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81da8ff0)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
```
```
In net/core/sysctl_net_core.c (ffffffff81e2ad18)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81e3155d)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/net-sysfs.c (ffffffff81e7e53f)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_rps_map
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
In arch/x86/events/amd/iommu.c (ffffffff838b5779)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/core.c (ffffffff8101a5ec)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102931f)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103f42e)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/xen/smp_pv.c (ffffffff838c2338)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff838cd99d)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_online
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81080a99)
Location: include/linux/cpumask.h:469
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d776)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81092471)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81095d8f)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:469
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff838ddcfa)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a75dd)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:cpu_update_apic
  - arch/x86/kernel/apic/apic.c:cpu_update_apic
  - arch/x86/kernel/apic/apic.c:cpu_mark_primary_thread
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b328d)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/tlb.c (ffffffff810d4351)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff810e0101)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In kernel/cpu.c (ffffffff838fac0d)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:notify_cpu_starting
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/workqueue.c (ffffffff838fbcea)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/workqueue.c:init_pod_type
```
```
In kernel/sched/core.c (ffffffff811590b0)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff81173513)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/build_policy.c (ffffffff811757c7)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_pushable_dl_task
  - kernel/sched/build_policy.c:cpudl_clear
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:rq_online_rt
```
```
In kernel/sched/build_utility.c (ffffffff811988f3)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_domains_numa_masks_set
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:cpupri_set
```
```
In kernel/irq/irqdesc.c (ffffffff8390151c)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff811bd7f7)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/rcu/tree.c (ffffffff811d4e82)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nocb_cpu_offload
```
```
In kernel/profile.c (ffffffff811fb4d5)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/hrtimer.c (ffffffff812047b9)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/clocksource.c (ffffffff8120b17e)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff81219e3d)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/watchdog_perf.c (ffffffff81279653)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/watchdog_perf.c:watchdog_hardlockup_disable
```
```
In kernel/trace/ring_buffer.c (ffffffff81294674)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff812993d1)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:print_trace_fmt
```
```
In kernel/trace/trace_hwlat.c (ffffffff812b000d)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/cpumask.c (ffffffff81386501)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_set_cpu
```
```
In kernel/events/core.c (ffffffff813a4b15)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/page_alloc.c (ffffffff81447caa)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - mm/page_alloc.c:__drain_all_pages
```
```
In mm/slub.c (ffffffff8145607b)
Location: include/linux/cpumask.h:469
Inline: True
```
```
In block/blk-mq.c (ffffffff817c7741)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In io_uring/io-wq.c (ffffffff8182c367)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_affinity
```
```
In lib/cpu_rmap.c (ffffffff819256df)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In lib/group_cpus.c (ffffffff8192e251)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - lib/group_cpus.c:group_cpus_evenly
  - lib/group_cpus.c:grp_spread_init_one
  - lib/group_cpus.c:grp_spread_init_one
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a69e77)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a6ae75)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a7267b)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pmdomain/core.c (ffffffff81aa2074)
Location: include/linux/cpumask.h:469
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81ab2ea3)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b70ac3)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_online
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff83950529)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/base/cacheinfo.c (ffffffff81b9ebea)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_add_dev
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
```
```
In drivers/net/virtio_net.c (ffffffff81d026db)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81e0a6c2)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
```
```
In drivers/opp/cpu.c (ffffffff81e4c292)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e52111)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e57f15)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81e5e9d3)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e60f5a)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
```
```
In net/core/sysctl_net_core.c (ffffffff81ee8b28)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81eefcdd)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/net-sysfs.c (ffffffff81f3f44f)
Location: include/linux/cpumask.h:469
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_rps_map
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
In arch/arm64/kernel/smp.c (ffff800011435d24)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:smp_prepare_cpus
  - arch/arm64/kernel/smp.c:smp_init_cpus
```
```
In arch/arm64/mm/numa.c (ffff8000100b217c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:numa_update_cpu
```
```
In virt/kvm/kvm_main.c (ffff8000100b9f60)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:hardware_enable_nolock
```
```
In kernel/cpu.c (ffff8000114422dc)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:notify_cpu_starting
```
```
In kernel/workqueue.c (ffff80001144303c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/core.c (ffff80001013d4a4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffff80001014c3e4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffff80001014e9b0)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffff800010152c54)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In kernel/sched/cpupri.c (ffff800010159ef4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffff80001015a7cc)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffff80001015c374)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/irqdesc.c (ffff80001144649c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffff80001017f7a0)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffff80001018822c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (ffff800010198bf8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffff8000101b3c3c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/trace/ring_buffer.c (ffff80001021d058)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffff800010227890)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_hwlat.c (ffff800010231fa4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (ffff8000102a15d8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/swap.c (ffff8000102c3228)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (ffff800010316b70)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/slub.c (ffff800010344c84)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffff8000105f2850)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/cpu_rmap.c (ffff8000106628ac)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/irqchip/irq-gic-v3.c (ffff800011472c14)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff80001067724c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff800010725798)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_hwirq_alloc
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff8000107262ac)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
```
```
In drivers/acpi/processor_perflib.c (ffff8000107a3b30)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a8d40)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/soc/fsl/qbman/bman_portal.c (ffff800010810fc4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe
```
```
In drivers/soc/fsl/qbman/qman_portal.c (ffff8000108115b4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
```
```
In drivers/soc/fsl/qbman/bman.c (ffff8000108123b8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman.c:bman_create_affine_portal
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010816740)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_create_affine_portal
```
```
In drivers/xen/cpu_hotplug.c (ffff80001082b744)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cacheinfo.c (ffff8000108f46fc)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/base/power/domain.c (ffff800010909a04)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/base/arch_topology.c (ffff80001092003c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
```
```
In drivers/opp/cpu.c (ffff800010b1aed8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/opp/of.c (ffff800010b1b558)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b215d4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/clocksource/arm_arch_timer.c (ffff800010b67b98)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu
```
```
In drivers/perf/arm_pmu_platform.c (ffff800010b9582c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/perf/arm_pmu_platform.c:pmu_parse_irqs
```
```
In drivers/perf/arm_pmu_acpi.c (ffff800010b95de4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/perf/arm_pmu_acpi.c:arm_pmu_acpi_cpu_starting
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b96a3c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_online_cpu
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b99c14)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_offline_cpu
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_online_cpu
  - drivers/perf/qcom_l2_pmu.c:l2cache_pmu_online_cpu
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a890)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_offline_cpu
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_online_cpu
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9c654)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_pmu_offline_cpu
```
```
In net/core/sysctl_net_core.c (ffff800010bc59f4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/net-sysfs.c (ffff800010c0b9e8)
Location: include/linux/cpumask.h:325
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
In arch/arm/kernel/smp.c (c0312aec)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:secondary_start_kernel
```
```
In arch/arm/kernel/devtree.c (c15063a8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/arm/kernel/devtree.c:arm_dt_init_cpu_maps
```
```
In arch/arm/kernel/hw_breakpoint.c (c0317754)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/arm/kernel/hw_breakpoint.c:debug_reg_trap
```
```
In arch/arm/mm/context.c (c0322394)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
  - arch/arm/mm/context.c:a15_erratum_get_cpumask
```
```
In arch/arm/mm/cache-l2x0-pmu.c (c150b25c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_init
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_offline_cpu
```
```
In arch/arm/common/bL_switcher.c (c0327870)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus
```
```
In arch/arm/mach-imx/mmdc.c (c033336c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_offline_cpu
```
```
In arch/arm/mach-imx/platsmp.c (0)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In arch/arm/mach-omap2/omap-smp.c (c15152d0)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-smp.c:omap4_smp_init_cpus
```
```
In arch/arm/mach-qcom/platsmp.c (0)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In arch/arm/mach-tegra/platsmp.c (c151abe4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/arm/mach-tegra/platsmp.c:tegra_smp_prepare_cpus
  - arch/arm/mach-tegra/platsmp.c:tegra_secondary_init
```
```
In kernel/cpu.c (c151c2b0)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:notify_cpu_starting
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In kernel/sched/core.c (c038d4fc)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (c0399fec)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (c039c76c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (c039f784)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In kernel/sched/cpupri.c (c03a6d18)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (c03a74a8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (c03a8d58)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/irqdesc.c (c1520b34)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (c03cf98c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (c03d6c1c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (c03e3ab8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/tick-broadcast.c (c03fdbdc)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/trace/ring_buffer.c (c045bb6c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (c0464ed0)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_hwlat.c (c046d610)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (c04d1770)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/swap.c (c04ee304)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (c05311e8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/slub.c (c054a164)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (c079e954)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/cpu_rmap.c (c080b518)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/irqchip/irq-gic-v3.c (c154bfb8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions
```
```
In drivers/soc/qcom/spm.c (c15905c8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/soc/qcom/spm.c:qcom_cpuidle_init
```
```
In drivers/base/cacheinfo.c (c09e0e50)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/base/power/domain.c (c09f1448)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/base/arch_topology.c (c0a05078)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
```
```
In drivers/opp/cpu.c (c0bf5958)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/opp/of.c (c0bf5c90)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (c0bfc230)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpuidle/coupled.c (c0c05590)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
  - drivers/cpuidle/coupled.c:cpuidle_coupled_handle_poke
```
```
In drivers/cpuidle/cpuidle-big_little.c (c15a4628)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-big_little.c:bl_idle_driver_init
```
```
In drivers/firmware/qcom_scm-32.c (0)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/clocksource/arm_arch_timer.c (c0c4b628)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_starting_cpu
```
```
In drivers/perf/arm_pmu_platform.c (c0c7edac)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
```
```
In net/core/sysctl_net_core.c (c0ce0d48)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/net-sysfs.c (c0d23a48)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
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
In arch/powerpc/kernel/cacheinfo.c (c00000000002acc4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online
```
```
In arch/powerpc/kernel/setup-common.c (c00000000134a30c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
```
```
In arch/powerpc/kernel/watchdog.c (c000000000036d64)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:start_watchdog
  - arch/powerpc/kernel/watchdog.c:start_watchdog
```
```
In arch/powerpc/kernel/smp.c (c000000000055fd0)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:start_secondary
  - arch/powerpc/kernel/smp.c:start_secondary
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:set_cpus_related
  - arch/powerpc/kernel/smp.c:set_cpus_related
  - arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi
```
```
In arch/powerpc/kernel/crash.c (c000000000070728)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/powerpc/kernel/crash.c:crash_ipi_callback
```
```
In arch/powerpc/mm/mmu_context.c (c00000000008a108)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/powerpc/mm/mmu_context.c:switch_mm_irqs_off
```
```
In arch/powerpc/mm/book3s64/radix_tlb.c (c000000000095e58)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:exit_flush_lazy_tlbs
```
```
In arch/powerpc/mm/numa.c (c0000000000a35d8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/mm/numa.c:map_cpu_to_node
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000be4a0)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_pick_irq_target
```
```
In arch/powerpc/platforms/powernv/idle.c (c0000000000c7960)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (c0000000000dfdc0)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In arch/powerpc/platforms/pseries/smp.c (c000000001363960)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/smp.c:smp_init_pseries
  - arch/powerpc/platforms/pseries/smp.c:smp_pSeries_kick_cpu
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000f9f90)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
```
```
In arch/powerpc/xmon/xmon.c (c000000000110fc4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:xmon_core
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012a2e0)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_offline
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_online
  - arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_online
  - arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_offline
```
```
In kernel/cpu.c (c000000001365ef8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:notify_cpu_starting
```
```
In kernel/workqueue.c (c000000001366ffc)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/core.c (c00000000018c2a4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (c00000000019ed2c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (c0000000001a1560)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (c0000000001a6064)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In kernel/sched/cpupri.c (c0000000001ae1b4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (c0000000001aea78)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (c0000000001b0b20)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/irqdesc.c (c00000000136b23c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (c0000000001da250)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (c0000000001e1fec)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (c0000000001f84a0)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/tick-broadcast.c (c000000000219280)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/trace/ring_buffer.c (c0000000002a0ae0)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (c0000000002ada08)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_hwlat.c (c0000000002bc448)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (c0000000003539d8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/swap.c (c00000000037d5ac)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (c0000000003e8e24)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/slub.c (c000000000422db8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (c000000000789c9c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/cpu_rmap.c (c000000000816a3c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/base/cacheinfo.c (c00000000098e928)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/base/power/domain.c (c0000000009a6e18)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/opp/cpu.c (c000000000c0cf70)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/opp/of.c (c000000000c0d53c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (c000000000c154fc)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/powernv-cpufreq.c (c000000000c1bdd4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (c000000000ca05e4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/net-sysfs.c (c000000000cf6ac8)
Location: include/linux/cpumask.h:325
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
In arch/riscv/kernel/smpboot.c (ffffffe00000352c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/riscv/kernel/smpboot.c:smp_prepare_cpus
  - arch/riscv/kernel/smpboot.c:setup_smp
```
```
In arch/riscv/kernel/smp.c (ffffffe0000b7c7a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/riscv/kernel/smp.c:riscv_cpuid_to_hartid_mask
```
```
In arch/riscv/mm/context.c (ffffffe0000ba18c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/riscv/mm/context.c:switch_mm
```
```
In kernel/cpu.c (ffffffe000004824)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:notify_cpu_starting
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In kernel/sched/core.c (ffffffe0000ec838)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffe0000f5952)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffe0000f77c8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffffffe0000fa546)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffe0000ff9b8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffe00010004a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffe0001011bc)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/irqdesc.c (ffffffe000008010)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffe000117bd0)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffffffe00011d9a4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffe0001291de)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffe00017a832)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffe00018207e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_hwlat.c (ffffffe00018941e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (ffffffe0001d08d4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/swap.c (ffffffe0001e447a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (ffffffe00021cf40)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/slub.c (ffffffe000238b30)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffe000431080)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/cpu_rmap.c (ffffffe00048ed66)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/base/cacheinfo.c (ffffffe000585d5c)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/base/power/domain.c (ffffffe00058ea98)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/base/arch_topology.c (ffffffe00059ed4e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
  - drivers/base/arch_topology.c:update_siblings_masks
```
```
In drivers/opp/cpu.c (ffffffe0007032e2)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/opp/of.c (ffffffe0007036bc)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
  - drivers/opp/of.c:dev_pm_opp_of_get_sharing_cpus
```
```
In net/core/sysctl_net_core.c (ffffffe000751fa6)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/net-sysfs.c (ffffffe000788654)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
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
In arch/x86/events/amd/uncore.c (ffffffff810097ce)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/events/amd/iommu.c (ffffffff8288e6c4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017469)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025d13)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/xen/smp_pv.c (ffffffff8289672c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f761)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045220)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ef5f)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105932d)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b2fe)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105eae6)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff828a467a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066c1d)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106cfa6)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/tlb.c (ffffffff810875c3)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff8108bfac)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In kernel/cpu.c (ffffffff828b3b7f)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:notify_cpu_starting
```
```
In kernel/workqueue.c (ffffffff828b46fc)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/core.c (ffffffff810d7dcd)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810e60e8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810e7de4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffffffff810ea0a4)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810ef60b)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810efb55)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810f132a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/irqdesc.c (ffffffff828b78e3)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff81113cf7)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffffffff8111a632)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff81129a95)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8114084a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/watchdog_hld.c (ffffffff81188cda)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ring_buffer.c (ffffffff8119b108)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff811a2db6)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_hwlat.c (ffffffff811abf9f)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (ffffffff8120f991)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/swap.c (ffffffff8122b726)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (ffffffff81277550)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/slub.c (ffffffff8129ccdf)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff814eb5ab)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/cpu_rmap.c (ffffffff8154e420)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/processor_throttling.c (ffffffff816064ab)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81607768)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8160982c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81628090)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff828ef8bc)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/base/cacheinfo.c (ffffffff816cc985)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff816dc736)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/opp/cpu.c (ffffffff81864574)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81868319)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8186cef1)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff818c9520)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/net-sysfs.c (ffffffff81906171)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
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
In arch/x86/events/amd/uncore.c (ffffffff81007f6e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/events/amd/iommu.c (ffffffff8288c62a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016899)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101ef71)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81034730)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103e441)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8104954d)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104b46e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8104ee16)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff8289c7bc)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056fed)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d356)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/tlb.c (ffffffff81076234)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff8107aadc)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In kernel/cpu.c (ffffffff828abd00)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:notify_cpu_starting
```
```
In kernel/workqueue.c (ffffffff828ac87d)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/core.c (ffffffff810c66ed)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810d5288)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810d72bc)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffffffff810da064)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810df67b)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810dfbc5)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810e139a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/irqdesc.c (ffffffff828afb63)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff81104a07)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffffffff8110b6a2)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff8111c325)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff811335ca)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/watchdog_hld.c (ffffffff8117be1a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ring_buffer.c (ffffffff8118e188)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff81195d86)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119ee8f)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (ffffffff81202721)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/swap.c (ffffffff8121e816)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (ffffffff81269470)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/slub.c (ffffffff8128e86f)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff814dbafb)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/cpu_rmap.c (ffffffff8153e700)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/processor_throttling.c (ffffffff815f157b)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff815f2868)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fb46c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff828e6d5f)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/base/cacheinfo.c (ffffffff816a7cb5)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff816b6db6)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/scsi/storvsc_drv.c (ffffffff81713023)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/scsi/storvsc_drv.c:storvsc_channel_init
  - drivers/scsi/storvsc_drv.c:handle_sc_creation
```
```
In drivers/opp/cpu.c (ffffffff8182d224)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81830fc9)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81835c71)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff81838c5b)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In drivers/hv/channel_mgmt.c (ffffffff81852afd)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:init_vp_index
  - drivers/hv/channel_mgmt.c:init_vp_index
  - drivers/hv/channel_mgmt.c:init_vp_index
```
```
In net/core/sysctl_net_core.c (ffffffff81883460)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/net-sysfs.c (ffffffff818bffa1)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
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
In arch/x86/events/amd/uncore.c (ffffffff8100978e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/events/amd/iommu.c (ffffffff828a16c4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017429)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025b73)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/xen/smp_pv.c (ffffffff828a971c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f5c1)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81045060)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104edaf)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105975d)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b72e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105ef16)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b758a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810670cd)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d456)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/tlb.c (ffffffff81087573)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff8108bf5c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In kernel/cpu.c (ffffffff828c6a7e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:notify_cpu_starting
```
```
In kernel/workqueue.c (ffffffff828c75fb)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/core.c (ffffffff810d45bd)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810e24b8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810e449c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffffffff810e71d4)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810ec73b)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810ecc85)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810ee45a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/irqdesc.c (ffffffff828ca81f)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff81111be7)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffffffff81118522)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff811277b5)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8113e6fa)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/watchdog_hld.c (ffffffff81186aaa)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ring_buffer.c (ffffffff81198ed8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff811a0b86)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_hwlat.c (ffffffff811a9d6f)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (ffffffff8120d731)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/swap.c (ffffffff812294c6)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (ffffffff812752f0)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/slub.c (ffffffff8129aaef)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff814e763b)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/cpu_rmap.c (ffffffff8154a160)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/processor_throttling.c (ffffffff8162b35d)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff8162c998)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81631c3c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81656060)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff8290340e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/base/cacheinfo.c (ffffffff816faef5)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff8170a0c6)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/opp/cpu.c (ffffffff818b5304)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b90a9)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818bdc81)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff818c0c5b)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/sysctl_net_core.c (ffffffff8191a520)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/net-sysfs.c (ffffffff819571a1)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
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
In arch/x86/events/amd/uncore.c (ffffffff810098ee)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/events/amd/iommu.c (ffffffff828a16d8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017669)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026665)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/xen/smp_pv.c (ffffffff828a972c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_smp_init
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81030411)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81046460)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
  - arch/x86/kernel/cpu/cacheinfo.c:__populate_cache_leaves
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810501ef)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105abfd)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105cbde)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81060456)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/acpi/boot.c (0)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b768b)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810686ad)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:generic_processor_info
  - arch/x86/kernel/apic/apic.c:generic_processor_info
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f6d6)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
```
```
In arch/x86/mm/tlb.c (ffffffff810896a3)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/numa.c (ffffffff8108e2bc)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_cpu
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81096f32)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:reset_with_ipi
```
```
In kernel/cpu.c (ffffffff828cbdc9)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_hotplug_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:boot_cpu_init
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:notify_cpu_starting
```
```
In kernel/workqueue.c (ffffffff828cc952)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/core.c (ffffffff810df9cd)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810ee058)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
```
In kernel/sched/rt.c (ffffffff810ef710)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_online_rt
```
```
In kernel/sched/deadline.c (ffffffff810f2194)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In kernel/sched/cpupri.c (ffffffff810f777b)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810f7cc5)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set_freecpu
  - kernel/sched/cpudeadline.c:cpudl_clear
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff810f949a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/irqdesc.c (ffffffff828cfc18)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/chip.c (ffffffff8111d1a7)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_enable
```
```
In kernel/irq/affinity.c (ffffffff81123bb2)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff81133df5)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/profile.c:profile_online_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8114b208)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/watchdog_hld.c (ffffffff811943fa)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_disable
```
```
In kernel/trace/ring_buffer.c (ffffffff811a6b58)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffff811ae916)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_line
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b7baf)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (ffffffff8121c5d1)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_cpu
```
```
In mm/swap.c (ffffffff812388d6)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (ffffffff81284eb0)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/slub.c (ffffffff812aa9cf)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff815005db)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/cpu_rmap.c (ffffffff81563fb0)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/acpi/processor_throttling.c (ffffffff816451fd)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81646838)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164bf6c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81670640)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff8290914d)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/base/cacheinfo.c (ffffffff81715795)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff81724c36)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/opp/cpu.c (ffffffff818d15b4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d5389)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818d9f91)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff818dcf6b)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/sysctl_net_core.c (ffffffff8193b765)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/net-sysfs.c (ffffffff81979286)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
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
</ul>
