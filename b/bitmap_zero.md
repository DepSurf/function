# Function: <code>bitmap_zero</code>

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
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/events/core.c (ffffffff810066b6)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/p4.c (ffffffff81012b5a)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101532f)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/xen/apic.c (ffffffff81025ad3)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:physid_set_mask_of_physid
  - arch/x86/xen/apic.c:flat_vector_allocation_domain
```
```
In arch/x86/xen/smp.c (ffffffff81f64fa3)
Location: include/linux/bitmap.h:181
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81f69630)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:init_amd_e400_c1e_mask
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81f6af01)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
```
```
In arch/x86/kernel/smpboot.c (ffffffff8107ce82)
Location: include/linux/bitmap.h:181
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
In arch/x86/kernel/apic/apic.c (ffffffff81f71c92)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810549b3)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81054e9f)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057eae)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059e38)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
  - arch/x86/kernel/apic/x2apic_cluster.c:update_clusterinfo
  - arch/x86/kernel/apic/x2apic_cluster.c:update_clusterinfo
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a431)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_vector_allocation_domain
```
```
In arch/x86/mm/numa.c (ffffffff81f78a34)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/fork.c (ffffffff8107db12)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff81081b82)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (ffffffff8109d176)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:init_workqueues
```
```
In kernel/sched/core.c (ffffffff810a5d72)
Location: include/linux/bitmap.h:181
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
In kernel/sched/fair.c (ffffffff810bb065)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:init_sched_fair_class
```
```
In kernel/sched/rt.c (ffffffff81f7e4d2)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffff81f7e525)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/cpupri.c (ffffffff810c428d)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810c48af)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/irq/irqdesc.c (ffffffff810da26f)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/proc.c (ffffffff810e1ae9)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/migration.c (ffffffff810e2621)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff810fcee3)
Location: include/linux/bitmap.h:181
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
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - kernel/smp.c:hotplug_cfd
  - kernel/smp.c:on_each_cpu_cond
```
```
In kernel/cpuset.c (ffffffff8111aaab)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - kernel/cpuset.c:generate_sched_domains
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/trace/trace.c (ffffffff811501de)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In mm/page_alloc.c (ffffffff81191f20)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/swap.c (ffffffff8119e257)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/rmap.c (ffffffff811ca674)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush
```
```
In mm/frontswap.c (ffffffff811d747c)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/hugetlb.c (ffffffff811dc09e)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff811e0469)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_parse_str
```
```
In mm/slub.c (ffffffff811e8f28)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In block/blk-mq.c (ffffffff813c4273)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In block/blk-mq-tag.c (ffffffff813c7845)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/blk-mq-cpumap.c (ffffffff813c85f7)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
```
```
In lib/bitmap.c (ffffffff813f962a)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:__bitmap_parse
  - lib/bitmap.c:__bitmap_parselist
  - lib/bitmap.c:bitmap_remap
```
```
In lib/cpu_rmap.c (ffffffff81415dc6)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/rapidio/rio.c (ffffffff814596ef)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/acpi/acpi_processor.c (ffffffff81482192)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/processor_throttling.c (ffffffff814ada1b)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff814af34a)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/pnp/quirks.c (ffffffff814bb1f5)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff81fa41c0)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (ffffffff814bd713)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff814c2fd1)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff814d6685)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/n_tty.c (ffffffff814e44c3)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:reset_buffer_flags
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81509510)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/base/node.c (ffffffff81560b25)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
```
```
In drivers/base/regmap/regcache-lzo.c (ffffffff81569403)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_init
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8166fabb)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816b1cdc)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff816b3b96)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81fb3ee7)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff816b87ba)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff816b978d)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/sysctl_net_core.c (ffffffff817132ef)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/neighbour.c (ffffffff81725797)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/core/flow.c (ffffffff81735189)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/core/net-sysfs.c (ffffffff817363be)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_xps_map
  - net/core/net-sysfs.c:show_rps_map
```
```
In net/ipv4/udp.c (ffffffff817861fd)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff817ce2fc)
Location: include/linux/bitmap.h:181
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
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
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/events/core.c (ffffffff810068bf)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/p4.c (ffffffff8101252a)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101489f)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/xen/apic.c (ffffffff81024f11)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:flat_vector_allocation_domain
  - arch/x86/xen/apic.c:physid_set_mask_of_physid
```
```
In arch/x86/xen/smp.c (ffffffff81f8cb64)
Location: include/linux/bitmap.h:191
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81f9151f)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:init_amd_e400_c1e_mask
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81f931fe)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
```
```
In arch/x86/kernel/smpboot.c (ffffffff81052688)
Location: include/linux/bitmap.h:191
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
In arch/x86/kernel/apic/apic.c (ffffffff81f9a47e)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81054b33)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055e53)
Location: include/linux/bitmap.h:191
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810581c9)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a0da)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a7e1)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_vector_allocation_domain
```
```
In arch/x86/mm/numa.c (ffffffff81fa11d6)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/fork.c (ffffffff8107f70d)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff8108500c)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:disable_nonboot_cpus
```
```
In kernel/workqueue.c (ffffffff81fa5111)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
```
```
In kernel/sched/core.c (ffffffff81fa72d6)
Location: include/linux/bitmap.h:191
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
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/rt.c (ffffffff81fa7397)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffff81fa73ea)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/cpupri.c (ffffffff810c7f7d)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffff810c855d)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/irq/irqdesc.c (ffffffff810df76e)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/irq/proc.c (ffffffff810e7589)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/migration.c (ffffffff810e80b1)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff81fa9a15)
Location: include/linux/bitmap.h:191
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
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/cpuset.c (ffffffff8112336a)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:generate_sched_domains
```
```
In kernel/trace/trace.c (ffffffff8115a928)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:__tracing_open
```
```
In mm/page_alloc.c (ffffffff811a69ed)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/swap.c (ffffffff811b3c05)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/rmap.c (ffffffff811e7032)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush
```
```
In mm/frontswap.c (ffffffff811f5909)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
  - mm/frontswap.c:frontswap_register_ops
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/hugetlb.c (ffffffff811fa33e)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff81201e04)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/slub.c (ffffffff81207b51)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
```
```
In block/blk-mq.c (ffffffff814079e0)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In block/blk-mq-tag.c (ffffffff8140ba80)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/blk-mq-cpumap.c (ffffffff8140c857)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
```
```
In lib/bitmap.c (ffffffff8144065a)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:__bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/cpu_rmap.c (ffffffff8145dc06)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/rapidio/rio.c (ffffffff814a717f)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/acpi/acpi_processor.c (ffffffff814d0c9b)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/processor_throttling.c (ffffffff814fd41e)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff814fecb6)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/pnp/quirks.c (ffffffff8150ac8c)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff81fd0751)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (ffffffff8150d509)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81513541)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81527425)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/n_tty.c (ffffffff815365ad)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:reset_buffer_flags
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8155b420)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff81fd3bd4)
Location: include/linux/bitmap.h:191
Inline: True
```
```
In drivers/base/node.c (ffffffff815b5262)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
```
```
In drivers/base/regmap/regcache-lzo.c (ffffffff815bdfc1)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_init
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816cfe0b)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81713e76)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81715bbb)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817181b1)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8171a516)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/speedstep-centrino.c (ffffffff8171b18d)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
```
```
In net/core/sysctl_net_core.c (ffffffff8177af57)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:191
Inline: True
```
```
In net/core/neighbour.c (ffffffff8178f247)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/core/flow.c (ffffffff817a1320)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/core/net-sysfs.c (ffffffff817a2564)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - net/core/net-sysfs.c:show_xps_map
  - net/core/net-sysfs.c:show_rps_map
```
```
In net/ipv4/udp.c (ffffffff817f488f)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff8183b8cd)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
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
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/events/core.c (ffffffff810068bf)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/p4.c (ffffffff8101263a)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014a7f)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/xen/apic.c (ffffffff810255f0)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:flat_vector_allocation_domain
  - arch/x86/xen/apic.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054f9d)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81fd5945)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81057913)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058c0a)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105af59)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d500)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_vector_allocation_domain
```
```
In arch/x86/mm/numa.c (ffffffff81fdc8ec)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/fork.c (ffffffff81083d42)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff81089fa8)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810b81b9)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:SyS_sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff810bdc4d)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/irq/irqdesc.c (ffffffff810e5e7d)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff810eeaf6)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff8110ba25)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/cpuset.c (ffffffff8112ba01)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:generate_sched_domains
```
```
In kernel/trace/trace.c (ffffffff8116513c)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff8116d819)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/page_alloc.c (ffffffff811b6cc6)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/swap.c (ffffffff811c4278)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/rmap.c (ffffffff811f83d4)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush
```
```
In mm/frontswap.c (ffffffff81206439)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
  - mm/frontswap.c:frontswap_register_ops
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/hugetlb.c (ffffffff8120a803)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff8121395a)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff81219b6f)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
```
```
In block/blk-mq.c (ffffffff81422e1e)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In block/blk-mq-cpumap.c (ffffffff81427bc9)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
```
In lib/bitmap.c (ffffffff8145d75a)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:__bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In drivers/rapidio/rio.c (ffffffff814c928f)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/acpi/processor_throttling.c (ffffffff815202f5)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff81521caa)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81525721)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffffffff8152eeac)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff8200de08)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (ffffffff81539639)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8153f95d)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81553985)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker
```
```
In drivers/tty/n_tty.c (ffffffff81562c83)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:reset_buffer_flags
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81587c0a)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff82011594)
Location: include/linux/bitmap.h:191
Inline: True
```
```
In drivers/base/node.c (ffffffff815e452b)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
```
```
In drivers/base/regmap/regcache-lzo.c (ffffffff815ed3d1)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_init
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816fdceb)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81745d4e)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81747906)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8174a04e)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff817a85a1)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:191
Inline: True
```
```
In net/core/neighbour.c (ffffffff817bcaf7)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/core/flow.c (ffffffff817cfc30)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/ipv4/udp.c (ffffffff8182595f)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff8186d2cd)
Location: include/linux/bitmap.h:191
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_zero(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff8209dcf4)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/events/core.c (ffffffff8100661f)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/p4.c (ffffffff81010c09)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (ffffffff81013041)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/xen/apic.c (ffffffff8101bfa0)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:flat_vector_allocation_domain
  - arch/x86/xen/apic.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810437b3)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff810548b5)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff820b668b)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81057193)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058263)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_irq_vector
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a509)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c832)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cpu_mask_to_apicid
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105cc00)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_vector_allocation_domain
```
```
In arch/x86/mm/tlb.c (ffffffff81074d84)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/mm/numa.c (ffffffff81078724)
Location: include/linux/bitmap.h:190
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/fork.c (ffffffff81080c72)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff81086e6e)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810b2eb5)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff810b8bd1)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/topology.c (ffffffff810ccbed)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (ffffffff810e54d2)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff810ee63b)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff8110da65)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff81113f94)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff8112f2c1)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/trace/trace.c (ffffffff81168486)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811709ce)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/page_alloc.c (ffffffff811bec06)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/swap.c (ffffffff811cc67a)
Location: include/linux/bitmap.h:190
Inline: True
```
```
In mm/frontswap.c (ffffffff81211bc9)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
  - mm/frontswap.c:frontswap_register_ops
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/hugetlb.c (ffffffff81215b83)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff8121ecda)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
Direct callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/slub.c (ffffffff8122589f)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
```
```
In security/integrity/ima/ima_template.c (ffffffff813fa79b)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/blk-mq.c (ffffffff814329f6)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/bitmap.c (ffffffff814629fb)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In drivers/rapidio/rio.c (ffffffff814d50ef)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/acpi/processor_throttling.c (ffffffff81531b66)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff81533649)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81538013)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffffffff815426a7)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff815437a7)
Location: include/linux/bitmap.h:190
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (ffffffff8154ce92)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815536fe)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff815682c5)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker
```
```
In drivers/tty/n_tty.c (ffffffff81577074)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8159c09a)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff820f30fe)
Location: include/linux/bitmap.h:190
Inline: True
```
```
In drivers/base/node.c (ffffffff815f912b)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
```
```
In drivers/net/tun.c (ffffffff81693790)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_link_ksettings
  - drivers/net/tun.c:tun_get_link_ksettings
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817141ab)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81765f9a)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8176866d)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff817c6bef)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:190
Inline: True
```
```
In net/core/neighbour.c (ffffffff817db1c7)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/core/flow.c (ffffffff817ef030)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/ipv4/udp.c (ffffffff81847981)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff818920f8)
Location: include/linux/bitmap.h:190
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
**Symbols:**

```
ffffffff810532b0-ffffffff810532cb: bitmap_zero (STB_LOCAL)
ffffffff81078724-ffffffff81078733: bitmap_zero.constprop.8 (STB_LOCAL)
ffffffff8121adb0-ffffffff8121adde: bitmap_zero.constprop.38 (STB_LOCAL)
ffffffff815437a7-ffffffff815437b6: bitmap_zero.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_zero(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff826a3c95)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/events/core.c (ffffffff81006a1f)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/p4.c (ffffffff81011429)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (ffffffff81013871)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/xen/apic.c (ffffffff8101cd23)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:physid_set_mask_of_physid
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81022afa)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81046e27)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105868f)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff826bceba)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8105ae23)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105ea21)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/mm/tlb.c (ffffffff8107af1c)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/mm/numa.c (ffffffff8107ea84)
Location: include/linux/bitmap.h:200
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/fork.c (ffffffff810875e2)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff8108dc03)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810ba2b5)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_setaffinity
```
```
In kernel/sched/fair.c (ffffffff810c0a31)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/topology.c (ffffffff810d3a33)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (ffffffff810ed721)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff810f706b)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff81118cf5)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff8111f524)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff8113c16d)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff8115b783)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff8115bed5)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff81175415)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff8117db96)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/page_alloc.c (ffffffff811d3906)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/swap.c (ffffffff811e16ac)
Location: include/linux/bitmap.h:200
Inline: True
```
```
In mm/frontswap.c (ffffffff8122c59f)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
  - mm/frontswap.c:frontswap_register_ops
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/hugetlb.c (ffffffff812307b6)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff81239efa)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
Direct callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/slub.c (ffffffff81240f2f)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
```
```
In security/integrity/ima/ima_template.c (ffffffff81422c3b)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/blk-mq.c (ffffffff8145e5c7)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/bitmap.c (ffffffff8148e8e5)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In drivers/rapidio/rio.c (ffffffff8151559f)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/acpi/processor_throttling.c (ffffffff81592e99)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff81594c95)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815997dd)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffffffff815a57c7)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff815a68bd)
Location: include/linux/bitmap.h:200
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (ffffffff815b0408)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815b707e)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff815cc475)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker
```
```
In drivers/tty/n_tty.c (ffffffff815db9f4)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8160139a)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff826fc7cc)
Location: include/linux/bitmap.h:200
Inline: True
```
```
In drivers/base/node.c (ffffffff816611fb)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
```
```
In drivers/net/tun.c (ffffffff816fd6a0)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_link_ksettings
  - drivers/net/tun.c:tun_get_link_ksettings
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817853ef)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (ffffffff817d5fcd)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff817dbf7a)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817de55d)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff818407ef)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:200
Inline: True
```
```
In net/core/neighbour.c (ffffffff8185597a)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/ipv4/udp.c (ffffffff818c73e1)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff8190f482)
Location: include/linux/bitmap.h:200
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
**Symbols:**

```
ffffffff81057080-ffffffff8105709b: bitmap_zero (STB_LOCAL)
ffffffff8107ea84-ffffffff8107ea93: bitmap_zero.constprop.8 (STB_LOCAL)
ffffffff81235fd0-ffffffff81235ffe: bitmap_zero.constprop.40 (STB_LOCAL)
ffffffff815a68bd-ffffffff815a68cc: bitmap_zero.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_zero(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff826ccd86)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/events/core.c (ffffffff810071be)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_schedule_events
```
```
In arch/x86/events/intel/p4.c (ffffffff81011cf7)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014130)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/xen/apic.c (ffffffff8101d730)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:physid_set_mask_of_physid
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810233e9)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff8104928d)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105b308)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff826e6c71)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8105de20)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810619c7)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/mm/tlb.c (ffffffff8107dcdc)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/mm/numa.c (ffffffff81081bc4)
Location: include/linux/bitmap.h:202
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826f2131)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8108aba2)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff81091457)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/sched/core.c (ffffffff810bc8ae)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff810c6042)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/topology.c (ffffffff810db70a)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (ffffffff810f5af1)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff810ff3b8)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff8112587f)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff8112c85b)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff8114a3f2)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/watchdog.c (ffffffff8116a2e3)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff8116aa45)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff811843cb)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff8118c9dc)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/page_alloc.c (ffffffff811f4bff)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/swap.c (ffffffff81202ddc)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/frontswap.c (ffffffff8124f083)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
  - mm/frontswap.c:frontswap_register_ops
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/hugetlb.c (ffffffff81252f99)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff8125d6b4)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff81263ee4)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
```
```
In security/integrity/ima/ima_template.c (ffffffff8145520b)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/blk-mq.c (ffffffff81491f05)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/bitmap.c (ffffffff814c36b0)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In drivers/gpio/gpiolib.c (ffffffff8150a502)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/rapidio/rio.c (ffffffff8154a94f)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/acpi/processor_throttling.c (ffffffff815ca2a7)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff815cc13b)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d103d)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffffffff815dd3c7)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff815de46f)
Location: include/linux/bitmap.h:202
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (ffffffff815e8864)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815ef57d)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff816043f5)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker
```
```
In drivers/tty/n_tty.c (ffffffff816148b6)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163a65a)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff82726abb)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/base/node.c (ffffffff8169c9c7)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
```
```
In drivers/net/tun.c (ffffffff8173b7db)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817c64b0)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (ffffffff8181ecad)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81824c30)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818272da)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff8188ae4a)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:202
Inline: True
```
```
In net/core/neighbour.c (ffffffff818a0f1a)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/ipv4/udp.c (ffffffff8191e5cf)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff81966575)
Location: include/linux/bitmap.h:202
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
**Symbols:**

```
ffffffff81059ef0-ffffffff81059f0b: bitmap_zero (STB_LOCAL)
ffffffff81081bc4-ffffffff81081bce: bitmap_zero.constprop.8 (STB_LOCAL)
ffffffff8108f5d0-ffffffff8108f5eb: bitmap_zero (STB_LOCAL)
ffffffff815de46f-ffffffff815de479: bitmap_zero.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_zero(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff82882da1)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/events/core.c (0)
Location: include/linux/bitmap.h:215
Inline: True
```
```
In arch/x86/events/intel/p4.c (ffffffff8101236f)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/bitmap.h:215
Inline: True
```
```
In arch/x86/xen/apic.c (ffffffff8101cfc0)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:physid_set_mask_of_physid
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81022e90)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105928e)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff81060f88)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8289d7ba)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_bsp_setup
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81063ab0)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810676a7)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/mm/tlb.c (ffffffff81084854)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/mm/numa.c (ffffffff810887d4)
Location: include/linux/bitmap.h:215
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828a9156)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81092b9f)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff81099737)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/sched/core.c (ffffffff810c372e)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff810d0612)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/topology.c (ffffffff810e5309)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (ffffffff81101281)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff8110ab98)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff81130f6f)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff8113812b)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff8115866c)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
```
In kernel/watchdog.c (ffffffff811772f5)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff81177a55)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff81191d3b)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119a4ec)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/page_alloc.c (ffffffff81206fdf)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/swap.c (ffffffff8121577c)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/frontswap.c (ffffffff81263570)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/hugetlb.c (ffffffff81267a09)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff81271f4c)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff81278654)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
```
```
In fs/iomap.c (ffffffff813245ee)
Location: include/linux/bitmap.h:215
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/bitmap.h:215
Inline: True
```
```
In block/blk-mq.c (ffffffff814ab969)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/bitmap.c (ffffffff814d7ae0)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In drivers/gpio/gpiolib.c (ffffffff8151ef0e)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/bitmap.h:215
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff815e3887)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_throttling_init
```
```
In drivers/acpi/processor_perflib.c (ffffffff815e571b)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815ea66d)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffffffff815f6b67)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff815f7c8b)
Location: include/linux/bitmap.h:215
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:215
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8161f4d5)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker
```
```
In drivers/tty/n_tty.c (ffffffff81631b06)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/bitmap.h:215
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff828dec9f)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/base/node.c (ffffffff816bd217)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
```
```
In drivers/net/phy/phy.c (ffffffff817580a5)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:phy_start_aneg
```
```
In drivers/net/phy/phy-c45.c (ffffffff817596e5)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:gen10g_config_init
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff8175c02b)
Location: include/linux/bitmap.h:215
Inline: True
```
```
In drivers/net/tun.c (ffffffff8176006b)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817eda80)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (ffffffff8184ab2d)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81850bc0)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818531da)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff818abe8a)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitmap.h:215
Inline: True
```
```
In net/core/neighbour.c (ffffffff818c3dda)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/ipv4/udp.c (ffffffff8194d3cf)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff8199bb95)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
**Symbols:**

```
ffffffff8105fb70-ffffffff8105fb8b: bitmap_zero (STB_LOCAL)
ffffffff810887d4-ffffffff810887de: bitmap_zero.constprop.10 (STB_LOCAL)
ffffffff810978d0-ffffffff810978eb: bitmap_zero (STB_LOCAL)
ffffffff815f7c8b-ffffffff815f7c95: bitmap_zero.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_zero(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff82899cfd)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/events/core.c (0)
Location: include/linux/bitmap.h:215
Inline: True
```
```
In arch/x86/events/intel/p4.c (ffffffff81013863)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/bitmap.h:215
Inline: True
```
```
In arch/x86/xen/apic.c (ffffffff8101ead0)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:physid_set_mask_of_physid
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025559)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c826)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff810645f3)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b535e)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810671b0)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106ae58)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/mm/tlb.c (ffffffff810884c1)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/mm/numa.c (ffffffff8108c41b)
Location: include/linux/bitmap.h:215
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c193d)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096b87)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff8109da85)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/sched/core.c (ffffffff810cb700)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff810d8541)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/topology.c (ffffffff810ec2a0)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/irqdesc.c (ffffffff81109a7e)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff8111424c)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff8113bacf)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff811432d8)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff81164e38)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff811840d6)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff811848b9)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff8119f757)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811a8154)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/swap.c (ffffffff81225178)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (ffffffff8126d045)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/frontswap.c (ffffffff8127e4c0)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/hugetlb.c (ffffffff8128216f)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff8128d578)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff8129475d)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
```
```
In fs/iomap/buffered-io.c (ffffffff8134b800)
Location: include/linux/bitmap.h:215
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/bitmap.h:215
Inline: True
```
```
In block/blk-mq.c (ffffffff814d9b5a)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/bitmap.c (ffffffff81504263)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In drivers/gpio/gpiolib.c (ffffffff8154d0af)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/bitmap.h:215
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff81615416)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81617316)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/hmat/hmat.c (ffffffff828f405f)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161c3f0)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffffffff8162887b)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff81629b8b)
Location: include/linux/bitmap.h:215
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:215
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81652ac5)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker
```
```
In drivers/tty/n_tty.c (ffffffff81666156)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/bitmap.h:215
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff828f95c4)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/base/node.c (ffffffff816f7fc5)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_memory_block_under_nodes
```
```
In drivers/net/phy/phy.c (ffffffff817948e5)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:phy_start_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff817993c1)
Location: include/linux/bitmap.h:215
Inline: True
```
```
In drivers/net/tun.c (ffffffff8179d7cb)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8182e4db)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (ffffffff8188dc9d)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818940fe)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818967b0)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff818f774a)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (ffffffff819092aa)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
```
In net/core/neighbour.c (ffffffff8190ff3e)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/ipv4/udp.c (ffffffff819b1b76)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff81a07960)
Location: include/linux/bitmap.h:215
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
**Symbols:**

```
ffffffff81063360-ffffffff8106337b: bitmap_zero (STB_LOCAL)
ffffffff8108c41b-ffffffff8108c425: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff8109be90-ffffffff8109beab: bitmap_zero (STB_LOCAL)
ffffffff81629b8b-ffffffff81629b95: bitmap_zero.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_zero(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff81014013)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In arch/x86/xen/apic.c (ffffffff8101f470)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:physid_set_mask_of_physid
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025b39)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d12c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064c73)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b8899)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81067820)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b7f8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/mm/tlb.c (ffffffff81089171)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/mm/numa.c (ffffffff8108d07b)
Location: include/linux/bitmap.h:219
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c7db6)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff810977e6)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:reset_with_ipi
```
```
In kernel/fork.c (ffffffff8109d3c7)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff810a3fd1)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/sched/core.c (ffffffff810d3930)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff810e2e41)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/topology.c (ffffffff810f7d4d)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (ffffffff81115e4e)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff811203bc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff811476df)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff8114ee18)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff81170d18)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff8118ff56)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff81190739)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff811ab117)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b3954)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/swap.c (ffffffff81232ff8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (ffffffff8127c0c5)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/frontswap.c (ffffffff8128df20)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/hugetlb.c (ffffffff81291c00)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
Direct callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff8129cf9f)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff812a452d)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
```
```
In fs/iomap/buffered-io.c (ffffffff81363ad0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In block/blk-mq.c (ffffffff814f2f07)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/bitmap.c (ffffffff81522273)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In drivers/gpio/gpiolib.c (ffffffff8156e2ad)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff81636906)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81638876)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/hmat/hmat.c (ffffffff8163ad75)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163de90)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffffffff8164a36b)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff8164b67b)
Location: include/linux/bitmap.h:219
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81675065)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker
```
```
In drivers/tty/n_tty.c (ffffffff81689206)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff829024c7)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/net/phy/phy.c (ffffffff817b8485)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
```
```
In drivers/net/phy/phy-c45.c (ffffffff817ba055)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
```
```
In drivers/net/phy/phy_device.c (ffffffff817bcee1)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/net/tun.c (ffffffff817c126b)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8185fe0b)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (ffffffff818bfe2d)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818c611e)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818c87c0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff819294ca)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (ffffffff8193b9ea)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
```
In net/core/neighbour.c (ffffffff819425ae)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/ipv4/udp.c (ffffffff819e88f9)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff81a3e4d0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
**Symbols:**

```
ffffffff81063a10-ffffffff81063a2b: bitmap_zero (STB_LOCAL)
ffffffff8108d07b-ffffffff8108d085: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff810a2410-ffffffff810a242b: bitmap_zero (STB_LOCAL)
ffffffff81297fde-ffffffff81297fe8: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff8164b67b-ffffffff8164b685: bitmap_zero.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_zero(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff8101563a)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/bitmap.h:235
Inline: True
```
```
In arch/x86/xen/apic.c (ffffffff81021a30)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:physid_set_mask_of_physid
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025edf)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106165e)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106a0c1)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff82cdd926)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8106e530)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81071613)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/mm/tlb.c (ffffffff8108ba7a)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/mm/numa.c (ffffffff810946ac)
Location: include/linux/bitmap.h:235
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82ceabfc)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109c92b)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:reset_with_ipi
```
```
In kernel/fork.c (ffffffff810a4227)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff810ab255)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:thaw_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810ddce2)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff810ec3a0)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/topology.c (ffffffff81101619)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_balance_mask
Direct callers:
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/irqdesc.c (ffffffff8112166d)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:desc_set_defaults
```
```
In kernel/irq/migration.c (ffffffff8112c8fc)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff811573ef)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff8115f788)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff81182959)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff811a4ad6)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff811a52e3)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff811c33dc)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811cc3e0)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In mm/swap.c (ffffffff81260633)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/frontswap.c (ffffffff812c08c0)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/hugetlb.c (ffffffff812c5372)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:set_max_huge_pages
Direct callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff812d0b7f)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
Direct callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/slub.c (ffffffff812d81b9)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - mm/slub.c:get_map
```
```
In fs/iomap/buffered-io.c (ffffffff813aa6cb)
Location: include/linux/bitmap.h:235
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/bitmap.h:235
Inline: True
```
```
In block/blk-mq.c (ffffffff8155351e)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/bitmap.c (ffffffff815855d3)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_parselist
```
```
In drivers/gpio/gpiolib.c (ffffffff81612759)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/bitmap.h:235
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e3b16)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff816e55d2)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/numa/hmat.c (ffffffff816e7ce4)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816eb287)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffffffff816f944b)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff82d15fb7)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:235
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81725b35)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker
```
```
In drivers/tty/n_tty.c (ffffffff8173c377)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/bitmap.h:235
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff82d19717)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/net/phy/phy.c (ffffffff8187f015)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
```
```
In drivers/net/phy/phy-c45.c (ffffffff81881215)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
```
```
In drivers/net/phy/phy_device.c (ffffffff818841ff)
Location: include/linux/bitmap.h:235
Inline: True
```
```
In drivers/net/phy/bcm84881.c (ffffffff818891e4)
Location: include/linux/bitmap.h:235
Inline: True
```
```
In drivers/net/tun.c (ffffffff8188b0bb)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8193277e)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (ffffffff81991b8d)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8199819e)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199aa10)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff819fd45a)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/neighbour.c (ffffffff81a1275a)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/ethtool/ioctl.c (ffffffff81a816c1)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32
  - net/ethtool/ioctl.c:ethtool_convert_legacy_u32_to_link_mode
```
```
In net/ethtool/bitset.c (ffffffff81a878a2)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/features.c (0)
Location: include/linux/bitmap.h:235
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad6c83)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff81b33380)
Location: include/linux/bitmap.h:235
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
**Symbols:**

```
ffffffff81069d40-ffffffff81069d5b: bitmap_zero (STB_LOCAL)
ffffffff810946ac-ffffffff810946b6: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff810a90e0-ffffffff810a90fb: bitmap_zero (STB_LOCAL)
ffffffff811006b0-ffffffff811006cb: bitmap_zero (STB_LOCAL)
ffffffff812cb684-ffffffff812cb68e: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff812cbb60-ffffffff812cbb89: bitmap_zero.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_zero(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff81015ada)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/bitmap.h:233
Inline: True
```
```
In arch/x86/xen/apic.c (ffffffff81022110)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:physid_set_mask_of_physid
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102671f)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fa6e)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068032)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106bd91)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff82fc9cdf)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8106f9b0)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81072c43)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/mm/tlb.c (ffffffff8108baca)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/mm/numa.c (ffffffff81bda1a6)
Location: include/linux/bitmap.h:233
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82fd8447)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8109fe37)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff810a6ae1)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:thaw_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810da2be)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff810e9eb0)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/topology.c (ffffffff81100179)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_balance_mask
Direct callers:
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/irqdesc.c (ffffffff8111d79d)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:desc_set_defaults
```
```
In kernel/irq/migration.c (ffffffff8112832c)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff811534bf)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff8115b728)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff8117f891)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff811a1b76)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff811a22d3)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff811c0fec)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811c9a3b)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:start_kthread
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In mm/swap.c (ffffffff8126a6e3)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/frontswap.c (ffffffff812cc2e0)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/hugetlb.c (ffffffff812d0f82)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:set_max_huge_pages
Direct callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff812dc69f)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
Direct callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/slub.c (ffffffff812e3b29)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - mm/slub.c:get_map
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/bitmap.h:233
Inline: True
```
```
In block/blk-mq.c (ffffffff8156fbce)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/bitmap.c (ffffffff815a26d8)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_parselist
```
```
In drivers/gpio/gpiolib.c (ffffffff816377d4)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/bitmap.h:233
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/bitmap.h:233
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff81701776)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81703032)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/numa/hmat.c (ffffffff81705523)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8170898f)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffffffff8171613b)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff83003c69)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:233
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81742925)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker
```
```
In drivers/tty/n_tty.c (ffffffff817584e7)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/vt/vt.c (ffffffff8176a4f8)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:reset_terminal
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/bitmap.h:233
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff830073e0)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/net/phy/phy.c (ffffffff8188d8b5)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
```
```
In drivers/net/phy/phy-c45.c (ffffffff8188f945)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
```
```
In drivers/net/phy/phy_device.c (ffffffff8189292f)
Location: include/linux/bitmap.h:233
Inline: True
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81896d65)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_quirk_ubnt_uf_instant
```
```
In drivers/net/phy/bcm84881.c (ffffffff81897454)
Location: include/linux/bitmap.h:233
Inline: True
```
```
In drivers/net/tun.c (ffffffff8189925b)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819399de)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (ffffffff81994e6d)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8199b2be)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199daf3)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff819fd0a2)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81a046f4)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/neighbour.c (ffffffff81a12aaa)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/ethtool/ioctl.c (ffffffff81a8b2b1)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32
  - net/ethtool/ioctl.c:ethtool_convert_legacy_u32_to_link_mode
```
```
In net/ethtool/bitset.c (ffffffff81a91222)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/features.c (0)
Location: include/linux/bitmap.h:233
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ae3263)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff81b41cb0)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
**Symbols:**

```
ffffffff8106ba10-ffffffff8106ba2b: bitmap_zero (STB_LOCAL)
ffffffff81bda1a6-ffffffff81bda1b0: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff810a4b30-ffffffff810a4b4b: bitmap_zero (STB_LOCAL)
ffffffff810ff200-ffffffff810ff21b: bitmap_zero (STB_LOCAL)
ffffffff81be8a4b-ffffffff81be8a55: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff812d7500-ffffffff812d7529: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff817691b0-ffffffff817691d0: bitmap_zero.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_zero(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008c78)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
```
```
In arch/x86/events/intel/p4.c (ffffffff81016e0a)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/bitmap.h:233
Inline: True
```
```
In arch/x86/xen/apic.c (ffffffff810244a0)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:physid_set_mask_of_physid
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102839f)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fade)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810685a2)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106c6ee)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff831d45f3)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810704e0)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81073381)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/mm/tlb.c (ffffffff8108c6fa)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
```
```
In arch/x86/mm/numa.c (ffffffff81bcc286)
Location: include/linux/bitmap.h:233
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff831e2e3d)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810a0b4a)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff810a7b7d)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:thaw_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810dc3ab)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff810eb7a3)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/topology.c (ffffffff81102e44)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
Direct callers:
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/irqdesc.c (ffffffff8111dc41)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff811285f2)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/clocksource.c (ffffffff811496e5)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_percpu
  - kernel/time/clocksource.c:clocksource_verify_percpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8115497f)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff8115c7f9)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff8117fed1)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff811a2867)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff811a2f93)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff811c1f38)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811cae1d)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In mm/swap.c (ffffffff8126f834)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/percpu.c (ffffffff831f0286)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/frontswap.c (ffffffff812d2e90)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/hugetlb.c (ffffffff812d7d62)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:set_max_huge_pages
Direct callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff812e3edc)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
Direct callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/slub.c (ffffffff812eb169)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - mm/slub.c:get_map
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/bitmap.h:233
Inline: True
```
```
In block/blk-mq.c (ffffffff81577a8a)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/bitmap.c (ffffffff815a95f8)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_parselist
```
```
In drivers/gpio/gpiolib.c (ffffffff8161b10e)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/bitmap.h:233
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/bitmap.h:233
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e2dbb)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff816e47a3)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/numa/hmat.c (ffffffff816e6bc3)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816e9fa4)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffffffff816f744f)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff8320e737)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:233
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff8170974f)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81726315)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker
```
```
In drivers/tty/n_tty.c (ffffffff8173b071)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/vt/vt.c (ffffffff8174e0c8)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:reset_terminal
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/bitmap.h:233
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff83211fb8)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/net/phy/phy.c (ffffffff818701f5)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
```
```
In drivers/net/phy/phy-c45.c (ffffffff81872205)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
```
```
In drivers/net/phy/phy_device.c (ffffffff8187501f)
Location: include/linux/bitmap.h:233
Inline: True
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81879215)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_quirk_ubnt_uf_instant
```
```
In drivers/net/phy/bcm84881.c (ffffffff81879c4a)
Location: include/linux/bitmap.h:233
Inline: True
```
```
In drivers/net/tun.c (ffffffff8187b63b)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8191d10b)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (ffffffff81979dad)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8197ff9e)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff819826b5)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff819e3912)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff819ebf0d)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/neighbour.c (ffffffff819f948a)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/ethtool/ioctl.c (ffffffff81a74751)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32
  - net/ethtool/ioctl.c:ethtool_convert_legacy_u32_to_link_mode
```
```
In net/ethtool/bitset.c (ffffffff81a7aa2e)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/features.c (0)
Location: include/linux/bitmap.h:233
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ace172)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff81b2f99e)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb8ec1)
Location: include/linux/bitmap.h:233
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:pm_nl_init_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
```
**Symbols:**

```
ffffffff8106c3f0-ffffffff8106c40b: bitmap_zero (STB_LOCAL)
ffffffff81bcc286-ffffffff81bcc290: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff810a5800-ffffffff810a581b: bitmap_zero (STB_LOCAL)
ffffffff811013c0-ffffffff811013db: bitmap_zero (STB_LOCAL)
ffffffff81bdaa67-ffffffff81bdaa71: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff812decb0-ffffffff812decd9: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff8174cda0-ffffffff8174cdc0: bitmap_zero.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_zero(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81009af4)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
```
```
In arch/x86/events/intel/p4.c (ffffffff81018a1a)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/bitmap.h:239
Inline: True
```
```
In arch/x86/xen/apic.c (ffffffff81028880)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:physid_set_mask_of_physid
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102ca0b)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106913e)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072d21)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
```
In arch/x86/kernel/smpboot.c (ffffffff8107751f)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff832b717f)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8107c080)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8107f804)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/mm/tlb.c (ffffffff8109bf3a)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
```
```
In arch/x86/mm/numa.c (ffffffff81ca223b)
Location: include/linux/bitmap.h:239
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff832c67e0)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810b1fb1)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff810b95dd)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:thaw_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810ef1eb)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff81103323)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/topology.c (ffffffff8111fa22)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:asym_cpu_capacity_scan
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
Direct callers:
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/irq/irqdesc.c (ffffffff8113e063)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff81148bc2)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/clocksource.c (ffffffff8116d786)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff811795d3)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff8118194f)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff811a8111)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff811cc033)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff811cc7d5)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff811ecb18)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811f6e37)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In mm/swap.c (ffffffff812ac984)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/percpu.c (ffffffff832d5a9e)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/frontswap.c (ffffffff813188e0)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/hugetlb.c (ffffffff8131e772)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:set_max_huge_pages
Direct callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff8132b1cc)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_new_preferred
Direct callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/slub.c (ffffffff8133374e)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - mm/slub.c:__fill_map
```
```
In fs/io_uring.c (ffffffff813decf4)
Location: include/linux/bitmap.h:239
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/bitmap.h:239
Inline: True
```
```
In block/blk-mq.c (ffffffff815dc7aa)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/bitmap.c (ffffffff81612778)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_parselist
```
```
In drivers/gpio/gpiolib.c (ffffffff8168a604)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (0)
Location: include/linux/bitmap.h:239
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/bitmap.h:239
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff8175b19b)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff8175d4db)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/numa/hmat.c (ffffffff81760193)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8176389e)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffffffff81771bef)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff832f74ca)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:239
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81785105)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff817a52e5)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker
```
```
In drivers/tty/n_tty.c (ffffffff817bbaf3)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/vt/vt.c (ffffffff817d0ed8)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:reset_terminal
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/bitmap.h:239
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff832fb161)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/net/phy/phy.c (ffffffff819007d5)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
```
```
In drivers/net/phy/phy-c45.c (ffffffff81902915)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
```
```
In drivers/net/phy/phy_device.c (ffffffff81905aef)
Location: include/linux/bitmap.h:239
Inline: True
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8190a075)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_quirk_ubnt_uf_instant
```
```
In drivers/net/phy/bcm84881.c (ffffffff8190acea)
Location: include/linux/bitmap.h:239
Inline: True
```
```
In drivers/net/tun.c (ffffffff8190cb5b)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819bfb10)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (ffffffff81a22dbd)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81a2913e)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81a2bb52)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff81a93eb2)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81a9ce9d)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/neighbour.c (ffffffff81aab0d2)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/ethtool/ioctl.c (ffffffff81b2e9a1)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32
  - net/ethtool/ioctl.c:ethtool_convert_legacy_u32_to_link_mode
```
```
In net/ethtool/bitset.c (ffffffff81b34e3e)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ethtool/features.c (0)
Location: include/linux/bitmap.h:239
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b8cb32)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff81bf5d1e)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
```
In net/mptcp/pm_netlink.c (ffffffff81c89ae8)
Location: include/linux/bitmap.h:239
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
```
**Symbols:**

```
ffffffff81077000-ffffffff8107701b: bitmap_zero (STB_LOCAL)
ffffffff81ca223b-ffffffff81ca2245: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff810b6fd0-ffffffff810b6feb: bitmap_zero (STB_LOCAL)
ffffffff8111d610-ffffffff8111d62b: bitmap_zero (STB_LOCAL)
ffffffff81cbf224-ffffffff81cbf22e: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff81326280-ffffffff813262a9: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff817cec50-ffffffff817cec70: bitmap_zero.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_zero(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81009202)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
```
```
In arch/x86/events/intel/p4.c (ffffffff8101abfb)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101eefe)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/xen/apic.c (ffffffff8102d050)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:physid_set_mask_of_physid
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810317bd)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810763c6)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080f82)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
```
```
In arch/x86/kernel/smpboot.c (ffffffff8108659a)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:prefill_possible_map
```
```
In arch/x86/kernel/apic/apic.c (ffffffff83468ce5)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8108b380)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8108ec84)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/mm/tlb.c (ffffffff810af4b7)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/mm/numa.c (ffffffff81e518d9)
Location: include/linux/bitmap.h:238
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83479578)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810c8918)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff810d0021)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:thaw_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff8110aba5)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff8111ea04)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/build_utility.c (ffffffff81149a5e)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/irqdesc.c (ffffffff8116167b)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff8116d6f8)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/clocksource.c (ffffffff811a1873)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff811ae993)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff811b7f9d)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff811d90d1)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff811ffdf1)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff812006e5)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff81224cc5)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff8123062f)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/core.c (ffffffff8126c104)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - kernel/bpf/core.c:alloc_new_pack
```
```
In mm/swap.c (ffffffff81302e01)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/percpu.c (ffffffff8348a330)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/frontswap.c (ffffffff81384174)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/hugetlb.c (ffffffff81389d5d)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:set_max_huge_pages
Direct callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff8139ac34)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_new_preferred
Direct callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/slub.c (ffffffff813a4dee)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - mm/slub.c:__fill_map
```
```
In security/integrity/ima/ima_template.c (ffffffff8164592f)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In block/blk-mq.c (ffffffff8168a37f)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In io_uring/io_uring.c (ffffffff81e8f64e)
Location: include/linux/bitmap.h:238
Inline: True
```
```
In lib/bitmap.c (ffffffff816debf4)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_parselist
```
```
In drivers/gpio/gpiolib.c (ffffffff817a780a)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817acfb6)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
```
```
In drivers/rapidio/rio.c (ffffffff817fe58f)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_mport_dma
```
```
In drivers/acpi/processor_throttling.c (ffffffff8188dd69)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff8189062b)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/numa/hmat.c (ffffffff81893b93)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81896d75)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffffffff818a72bd)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff834afb1a)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (ffffffff818b8755)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff818bbce5)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff818df045)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker
```
```
In drivers/tty/n_tty.c (ffffffff818f6e92)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/vt/vt.c (ffffffff81913673)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff819256da)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff834b3b37)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/net/phy/phy.c (ffffffff81a525d5)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:phy_speed_up
```
```
In drivers/net/phy/phy-c45.c (ffffffff81a54f05)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
```
```
In drivers/net/phy/phy_device.c (ffffffff81a58830)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81a5d7b5)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_quirk_ubnt_uf_instant
```
```
In drivers/net/phy/bcm84881.c (ffffffff81a5e666)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/tun.c (ffffffff81a616bb)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81b20780)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (ffffffff81b8bd39)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b9108a)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81b9319e)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81b96117)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff81c0a281)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81c0f62d)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/neighbour.c (ffffffff81c2407a)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/ethtool/ioctl.c (ffffffff81cb97a1)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_convert_link_mode_to_legacy_u32
  - net/ethtool/ioctl.c:ethtool_convert_legacy_u32_to_link_mode
```
```
In net/ethtool/bitset.c (ffffffff81cc061c)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv4/udp.c (ffffffff81d1b1e3)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff81d8ef02)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
```
In net/mptcp/pm_netlink.c (ffffffff81e32596)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
```
```
In net/mptcp/pm_userspace.c (ffffffff81e35236)
Location: include/linux/bitmap.h:238
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
**Symbols:**

```
ffffffff81e518d9-ffffffff81e518ef: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff810cd730-ffffffff810cd75b: bitmap_zero (STB_LOCAL)
ffffffff81e71537-ffffffff81e7154d: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff813952a0-ffffffff813952d3: bitmap_zero.constprop.0 (STB_LOCAL)
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
In arch/x86/events/core.c (ffffffff8100a64e)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
```
```
In arch/x86/events/intel/p4.c (ffffffff8101ed7b)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (ffffffff810235fe)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/xen/apic.c (ffffffff81034390)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:physid_set_mask_of_physid
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81038fd6)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81086966)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108fd02)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/smpboot.c (ffffffff81099b02)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff83e8d5c1)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff8109f6d0)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a34b4)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/mm/tlb.c (ffffffff810c9939)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/mm/numa.c (ffffffff83e9e385)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83ea36c3)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810e5c65)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff810ee8c6)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff81132195)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff81147dc1)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/build_utility.c (ffffffff81178c30)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/irqdesc.c (ffffffff81194d02)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff811a2898)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/clocksource.c (ffffffff811e0a21)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff811ef2f3)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff811f9239)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff8121e1ec)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff812478b9)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff812483e1)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff8126fe25)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff8127cca6)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/core.c (ffffffff812c1330)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/bpf/core.c:alloc_new_pack
```
```
In mm/swap.c (ffffffff8136ddc8)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/vmscan.c (ffffffff8137f7fe)
Location: include/linux/bitmap.h:240
Inline: True
```
```
In mm/percpu.c (ffffffff83ebadbb)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/frontswap.c (ffffffff81401c84)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/hugetlb.c (ffffffff8140aadd)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff8141aca4)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/slub.c (ffffffff8142580e)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - mm/slub.c:__fill_map
```
```
In mm/khugepaged.c (ffffffff8144cb00)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/bitmap.h:240
Inline: True
```
```
In block/blk-mq.c (ffffffff8174897f)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In io_uring/io_uring.c (ffffffff81788ecf)
Location: include/linux/bitmap.h:240
Inline: True
```
```
In lib/bitmap.c (ffffffff817cece7)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_parselist
```
```
In drivers/gpio/gpiolib.c (ffffffff818bfdca)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c62c6)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
```
```
In drivers/rapidio/rio.c (ffffffff8192bdea)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_dma
```
```
In drivers/acpi/processor_throttling.c (ffffffff819d67d7)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff819d835f)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/numa/hmat.c (ffffffff819db717)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819df8ff)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffffffff819f14a2)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff83ee931a)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (ffffffff81a05c55)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0a8d9)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81a33375)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker
```
```
In drivers/tty/n_tty.c (ffffffff81a4fbd2)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/vt/vt.c (ffffffff81a6e608)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81a8210a)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff83eee805)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/net/phy/phy.c (ffffffff81bdbef5)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
  - drivers/net/phy/phy.c:phy_speed_up
```
```
In drivers/net/phy/phy-c45.c (ffffffff81bde275)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
```
```
In drivers/net/phy/phy_device.c (ffffffff81be4c25)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/phy/bcm84881.c (ffffffff81be9406)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/tun.c (ffffffff81bed30b)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81cb2ae0)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (ffffffff81d2b489)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d310a6)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d3381c)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d36ccc)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff81dba326)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81dc1f88)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/neighbour.c (ffffffff81dd8c85)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/ethtool/ioctl.c (ffffffff81e77255)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_convert_legacy_u32_to_link_mode
```
```
In net/ethtool/bitset.c (ffffffff81e7f26c)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv4/udp.c (ffffffff81ee1bd9)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff81f5cdb2)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
```
In net/mptcp/pm_netlink.c (ffffffff8200a8e6)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
```
```
In net/mptcp/pm_userspace.c (ffffffff8200ded6)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
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
In arch/x86/events/core.c (ffffffff81009e9e)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
```
```
In arch/x86/events/intel/p4.c (ffffffff8101ea6b)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (ffffffff810232ee)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/xen/apic.c (ffffffff81034320)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:physid_set_mask_of_physid
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81038f09)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089414)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092c12)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/smp.c (ffffffff8109b93f)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109cf82)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff836b0e2f)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810a2660)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a6444)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/mm/tlb.c (ffffffff810ccfb4)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/mm/numa.c (ffffffff836c24e5)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff836c7953)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810f13db)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff810fa8a6)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff81140405)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff81157c65)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/build_utility.c (ffffffff81189820)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/irqdesc.c (ffffffff811a6497)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff811b4798)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/clocksource.c (ffffffff811f4f81)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff81203853)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff8120dee3)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff812342ec)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_prstate
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff8125ecd9)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
```
In kernel/watchdog_perf.c (ffffffff8125f701)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/watchdog_perf.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff81287083)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:close_pipe_on_cpu
```
```
In kernel/trace/trace_hwlat.c (ffffffff81294986)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/core.c (ffffffff812e80e7)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/bpf/core.c:alloc_new_pack
```
```
In kernel/bpf/cpumask.c (ffffffff8135d8e5)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_clear
```
```
In mm/swap.c (ffffffff8139ffe8)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/vmscan.c (ffffffff813b0c99)
Location: include/linux/bitmap.h:240
Inline: True
```
```
In mm/percpu.c (ffffffff836e33eb)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/vmalloc.c (ffffffff81414ea4)
Location: include/linux/bitmap.h:240
Inline: True
```
```
In mm/frontswap.c (ffffffff81434c14)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/hugetlb.c (ffffffff8143e18d)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff8144e21c)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/slub.c (ffffffff8145aa9e)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - mm/slub.c:__fill_map
```
```
In mm/khugepaged.c (ffffffff814823ab)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In fs/exec.c (ffffffff814b889c)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - fs/exec.c:mm_init_cid
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/bitmap.h:240
Inline: True
```
```
In block/blk-mq.c (ffffffff8178508f)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In io_uring/io_uring.c (ffffffff817cad9e)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_iowq_aff
```
```
In lib/bitmap.c (ffffffff8180d197)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_parselist
```
```
In drivers/gpio/gpiolib.c (ffffffff81902daa)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81909378)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked
```
```
In drivers/rapidio/rio.c (ffffffff8197005a)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_dma
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a1e130)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a1fdb7)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/numa/hmat.c (ffffffff81a233c7)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a2760f)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffffffff81a39b52)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff8370ebc4)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (ffffffff81a4eb15)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a53760)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81a7cc65)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker
```
```
In drivers/tty/n_tty.c (ffffffff81a99dde)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/vt/vt.c (ffffffff81ab8cf7)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81acd70a)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff83714465)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/net/phy/phy.c (ffffffff81c3290c)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_speed_up
```
```
In drivers/net/phy/phy-c45.c (ffffffff81c35415)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3cb1a)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/phy/bcm84881.c (ffffffff81c41836)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/tun.c (ffffffff81c4583b)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/net/virtio_net.c (ffffffff81c4ced0)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81d1a100)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (ffffffff81d94759)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d9a358)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d9cbac)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81da0081)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff81e2accd)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81e314e8)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/neighbour.c (ffffffff81e49af1)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/ethtool/ioctl.c (ffffffff81ed3145)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_convert_legacy_u32_to_link_mode
```
```
In net/ethtool/bitset.c (ffffffff81edb85c)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv4/udp.c (ffffffff81f415f8)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff81fbcad2)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
```
In net/mptcp/pm_netlink.c (ffffffff82086a46)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
```
```
In net/mptcp/pm_userspace.c (ffffffff8208a7b6)
Location: include/linux/bitmap.h:240
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
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
In arch/x86/events/core.c (ffffffff8100f5be)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_clear_dirty_counters
```
```
In arch/x86/events/intel/p4.c (ffffffff81024b2b)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102941e)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_events
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103f3b9)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81090404)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a052)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/smp.c (ffffffff810a2f49)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a44c2)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff838e1517)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810ad4a4)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:io_apic_unique_id
```
```
In arch/x86/mm/tlb.c (ffffffff810d5684)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/mm/numa.c (ffffffff838f2ee5)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff838f8553)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810fa7ab)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff81103cc6)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/workqueue.c (ffffffff838fba40)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_unbound_cpus_setup
```
```
In kernel/sched/core.c (ffffffff8114b4b5)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff81163eb5)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/build_utility.c (ffffffff81198120)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:sched_domain_debug_one
```
```
In kernel/irq/irqdesc.c (ffffffff811b5fb6)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff811c4618)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/clocksource.c (ffffffff8120b121)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff81219e13)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/time/tick-sched.c (ffffffff839058de)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_init
```
```
In kernel/smp.c (ffffffff81225673)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/cgroup/cpuset.c (ffffffff8124e090)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_exclusive_cpumask
  - kernel/cgroup/cpuset.c:update_exclusive_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:reset_partition_data
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff81278ce9)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
```
In kernel/watchdog_perf.c (ffffffff81279711)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - kernel/watchdog_perf.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff812a214c)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:close_pipe_on_cpu
```
```
In kernel/trace/trace_hwlat.c (ffffffff812affe6)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
```
```
In kernel/bpf/core.c (ffffffff81307cf7)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - kernel/bpf/core.c:alloc_new_pack
```
```
In kernel/bpf/cpumask.c (ffffffff81386685)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_clear
```
```
In mm/swap.c (ffffffff813c9c68)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - mm/swap.c:__lru_add_drain_all
```
```
In mm/vmscan.c (ffffffff813da054)
Location: include/linux/bitmap.h:217
Inline: True
```
```
In mm/percpu.c (ffffffff83915c7b)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/vmalloc.c (ffffffff81441973)
Location: include/linux/bitmap.h:217
Inline: True
```
```
In mm/slub.c (ffffffff81455dfe)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - mm/slub.c:__fill_map
```
```
In mm/hugetlb.c (ffffffff81477e1d)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff81487dbc)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/khugepaged.c (ffffffff814b1751)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In fs/exec.c (ffffffff814eadac)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - fs/exec.c:mm_init_cid
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/bitmap.h:217
Inline: True
```
```
In block/blk-mq.c (ffffffff817c761f)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In io_uring/register.c (ffffffff8182b36e)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - io_uring/register.c:io_register_iowq_aff
```
```
In lib/bitmap.c (ffffffff81852e47)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
```
```
In lib/bitmap-str.c (ffffffff81861842)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - lib/bitmap-str.c:bitmap_parselist
```
```
In drivers/gpio/gpiolib.c (ffffffff8194a978)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8195055a)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values
```
```
In drivers/rapidio/rio.c (ffffffff819ba06a)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_request_dma
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a69440)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a6b0d7)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/numa/hmat.c (ffffffff81a6e0c7)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_update_target_attrs
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a7277f)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffffffff81a853d2)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff83942394)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (ffffffff81a9a7b5)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
  - drivers/dma/dmaengine.c:dma_get_any_slave_channel
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9f510)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81acf105)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker
```
```
In drivers/tty/n_tty.c (ffffffff81aec9fe)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/vt/vt.c (ffffffff81b0b9de)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
```
```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81b207da)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
```
```
In drivers/tty/serial/max310x.c (ffffffff83947ec5)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/net/phy/phy.c (ffffffff81ce75fc)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_speed_up
```
```
In drivers/net/phy/phy-c45.c (ffffffff81cea3e5)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
```
```
In drivers/net/phy/phy_device.c (ffffffff81cf1f1a)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:phy_init_hw
```
```
In drivers/net/phy/bcm84881.c (ffffffff81cf6ec6)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
```
```
In drivers/net/tun.c (ffffffff81cfb14b)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/net/virtio_net.c (ffffffff81d02773)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81dcfe20)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (ffffffff81e4c269)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e52087)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81e5486c)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e57f00)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff81ee8add)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/dev.c (ffffffff81eefc68)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - net/core/dev.c:flush_all_backlogs
```
```
In net/core/neighbour.c (ffffffff81f0880e)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/ethtool/ioctl.c (ffffffff81f96a55)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_convert_legacy_u32_to_link_mode
```
```
In net/ethtool/bitset.c (ffffffff81f9f61f)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
```
In net/ipv4/udp.c (ffffffff82007258)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff82089ef2)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
```
In net/mptcp/pm_netlink.c (ffffffff8215bbc6)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit
  - net/mptcp/pm_netlink.c:fill_remote_addresses_vec
```
```
In net/mptcp/pm_userspace.c (ffffffff82160369)
Location: include/linux/bitmap.h:217
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_zero(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm64/kernel/fpsimd.c (ffff80001008723c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:sve_probe_vqs
```
```
In arch/arm64/kernel/process.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In arch/arm64/kernel/stacktrace.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In arch/arm64/kernel/time.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In arch/arm64/kernel/traps.c (ffff8000100941f0)
Location: include/linux/bitmap.h:219
Inline: True
Direct callers:
  - arch/arm64/kernel/traps.c:dump_backtrace
  - arch/arm64/kernel/traps.c:dump_backtrace
```
```
In arch/arm64/kernel/return_address.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In arch/arm64/kernel/perf_callchain.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In arch/arm64/mm/numa.c (ffff8000100b22f8)
Location: include/linux/bitmap.h:219
Inline: False
Direct callers:
  - arch/arm64/mm/numa.c:numa_init
  - arch/arm64/mm/numa.c:numa_init
  - arch/arm64/mm/numa.c:numa_init
  - arch/arm64/mm/numa.c:numa_init
```
```
In virt/kvm/kvm_main.c (ffff8000100b6ae0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_init
  - virt/kvm/kvm_main.c:kvm_make_all_cpus_request
```
```
In virt/kvm/arm/arm.c (ffff8000100c46e4)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_vcpu_init
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_init
```
```
In virt/kvm/arm/pmu.c (ffff8000100eed40)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - virt/kvm/arm/pmu.c:kvm_pmu_vcpu_reset
```
```
In kernel/fork.c (ffff8000100f1c1c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffff8000100f9b30)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (ffff8000101232d0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
Direct callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/core.c (ffff80001013c7e8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:__arm64_sys_sched_setaffinity
```
```
In kernel/sched/fair.c (ffff800011445088)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
```
```
In kernel/sched/rt.c (ffff8000114450cc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffff800011445140)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/cpupri.c (ffff80001015a044)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffff80001015a898)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/topology.c (ffff80001015d224)
Location: include/linux/bitmap.h:219
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
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
```
```
In kernel/irq/irqdesc.c (ffff8000101774c4)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/proc.c (ffff800010185788)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (ffff8000101881d8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/time/tick-broadcast.c (ffff8000101b2888)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
Direct callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
```
```
In kernel/smp.c (ffff8000101bd7b8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/cgroup/cpuset.c (ffff8000101e3f08)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/watchdog.c (ffff800010207804)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/ring_buffer.c (ffff80001021a138)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffff800010227e9c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/trace_hwlat.c (ffff800010231f88)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (ffff800011451240)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_all_cpus
```
```
In mm/swap.c (ffff8000102c317c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In mm/frontswap.c (ffff80001032a1dc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/hugetlb.c (ffff80001032e338)
Location: include/linux/bitmap.h:219
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffff80001033aa38)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:get_nodes
```
```
In mm/slub.c (ffff800010344ae0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab_slab
```
```
In fs/iomap/buffered-io.c (ffff80001042a590)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In block/blk-mq.c (ffff8000105f20d0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/bitmap.c (ffff80001062bdc8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/cpu_rmap.c (ffff80001066286c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff80001067722c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106ad664)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_init_valid_mask
```
```
In drivers/gpio/gpiolib.c (ffff8000106c3d68)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff800010725790)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_hwirq_alloc
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff8000107262a4)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/video/fbdev/mx3fb.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/acpi/acpi_processor.c (ffff80001076f648)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/processor_perflib.c (ffff8000107a3a18)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/hmat/hmat.c (ffff8000107a5fdc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a8cbc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffff8000107b7824)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffff8000107b89b4)
Location: include/linux/bitmap.h:219
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/dma/mv_xor.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/dma/mv_xor_v2.c (ffff800010809218)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
```
```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081b4c8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe
  - drivers/soc/qcom/rpmh-rsc.c:tcs_invalidate
```
```
In drivers/tty/n_tty.c (ffff800010857474)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/tty/serial/amba-pl011.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffff800011494db8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/base/power/domain.c (ffff800010907f80)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/arch_topology.c (ffff800010920030)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
```
```
In drivers/net/phy/phy.c (ffff8000109d11e4)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
```
```
In drivers/net/phy/phy-c45.c (ffff8000109d2338)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
```
```
In drivers/net/phy/phy_device.c (ffff8000109d5e68)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/net/tun.c (ffff8000109db520)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/input/keyboard/atkbd.c (ffff800010aa2310)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (ffff800010b1aec0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b216b8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffff800010b24180)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/firmware/ti_sci.c (ffff800010b511ac)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/firmware/ti_sci.c:ti_sci_probe
```
```
In drivers/firmware/efi/arm-runtime.c (ffff8000114a78cc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services
```
```
In drivers/of/base.c (ffff800010b693e8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/of/base.c:of_alias_get_alias_list
```
```
In drivers/perf/arm-cci.c (ffff800010b9157c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:__cci_pmu_enable_sync
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b99068)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe
```
```
In net/core/sysctl_net_core.c (ffff800010bc59a0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (ffff800010bd9c60)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
```
In net/core/neighbour.c (ffff800010be4d74)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/core/net-sysfs.c (ffff800010c0b96c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
```
```
In net/ipv4/udp.c (ffff800010c9bdec)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffff800010cff4d4)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
**Symbols:**

```
ffff8000100941f0-ffff8000100941f8: bitmap_zero.constprop.0 (STB_LOCAL)
ffff8000100b22f8-ffff8000100b2320: bitmap_zero (STB_LOCAL)
ffff8000100f7858-ffff8000100f786c: bitmap_zero.constprop.0 (STB_LOCAL)
ffff80001011c7b0-ffff80001011c7bc: bitmap_zero.constprop.0 (STB_LOCAL)
ffff80001015d9e0-ffff80001015d9ec: bitmap_zero.constprop.0 (STB_LOCAL)
ffff8000101b24e8-ffff8000101b24f4: bitmap_zero.constprop.0 (STB_LOCAL)
ffff8000101dfd78-ffff8000101dfda0: bitmap_zero (STB_LOCAL)
ffff80001032e338-ffff80001032e340: bitmap_zero.constprop.0 (STB_LOCAL)
ffff8000107b89b4-ffff8000107b89c0: bitmap_zero.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_zero(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm/mm/context.c (c03224f4)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
```
```
In arch/arm/common/bL_switcher.c (c03277a8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus
```
```
In kernel/fork.c (c0350b1c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (c0355c94)
Location: include/linux/bitmap.h:219
Inline: True
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In kernel/sched/rt.c (c151f234)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (c151f290)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/cpupri.c (c03a6dfc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (c03a7534)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/topology.c (c03a7ab8)
Location: include/linux/bitmap.h:219
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
Location: include/linux/bitmap.h:219
Inline: True
```
```
In kernel/irq/irqdesc.c (c03c93c0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/proc.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In kernel/irq/affinity.c (c03d6c04)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/time/tick-broadcast.c (c03fcfb8)
Location: include/linux/bitmap.h:219
Inline: True
Direct callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
```
```
In kernel/smp.c (c0405544)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/cgroup/cpuset.c (c04251d0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
  - kernel/cgroup/cpuset.c:alloc_trial_cpuset
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/watchdog.c (c04465f8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/ring_buffer.c (c0457660)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (c0465504)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/trace_hwlat.c (c046d604)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (c152bd34)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/swap.c (c04ee20c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/frontswap.c (c0540d0c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/slub.c (c0549fbc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab_slab
```
```
In fs/iomap/buffered-io.c (c05f2f90)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In block/blk-mq.c (c079e224)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/bitmap.c (c07d25ec)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/cpu_rmap.c (c080b4dc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (c084fedc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_init_valid_mask
```
```
In drivers/gpio/gpiolib.c (c0862158)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/video/fbdev/mx3fb.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/dma/mv_xor.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/dma/ti/edma.c (c092ef60)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
```
```
In drivers/soc/qcom/spm.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/soc/tegra/fuse/fuse-tegra20.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/tty/n_tty.c (c095ff94)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/tty/serial/amba-pl011.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/tty/serial/max310x.c (c159568c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/iommu/ipmmu-vmsa.c (c09c26a4)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_probe
```
```
In drivers/base/power/domain.c (c09f2454)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/arch_topology.c (c0a05058)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
```
```
In drivers/mtd/nand/raw/omap2.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/net/phy/phy.c (c0ab8ef8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
```
```
In drivers/net/phy/phy-c45.c (c0aba4a0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
```
```
In drivers/net/phy/phy_device.c (c0abd84c)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/net/tun.c (c0ac2984)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/input/keyboard/atkbd.c (c0b82250)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (c0bf5944)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (c0bfbcf8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/firmware/efi/arm-runtime.c (c15aa044)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services
```
```
In drivers/of/base.c (c0c4d8c8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/of/base.c:of_alias_get_alias_list
```
```
In drivers/perf/arm-cci.c (c0c7a630)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci5xx_pmu_write_counters
  - drivers/perf/arm-cci.c:__cci_pmu_enable_sync
```
```
In sound/core/pcm_dmaengine.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In net/core/ethtool.c (c0cf4c84)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
```
In net/core/neighbour.c (c0cfcff0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In net/ipv4/udp.c (c0da856c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (c0e079ec)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
**Symbols:**

```
c0355c94-c0355cb4: bitmap_zero.constprop.0 (STB_LOCAL)
c03a7878-c03a7890: bitmap_zero.constprop.0 (STB_LOCAL)
c03fcfb8-c03fcfd0: bitmap_zero.constprop.0 (STB_LOCAL)
c0421654-c042166c: bitmap_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_zero(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/powerpc/kernel/setup-common.c (c00000000134a4f4)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
```
```
In arch/powerpc/kernel/smp.c (c000000000054bf0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi
Direct callers:
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
```
```
In arch/powerpc/mm/book3s64/radix_tlb.c (c000000000095e3c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:exit_flush_lazy_tlbs
```
```
In arch/powerpc/mm/numa.c (c0000000000a34c4)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
```
```
In arch/powerpc/mm/slice.c (c0000000000a48bc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/powerpc/mm/slice.c:slice_get_unmapped_area
  - arch/powerpc/mm/slice.c:slice_range_to_mask
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000be434)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_pick_irq_target
```
```
In arch/powerpc/platforms/powernv/idle.c (c0000000000c78c0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (c0000000000dfd20)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000f9f3c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
```
```
In kernel/fork.c (c00000000013736c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (c000000000140b28)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/workqueue.c (c00000000016d1d4)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:workqueue_set_unbound_cpumask
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/core.c (c00000000018aee4)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:__do_sys_sched_setaffinity
```
```
In kernel/sched/fair.c (c0000000013699a0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/rt.c (c000000001369a0c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (c000000001369abc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/cpupri.c (c0000000001ae2e4)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (c0000000001aeb6c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/topology.c (c0000000001b1d68)
Location: include/linux/bitmap.h:219
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
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/irq/irqdesc.c (c0000000001d1084)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/proc.c (c0000000001dfc28)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/irq/proc.c:irq_affinity_hint_proc_show
```
```
In kernel/irq/affinity.c (c0000000001e1f24)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:irq_build_affinity_masks
```
```
In kernel/time/tick-broadcast.c (c000000000218280)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
Direct callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
  - kernel/time/tick-broadcast.c:tick_broadcast_init
```
```
In kernel/smp.c (c000000000223c2c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/cgroup/cpuset.c (c00000000025438c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/watchdog.c (c000000000283fc4)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/trace/ring_buffer.c (c00000000029d43c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (c0000000002ae598)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/trace_hwlat.c (c0000000002bc434)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In kernel/events/core.c (c000000001378cb4)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
```
In mm/swap.c (c00000000037d4ac)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (c0000000003e4afc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/frontswap.c (c00000000040182c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/hugetlb.c (c0000000004082ac)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
Direct callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (c000000000416fe0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (c000000000422c08)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
```
```
In fs/iomap/buffered-io.c (c00000000053b0b4)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In block/blk-mq.c (c0000000007891fc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/bitmap.c (c0000000007ce55c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/cpu_rmap.c (c0000000008169dc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_update
```
```
In drivers/gpio/gpiolib.c (c0000000008404b8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/tty/n_tty.c (c0000000008f583c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/tty/serial/max310x.c (c0000000013a8068)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/base/power/domain.c (c0000000009a7b00)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/net/phy/phy.c (c000000000a90a68)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
```
```
In drivers/net/phy/phy-c45.c (c000000000a922c0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
```
```
In drivers/net/phy/phy_device.c (c000000000a96c20)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/tun.c (c000000000a9e3f0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/input/keyboard/atkbd.c (c000000000b82f44)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (c000000000c0cf50)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq.c (c000000000c15634)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpufreq/cpufreq_ondemand.c (c000000000c189e4)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/of/base.c (c000000000c43574)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/of/base.c:of_alias_get_alias_list
```
```
In net/core/sysctl_net_core.c (c000000000ca0574)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (c000000000cba0fc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
```
In net/core/neighbour.c (c000000000cc67fc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/core/net-sysfs.c (c000000000cf6a04)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/net-sysfs.c:xps_cpus_show
  - net/core/net-sysfs.c:show_rps_map
```
```
In net/ipv4/udp.c (c000000000dade8c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (c000000000e28b54)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
**Symbols:**

```
c000000000054670-c0000000000546a4: bitmap_zero.constprop.0 (STB_LOCAL)
c00000000013e200-c00000000013e23c: bitmap_zero.constprop.0 (STB_LOCAL)
c0000000001b24ec-c0000000001b2520: bitmap_zero.constprop.0 (STB_LOCAL)
c0000000002181c0-c0000000002181f4: bitmap_zero.constprop.0 (STB_LOCAL)
c00000000024e580-c00000000024e5c0: bitmap_zero (STB_LOCAL)
c000000000406e80-c000000000406e98: bitmap_zero.constprop.0 (STB_LOCAL)
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
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/riscv/kernel/smp.c:riscv_cpuid_to_hartid_mask
```
```
In kernel/fork.c (ffffffe0000bec4c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In kernel/sched/rt.c (ffffffe000006eee)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffe000006f70)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/sched/cpupri.c (ffffffe0000ffa98)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_init
```
```
In kernel/sched/cpudeadline.c (ffffffe00010010c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_init
```
```
In kernel/sched/topology.c (ffffffe000100214)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In kernel/irq/irqdesc.c (ffffffe0001124f4)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In kernel/irq/proc.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In kernel/irq/affinity.c (ffffffe00011d99c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/smp.c (ffffffe000140a08)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In kernel/cgroup/cpuset.c (ffffffe00015962a)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
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
In kernel/watchdog.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffe000177e5a)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/trace/trace.c (ffffffe0001827f2)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:__tracing_open
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In mm/frontswap.c (ffffffe000229700)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/hugetlb.c (ffffffe000017ba6)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/slub.c (ffffffe0002389a4)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab_slab
```
```
In fs/iomap/buffered-io.c (ffffffe0002c8050)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In block/blk-mq.c (ffffffe000430a16)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/bitmap.c (ffffffe00045bd2a)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/cpu_rmap.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a883a)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffe0005313f2)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/base/power/domain.c (ffffffe00058daf8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_init
```
```
In drivers/base/arch_topology.c (ffffffe00059ed72)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
  - drivers/base/arch_topology.c:clear_cpu_topology
```
```
In drivers/net/phy/phy.c (ffffffe00061d46e)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
```
```
In drivers/net/phy/phy-c45.c (ffffffe00061eb26)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
```
```
In drivers/net/phy/phy_device.c (ffffffe000622268)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/tun.c (ffffffe0006262cc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/input/keyboard/atkbd.c (ffffffe0006b009a)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (ffffffe0007032b8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/of/base.c (ffffffe00071fabe)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/of/base.c:of_alias_get_alias_list
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In net/core/ethtool.c (ffffffe00076179c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
```
In net/core/neighbour.c (ffffffe000768512)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In net/ipv4/udp.c (ffffffe0007fae9e)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffe000849dd8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_zero(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff81014013)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In arch/x86/xen/apic.c (ffffffff8101f5d0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:physid_set_mask_of_physid
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025c99)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ccac)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064763)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828a68a0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81067310)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b2e8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/mm/tlb.c (ffffffff81088131)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/mm/numa.c (ffffffff8108c03b)
Location: include/linux/bitmap.h:219
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828b2d4e)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096ce7)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff8109d8f1)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/sched/core.c (ffffffff810cdc20)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff810dcff1)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/topology.c (ffffffff810f114d)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (ffffffff8110e42e)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff8111899c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff8113fcff)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff81147438)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff81169338)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff81188576)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff81188d59)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff811a3737)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811abf74)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/swap.c (ffffffff8122b648)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (ffffffff81274715)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/frontswap.c (ffffffff81286500)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/hugetlb.c (ffffffff8128a1e0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
Direct callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff8129557f)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff8129cb0d)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
```
```
In fs/iomap/buffered-io.c (ffffffff8135c0b0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In block/blk-mq.c (ffffffff814eb4e7)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/bitmap.c (ffffffff8151a853)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In drivers/gpio/gpiolib.c (ffffffff81563a6d)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff81605de6)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff81607926)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/hmat/hmat.c (ffffffff816080d5)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816098c0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffffffff816103cb)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff816116db)
Location: include/linux/bitmap.h:219
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8163ad55)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker
```
```
In drivers/tty/n_tty.c (ffffffff8164ec86)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff828e9cae)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/net/phy/phy.c (ffffffff8177cf55)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
```
```
In drivers/net/phy/phy-c45.c (ffffffff8177eb25)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
```
```
In drivers/net/phy/phy_device.c (ffffffff817819b1)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/net/tun.c (ffffffff81785d3b)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81814e1b)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (ffffffff8186454d)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8186a83e)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8186cee0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff818c94ca)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (ffffffff818db9ba)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
```
In net/core/neighbour.c (ffffffff818e257e)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/ipv4/udp.c (ffffffff81988769)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff819ddb60)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
**Symbols:**

```
ffffffff81063500-ffffffff8106351b: bitmap_zero (STB_LOCAL)
ffffffff8108c03b-ffffffff8108c045: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff8109bd30-ffffffff8109bd4b: bitmap_zero (STB_LOCAL)
ffffffff812905be-ffffffff812905c8: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff816116db-ffffffff816116e5: bitmap_zero.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_zero(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff810132c3)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104ce7c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054a53)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8289e9c0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810576d0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105b621)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/mm/tlb.c (ffffffff81076d91)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/mm/numa.c (ffffffff8107ab6b)
Location: include/linux/bitmap.h:219
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828aaecf)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81085767)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff8108c311)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/sched/core.c (ffffffff810bc4b0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff810cc001)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/topology.c (ffffffff810e11bd)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (ffffffff810ff18e)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff81109a0c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff81132a7f)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/time/tick-sched.c (ffffffff828b25da)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_init
```
```
In kernel/smp.c (ffffffff8113a713)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff8115c53c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff8117b6b6)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff8117be99)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff81196707)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff8119ee64)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/swap.c (ffffffff8121e738)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (ffffffff81266685)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/frontswap.c (ffffffff81278360)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/hugetlb.c (ffffffff8127c010)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
Direct callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff8128718f)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff8128e69d)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
```
```
In fs/iomap/buffered-io.c (ffffffff8134cd50)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In block/blk-mq.c (ffffffff814dba37)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/bitmap.c (ffffffff8150ab43)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In drivers/gpio/gpiolib.c (ffffffff815548bd)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff815f0eb6)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff815f2a26)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/hmat/hmat.c (ffffffff815fa225)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fb500)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffffffff8160491b)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff81605c2b)
Location: include/linux/bitmap.h:219
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/tty/n_tty.c (ffffffff8162f0d6)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff828e115d)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/net/phy/phy.c (ffffffff8175cd05)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
```
```
In drivers/net/phy/phy-c45.c (ffffffff8175e8c5)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
```
```
In drivers/net/phy/phy_device.c (ffffffff81761741)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/net/tun.c (ffffffff8176568b)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817dc54b)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (ffffffff8182d1fd)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818334ee)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81835c60)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/hv/channel_mgmt.c (ffffffff81852bfe)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:init_vp_index
  - drivers/hv/channel_mgmt.c:init_vp_index
```
```
In net/core/sysctl_net_core.c (ffffffff8188340a)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (ffffffff818957fa)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
```
In net/core/neighbour.c (ffffffff8189c3be)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/ipv4/udp.c (ffffffff81942229)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff8199a920)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
**Symbols:**

```
ffffffff81053810-ffffffff8105382b: bitmap_zero (STB_LOCAL)
ffffffff8107ab6b-ffffffff8107ab75: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff8108a760-ffffffff8108a77b: bitmap_zero (STB_LOCAL)
ffffffff8128224e-ffffffff81282258: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff81605c2b-ffffffff81605c35: bitmap_zero.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_zero(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff81013fd3)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In arch/x86/xen/apic.c (ffffffff8101f430)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:physid_set_mask_of_physid
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025af9)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d0dc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064c13)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b97b0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810677c0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b798)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/mm/tlb.c (ffffffff810880e1)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/mm/numa.c (ffffffff8108bfeb)
Location: include/linux/bitmap.h:219
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c5c4d)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096c97)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff8109d8a1)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/sched/core.c (ffffffff810cd090)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff810d9371)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/topology.c (ffffffff810ee27d)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (ffffffff8110c31e)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff8111688c)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff8113dbaf)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff811452e8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff81167108)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff81186346)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff81186b29)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff811a1507)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811a9d44)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/swap.c (ffffffff812293e8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (ffffffff812724b5)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/frontswap.c (ffffffff81284310)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/hugetlb.c (ffffffff81287ff0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
Direct callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff8129338f)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff8129a91d)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
```
```
In fs/iomap/buffered-io.c (ffffffff81359b80)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In block/blk-mq.c (ffffffff814e7577)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/bitmap.c (ffffffff815168e3)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In drivers/gpio/gpiolib.c (ffffffff815625dd)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff8162abe6)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff8162cb56)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81631cd0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffffffff8163e1ab)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff8163f4bb)
Location: include/linux/bitmap.h:219
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81668ea5)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker
```
```
In drivers/tty/n_tty.c (ffffffff8167d046)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff828fd7ea)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/net/phy/phy.c (ffffffff817ad305)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
```
```
In drivers/net/phy/phy-c45.c (ffffffff817aeed5)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
```
```
In drivers/net/phy/phy_device.c (ffffffff817b1d61)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/net/tun.c (ffffffff817b60eb)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81853f9b)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (ffffffff818b52dd)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818bb5ce)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818bdc70)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff8191a4ca)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (ffffffff8192c9ea)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
```
In net/core/neighbour.c (ffffffff819335ae)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/ipv4/udp.c (ffffffff819f2f39)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff81a485e0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
**Symbols:**

```
ffffffff810639b0-ffffffff810639cb: bitmap_zero (STB_LOCAL)
ffffffff8108bfeb-ffffffff8108bff5: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff8109bce0-ffffffff8109bcfb: bitmap_zero (STB_LOCAL)
ffffffff8128e3ce-ffffffff8128e3d8: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff8163f4bb-ffffffff8163f4c5: bitmap_zero.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_zero(long unsigned int *dst, unsigned int nbits);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff81014213)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_schedule_events
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In arch/x86/xen/apic.c (ffffffff8101f680)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:physid_set_mask_of_physid
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810265eb)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e5fc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff810661f3)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:disable_smp
  - arch/x86/kernel/smpboot.c:disable_smp
```
```
In arch/x86/kernel/apic/apic.c (ffffffff828b98b1)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81068da0)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_noop.c:physid_set_mask_of_physid
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106ce98)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_ioapic
```
```
In arch/x86/mm/tlb.c (ffffffff8108a368)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
```
```
In arch/x86/mm/numa.c (ffffffff8108e34b)
Location: include/linux/bitmap.h:219
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c8df3)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81098cb6)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:reset_with_ipi
```
```
In kernel/fork.c (ffffffff8109eb37)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/cpu.c (ffffffff810a5731)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
```
In kernel/sched/core.c (ffffffff810d5a20)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:get_user_cpu_mask
```
```
In kernel/sched/fair.c (ffffffff810e4da1)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/sched/topology.c (ffffffff810f92bd)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/irq/irqdesc.c (ffffffff81117a4e)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/migration.c (ffffffff81121ecc)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In kernel/time/tick-broadcast.c (ffffffff8114a6bf)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
```
```
In kernel/smp.c (ffffffff81151ec8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffff811746e9)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/watchdog.c (ffffffff81193c96)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
```
```
In kernel/watchdog_hld.c (ffffffff81194479)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
```
```
In kernel/trace/trace.c (ffffffff811af297)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_hwlat.c (ffffffff811b7b84)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
```
In mm/swap.c (ffffffff812387f8)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
```
```
In mm/page_alloc.c (ffffffff81281de5)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/frontswap.c (ffffffff81294140)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_invalidate_area
```
```
In mm/hugetlb.c (ffffffff81298430)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
Direct callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff812a31ef)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff812aa7fd)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab_slab
```
```
In fs/iomap/buffered-io.c (ffffffff8136d290)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In block/blk-mq.c (ffffffff81500517)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_swqueue
```
```
In lib/bitmap.c (ffffffff81530073)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_parselist
  - lib/bitmap.c:__bitmap_parse
```
```
In drivers/gpio/gpiolib.c (ffffffff8157c4dd)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
```
In drivers/rapidio/rio.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff81644a86)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
```
```
In drivers/acpi/processor_perflib.c (ffffffff816469f6)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
```
In drivers/acpi/hmat/hmat.c (ffffffff81648ef5)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164c000)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
```
```
In drivers/pnp/quirks.c (ffffffff816584fb)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_cmi8330_resources
```
```
In drivers/pnp/pnpacpi/rsparser.c (ffffffff8165980b)
Location: include/linux/bitmap.h:219
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81683465)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume_worker
```
```
In drivers/tty/n_tty.c (ffffffff816976a6)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:n_tty_set_termios
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff82903529)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/net/phy/phy.c (ffffffff817c7295)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:mmd_eee_adv_to_linkmode
```
```
In drivers/net/phy/phy-c45.c (ffffffff817c8e65)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_pma
```
```
In drivers/net/phy/phy_device.c (ffffffff817cbcf1)
Location: include/linux/bitmap.h:219
Inline: True
```
```
In drivers/net/tun.c (ffffffff817d09cb)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_setup
  - drivers/net/tun.c:tun_setup
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8186f4db)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
```
In drivers/opp/cpu.c (ffffffff818d158d)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/opp/cpu.c:dev_pm_opp_get_sharing_cpus
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818d78be)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818d9f80)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In net/core/sysctl_net_core.c (ffffffff8193b70a)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (ffffffff8194e0ba)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:ethtool_convert_link_mode_to_legacy_u32
```
```
In net/core/neighbour.c (ffffffff81954ede)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
```
```
In net/ipv4/udp.c (ffffffff819fb809)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/addrconf.c (ffffffff81a54510)
Location: include/linux/bitmap.h:219
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_dev_get_saddr
```
**Symbols:**

```
ffffffff81064f70-ffffffff81064f8b: bitmap_zero (STB_LOCAL)
ffffffff8108e34b-ffffffff8108e355: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff810a38e0-ffffffff810a38fb: bitmap_zero (STB_LOCAL)
ffffffff8129e15f-ffffffff8129e169: bitmap_zero.constprop.0 (STB_LOCAL)
ffffffff8165980b-ffffffff81659815: bitmap_zero.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
