# Function: <code>bitmap_weight</code>

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
In arch/x86/events/intel/core.c (ffffffff81f5def6)
Location: include/linux/bitmap.h:298
Inline: True
```
```
In arch/x86/xen/trace.c (ffffffff8102a840)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp.c (ffffffff81f6501a)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/alternative.c (ffffffff810369bb)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff81038554)
Location: include/linux/bitmap.h:298
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8103e08f)
Location: include/linux/bitmap.h:298
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff8104160b)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045ac9)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8104fea3)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81050518)
Location: include/linux/bitmap.h:298
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81050971)
Location: include/linux/bitmap.h:298
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff810513a6)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:smp_announce
  - arch/x86/kernel/smpboot.c:smp_announce
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81052a84)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81f71367)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a403)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/crash.c (ffffffff8105dce5)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/kernel/hpet.c (ffffffff8107d368)
Location: include/linux/bitmap.h:298
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810747e1)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff81f78e5a)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff81f79138)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/cpu.c (ffffffff81081515)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:disable_nonboot_cpus
```
```
In kernel/workqueue.c (ffffffff81097702)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
  - kernel/workqueue.c:workqueue_cpu_up_callback
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
```
```
In kernel/pid.c (ffffffff81f7c7e6)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/pid.c:pidmap_init
  - kernel/pid.c:pidmap_init
```
```
In kernel/sched/core.c (ffffffff810a58a6)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/sched/core.c:sd_degenerate
  - kernel/sched/core.c:register_sched_domain_sysctl
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:set_cpus_allowed_common
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
```
```
In kernel/sched/fair.c (ffffffff810b2166)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:update_max_interval
```
```
In kernel/sched/rt.c (ffffffff810bf948)
Location: include/linux/bitmap.h:298
Inline: True
```
```
In kernel/locking/qspinlock.c (ffffffff81f7e61e)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/power/swap.c (ffffffff810d32ee)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk.c (ffffffff81f7ed5c)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/rcu/tree.c (ffffffff810e58d1)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/clockevents.c (ffffffff810fb98f)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
```
```
In kernel/time/tick-common.c (ffffffff810fcbaa)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_unfreeze
```
```
In kernel/time/tick-sched.c (ffffffff810fede8)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff81f80b36)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff81103cba)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_announce
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff81120111)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/stop_machine.c:__stop_cpus
  - kernel/stop_machine.c:stop_machine
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
```
```
In kernel/kprobes.c (ffffffff8112f40b)
Location: include/linux/bitmap.h:298
Inline: True
```
```
In kernel/debug/debug_core.c (ffffffff8112fc7b)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81136b7f)
Location: include/linux/bitmap.h:298
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81138296)
Location: include/linux/bitmap.h:298
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8113935a)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/trace/trace.c (ffffffff8114cb10)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_event_info
  - kernel/trace/trace.c:print_trace_header
```
```
In kernel/events/core.c (ffffffff811813f0)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/padata.c (ffffffff8118996a)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_reorder
```
```
In kernel/membarrier.c (ffffffff8118b4bf)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - kernel/membarrier.c:SyS_membarrier
```
```
In mm/page_alloc.c (ffffffff81f8751a)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/page-writeback.c (ffffffff8119b6ae)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff811ad6a6)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - mm/vmstat.c:calculate_pressure_threshold
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/mm_init.c (ffffffff8181d842)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff81208d28)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/vmalloc.c (ffffffff811cd1f4)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/hugetlb.c (ffffffff811dabf1)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff811e0451)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_relative_nodemask
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:node_random
```
```
In mm/slub.c (ffffffff811eccb6)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff811efb07)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In fs/aio.c (ffffffff8125c94c)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:SyS_io_setup
```
```
In fs/proc/stat.c (ffffffff81283346)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In security/apparmor/lsm.c (ffffffff81f9956c)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In block/blk-mq-tag.c (ffffffff813c6f9a)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_unused_tags
```
```
In lib/cpumask.c (ffffffff813e91f6)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
```
In lib/bitmap.c (ffffffff813f9c24)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_bitremap
```
```
In lib/memweight.c (ffffffff813fe150)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/percpu_ida.c (ffffffff813ffa7f)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/rhashtable.c (ffffffff8140010b)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_alloc
```
```
In lib/percpu_counter.c (ffffffff81f9e5be)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/acpi/acpi_processor.c (ffffffff814823e4)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/numa.c (ffffffff8148b142)
Location: include/linux/bitmap.h:298
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff814ace98)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/iommu/intel-iommu.c (ffffffff81536ce6)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
```
```
In drivers/nvdimm/region.c (ffffffff8159acdb)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff8159fcee)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/net/virtio_net.c (ffffffff815f16b0)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
```
In drivers/net/xen-netfront.c (ffffffff81fb01b1)
Location: include/linux/bitmap.h:298
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff8164cf64)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/input/input.c (ffffffff81667c5d)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/thermal/thermal_core.c (ffffffff81684c89)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
```
```
In drivers/md/dm-stats.c (ffffffff816adb78)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff816b3829)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_timer
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff816b47e4)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_timer
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff816b551e)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_timer
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff816b688c)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff816b7788)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81fb4963)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In net/core/dev.c (ffffffff81715c56)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In net/core/flow.c (ffffffff81735242)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/core/net-sysfs.c (ffffffff817369a7)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/inet_hashtables.c (ffffffff817620b6)
Location: include/linux/bitmap.h:298
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
In arch/x86/events/amd/core.c (ffffffff81f855c0)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101550c)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_cpu_starting
```
```
In arch/x86/xen/trace.c (ffffffff81028aff)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp.c (ffffffff8102b0d3)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/alternative.c (ffffffff81f90d0f)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff81037862)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8103deb3)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81041562)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045848)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81050023)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81050693)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81050b41)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff810525e1)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:smp_announce
  - arch/x86/kernel/smpboot.c:smp_announce
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81052ce2)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81f99b27)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a793)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/crash.c (ffffffff8105dbb4)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/kernel/hpet.c (ffffffff8107ee54)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81075f8c)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff81fa1585)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff81fa188e)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/cpu.c (ffffffff81084df0)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/workqueue.c (ffffffff81fa5422)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:wq_clamp_max_active
```
```
In kernel/pid.c (ffffffff81fa55a9)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/pid.c:pidmap_init
  - kernel/pid.c:pidmap_init
```
```
In kernel/sched/core.c (ffffffff810b1f90)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:sd_degenerate
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/fair.c (ffffffff810c1db6)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/rt.c (ffffffff810c3279)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810cb346)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/locking/qspinlock.c (ffffffff81fa7507)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/power/swap.c (ffffffff810d809e)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk.c (ffffffff81fa7ce9)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/nmi.c (ffffffff810df3e8)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/printk/nmi.c:printk_nmi_flush_on_panic
```
```
In kernel/irq/affinity.c (ffffffff810e8e4f)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_mask
  - kernel/irq/affinity.c:irq_create_affinity_mask
```
```
In kernel/rcu/tree.c (ffffffff810eed36)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/clockevents.c (ffffffff81103707)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff81103fea)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff81106187)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff81fa9b68)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff8110b556)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/smp.c:smp_announce
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff81128842)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffffffff811376cb)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In kernel/debug/debug_core.c (ffffffff81137f85)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8113f00f)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8114078a)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8114184f)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/trace/trace.c (ffffffff81159976)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/bpf/syscall.c (ffffffff81180b9a)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffff81186390)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff81187869)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffff81187f4b)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/events/core.c (ffffffff811931c3)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/padata.c (ffffffff8119c3aa)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/membarrier.c (ffffffff8119dbbf)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/membarrier.c:SyS_membarrier
```
```
In mm/page_alloc.c (ffffffff81fb0449)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/page-writeback.c (ffffffff811b075e)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff811c6a13)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/mm_init.c (ffffffff81897c2a)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff81fb24aa)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/vmalloc.c (ffffffff811ebcb6)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/hugetlb.c (ffffffff811f9daa)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff811ffeea)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/slub.c (ffffffff8120c40c)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff8120ef52)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In fs/aio.c (ffffffff81285a0d)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:SyS_io_setup
```
```
In fs/proc/stat.c (ffffffff812b03a6)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff813257c6)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_max_decompressors
```
```
In security/apparmor/lsm.c (ffffffff81fc42df)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In block/blk-mq-tag.c (ffffffff8140b1cc)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_unused_tags
```
```
In lib/cpumask.c (ffffffff8142f43e)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
```
In lib/nodemask.c (ffffffff81433f0a)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In lib/bitmap.c (ffffffff81440d14)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
```
```
In lib/memweight.c (ffffffff814457c0)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/percpu_ida.c (ffffffff8144716f)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/rhashtable.c (ffffffff81447892)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_alloc
```
```
In lib/percpu_counter.c (ffffffff81fc9a47)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/acpi/acpi_processor.c (ffffffff814d0ef2)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/numa.c (ffffffff814d9f7c)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff814fca18)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158afed)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
```
```
In drivers/block/xen-blkfront.c (ffffffff81fda48f)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff815f0d22)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff815f5c87)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/net/virtio_net.c (ffffffff816510d0)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81fdcd16)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff816ad894)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/input/input.c (ffffffff816c9486)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/thermal/thermal_core.c (ffffffff816e6f02)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
```
```
In drivers/md/dm.c (ffffffff81703b4f)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-stats.c (ffffffff8170e069)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81716db1)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817183d6)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81719266)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81fe159f)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In net/core/dev.c (ffffffff8177ea36)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In net/core/ethtool.c (ffffffff8178929f)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
```
```
In net/core/flow.c (ffffffff817a13cb)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/core/net-sysfs.c (ffffffff817a2b79)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ce876)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
In arch/x86/events/amd/core.c (ffffffff81fc09f0)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/trace.c (ffffffff8102a6dd)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp.c (ffffffff8102b7a3)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/alternative.c (ffffffff81035a06)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff810375f2)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8103d763)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81040fb3)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810444ac)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104748e)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81052b03)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81052f03)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff810533f9)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054ee0)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055948)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81083071)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d693)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/crash.c (ffffffff81060c3c)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/kernel/hpet.c (ffffffff810834fa)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81079b78)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff81fdc354)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff81fdce6f)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/cpu.c (ffffffff81089d94)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/workqueue.c (ffffffff810a34e2)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/pid.c (ffffffff811ae2f8)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b8352)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
```
```
In kernel/sched/fair.c (ffffffff810bc261)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810c92d9)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810d1376)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d45af)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/locking/qspinlock.c (ffffffff81fe31e8)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/power/swap.c (ffffffff810deb9e)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk.c (ffffffff811ae4c3)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In kernel/printk/nmi.c (ffffffff810e59d8)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/printk/nmi.c:printk_nmi_flush_on_panic
```
```
In kernel/irq/affinity.c (ffffffff810efdef)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff810f5ea6)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/clockevents.c (ffffffff8110adfa)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff8110b6ea)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8110d8e7)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff81fe5b1f)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff81112aac)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff811324f2)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffffffff8114144b)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In kernel/debug/debug_core.c (ffffffff81141d15)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81148ddf)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8114a57a)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8114b633)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/trace/trace.c (ffffffff81164196)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/bpf/syscall.c (ffffffff8118ccc0)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffff811950aa)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff81195aac)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffff81195f0b)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81196c94)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_percpu_lru_populate
```
```
In kernel/events/core.c (ffffffff811a29a3)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/padata.c (ffffffff811ac194)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/membarrier.c (ffffffff811ad5df)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - kernel/membarrier.c:SyS_membarrier
```
```
In mm/page_alloc.c (ffffffff81fed11b)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/page-writeback.c (ffffffff811c0d4e)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff811d6c55)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/mm_init.c (ffffffff818cc2c8)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff81240f44)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In mm/vmalloc.c (ffffffff811fb364)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/hugetlb.c (ffffffff8120a861)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff81ff2baf)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/slub.c (ffffffff8121e42b)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff81221056)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In fs/aio.c (ffffffff81299b6e)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/proc/stat.c (ffffffff812c5d96)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In security/apparmor/lsm.c (ffffffff82000d98)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In lib/cpumask.c (ffffffff8144b65d)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
```
In lib/nodemask.c (ffffffff81450191)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In lib/bitmap.c (ffffffff8145df34)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
```
```
In lib/memweight.c (ffffffff81463fb0)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/percpu_ida.c (ffffffff81465999)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/rhashtable.c (ffffffff8146626e)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In lib/percpu_counter.c (ffffffff814783c9)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In lib/sbitmap.c (ffffffff81482337)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_weight
```
```
In drivers/acpi/acpi_processor.c (ffffffff814f2fa8)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/numa.c (ffffffff814fc832)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff8151f1d0)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff815b873d)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
```
```
In drivers/block/xen-blkfront.c (ffffffff82017ef3)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff8161e0db)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff81623a07)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/net/xen-netfront.c (ffffffff8201a92c)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff816dac1c)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_msix
```
```
In drivers/input/input.c (ffffffff816f7466)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/thermal/thermal_core.c (ffffffff8171794b)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
```
```
In drivers/md/dm.c (ffffffff81735a08)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-stats.c (ffffffff8173f80e)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81748b88)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8174a2c8)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8174b8aa)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8201f2b1)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In net/core/dev.c (ffffffff817adca6)
Location: include/linux/bitmap.h:311
Inline: True
```
```
In net/core/ethtool.c (ffffffff817b6b4f)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
```
```
In net/core/flow.c (ffffffff817cfcf8)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_lookup
```
```
In net/core/net-sysfs.c (ffffffff817d1597)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fe686)
Location: include/linux/bitmap.h:311
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
In arch/x86/events/amd/core.c (ffffffff820a0c0f)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/trace.c (ffffffff810289eb)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp.c (ffffffff8102907b)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/xen/smp_pv.c (ffffffff81029abc)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff810339b6)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff81035689)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8103b653)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff8103f0d5)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043457)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81047017)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104c66f)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81052623)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81052a13)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81052f8a)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff810547d6)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055256)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056f60)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105cd93)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In arch/x86/kernel/ftrace.c (ffffffff8105d101)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In arch/x86/kernel/crash.c (ffffffff8105fc1f)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/kernel/hpet.c (ffffffff81065178)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81078428)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff820bd36b)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff820bde79)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/cpu.c (ffffffff81086c5b)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/workqueue.c (ffffffff810a07f2)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/pid.c (ffffffff810a3ea2)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b36ee)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/fair.c (ffffffff810b6cc1)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810c3369)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c92bd)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
```
```
In kernel/sched/topology.c (ffffffff810ccd1c)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/debug.c (ffffffff810d0496)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d37fd)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/locking/qspinlock.c (ffffffff820c3be4)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/power/swap.c (ffffffff810ddc4e)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk.c (ffffffff810e4aa0)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In kernel/printk/printk_safe.c (ffffffff810e4f28)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/affinity.c (ffffffff810efda3)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff810f6b96)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/clockevents.c (ffffffff8110ccfb)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff8110d5da)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8110f7e7)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff820c6430)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff81113f7d)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff81133ad2)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffffffff81142dc3)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff81143555)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8114abef)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8114c47b)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8114d598)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/trace/trace.c (ffffffff81168784)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:print_trace_header
```
```
In kernel/bpf/syscall.c (ffffffff8119301b)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/bpf/hashtab.c (ffffffff8119c253)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff8119cf87)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffff8119d47b)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8119e094)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/events/core.c (ffffffff811aa012)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/padata.c (ffffffff811b37c0)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/membarrier.c (ffffffff811b4abf)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - kernel/membarrier.c:SyS_membarrier
```
```
In mm/page_alloc.c (ffffffff820ced86)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/page-writeback.c (ffffffff811c8ebe)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff811dfab5)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/mm_init.c (ffffffff81903843)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff811e4bb8)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In mm/swap_slots.c (ffffffff811ec9ca)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/vmalloc.c (ffffffff812060a4)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/hugetlb.c (ffffffff81215bd9)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff820d5279)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/slub.c (ffffffff81229f37)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff8122c91d)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In fs/aio.c (ffffffff812a78ce)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/proc/stat.c (ffffffff812d2fa6)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In security/apparmor/lsm.c (ffffffff820e467a)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In lib/bitmap.c (ffffffff81463234)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
```
```
In lib/memweight.c (ffffffff8146902d)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/percpu_ida.c (ffffffff8146a76c)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/rhashtable.c (ffffffff8146b3eb)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In lib/percpu_counter.c (ffffffff81481709)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In lib/sbitmap.c (ffffffff8148b667)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_weight
```
```
In drivers/acpi/acpi_processor.c (ffffffff81500be2)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/numa.c (ffffffff8150cb9d)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81530a28)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/iommu/intel-iommu.c (ffffffff815ce4d0)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
```
```
In drivers/block/xen-blkfront.c (ffffffff820f9cde)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff8163263b)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff8163876b)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/net/xen-netfront.c (ffffffff820fc9d4)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff816f02cb)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/input/input.c (ffffffff8170cfa2)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/thermal/thermal_core.c (ffffffff8172fbfb)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
```
```
In drivers/md/dm.c (ffffffff8174ee38)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-stats.c (ffffffff8175959e)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81767248)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817687d4)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8176a0ad)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff82101da3)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff817836e0)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (ffffffff817cc806)
Location: include/linux/bitmap.h:308
Inline: True
```
```
In net/core/ethtool.c (ffffffff817d556f)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
```
```
In net/core/flow.c (ffffffff817ef0f6)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_lookup
```
```
In net/core/net-sysfs.c (ffffffff817f0969)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181ecb6)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In lib/cpumask.c (ffffffff818ebd1d)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
```
In lib/nodemask.c (ffffffff818eff31)
Location: include/linux/bitmap.h:308
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/x86/events/amd/core.c (ffffffff826a6d5a)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102473a)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/trace.c (ffffffff81028c01)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp.c (ffffffff8102928b)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/xen/smp_pv.c (ffffffff81029cdc)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102a211)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102ae69)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/alternative.c (ffffffff81035d06)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff810379d9)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8103e073)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff8104230a)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81046ac2)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104aac3)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104ff1f)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052adf)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81056273)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81056703)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81056cba)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff810585ce)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81059026)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105abcd)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81060a53)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In arch/x86/kernel/ftrace.c (ffffffff81060da1)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In arch/x86/kernel/crash.c (ffffffff81063c6f)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/kernel/hpet.c (ffffffff8106930a)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107e778)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff826c41aa)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff826c4cb0)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/cpu.c (ffffffff8108d9f8)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/workqueue.c (ffffffff810a7082)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/pid.c (ffffffff810aa480)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In kernel/sched/core.c (ffffffff810ba95e)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
```
```
In kernel/sched/fair.c (ffffffff810be031)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810ca636)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810d09ad)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
```
```
In kernel/sched/topology.c (ffffffff810d352b)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/debug.c (ffffffff810d82e1)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810db3d5)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/sched/membarrier.c (ffffffff810dbe52)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:SyS_membarrier
  - kernel/sched/membarrier.c:SyS_membarrier
```
```
In kernel/locking/qspinlock.c (ffffffff826cbe33)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/power/swap.c (ffffffff810e5ebe)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk.c (ffffffff810ecd3f)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In kernel/printk/printk_safe.c (ffffffff810ed188)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/affinity.c (ffffffff810f8953)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff81100bb6)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_scheduler_starting
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (ffffffff81117f7b)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff8111885a)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8111aac7)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff826ceab0)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff8111f50d)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff81140882)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffffffff8114fa73)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff81150205)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81157b6f)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81158d1b)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81159e19)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/trace/trace.c (ffffffff81175714)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:print_trace_header
```
```
In kernel/bpf/syscall.c (ffffffff811a0cc2)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/bpf/hashtab.c (ffffffff811abb61)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811acb70)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffff811ad02b)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811adca4)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/devmap.c (ffffffff811af498)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811afad7)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In kernel/events/core.c (ffffffff811bd905)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/padata.c (ffffffff811c7d0f)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder_timer
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In mm/page_alloc.c (ffffffff826d77a1)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/page-writeback.c (ffffffff811ddcbe)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff811f58c5)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/mm_init.c (ffffffff8198d84e)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff811f9d43)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_refresh_hint
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
```
In mm/swap_slots.c (ffffffff81202d2a)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/vmalloc.c (ffffffff8121edc4)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/hugetlb.c (ffffffff8123080c)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff826dde3f)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/slub.c (ffffffff812450e7)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff81248151)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In fs/aio.c (ffffffff812cae5e)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/proc/stat.c (ffffffff812f77a6)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In security/apparmor/lsm.c (ffffffff826ed319)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In lib/bitmap.c (ffffffff8148f144)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
```
```
In lib/memweight.c (ffffffff814952fd)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/percpu_ida.c (ffffffff81496a54)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/rhashtable.c (ffffffff814976db)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In lib/percpu_counter.c (ffffffff814bd549)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In lib/sbitmap.c (ffffffff814c7787)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_weight
```
```
In drivers/acpi/acpi_processor.c (ffffffff81542fb7)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/x86/apple.c (ffffffff8154f78b)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa.c (ffffffff8154fafd)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81591a5a)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/xen/time.c (ffffffff815bc674)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/iommu/intel-iommu.c (ffffffff81635320)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
```
```
In drivers/block/xen-blkfront.c (ffffffff827034c1)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff8169afab)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff816a0e6b)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/net/xen-netfront.c (ffffffff82706149)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff8175c48b)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/input/input.c (ffffffff8177e1e2)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (ffffffff817c1058)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-stats.c (ffffffff817cb7fe)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff817dd165)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817de6c4)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817dff8d)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8270b3f3)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff817f9aa0)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (ffffffff81845e86)
Location: include/linux/bitmap.h:326
Inline: True
```
```
In net/core/ethtool.c (ffffffff8184f9bf)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
```
```
In net/core/net-sysfs.c (ffffffff8186bf69)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189dc66)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In lib/cpumask.c (ffffffff81971cfd)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
```
In lib/nodemask.c (ffffffff81976381)
Location: include/linux/bitmap.h:326
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/x86/events/amd/core.c (ffffffff826cfee6)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025645)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/trace.c (ffffffff81029643)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp.c (ffffffff81029cef)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a777)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102afe0)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102ba2f)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/alternative.c (ffffffff81036c82)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff81038912)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8103f613)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff810441f9)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81049013)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104d827)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff81052b85)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055929)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810590d6)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81059524)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81059b1b)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105b24a)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8105be94)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105dada)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81063b42)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/ftrace.c (ffffffff81063ec0)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:run_sync
```
```
In arch/x86/kernel/hpet.c (ffffffff8106bf78)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810817a9)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff826ee445)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff826eef36)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/cpu.c (ffffffff810917f6)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/workqueue.c (ffffffff826f3c0d)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_clamp_max_active
```
```
In kernel/pid.c (ffffffff810b10af)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In kernel/sched/core.c (ffffffff810ba360)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/sched/core.c:cpumask_weight
```
```
In kernel/sched/fair.c (ffffffff810c5d60)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810d3376)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810d8ee6)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
```
```
In kernel/sched/topology.c (ffffffff810db1f1)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sd_degenerate
```
```
In kernel/sched/debug.c (ffffffff810df75e)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810e362d)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/sched/membarrier.c (ffffffff810e4492)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/locking/qspinlock.c (ffffffff826f5f9b)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/power/swap.c (ffffffff810ee36f)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk.c (ffffffff810f4e88)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In kernel/printk/printk_safe.c (ffffffff810f5413)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/affinity.c (ffffffff81100ed0)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
```
```
In kernel/rcu/tree.c (ffffffff8110731e)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_scheduler_starting
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (ffffffff81124a5a)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff811253fa)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff81127848)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff826f91ed)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff8112c844)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
```
```
In kernel/kexec_file.c (ffffffff8113a025)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/stop_machine.c (ffffffff8114f1c2)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffffffff8115e5b3)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff8115ed95)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81166765)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81167931)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81168a48)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/trace/trace.c (ffffffff811847cb)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:print_trace_header
```
```
In kernel/bpf/syscall.c (ffffffff811b4271)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffff811c3038)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811c4076)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffff811c4595)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811c5217)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/devmap.c (ffffffff811c9cde)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811ca5d7)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffff811cb13e)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In kernel/events/core.c (ffffffff811ddb7d)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/padata.c (ffffffff811e8131)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder_timer
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In mm/page_alloc.c (ffffffff82701be2)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/page-writeback.c (ffffffff811ff242)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff81216b45)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/mm_init.c (ffffffff819ea10d)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff81219440)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_cnt_pop_pages
  - mm/percpu.c:pcpu_cnt_pop_pages
```
```
In mm/vmalloc.c (ffffffff81241694)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/swap_slots.c (ffffffff8124eddc)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/hugetlb.c (ffffffff827080aa)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff82708399)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/slub.c (ffffffff81269253)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff8126ba85)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In fs/aio.c (ffffffff812f5376)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/crypto.c (ffffffff8270d81c)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/proc/stat.c (ffffffff81324b45)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In security/apparmor/lsm.c (ffffffff82717647)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In lib/bitmap.c (ffffffff814c3d80)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
```
```
In lib/memweight.c (ffffffff814ca6bf)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/percpu_ida.c (ffffffff814cbdcf)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/bucket_locks.c (ffffffff814cdcc0)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - lib/bucket_locks.c:alloc_bucket_spinlocks
```
```
In lib/percpu_counter.c (ffffffff814efda0)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In lib/sbitmap.c (ffffffff814f8467)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_weight
```
```
In drivers/acpi/acpi_processor.c (ffffffff81578d06)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/x86/apple.c (ffffffff81586042)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa.c (ffffffff8158639d)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff815c8dc8)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/xen/time.c (ffffffff815f4d24)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/iommu/intel-iommu.c (ffffffff816708f9)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
```
```
In drivers/block/xen-blkfront.c (ffffffff8272d241)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff816d7538)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff816dd67a)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/net/xen-netfront.c (ffffffff8272ff8a)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netif_init
```
```
In drivers/usb/host/xhci.c (ffffffff8179ce91)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/input/input.c (ffffffff817bf303)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (ffffffff818096d5)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-stats.c (ffffffff818145f4)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81825dd8)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81827342)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81828f22)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff827356d1)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818430f4)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (ffffffff8188f525)
Location: include/linux/bitmap.h:357
Inline: True
```
```
In net/core/ethtool.c (ffffffff8189b4da)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
```
```
In net/core/net-sysfs.c (ffffffff818bc6d9)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f1865)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In lib/cpumask.c (ffffffff819ce0a0)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
```
In lib/nodemask.c (ffffffff819d2b40)
Location: include/linux/bitmap.h:357
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/x86/events/amd/core.c (ffffffff82885f57)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81024ce5)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/trace.c (ffffffff81029c23)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp.c (ffffffff8102a2cf)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102adb7)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8288e1fb)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102b710)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102c47b)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/alternative.c (ffffffff81037e92)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff81039b82)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81040d63)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81045bf9)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104af1a)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810501f5)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052fc9)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81058175)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8105ed26)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff8105f1d4)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff8105f79b)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff81060eca)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81061b74)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106376b)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81069842)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/ftrace.c (ffffffff81069b70)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:run_sync
```
```
In arch/x86/kernel/hpet.c (ffffffff81071d08)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff828a038d)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81073924)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff81080f34)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810883b9)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff828a5133)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff828a5c24)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/cpu.c (ffffffff81099ad6)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/workqueue.c (ffffffff828aa9f5)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_clamp_max_active
```
```
In kernel/pid.c (ffffffff810ba1ef)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c3460)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/sched/core.c:cpumask_weight
```
```
In kernel/sched/fair.c (ffffffff810ce700)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810dc716)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810e29e6)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
```
```
In kernel/sched/topology.c (ffffffff810e4dee)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sd_degenerate
```
```
In kernel/sched/debug.c (ffffffff810e9ede)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810edcfd)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/sched/membarrier.c (ffffffff810eec63)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/locking/qspinlock.c (ffffffff828aceac)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/power/swap.c (ffffffff810f99df)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk.c (ffffffff81100648)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/printk/printk_safe.c (ffffffff81100bb3)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/affinity.c (ffffffff8110c7e4)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
```
```
In kernel/rcu/tree.c (ffffffff811130fe)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_scheduler_starting
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (ffffffff8113015a)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff81130aea)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff81132f38)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff828b00c7)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff81138114)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
```
```
In kernel/kexec_file.c (ffffffff811458f5)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cpuset.c (ffffffff811577a6)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/stop_machine.c (ffffffff8115bea2)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffffffff8116b12b)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff8116bac5)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811734c5)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81174761)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8117588f)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/trace/trace.c (ffffffff81190deb)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/bpf/syscall.c (ffffffff811c5488)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/hashtab.c (ffffffff811d4b04)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811d5c76)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffff811d6165)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811d6e17)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffff811d82f6)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811dd5de)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811ddef7)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffff811dea4e)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/events/core.c (ffffffff811edf7d)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/padata.c (ffffffff811f8e77)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder_timer
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In mm/page_alloc.c (ffffffff828b86db)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/page-writeback.c (ffffffff81211b02)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff81229a55)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/mm_init.c (ffffffff81a25390)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff8122c3a0)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_cnt_pop_pages
  - mm/percpu.c:pcpu_cnt_pop_pages
```
```
In mm/vmalloc.c (ffffffff81255d94)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/swap_slots.c (ffffffff812632c4)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/hugetlb.c (ffffffff828bf47c)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffffffff8126f24c)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/slub.c (ffffffff81278c6b)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff81a2204a)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In fs/aio.c (ffffffff8130a466)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/crypto.c (ffffffff828c4a42)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/proc/stat.c (ffffffff8133bce5)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In security/apparmor/lsm.c (ffffffff828cf017)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In lib/bitmap.c (ffffffff814d8470)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
```
```
In lib/memweight.c (ffffffff814df3f2)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/bucket_locks.c (ffffffff814e2590)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/percpu_counter.c (ffffffff81503cc0)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In lib/sbitmap.c (ffffffff8150c7f1)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
```
```
In drivers/acpi/acpi_processor.c (ffffffff8159095f)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/x86/apple.c (ffffffff8159e364)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa.c (ffffffff8159e6ad)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff815e2398)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/xen/time.c (ffffffff8160fb84)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168ec99)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
```
```
In drivers/block/xen-blkfront.c (ffffffff828e5bc1)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff816f9408)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffff816ff9da)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/net/xen-netfront.c (ffffffff828e8c47)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netif_init
```
```
In drivers/usb/host/xhci.c (ffffffff817c3271)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/input/input.c (ffffffff817e6763)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (ffffffff818357e5)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-stats.c (ffffffff818405fc)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81851cb8)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81853242)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81854fb2)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff828ef118)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff828ef5fd)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8186f0f9)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (ffffffff818b2dd2)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/ethtool.c (ffffffff818bcc1a)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
```
```
In net/core/net-sysfs.c (ffffffff818e3839)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191f445)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In lib/cpumask.c (ffffffff81a07560)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
```
In lib/nodemask.c (ffffffff81a0c1c0)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/x86/events/amd/core.c (ffffffff81009144)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81022c40)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/xen/trace.c (ffffffff8102a6f0)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:cpumask_weight
```
```
In arch/x86/xen/smp.c (ffffffff8102baf0)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cb8d)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102ce1b)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102d4b1)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102d6a0)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:cpumask_weight
```
```
In arch/x86/kernel/alternative.c (ffffffff81039da2)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff8103b290)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81043440)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff810485a0)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:cpumask_weight
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cb20)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81053260)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056070)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b715)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81062126)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81062290)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff810629f0)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063010)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpumask_weight
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81064c40)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:cpumask_weight
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066de6)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d022)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106d420)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:run_sync
```
```
In arch/x86/kernel/hpet.c (ffffffff8107585e)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810771a3)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8107749e)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff81084b25)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108ba20)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:cpumask_weight
```
```
In arch/x86/mm/numa.c (ffffffff8108c404)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In arch/x86/mm/amdtopology.c (ffffffff8108c425)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/cpu.c (ffffffff8109c1b0)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/workqueue.c (ffffffff810bd1a9)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
```
```
In kernel/pid.c (ffffffff810c00ff)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d2d95)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/fair.c (ffffffff810e1f25)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/rt.c (ffffffff810e2c50)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/sched/rt.c:cpumask_weight
```
```
In kernel/sched/deadline.c (ffffffff810e55e0)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/sched/deadline.c:cpumask_weight
```
```
In kernel/sched/topology.c (ffffffff810eb5e5)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/sched/topology.c:sd_degenerate
```
```
In kernel/sched/debug.c (ffffffff810f0970)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f4a10)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:cpumask_weight
```
```
In kernel/sched/membarrier.c (ffffffff810f5710)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/locking/qspinlock.c (ffffffff810f9247)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/power/swap.c (ffffffff81102090)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/printk/printk.c (ffffffff81108e2a)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/printk/printk_safe.c (ffffffff81109373)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/affinity.c (ffffffff811155a0)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/irq/affinity.c:cpumask_weight
```
```
In kernel/rcu/tree.c (ffffffff8111db55)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_scheduler_starting
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (ffffffff8113a0f0)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/time/clockevents.c:cpumask_weight
```
```
In kernel/time/tick-common.c (ffffffff8113aea0)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/time/tick-sched.c (ffffffff8113cda0)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/futex.c (ffffffff8114293f)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/smp.c (ffffffff81142bf0)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/smp.c:cpumask_weight
```
```
In kernel/kexec_file.c (ffffffff8114f770)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff8115fea0)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpumask_weight
```
```
In kernel/stop_machine.c (ffffffff81167bb0)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpumask_weight
```
```
In kernel/kprobes.c (ffffffff81176080)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/debug/debug_core.c (ffffffff81178400)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8117da60)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81180c70)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81182230)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/trace/trace.c (ffffffff8119a210)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d2ae0)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811e7740)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811ea4b0)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (ffffffff811eaa20)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811eb110)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff811ecd50)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811f2be0)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811f34f0)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffff811f4320)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/events/core.c (ffffffff811fe590)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In kernel/padata.c (ffffffff8120f9b0)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - kernel/padata.c:cpumask_weight
```
```
In mm/page-writeback.c (ffffffff81221112)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff812396f5)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/mm_init.c (ffffffff8123bdc5)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In mm/percpu.c (ffffffff8123f0ba)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In mm/vmalloc.c (ffffffff81268ee9)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff81273a5b)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In mm/swap_slots.c (ffffffff8127dd00)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In mm/hugetlb.c (ffffffff81281400)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In mm/mempolicy.c (ffffffff8128a116)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/slub.c (ffffffff81293aa0)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8129be80)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In fs/aio.c (ffffffff81328b90)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In fs/io_uring.c (ffffffff8132df70)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In fs/crypto/crypto.c (ffffffff81337094)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In fs/proc/stat.c (ffffffff81363f25)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In security/apparmor/lsm.c (ffffffff8148e3d5)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In lib/bitmap.c (ffffffff81504150)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
```
```
In lib/memweight.c (ffffffff8150b242)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/bucket_locks.c (ffffffff8150e430)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In lib/percpu_counter.c (ffffffff81531e20)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In lib/sbitmap.c (ffffffff8153af01)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
```
```
In drivers/acpi/acpi_processor.c (ffffffff815c1450)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In drivers/acpi/x86/apple.c (ffffffff815cf8c4)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa.c (ffffffff815cfbad)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81613ca0)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In drivers/xen/time.c (ffffffff816438c0)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c61c7)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816d046a)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff8170fcec)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81732cb0)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:cpumask_weight
```
```
In drivers/nvdimm/label.c (ffffffff817397bf)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/net/xen-netfront.c (ffffffff817ac3ff)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81802410)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In drivers/input/input.c (ffffffff81827392)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (ffffffff81876b15)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/md/dm-stats.c (ffffffff81882d10)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818951b0)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpumask_weight
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81895fe0)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpumask_weight
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81897840)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81899461)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8189c5fb)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818b3380)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In net/core/dev.c (ffffffff818fa030)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In net/core/ethtool.c (ffffffff81909cba)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
```
```
In net/core/net-sysfs.c (ffffffff819320d0)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - net/core/net-sysfs.c:cpumask_weight
```
```
In net/core/bpf_sk_storage.c (ffffffff81953570)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81981d90)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In lib/cpumask.c (ffffffff81a76ec0)
Location: include/linux/bitmap.h:358
Inline: True
```
```
In lib/nodemask.c (ffffffff81a7bb20)
Location: include/linux/bitmap.h:358
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/x86/events/amd/core.c (ffffffff81009544)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023580)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/xen/trace.c (ffffffff8102aff0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:cpumask_weight
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d463)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102d6eb)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102ddc1)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102dfb0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:cpumask_weight
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a582)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff8103bd70)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81048e70)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:cpumask_weight
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81053b50)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c025)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight
```
```
In arch/x86/kernel/smpboot.c (ffffffff810636c0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpumask_weight
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810652b0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:cpumask_weight
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106745b)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106da13)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106e702)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff8107682e)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81078202)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8107852e)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108c690)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:cpumask_weight
```
```
In arch/x86/mm/numa.c (ffffffff8108d064)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/mm/amdtopology.c (ffffffff8108d085)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff810975e0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_next
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_start
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81099330)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:cpumask_weight
```
```
In kernel/workqueue.c (ffffffff810c2e29)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
```
```
In kernel/pid.c (ffffffff810c64cf)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/sched/core.c (ffffffff810dd225)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/rt.c (ffffffff810ed3d0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/rt.c:cpumask_weight
```
```
In kernel/sched/deadline.c (ffffffff810f0a00)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/deadline.c:cpumask_weight
```
```
In kernel/sched/topology.c (ffffffff810f6f85)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/topology.c:sd_degenerate
```
```
In kernel/sched/debug.c (ffffffff810fc620)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81100680)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:cpumask_weight
```
```
In kernel/locking/qspinlock.c (ffffffff81105037)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/printk/printk.c (ffffffff8111520a)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff811217a0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/irq/affinity.c:cpumask_weight
```
```
In kernel/rcu/tree.c (ffffffff81129d9b)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (ffffffff81145d60)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/time/clockevents.c:cpumask_weight
```
```
In kernel/time/tick-sched.c (ffffffff81148b40)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/futex.c (ffffffff8114e62c)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/smp.c (ffffffff8114e760)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/smp.c:cpumask_weight
```
```
In kernel/kexec_file.c (ffffffff8115b450)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff8116bb70)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpumask_weight
```
```
In kernel/stop_machine.c (ffffffff81173a70)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpumask_weight
```
```
In kernel/kprobes.c (ffffffff81181f30)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811898e0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8118cae0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8118e0a0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811dedc0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811f3ea0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811f6c10)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (ffffffff811f7180)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811f7870)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff811f94a0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811ff9a0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff81200290)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffff81201350)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/padata.c (ffffffff8121cfe0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/padata.c:cpumask_weight
```
```
In mm/vmstat.c (ffffffff812479f5)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (ffffffff8124a216)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/percpu.c (ffffffff8124d51a)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/page_alloc.c (ffffffff812828cb)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/hugetlb.c (ffffffff81290cf0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/mempolicy.c (ffffffff81299c86)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory_hotplug.c (ffffffff812abc40)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In fs/aio.c (ffffffff8133b940)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff814a8295)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In lib/bitmap.c (ffffffff81522160)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
```
```
In lib/memweight.c (ffffffff81529062)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/bucket_locks.c (ffffffff8152c350)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In lib/sbitmap.c (ffffffff8155bd21)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
```
```
In drivers/acpi/x86/apple.c (ffffffff815f0b44)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa.c (ffffffff815f0e1d)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/xen/time.c (ffffffff81665e70)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e91f7)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816f428a)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff817568d0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8175d50b)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/input/input.c (ffffffff818588c2)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (ffffffff818a8915)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/md/dm-stats.c (ffffffff818b4bb0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818c71d0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpumask_weight
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818c7ff0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpumask_weight
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818c9e00)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff818cb451)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818ce8d0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818e5ca0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In net/core/dev.c (ffffffff8192e2c0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In net/core/ethtool.c (ffffffff8193c28a)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
```
```
In net/core/net-sysfs.c (ffffffff81964c10)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/net-sysfs.c:cpumask_weight
```
```
In net/core/bpf_sk_storage.c (ffffffff81989920)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b85e0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In lib/nodemask.c (ffffffff81ab2e80)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/x86/events/amd/core.c (ffffffff8100a6e9)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025c20)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In arch/x86/xen/trace.c (ffffffff8102cdf0)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:cpumask_weight
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102f593)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102f81b)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8103018b)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In arch/x86/hyperv/mmu.c (ffffffff81030460)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:cpumask_weight
```
```
In arch/x86/kernel/alternative.c (ffffffff8103c910)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:cpumask_weight
```
```
In arch/x86/kernel/tsc.c (ffffffff8103eb60)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff8104cf70)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:cpumask_weight
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81058b50)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061971)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight
```
```
In arch/x86/kernel/smpboot.c (ffffffff81069993)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
  - arch/x86/kernel/smpboot.c:cpumask_weight
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106bbf0)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:cpumask_weight
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106e06f)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce1643)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81075bb0)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff8107dabb)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f534)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8107f92f)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093c40)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:cpumask_weight
```
```
In arch/x86/mm/numa.c (ffffffff82ce6c4e)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff82ce79d1)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109c9d3)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ea40)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:cpumask_weight
```
```
In kernel/workqueue.c (ffffffff82ced78b)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/pid.c (ffffffff810ce40f)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In kernel/sched/core.c (ffffffff810dc520)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - kernel/sched/core.c:cpumask_weight
```
```
In kernel/sched/fair.c (ffffffff810e9050)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - kernel/sched/fair.c:cpumask_weight
```
```
In kernel/sched/rt.c (ffffffff810f71f0)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - kernel/sched/rt.c:cpumask_weight
```
```
In kernel/sched/deadline.c (ffffffff810f9d60)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - kernel/sched/deadline.c:cpumask_weight
```
```
In kernel/sched/topology.c (ffffffff81100700)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpumask_weight
```
```
In kernel/sched/debug.c (ffffffff81105cd0)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110acd0)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:cpumask_weight
```
```
In kernel/locking/qspinlock.c (ffffffff8110fe22)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In kernel/printk/printk.c (ffffffff81120bba)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff8112ddc0)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - kernel/irq/affinity.c:cpumask_weight
```
```
In kernel/rcu/update.c (ffffffff81130190)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff811381e3)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (ffffffff81155bd0)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - kernel/time/clockevents.c:cpumask_weight
```
```
In kernel/time/tick-sched.c (ffffffff81158930)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In kernel/futex.c (ffffffff8115eec9)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In kernel/smp.c (ffffffff82cf218d)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
  - kernel/smp.c:cpumask_weight
```
```
In kernel/kexec_file.c (ffffffff8116c2d0)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff8117d650)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpumask_weight
```
```
In kernel/stop_machine.c (ffffffff81185960)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpumask_weight
```
```
In kernel/kprobes.c (ffffffff81195740)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119d980)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811a1490)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811a29f0)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811fc440)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff81217480)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff8121a4e0)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (ffffffff8121ae70)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8121b490)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff8121cf00)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In kernel/padata.c (ffffffff812493f0)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - kernel/padata.c:cpumask_weight
```
```
In mm/vmstat.c (ffffffff812748a0)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - mm/vmstat.c:cpumask_weight
```
```
In mm/mm_init.c (ffffffff8127851c)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In mm/percpu.c (ffffffff8127b8aa)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In mm/page_alloc.c (ffffffff82cfc584)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/hugetlb.c (ffffffff812c50e4)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff82cfe501)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory_hotplug.c (ffffffff812e05ed)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In fs/aio.c (ffffffff813751b0)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In fs/io-wq.c (ffffffff8138a925)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_manager
```
```
In lib/bitmap.c (ffffffff81585480)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
```
```
In lib/memweight.c (ffffffff8158c912)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/bucket_locks.c (ffffffff8158fcc0)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In lib/sbitmap.c (ffffffff815e5811)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
```
```
In lib/nodemask.c (ffffffff815ed730)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In drivers/acpi/x86/apple.c (ffffffff8169cd91)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa/srat.c (ffffffff816e7a1d)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In drivers/xen/time.c (ffffffff81715570)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a0207)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_show_ndoms_used
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff817ac97a)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81815ec0)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8181ce4b)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/input/input.c (ffffffff8192898e)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/md/dm.c (ffffffff8197a135)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff819855a0)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff819994b0)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpumask_weight
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199a0f0)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpumask_weight
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199b5c2)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff8199d7f1)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a0d99)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff819b8f50)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In net/core/dev.c (ffffffff81a00840)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81a377c0)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - net/core/net-sysfs.c:cpumask_weight
```
```
In net/core/bpf_sk_storage.c (ffffffff81a610b0)
Location: include/linux/bitmap.h:398
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81a829e8)
Location: include/linux/bitmap.h:398
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa2f00)
Location: include/linux/bitmap.h:398
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff81bd203e)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026340)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/xen/trace.c (ffffffff8102dda0)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:cpumask_weight
```
```
In arch/x86/xen/smp_pv.c (ffffffff81bd2d43)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff81bd2d5b)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81bd2ee3)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/hyperv/mmu.c (ffffffff810311d0)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:cpumask_weight
```
```
In arch/x86/kernel/alternative.c (ffffffff8103cdb0)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:cpumask_weight
```
```
In arch/x86/kernel/tsc.c (ffffffff8103ec10)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff8104c3d0)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:cpumask_weight
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81057960)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fd7f)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b663)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
  - arch/x86/kernel/smpboot.c:cpumask_weight
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106d4d0)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:cpumask_weight
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81bd6dd7)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fce3ea)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810761e0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff81bd7f60)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81bd80ba)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81bd8132)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093190)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:cpumask_weight
```
```
In arch/x86/mm/numa.c (ffffffff82fd45cd)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff82fd53c8)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a5a0)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:cpumask_weight
```
```
In kernel/workqueue.c (ffffffff82fd9de5)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/pid.c (ffffffff81bdc130)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/reboot.c (ffffffff810d3300)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d8d40)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/sched/core.c:cpumask_weight
```
```
In kernel/sched/fair.c (ffffffff810e6e00)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/sched/fair.c:cpumask_weight
```
```
In kernel/sched/rt.c (ffffffff810f5380)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/sched/rt.c:cpumask_weight
```
```
In kernel/sched/deadline.c (ffffffff810f8120)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/sched/deadline.c:cpumask_weight
```
```
In kernel/sched/topology.c (ffffffff810ff250)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpumask_weight
```
```
In kernel/sched/debug.c (ffffffff81104320)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81107be0)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:cpumask_weight
```
```
In kernel/locking/qspinlock.c (ffffffff81bde8a9)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/printk/printk.c (ffffffff81be11c8)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff811299b0)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/irq/affinity.c:cpumask_weight
```
```
In kernel/rcu/update.c (ffffffff8112bfd0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/time/clockevents.c (ffffffff81151d70)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/time/clockevents.c:cpumask_weight
```
```
In kernel/time/tick-sched.c (ffffffff81154940)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/futex.c (ffffffff81be3daa)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/smp.c (ffffffff82fdec66)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
  - kernel/smp.c:cpumask_weight
```
```
In kernel/kexec_file.c (ffffffff81168910)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff8117a4a0)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpumask_weight
```
```
In kernel/stop_machine.c (ffffffff81182a70)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpumask_weight
```
```
In kernel/kprobes.c (ffffffff81192400)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119a9c0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119e5e0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8119fb40)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811fb840)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/bpf/map_iter.c (ffffffff812181b0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff81219580)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff8121d160)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (ffffffff8121dc00)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8121e410)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff8121fd60)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8122f890)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/padata.c (ffffffff812538f0)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/padata.c:cpumask_weight
```
```
In mm/vmstat.c (ffffffff8127f0f0)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - mm/vmstat.c:cpumask_weight
```
```
In mm/mm_init.c (ffffffff81282b00)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In mm/percpu.c (ffffffff812841a0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In mm/mmap_lock.c (ffffffff81295fd0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In mm/page_alloc.c (ffffffff82fe8f9f)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/hugetlb.c (ffffffff812d0ce4)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff82feaef4)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/slub.c (ffffffff812e3890)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812ebdcd)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In fs/aio.c (ffffffff81383060)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In lib/bitmap.c (ffffffff815a2580)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
```
```
In lib/memweight.c (ffffffff815a9382)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/bucket_locks.c (ffffffff815ac830)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In lib/sbitmap.c (ffffffff81609bd1)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
```
```
In lib/nodemask.c (ffffffff81611e6e)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In drivers/acpi/x86/apple.c (ffffffff816b9bf1)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa/srat.c (ffffffff8170530d)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In drivers/xen/time.c (ffffffff81731f40)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff817add07)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_show_ndoms_used
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81c0d857)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81825050)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8182beab)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/input/input.c (ffffffff8192febe)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/md/dm.c (ffffffff8197e775)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff81989620)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8199c590)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpumask_weight
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199d250)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpumask_weight
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199e662)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81c29f72)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81c29f8a)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff819bb3c0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In net/core/dev.c (ffffffff81a00c50)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81a39bd0)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - net/core/net-sysfs.c:cpumask_weight
```
```
In net/ethtool/ioctl.c (ffffffff81a8c4b8)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aad430)
Location: include/linux/bitmap.h:396
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff81bc40ce)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028240)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/xen/trace.c (ffffffff8102e810)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:cpumask_weight
```
```
In arch/x86/xen/smp_pv.c (ffffffff81bc5092)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff81bc50aa)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81bc524b)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/hyperv/mmu.c (ffffffff81031d30)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:cpumask_weight
```
```
In arch/x86/kernel/alternative.c (ffffffff8103e6a0)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:cpumask_weight
```
```
In arch/x86/kernel/tsc.c (ffffffff810404c0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff8104df10)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:cpumask_weight
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810582c0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060309)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff831ceb8c)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106c043)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
  - arch/x86/kernel/smpboot.c:cpumask_weight
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106df40)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:cpumask_weight
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81bc8eda)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d8e8e)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81076c70)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff81bc9e0f)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81bc9ed9)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81bc9f51)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093b90)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:cpumask_weight
```
```
In arch/x86/mm/numa.c (ffffffff831df14c)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff831dfe7e)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ad60)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:cpumask_weight
```
```
In kernel/workqueue.c (ffffffff831e479c)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/pid.c (ffffffff81bce255)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/reboot.c (ffffffff810d4ff0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/sched/core.c (ffffffff810da6c0)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/sched/core.c:cpumask_weight
```
```
In kernel/sched/fair.c (ffffffff810e8eb0)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/sched/fair.c:cpumask_weight
```
```
In kernel/sched/rt.c (ffffffff810f7450)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/sched/rt.c:cpumask_weight
```
```
In kernel/sched/deadline.c (ffffffff810fa280)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/sched/deadline.c:cpumask_weight
```
```
In kernel/sched/topology.c (ffffffff81103355)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpumask_weight
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81109d20)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:cpumask_weight
```
```
In kernel/locking/qspinlock.c (ffffffff81bd0a4a)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/printk/printk.c (ffffffff81bd3249)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff81129c40)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/irq/affinity.c:cpumask_weight
```
```
In kernel/rcu/update.c (ffffffff8112c500)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/time/clockevents.c (ffffffff81153120)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/time/clockevents.c:cpumask_weight
```
```
In kernel/time/tick-sched.c (ffffffff81155dc0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/futex.c (ffffffff81bd5cc4)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/smp.c (ffffffff831e9778)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/kexec_file.c (ffffffff811696c0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff8117b020)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpumask_weight
```
```
In kernel/stop_machine.c (ffffffff81183bc0)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpumask_weight
```
```
In kernel/kprobes.c (ffffffff811932d0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119b800)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119f2d0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811a07a0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811fc560)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/bpf/map_iter.c (ffffffff8121b600)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff8121cf80)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff81220c70)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (ffffffff81221710)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81221e00)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff812237f0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81224e30)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In kernel/padata.c (ffffffff81257f10)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - kernel/padata.c:cpumask_weight
```
```
In mm/vmstat.c (ffffffff81284240)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - mm/vmstat.c:cpumask_weight
```
```
In mm/mm_init.c (ffffffff81287c30)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In mm/percpu.c (ffffffff831f0466)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/mmap_lock.c (ffffffff8129b8f0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In mm/page_alloc.c (ffffffff831f37d9)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffffffff812c6745)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/hugetlb.c (ffffffff812d7a3a)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff831f5840)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/slub.c (ffffffff812eb040)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In fs/aio.c (ffffffff8138a0d0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In lib/bitmap.c (ffffffff815a94d0)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
```
```
In lib/memweight.c (ffffffff815b3f82)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/bucket_locks.c (ffffffff815b74a0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In lib/sbitmap.c (ffffffff815ece21)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
```
```
In lib/nodemask.c (ffffffff815f555e)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In drivers/acpi/x86/apple.c (ffffffff8169bad1)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa/srat.c (ffffffff816e69bd)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In drivers/xen/time.c (ffffffff81715a10)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff81790717)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_show_ndoms_used
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81bffbc6)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff818083e0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8180f1be)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/input/input.c (ffffffff819141f4)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/md/dm.c (ffffffff819625c5)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff8196dd00)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81981260)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpumask_weight
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81981d90)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpumask_weight
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff819832c9)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81c1c356)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81c1c36e)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8199fbd0)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In drivers/powercap/dtpm_cpu.c (ffffffff819badc0)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - drivers/powercap/dtpm_cpu.c:cpumask_weight
```
```
In net/core/dev.c (ffffffff819e7420)
Location: include/linux/bitmap.h:396
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81a20f90)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - net/core/net-sysfs.c:cpumask_weight
```
```
In net/ethtool/ioctl.c (ffffffff81a75278)
Location: include/linux/bitmap.h:396
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a98510)
Location: include/linux/bitmap.h:396
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff81c954a1)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102c8a0)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In arch/x86/xen/trace.c (ffffffff81033080)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:cpumask_weight
```
```
In arch/x86/xen/smp_pv.c (ffffffff81c97be1)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff81c97bf9)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81c97da9)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In arch/x86/hyperv/mmu.c (ffffffff81036eb0)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:cpumask_weight
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81038a80)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:cpumask_weight
```
```
In arch/x86/kernel/alternative.c (ffffffff81044410)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:cpumask_weight
```
```
In arch/x86/kernel/tsc.c (ffffffff81046330)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81055710)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:cpumask_weight
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81061190)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81069490)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff832b0e32)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81076c2b)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
  - arch/x86/kernel/smpboot.c:cpumask_weight
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81079760)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:cpumask_weight
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c9d92e)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bc355)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81084450)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff81c9ed7c)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81c9f068)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81c9f1cc)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810a3790)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:cpumask_weight
```
```
In arch/x86/mm/numa.c (ffffffff832c26a1)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff832c344b)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ab040)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:cpumask_weight
```
```
In kernel/workqueue.c (ffffffff832c8458)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/pid.c (ffffffff81ca54d8)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/reboot.c (ffffffff810e81c0)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/sched/core.c (ffffffff810ee090)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - kernel/sched/core.c:cpumask_weight
```
```
In kernel/sched/fair.c (ffffffff811005d0)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - kernel/sched/fair.c:cpumask_weight
```
```
In kernel/sched/rt.c (ffffffff811119c0)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - kernel/sched/rt.c:cpumask_weight
```
```
In kernel/sched/deadline.c (ffffffff811150f0)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - kernel/sched/deadline.c:cpumask_weight
```
```
In kernel/sched/topology.c (ffffffff81120155)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:cpumask_weight
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff811280b0)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:cpumask_weight
```
```
In kernel/locking/qspinlock.c (ffffffff81ca9641)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/printk/printk.c (ffffffff81cac187)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff8114a570)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - kernel/irq/affinity.c:cpumask_weight
```
```
In kernel/rcu/update.c (ffffffff8114d200)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/time/clocksource.c (ffffffff8116cb20)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/time/clockevents.c (ffffffff811776f0)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - kernel/time/clockevents.c:cpumask_weight
```
```
In kernel/time/tick-sched.c (ffffffff8117aa50)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/futex.c (ffffffff81cb230e)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/smp.c (ffffffff832cdd7b)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/kexec_file.c (ffffffff8118f260)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff811a2b90)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpumask_weight
```
```
In kernel/stop_machine.c (ffffffff811abc20)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpumask_weight
```
```
In kernel/kprobes.c (ffffffff811bc180)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811c5760)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811c90e0)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811c9ec0)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff8122de90)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/bpf/map_iter.c (ffffffff81252500)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff81253f00)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff81258630)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (ffffffff81259110)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff812598e0)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff8125b620)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125cd70)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In kernel/padata.c (ffffffff81293a80)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - kernel/padata.c:cpumask_weight
```
```
In mm/vmstat.c (ffffffff812c2a60)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - mm/vmstat.c:cpumask_weight
```
```
In mm/mm_init.c (ffffffff812c73d0)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In mm/percpu.c (ffffffff832d5d5f)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/mmap_lock.c (ffffffff812dc3e0)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In mm/page_alloc.c (ffffffff832d9a15)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:cpumask_weight
```
```
In mm/memory_hotplug.c (ffffffff8130b1ab)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/hugetlb.c (ffffffff8131e343)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff832dbee3)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/slub.c (ffffffff813330a0)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In fs/aio.c (ffffffff813d73e0)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In lib/bitmap.c (ffffffff81612650)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
```
```
In lib/memweight.c (ffffffff8161a182)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/bucket_locks.c (ffffffff8161dad0)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In lib/sbitmap.c (ffffffff81659d41)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
```
```
In lib/nodemask.c (ffffffff816629be)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In drivers/acpi/x86/apple.c (ffffffff81711986)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa/srat.c (ffffffff8175fe66)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In drivers/xen/time.c (ffffffff81792b20)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff81818017)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domains_used_show
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81d0213f)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81892bb0)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8189974e)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/input/input.c (ffffffff819b6302)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/md/dm.c (ffffffff81a09805)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff81a16450)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81a2a4d0)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpumask_weight
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81a2b050)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpumask_weight
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81a2c8b9)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81d2c8ea)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d2c993)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81a4c870)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In drivers/hv/hv_common.c (ffffffff81d32ec2)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In drivers/powercap/dtpm_cpu.c (ffffffff81a69ec0)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - drivers/powercap/dtpm_cpu.c:cpumask_weight
```
```
In net/core/dev.c (ffffffff81a97e10)
Location: include/linux/bitmap.h:402
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81ad5410)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - net/core/net-sysfs.c:cpumask_weight
```
```
In net/ethtool/ioctl.c (ffffffff81b30458)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b539e0)
Location: include/linux/bitmap.h:402
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff81e4472d)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810318a0)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In arch/x86/xen/trace.c (ffffffff81039ba0)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:cpumask_weight
```
```
In arch/x86/xen/smp_pv.c (ffffffff81e46fd7)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff81e4700b)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81e471e2)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In arch/x86/hyperv/mmu.c (ffffffff8103cf90)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:cpumask_weight
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103f700)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:cpumask_weight
```
```
In arch/x86/kernel/alternative.c (ffffffff8104c700)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:cpumask_weight
```
```
In arch/x86/kernel/tsc.c (ffffffff8104efa0)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81061710)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:cpumask_weight
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8106db40)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81076735)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff83461fc9)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81085ac9)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
  - arch/x86/kernel/smpboot.c:cpumask_weight
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810884e0)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:cpumask_weight
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81e4cdee)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346dc72)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81094620)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff81e4e1c2)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81e4e7aa)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81e4e922)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In arch/x86/mm/numa.c (ffffffff81e5189f)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:node_set_online
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c0a50)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:cpumask_weight
```
```
In kernel/workqueue.c (ffffffff8347b564)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/pid.c (ffffffff81e54dac)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/reboot.c (ffffffff81102600)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/sched/core.c (ffffffff8110a8f0)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - kernel/sched/core.c:cpumask_weight
```
```
In kernel/sched/fair.c (ffffffff8111b7d0)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - kernel/sched/fair.c:cpumask_weight
```
```
In kernel/sched/build_policy.c (ffffffff8112e160)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpumask_weight
```
```
In kernel/sched/build_utility.c (ffffffff8114a375)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:cpumask_weight
```
```
In kernel/locking/qspinlock.c (ffffffff81e59634)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/power/energy_model.c (ffffffff8115a2c0)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - kernel/power/energy_model.c:cpumask_weight
```
```
In kernel/printk/printk.c (ffffffff81e5c655)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff8116fb70)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - kernel/irq/affinity.c:cpumask_weight
```
```
In kernel/rcu/update.c (ffffffff81173e10)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/time/clockevents.c (ffffffff811ac790)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - kernel/time/clockevents.c:cpumask_weight
```
```
In kernel/time/tick-sched.c (ffffffff811b0300)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/futex/core.c (ffffffff81e638ba)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/smp.c (ffffffff83481a29)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/kexec_file.c (ffffffff811be9d0)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff811d38d0)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpumask_weight
```
```
In kernel/stop_machine.c (ffffffff811dd3f0)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpumask_weight
```
```
In kernel/kprobes.c (ffffffff811ef9e0)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811f9500)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fcc00)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811fdaf0)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/trace/fprobe.c (ffffffff812687c0)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8126c33e)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_alloc
```
```
In kernel/bpf/syscall.c (ffffffff8126ffa0)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/bpf/map_iter.c (ffffffff8129a310)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff8129c4a0)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff812a1410)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (ffffffff812a2030)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff812a28b0)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff812a5020)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812a6e20)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In kernel/padata.c (ffffffff812e98b0)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - kernel/padata.c:cpumask_weight
```
```
In mm/mm_init.c (ffffffff81324720)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In mm/percpu.c (ffffffff8348a5df)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/mmap_lock.c (ffffffff8133c450)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In mm/vmalloc.c (ffffffff8136703d)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/page_alloc.c (ffffffff8348e9dc)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:cpumask_weight
```
```
In mm/memory_hotplug.c (ffffffff81373c38)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/hugetlb.c (ffffffff81389ddb)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff83491681)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/slub.c (ffffffff813a48e0)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In fs/aio.c (ffffffff81460fe0)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff81551a50)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In lib/bitmap.c (ffffffff816dea80)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
```
```
In lib/memweight.c (ffffffff816e776a)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/bucket_locks.c (ffffffff816eb690)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In lib/sbitmap.c (ffffffff81772926)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
```
```
In lib/nodemask.c (ffffffff8177c85e)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In drivers/acpi/x86/apple.c (ffffffff81840a3c)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa/srat.c (ffffffff81893804)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In drivers/xen/time.c (ffffffff818cb410)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff81959136)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domains_used_show
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81eca606)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff819dce70)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff819e39f2)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/input/input.c (ffffffff81b15ad9)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81b525b0)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:cpumask_weight
```
```
In drivers/md/dm.c (ffffffff81b71145)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff81b7f810)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81b947f0)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpumask_weight
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81b95490)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpumask_weight
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81b98065)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81ef8bf9)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81ef8cbf)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81bbb000)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In drivers/hv/hv_common.c (ffffffff81eff303)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In net/core/dev.c (ffffffff81c0f5e0)
Location: include/linux/bitmap.h:422
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81c55780)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - net/core/net-sysfs.c:cpumask_weight
```
```
In net/ethtool/ioctl.c (ffffffff81cbb270)
Location: include/linux/bitmap.h:422
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce1530)
Location: include/linux/bitmap.h:422
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff8100bfb0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81038ec0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In arch/x86/xen/trace.c (ffffffff81041ca0)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:cpumask_weight
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043aa0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff81044820)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81044d50)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In arch/x86/hyperv/mmu.c (ffffffff81045c80)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:cpumask_weight
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810488a0)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:cpumask_weight
```
```
In arch/x86/kernel/alternative.c (ffffffff810589b0)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:cpumask_weight
```
```
In arch/x86/kernel/tsc.c (ffffffff8105bf50)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81070160)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:cpumask_weight
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8107dde0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810871b4)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff83e8423d)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81098d06)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
  - arch/x86/kernel/smpboot.c:cpumask_weight
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109bfb0)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:cpumask_weight
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109d080)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e939c2)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810a9fe0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff810b48a0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810b64d0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810b7c20)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In arch/x86/mm/numa.c (ffffffff83e9e91b)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dcc00)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:cpumask_weight
```
```
In kernel/workqueue.c (ffffffff83ea63e5)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/pid.c (ffffffff811187e0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/reboot.c (ffffffff81127950)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/sched/core.c (ffffffff8112f5a0)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - kernel/sched/core.c:cpumask_weight
```
```
In kernel/sched/fair.c (ffffffff811432e0)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - kernel/sched/fair.c:cpumask_weight
```
```
In kernel/sched/build_policy.c (ffffffff81158070)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpumask_weight
```
```
In kernel/sched/build_utility.c (ffffffff81178d34)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:cpumask_weight
```
```
In kernel/locking/qspinlock.c (ffffffff8117e2c0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/power/energy_model.c (ffffffff8118c5f0)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - kernel/power/energy_model.c:cpumask_weight
```
```
In kernel/printk/printk.c (ffffffff8118ecf0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff811a5f90)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - kernel/irq/affinity.c:cpumask_weight
```
```
In kernel/rcu/update.c (ffffffff811a9e40)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff811c4170)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/time/clockevents.c (ffffffff811ecbd0)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - kernel/time/clockevents.c:cpumask_weight
```
```
In kernel/time/tick-sched.c (ffffffff811f0dc0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/futex/core.c (ffffffff811f3090)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/smp.c (ffffffff83eaec7a)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/kexec_file.c (ffffffff81200b20)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff8121795d)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:node_random
  - kernel/cgroup/cpuset.c:cpumask_weight
```
```
In kernel/stop_machine.c (ffffffff81222e10)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpumask_weight
```
```
In kernel/kprobes.c (ffffffff81236420)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81240a10)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81244130)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81245300)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/trace/fprobe.c (ffffffff812ba970)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812c40af)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
```
```
In kernel/bpf/syscall.c (ffffffff812c5a20)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/bpf/map_iter.c (ffffffff812f62f0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff812f8980)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff812fe210)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (ffffffff812ff740)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff813003a0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff81302df0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81305760)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In kernel/padata.c (ffffffff813536b0)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - kernel/padata.c:cpumask_weight
```
```
In mm/vmscan.c (ffffffff8138767d)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
```
```
In mm/mm_init.c (ffffffff81399080)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In mm/percpu.c (ffffffff83ebb287)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/mmap_lock.c (ffffffff813b3fb0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In mm/vmalloc.c (ffffffff813e2edd)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/page_alloc.c (ffffffff83ec0c75)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:cpumask_weight
```
```
In mm/memory_hotplug.c (ffffffff813f1385)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/hugetlb.c (ffffffff8140ab5b)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff83ec4a6f)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/slub.c (ffffffff81424c90)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In mm/memory-tiers.c (ffffffff81437961)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - mm/memory-tiers.c:next_demotion_node
```
```
In fs/aio.c (ffffffff814f0f60)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In fs/proc/fd.c (ffffffff8153d6d1)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_count
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff815f2f20)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In lib/bitmap.c (ffffffff817ce2e0)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_pos_to_ord
```
```
In lib/memweight.c (ffffffff817d759a)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/bucket_locks.c (ffffffff817dbdc0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In lib/sbitmap.c (ffffffff818a2f26)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
```
```
In drivers/acpi/x86/apple.c (ffffffff81977482)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa/srat.c (ffffffff819db2e4)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In drivers/xen/time.c (ffffffff81a1c6f0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In drivers/char/random.c (ffffffff81a92aa0)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - drivers/char/random.c:cpumask_weight
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac0266)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domains_used_show
  - drivers/iommu/intel/iommu.c:disable_dmar_iommu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81ad9780)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81b585a0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff81b5f642)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/input/input.c (ffffffff81ca739d)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81cea7b0)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:cpumask_weight
```
```
In drivers/md/dm.c (ffffffff81d0df55)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff81d1d100)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d34b30)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpumask_weight
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d35d50)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpumask_weight
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81d39313)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81d3b400)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3d2a0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81d60680)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In drivers/hv/hv_common.c (ffffffff81d7d140)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In net/core/dev.c (ffffffff81dbf3e0)
Location: include/linux/bitmap.h:437
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81e0b230)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - net/core/net-sysfs.c:cpumask_weight
```
```
In net/ethtool/ioctl.c (ffffffff81e79841)
Location: include/linux/bitmap.h:437
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea25d0)
Location: include/linux/bitmap.h:437
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff8100b750)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81038df0)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In arch/x86/xen/trace.c (ffffffff81041de0)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:cpumask_weight
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043bc0)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff81044960)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81044e90)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In arch/x86/hyperv/mmu.c (ffffffff81045e30)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:cpumask_weight
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048b50)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:cpumask_weight
```
```
In arch/x86/kernel/alternative.c (ffffffff81059a70)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:cpumask_weight
```
```
In arch/x86/kernel/tsc.c (ffffffff8105d700)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81071d70)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:cpumask_weight
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810801c0)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108a064)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff836a778d)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109c01b)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
  - arch/x86/kernel/smpboot.c:cpumask_weight
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109ef10)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:cpumask_weight
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a0020)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b74df)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810ad3a0)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff810b7970)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810b95d0)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810bae10)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In arch/x86/mm/numa.c (ffffffff836c2a7b)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:alloc_node_data
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e81e0)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:cpumask_weight
```
```
In kernel/workqueue.c (ffffffff836caba5)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/pid.c (ffffffff81125a20)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/reboot.c (ffffffff81134df0)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/sched/core.c (ffffffff8113d020)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/sched/core.c:cpumask_weight
```
```
In kernel/sched/fair.c (ffffffff811532c0)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/sched/fair.c:cpumask_weight
```
```
In kernel/sched/build_policy.c (ffffffff81168170)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpumask_weight
```
```
In kernel/sched/build_utility.c (ffffffff81189924)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:cpumask_weight
```
```
In kernel/locking/qspinlock.c (ffffffff8118ef60)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/power/energy_model.c (ffffffff8119dd10)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/power/energy_model.c:cpumask_weight
```
```
In kernel/printk/printk.c (ffffffff811a0460)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff811b8300)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/rcu/update.c (ffffffff811bbd30)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff811d6d10)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/time/clockevents.c (ffffffff81201300)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/time/clockevents.c:cpumask_weight
```
```
In kernel/time/tick-sched.c (ffffffff812057f0)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/futex/core.c (ffffffff81207810)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/smp.c (ffffffff836d3caa)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/kexec_file.c (ffffffff81215f30)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff81234e25)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - kernel/cgroup/cpuset.c:cpumask_weight
```
```
In kernel/stop_machine.c (ffffffff812394e0)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpumask_weight
```
```
In kernel/kprobes.c (ffffffff8124d240)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81257aa0)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8125b210)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8125c390)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/trace/fprobe.c (ffffffff812de2a0)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812eb05f)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
```
```
In kernel/bpf/syscall.c (ffffffff812ecb30)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/bpf/map_iter.c (ffffffff813241a0)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff813269b0)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff8132ce20)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (ffffffff8132e2a0)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8132ef00)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff81331890)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813340c0)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In kernel/padata.c (ffffffff813848b0)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - kernel/padata.c:cpumask_weight
```
```
In mm/mm_init.c (ffffffff836e25cd)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
```
```
In mm/percpu.c (ffffffff836e38d2)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/mmap_lock.c (ffffffff813e8920)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In mm/vmalloc.c (ffffffff81417b3a)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/page_alloc.c (ffffffff81419840)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - mm/page_alloc.c:cpumask_weight
```
```
In mm/memory_hotplug.c (ffffffff81424ec5)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:__try_online_node
```
```
In mm/hugetlb.c (ffffffff8143e20b)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff836e9b8f)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/slub.c (ffffffff81459f30)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In mm/memory-tiers.c (ffffffff8146d621)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - mm/memory-tiers.c:next_demotion_node
```
```
In fs/aio.c (ffffffff815282c0)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In fs/proc/fd.c (ffffffff815759b1)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_count
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff8162b010)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In lib/bitmap.c (ffffffff8180c790)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_pos_to_ord
```
```
In lib/memweight.c (ffffffff818167aa)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/bucket_locks.c (ffffffff8181b180)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In lib/sbitmap.c (ffffffff818e5419)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
```
```
In lib/group_cpus.c (ffffffff818e69d0)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - lib/group_cpus.c:cpumask_weight
```
```
In drivers/acpi/x86/apple.c (ffffffff819bde69)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa/srat.c (ffffffff81a22f94)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In drivers/xen/time.c (ffffffff81a658b0)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In drivers/char/random.c (ffffffff81ade320)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - drivers/char/random.c:cpumask_weight
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0cb16)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domains_used_show
  - drivers/iommu/intel/iommu.c:disable_dmar_iommu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81b27900)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81babb10)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff81bb2bd2)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/input/input.c (ffffffff81d0e579)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81d533c0)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:cpumask_weight
```
```
In drivers/md/dm.c (ffffffff81d77555)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff81d862f0)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d9dea0)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpumask_weight
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d9f0c0)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpumask_weight
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81da3db3)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81da5f00)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81da7e30)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81dcb740)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In drivers/hv/hv_common.c (ffffffff81deb530)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In net/core/dev.c (ffffffff81e2f090)
Location: include/linux/bitmap.h:435
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81e7e5e0)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - net/core/net-sysfs.c:cpumask_weight
```
```
In net/ethtool/ioctl.c (ffffffff81ed5b41)
Location: include/linux/bitmap.h:435
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f00df0)
Location: include/linux/bitmap.h:435
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
In arch/x86/events/amd/core.c (ffffffff81010ed0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103f2a0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In arch/x86/xen/trace.c (ffffffff810482b0)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:cpumask_weight
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104a0c0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8104ae90)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8104b4f0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In arch/x86/hyperv/mmu.c (ffffffff8104c500)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:cpumask_weight
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8104fbd0)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:cpumask_weight
```
```
In arch/x86/kernel/alternative.c (ffffffff81060be0)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:cpumask_weight
```
```
In arch/x86/kernel/tsc.c (ffffffff810647c0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81079590)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:cpumask_weight
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81087cd0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81091184)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff838d7ccd)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a361b)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
  - arch/x86/kernel/smpboot.c:cpumask_weight
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6390)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:cpumask_weight
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a7690)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e7def)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810b3f20)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff810bedb0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810c09f0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810c2250)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In arch/x86/mm/numa.c (ffffffff838f349b)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f0370)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:cpumask_weight
```
```
In kernel/pid.c (ffffffff81130020)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/reboot.c (ffffffff8113fde0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/sched/core.c (ffffffff81148190)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - kernel/sched/core.c:cpumask_weight
```
```
In kernel/sched/fair.c (ffffffff8115eda0)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - kernel/sched/fair.c:cpumask_weight
```
```
In kernel/sched/build_policy.c (ffffffff81174f40)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:cpumask_weight
```
```
In kernel/sched/build_utility.c (ffffffff81198224)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:cpumask_weight
```
```
In kernel/locking/qspinlock.c (ffffffff8119d910)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/power/energy_model.c (ffffffff811ace80)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - kernel/power/energy_model.c:cpumask_weight
```
```
In kernel/printk/printk.c (ffffffff811af480)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff811c81c0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/rcu/update.c (ffffffff811cc1d0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff811ebec0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/time/clockevents.c (ffffffff812177a0)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - kernel/time/clockevents.c:cpumask_weight
```
```
In kernel/time/tick-sched.c (ffffffff8121bcb0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/futex/core.c (ffffffff8121ea20)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/smp.c (ffffffff83905c8a)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/crash_core.c (ffffffff8122a4e0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff8124ea45)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
```
```
In kernel/stop_machine.c (ffffffff812531b0)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpumask_weight
```
```
In kernel/kprobes.c (ffffffff81267140)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81271990)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff812750e0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff812762d0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/trace/trace_events_filter.c (ffffffff812c6480)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:cpumask_weight
```
```
In kernel/trace/fprobe.c (ffffffff812fc460)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/bpf/core.c (ffffffff81309574)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
```
```
In kernel/bpf/syscall.c (ffffffff8130b2e0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/bpf/map_iter.c (ffffffff81348170)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff8134b000)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff81351180)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (ffffffff813527c0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81353420)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff81355e30)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813587b0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In kernel/bpf/cpumask.c (ffffffff81386260)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:cpumask_weight
```
```
In kernel/padata.c (ffffffff813adcc0)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - kernel/padata.c:cpumask_weight
```
```
In mm/mm_init.c (ffffffff83914ece)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
```
```
In mm/percpu.c (ffffffff83916162)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/mmap_lock.c (ffffffff81413590)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In mm/vmalloc.c (ffffffff8144468a)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/page_alloc.c (ffffffff81446580)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - mm/page_alloc.c:cpumask_weight
```
```
In mm/memory_hotplug.c (ffffffff81452105)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:__try_online_node
```
```
In mm/slub.c (ffffffff81455000)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In mm/hugetlb.c (ffffffff81477e9b)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_hugetlb_folio
  - mm/hugetlb.c:alloc_pool_huge_folio
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff8391cf4f)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:interleave_nid
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory-tiers.c (ffffffff8149c791)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - mm/memory-tiers.c:next_demotion_node
```
```
In fs/aio.c (ffffffff8155d340)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In fs/proc/fd.c (ffffffff815ae301)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_count
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff816643e0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In lib/bitmap.c (ffffffff818528a0)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_pos_to_ord
```
```
In lib/memweight.c (ffffffff8185ba8a)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/bucket_locks.c (ffffffff818604c0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In lib/sbitmap.c (ffffffff8192c419)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
```
```
In lib/group_cpus.c (ffffffff8192d9f0)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - lib/group_cpus.c:cpumask_weight
```
```
In drivers/acpi/x86/apple.c (ffffffff81a08739)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/xen/time.c (ffffffff81ab8110)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In drivers/char/random.c (ffffffff81b31740)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - drivers/char/random.c:cpumask_weight
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b612c6)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domains_used_show
  - drivers/iommu/intel/iommu.c:disable_dmar_iommu
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81b7e7c0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In drivers/base/cacheinfo.c (ffffffff81b9d000)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cpumask_weight
```
```
In drivers/nvdimm/region.c (ffffffff81bffe50)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff81c070c2)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/input/input.c (ffffffff81dc41c9)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81e0a100)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:cpumask_weight
```
```
In drivers/md/dm.c (ffffffff81e2e785)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff81e3da30)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81e55c20)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpumask_weight
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e56ed0)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpumask_weight
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5be43)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81e5df90)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e5fb60)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81e84280)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In drivers/hv/hv_common.c (ffffffff81ea16d0)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In net/core/dev.c (ffffffff81eedd10)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff81f3f4f0)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - net/core/net-sysfs.c:cpumask_weight
```
```
In net/ethtool/ioctl.c (ffffffff81f99231)
Location: include/linux/bitmap.h:412
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc5150)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204cb90)
Location: include/linux/bitmap.h:412
Inline: True
```
```
In lib/objpool.c (ffffffff82191840)
Location: include/linux/bitmap.h:412
Inline: True
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
In arch/arm64/kernel/setup.c (ffff8000114345c0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:setup_arch
```
```
In arch/arm64/kernel/smp.c (ffff80001009d4b0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:cpus_are_stuck_in_kernel
```
```
In arch/arm64/mm/context.c (ffff8000100af910)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:asids_init
```
```
In arch/arm64/mm/numa.c (ffff8000100b2344)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:node_set_online
```
```
In kernel/workqueue.c (ffff800011442ef4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_clamp_max_active
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffff800011443640)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/sched/core.c (ffff80001013d3e8)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/rt.c (ffff80001014f4f8)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/sched/deadline.c (ffff8000101577e8)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (ffff80001015bd18)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sd_degenerate
```
```
In kernel/sched/debug.c (ffff800010161e34)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffff800010164f10)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/printk/printk.c (ffff8000114460d4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/irq/affinity.c (ffff8000101884f4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (ffff800010191a48)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (ffff8000101b145c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (ffff8000101b5c70)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffff8000114494c0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffff8000101bd368)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
```
```
In kernel/kexec_file.c (ffff8000101cb4f0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cpuset.c (ffff8000101e3cf0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/stop_machine.c (ffff8000101e8cf8)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffff8000101f9428)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffff800010202cac)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffff8000102047d8)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffff800010205990)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/bpf/syscall.c (ffff800010263680)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffff8000102779d4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffff80001027b404)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffff80001027bf40)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffff80001027d148)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffff80001027e770)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/devmap.c (ffff800010286900)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/cpumap.c (ffff800010287d18)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/xskmap.c (ffff800010288e14)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/padata.c (ffff8000102aa108)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmstat.c (ffff800011453490)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (ffff800010d9f920)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffff8000102e40dc)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_embed_first_chunk
```
```
In mm/page_alloc.c (ffff80001031b168)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/hugetlb.c (ffff800011459d70)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffff800010338a00)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory_hotplug.c (ffff80001034dbd8)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In fs/aio.c (ffff8000103fea8c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In security/apparmor/lsm.c (ffff80001146b774)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In lib/bitmap.c (ffff80001062bc18)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
```
```
In lib/memweight.c (ffff800010633a24)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/bucket_locks.c (ffff8000106382c8)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/sbitmap.c (ffff80001066963c)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/irqchip/irq-gic.c (ffff80001066bef4)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff8000106771e4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b574)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff8000107258e0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff80001072606c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
```
```
In drivers/acpi/numa.c (ffff80001077b950)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/dma/mv_xor.c (ffff800010808064)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010817370)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_enable_irqs
```
```
In drivers/xen/time.c (ffff80001082fa54)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/base/arch_topology.c (ffff80001149801c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:topology_parse_cpu_capacity
```
```
In drivers/nvdimm/region.c (ffff800010957f78)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffff80001095ec6c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/input/input.c (ffff800010a975cc)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/thermal/thermal_core.c (ffff800010ad4200)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
```
```
In drivers/thermal/cpu_cooling.c (ffff800010adc388)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/cpu_cooling.c:cpufreq_state2power
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
```
```
In drivers/md/dm.c (ffff800010afd038)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/md/dm-stats.c (ffff800010b0d188)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffff800010b255ac)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffff800010b4b214)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/perf/arm-cci.c (ffff800010b90ffc)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_enable
```
```
In drivers/perf/arm-ccn.c (ffff800010b92998)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_active_counters
```
```
In drivers/perf/arm_pmu.c (ffff800010b9525c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:cpu_pm_pmu_notify
  - drivers/perf/arm_pmu.c:armpmu_request_irq
  - drivers/perf/arm_pmu.c:armpmu_enable
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (ffff800010b96978)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_enable
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9b668)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_perf_pmu_enable
```
```
In net/core/dev.c (ffff800010bca830)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/ethtool.c (ffff800010bda950)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
```
```
In net/core/net-sysfs.c (ffff800010c09ff4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/bpf_sk_storage.c (ffff800010c31008)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffff800010c69898)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In lib/nodemask.c (ffff800010d8d0f0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/arm/kernel/setup.c (c1504e00)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_arch
```
```
In arch/arm/kernel/smp.c (c1505ca8)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:smp_prepare_cpus
```
```
In arch/arm/kernel/machine_kexec.c (c03151cc)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/arm/kernel/machine_kexec.c:machine_kexec_prepare
```
```
In arch/arm/mach-exynos/exynos.c (c032cbf4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/arm/mach-exynos/exynos.c:exynos_set_delayed_reset_assertion
```
```
In arch/arm/mach-mvebu/platsmp.c (c150e588)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_smp_init_cpus
```
```
In kernel/workqueue.c (c0371710)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
```
```
In kernel/pid.c (c0377da0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/sched/core.c (c038d180)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/rt.c (c039b8d4)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/sched/deadline.c (c03a55ac)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (c03a873c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sd_degenerate
```
```
In kernel/sched/debug.c (c03ae5fc)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (c03b1560)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/printk/printk.c (c03c85b0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/irq/affinity.c (c03d6e50)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (c03df5e4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (c03fbe80)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (c03ffc6c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (c1523684)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (c0405524)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (c04248c0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/stop_machine.c (c0428d78)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (c04396d4)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (c0441cd4)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (c04434c0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (c0444670)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/bpf/syscall.c (c0493c74)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (c04aaab8)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (c04ad4c0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (c04adce8)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (c04aeb18)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (c04b0180)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/devmap.c (c04b6f8c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/cpumap.c (c04b7af0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/xskmap.c (c04b8d00)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/padata.c (c04d81d0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmstat.c (c0501f08)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (c152e4a0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch_init
```
```
In mm/percpu.c (c050818c)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In fs/aio.c (c05d096c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
```
```
In lib/memweight.c (c07d9d68)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/bucket_locks.c (c07ddc10)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/sbitmap.c (c081246c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
```
```
In drivers/irqchip/irq-gic.c (c08152bc)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_get_cpumask
```
```
In drivers/dma/mv_xor.c (c0925324)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/soc/tegra/flowctrl.c (c093ad48)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/soc/tegra/flowctrl.c:flowctrl_cpu_suspend_enter
```
```
In drivers/base/arch_topology.c (c1598d24)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:topology_parse_cpu_capacity
```
```
In drivers/input/input.c (c0b7a7bc)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/thermal/thermal_core.c (c0bb57ec)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
```
```
In drivers/thermal/cpu_cooling.c (c0bbc8e0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/cpu_cooling.c:cpufreq_state2power
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
```
```
In drivers/md/dm-stats.c (c0beb2d8)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (c0bff58c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpuidle/coupled.c (c0c05088)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:coupled_cpu_online
  - drivers/cpuidle/coupled.c:cpuidle_coupled_register_device
```
```
In drivers/leds/trigger/ledtrig-cpu.c (c0c344e4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/perf/arm-cci.c (c0c7ba54)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_enable
```
```
In drivers/perf/arm-ccn.c (c0c7c550)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_active_counters
```
```
In drivers/perf/arm_pmu.c (c0c7e848)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:cpu_pm_pmu_notify
  - drivers/perf/arm_pmu.c:armpmu_request_irq
  - drivers/perf/arm_pmu.c:armpmu_enable
```
```
In net/core/dev.c (c0cea738)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/ethtool.c (c0cf5e20)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
```
```
In net/core/net-sysfs.c (c0d2377c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/bpf_sk_storage.c (c0d48534)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (c0d78d04)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
In arch/powerpc/kernel/setup-common.c (c00000000134a4a4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
```
```
In arch/powerpc/kernel/watchdog.c (c000000000036d78)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:start_watchdog
  - arch/powerpc/kernel/watchdog.c:watchdog_timer_fn
```
```
In arch/powerpc/kernel/crash.c (c00000000007081c)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/powerpc/mm/numa.c (c0000000000a33e4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/mm/numa.c:node_set_online
```
```
In arch/powerpc/sysdev/mpic.c (c0000000013591ac)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:smp_mpic_probe
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000bcdf4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_find_target_in_mask
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (c0000000000dfae0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-imc.c:disable_nest_pmu_counters
```
```
In arch/powerpc/platforms/powernv/memtrace.c (c0000000000e0984)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime
```
```
In arch/powerpc/platforms/pseries/lpar.c (c0000000000eab88)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write
```
```
In arch/powerpc/platforms/pseries/setup.c (c0000000013622b4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000f8e9c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_online_cpu
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
```
```
In arch/powerpc/xmon/xmon.c (c00000000010f6a0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:symbol_lookup
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:wait_for_other_cpus
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012cf5c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:cleanup_all_core_imc_memory
```
```
In kernel/workqueue.c (c000000000163c10)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (c0000000013676e8)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/sched/core.c (c00000000018c1b0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/rt.c (c0000000001a17c4)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/sched/deadline.c (c0000000001ac39c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (c0000000001b04c0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sd_degenerate
```
```
In kernel/sched/debug.c (c0000000001b8090)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (c0000000001bc058)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/printk/printk.c (c00000000136ad74)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/irq/affinity.c (c0000000001e2570)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (c0000000001ed05c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (c000000000216558)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (c00000000021b650)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (c00000000136e6d0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (c00000000022373c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
```
```
In kernel/kexec_file.c (c0000000002353a4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cpuset.c (c000000000252f2c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/stop_machine.c (c0000000002598dc)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (c000000000270b40)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (c00000000027cf48)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (c00000000027f3a8)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (c000000000281324)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/bpf/syscall.c (c000000000305b98)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (c000000000320a20)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (c000000000324c48)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (c0000000003257b0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (c000000000326bd0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (c000000000328d80)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/devmap.c (c000000000331f00)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/cpumap.c (c000000000333134)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/xskmap.c (c000000000334940)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/padata.c (c00000000035c28c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmstat.c (c00000000137b8bc)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (c000000000eec21c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (c0000000003a4680)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_embed_first_chunk
```
```
In mm/page_alloc.c (c000000001381770)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/hugetlb.c (c000000001383a2c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (c000000001383e60)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory_hotplug.c (c00000000042d5e4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In fs/aio.c (c0000000005084e0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In security/apparmor/lsm.c (c00000000139a334)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In lib/bitmap.c (c0000000007ce33c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
```
```
In lib/memweight.c (c0000000007d8e18)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/bucket_locks.c (c0000000007de578)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/sbitmap.c (c00000000081f0f8)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/nvdimm/region.c (c000000000a06364)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (c000000000a11008)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/input/input.c (c000000000b78170)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/thermal/thermal_core.c (c000000000bb8d88)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
```
```
In drivers/thermal/cpu_cooling.c (c000000000bc4740)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/cpu_cooling.c:cpufreq_state2power
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
```
```
In drivers/md/dm.c (c000000000beb3f8)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (c000000000bffa78)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (c000000000c1a4c0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/powernv-cpufreq.c (c0000000013b8760)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (c000000000c40478)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (c000000000cad82c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/ethtool.c (c000000000cbb684)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
```
```
In net/core/net-sysfs.c (c000000000cf67c0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/bpf_sk_storage.c (c000000000d2b274)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (c000000000d6e634)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In lib/nodemask.c (c000000000ecf33c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In kernel/workqueue.c (ffffffe0000d7104)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
```
```
In kernel/pid.c (ffffffe0000dcd74)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/sched/core.c (ffffffe0000ec4f8)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/rt.c (ffffffe0000f7b10)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/rt.c:do_balance_runtime
```
```
In kernel/sched/deadline.c (ffffffe0000fe568)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (ffffffe000100e8a)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sd_degenerate
```
```
In kernel/sched/debug.c (ffffffe000105bd2)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/printk/printk.c (ffffffe0001119da)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/irq/affinity.c (ffffffe00011db8a)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffe000124ce8)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (ffffffe000139864)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (ffffffe00013be36)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffe00000a92a)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffe0001409f0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffe00015a1aa)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/stop_machine.c (ffffffe00015dc24)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/bpf/syscall.c (ffffffe00019e324)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffe0001b03aa)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffe0001b326a)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffe0001b3990)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffe0001b4628)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffe0001b5ba0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffe0001bbda6)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/cpumap.c (ffffffe0001bc7dc)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffe0001bd736)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/padata.c (ffffffe0001d2fec)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmstat.c (ffffffe000012788)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (ffffffe000012aa0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch_init
```
```
In mm/percpu.c (ffffffe0001fa756)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/page_alloc.c (ffffffe0000156c4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/hugetlb.c (ffffffe000018142)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In fs/aio.c (ffffffe0002aba50)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
```
```
In lib/memweight.c (ffffffe0004619f4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/bucket_locks.c (ffffffe0004650c0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/sbitmap.c (ffffffe0004949b8)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/irqchip/irq-sifive-plic.c (ffffffe00002abd2)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/irqchip/irq-sifive-plic.c:plic_init
```
```
In drivers/base/arch_topology.c (ffffffe0000317d8)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:topology_parse_cpu_capacity
```
```
In drivers/nvdimm/region.c (ffffffe0005c6e96)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (ffffffe0005ccabe)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/input/input.c (ffffffe0006a8aee)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm-stats.c (ffffffe0006fa83e)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffe00071e1f6)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (ffffffe00075a824)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/ethtool.c (ffffffe000762fe8)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
```
```
In net/core/net-sysfs.c (ffffffe00078906c)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a7916)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007cf862)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
In arch/x86/events/amd/core.c (ffffffff81009544)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810236e0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/xen/trace.c (ffffffff8102b150)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:cpumask_weight
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d5c3)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102d84b)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102df21)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e110)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:cpumask_weight
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a6e2)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff8103bed0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81048fe0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:cpumask_weight
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810536d0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105bba5)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight
```
```
In arch/x86/kernel/smpboot.c (ffffffff810631b0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpumask_weight
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81064da0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:cpumask_weight
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066f4b)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d6a2)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff8107582e)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81077202)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8107752e)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108b650)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:cpumask_weight
```
```
In arch/x86/mm/numa.c (ffffffff8108c024)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/mm/amdtopology.c (ffffffff8108c045)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/workqueue.c (ffffffff810bd199)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
```
```
In kernel/pid.c (ffffffff810c084f)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d7415)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/rt.c (ffffffff810e7480)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/rt.c:cpumask_weight
```
```
In kernel/sched/deadline.c (ffffffff810e9e00)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/deadline.c:cpumask_weight
```
```
In kernel/sched/topology.c (ffffffff810f0385)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/topology.c:sd_degenerate
```
```
In kernel/sched/debug.c (ffffffff810f5950)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f9990)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:cpumask_weight
```
```
In kernel/locking/qspinlock.c (ffffffff810fe347)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/printk/printk.c (ffffffff8110d7ea)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff81119d80)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/irq/affinity.c:cpumask_weight
```
```
In kernel/rcu/tree.c (ffffffff8112237b)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (ffffffff8113e510)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/time/clockevents.c:cpumask_weight
```
```
In kernel/time/tick-sched.c (ffffffff81141160)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/futex.c (ffffffff81146c4c)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/smp.c (ffffffff81146d80)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/smp.c:cpumask_weight
```
```
In kernel/kexec_file.c (ffffffff81153a70)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff81164190)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpumask_weight
```
```
In kernel/stop_machine.c (ffffffff8116c090)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpumask_weight
```
```
In kernel/kprobes.c (ffffffff8117a550)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81181f00)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81185100)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811866c0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d73e0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811ec4c0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811ef230)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (ffffffff811ef7a0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811efe90)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff811f1ac0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811f7fc0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811f88b0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffff811f9970)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/padata.c (ffffffff81215630)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/padata.c:cpumask_weight
```
```
In mm/vmstat.c (ffffffff81240045)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (ffffffff81242866)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/percpu.c (ffffffff81245b6a)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/page_alloc.c (ffffffff8127af1b)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/hugetlb.c (ffffffff812892d0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/mempolicy.c (ffffffff81292266)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory_hotplug.c (ffffffff812a4220)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In fs/aio.c (ffffffff81333f20)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff814a0875)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In lib/bitmap.c (ffffffff8151a740)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
```
```
In lib/memweight.c (ffffffff81521642)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/bucket_locks.c (ffffffff81524930)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In lib/sbitmap.c (ffffffff81554311)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
```
```
In drivers/acpi/x86/apple.c (ffffffff815df7d4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa.c (ffffffff815dfaad)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/xen/time.c (ffffffff8162bae0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff816aecd7)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816b9a7a)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff8170afc0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff81711bfb)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/nvme/host/core.c (ffffffff81746b15)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
```
```
In drivers/nvme/host/pci.c (ffffffff817507ae)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_dbbuf_dma_free
```
```
In drivers/input/input.c (ffffffff8180d8d2)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (ffffffff8184e795)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/md/dm-stats.c (ffffffff8185aa30)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8186b8f0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpumask_weight
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8186c710)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpumask_weight
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8186e520)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818724d0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In net/core/dev.c (ffffffff818ce2c0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In net/core/ethtool.c (ffffffff818dc25a)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
```
```
In net/core/net-sysfs.c (ffffffff81904be0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/net-sysfs.c:cpumask_weight
```
```
In net/core/bpf_sk_storage.c (ffffffff81929790)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81958450)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In lib/nodemask.c (ffffffff81a51cd0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/x86/events/amd/core.c (ffffffff81007d84)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8101d8e4)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/hyperv/mmu.c (ffffffff8101dad0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:cpumask_weight
```
```
In arch/x86/kernel/alternative.c (ffffffff81029f12)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff8102bdf0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff810383b0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:cpumask_weight
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810437a0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104bd75)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight
```
```
In arch/x86/kernel/smpboot.c (ffffffff810534c0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpumask_weight
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055070)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:cpumask_weight
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81057308)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105dad2)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff8106581e)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810672ee)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8106760e)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107a180)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:cpumask_weight
```
```
In arch/x86/mm/numa.c (ffffffff8107ab54)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/mm/amdtopology.c (ffffffff8107ab75)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/workqueue.c (ffffffff810ab9c9)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
```
```
In kernel/pid.c (ffffffff810af04f)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c5d35)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/rt.c (ffffffff810d66d0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/rt.c:cpumask_weight
```
```
In kernel/sched/deadline.c (ffffffff810d9dc0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/deadline.c:cpumask_weight
```
```
In kernel/sched/topology.c (ffffffff810e03f5)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/topology.c:sd_degenerate
```
```
In kernel/sched/debug.c (ffffffff810e5b10)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810e9b70)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:cpumask_weight
```
```
In kernel/locking/qspinlock.c (ffffffff810ee547)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/printk/printk.c (ffffffff810fe54a)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff8110adf0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/irq/affinity.c:cpumask_weight
```
```
In kernel/rcu/tree.c (ffffffff81114a2b)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (ffffffff81131030)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/time/clockevents.c:cpumask_weight
```
```
In kernel/time/tick-sched.c (ffffffff81133f80)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/futex.c (ffffffff81139f4c)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/smp.c (ffffffff8113a080)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/smp.c:cpumask_weight
```
```
In kernel/kexec_file.c (ffffffff81146d90)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff811573e0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpumask_weight
```
```
In kernel/stop_machine.c (ffffffff8115f290)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpumask_weight
```
```
In kernel/kprobes.c (ffffffff8116d6f0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81175040)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81178240)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81179800)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811ca1a0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811df250)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811e1fc0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (ffffffff811e2530)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811e2be0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff811e4810)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811ead10)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811eb600)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffff811ec6c0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/padata.c (ffffffff81208390)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/padata.c:cpumask_weight
```
```
In mm/vmstat.c (ffffffff81233045)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (ffffffff81235836)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/percpu.c (ffffffff81238b1a)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/page_alloc.c (ffffffff8126cdfb)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/hugetlb.c (ffffffff8127b170)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/mempolicy.c (ffffffff81283e76)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81295cf0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In fs/aio.c (ffffffff81324b90)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff81491295)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In lib/bitmap.c (ffffffff8150aa30)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
```
```
In lib/memweight.c (ffffffff81511932)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/bucket_locks.c (ffffffff81514c10)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In lib/sbitmap.c (ffffffff81544591)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
```
```
In drivers/acpi/x86/apple.c (ffffffff815cadf4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa.c (ffffffff815cb0ed)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168c637)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816976ba)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff816dea40)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff816e567b)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/scsi/storvsc_drv.c (ffffffff81712c50)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/scsi/storvsc_drv.c:cpumask_weight
```
```
In drivers/nvme/host/core.c (ffffffff81728795)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
```
```
In drivers/nvme/host/pci.c (ffffffff8173064e)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_dbbuf_dma_free
```
```
In drivers/input/input.c (ffffffff817d5042)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (ffffffff81815db5)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/md/dm-stats.c (ffffffff818225f0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818345a0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpumask_weight
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81835230)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpumask_weight
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818364e0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81838901)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8183c176)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/hv/channel_mgmt.c (ffffffff81852490)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:cpumask_weight
```
```
In net/core/dev.c (ffffffff818883e0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In net/core/ethtool.c (ffffffff8189609a)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
```
```
In net/core/net-sysfs.c (ffffffff818bea10)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/net-sysfs.c:cpumask_weight
```
```
In net/core/bpf_sk_storage.c (ffffffff818e3540)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81911f40)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In lib/nodemask.c (ffffffff81a0edd0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/x86/events/amd/core.c (ffffffff81009504)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023540)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/xen/trace.c (ffffffff8102afb0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:cpumask_weight
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d423)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102d6ab)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102dd81)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102df70)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:cpumask_weight
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a542)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff8103bd30)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81048e20)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:cpumask_weight
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81053b00)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105bfd5)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063660)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpumask_weight
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065250)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:cpumask_weight
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810673fb)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106db52)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff810757de)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810771b2)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810774de)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108b600)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:cpumask_weight
```
```
In arch/x86/mm/numa.c (ffffffff8108bfd4)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/mm/amdtopology.c (ffffffff8108bff5)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/workqueue.c (ffffffff810bc6f9)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
```
```
In kernel/pid.c (ffffffff810bfd9f)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d4075)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/rt.c (ffffffff810e3900)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/rt.c:cpumask_weight
```
```
In kernel/sched/deadline.c (ffffffff810e6f30)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/deadline.c:cpumask_weight
```
```
In kernel/sched/topology.c (ffffffff810ed4b5)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/topology.c:sd_degenerate
```
```
In kernel/sched/debug.c (ffffffff810f2b50)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f6bb0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:cpumask_weight
```
```
In kernel/locking/qspinlock.c (ffffffff810fb507)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/printk/printk.c (ffffffff8110b6da)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff81117c70)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/irq/affinity.c:cpumask_weight
```
```
In kernel/rcu/tree.c (ffffffff8112026b)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (ffffffff8113c230)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/time/clockevents.c:cpumask_weight
```
```
In kernel/time/tick-sched.c (ffffffff8113f010)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/futex.c (ffffffff81144afc)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/smp.c (ffffffff81144c30)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/smp.c:cpumask_weight
```
```
In kernel/kexec_file.c (ffffffff81151920)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff81161f60)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpumask_weight
```
```
In kernel/stop_machine.c (ffffffff81169e60)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpumask_weight
```
```
In kernel/kprobes.c (ffffffff81178320)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8117fcd0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81182ed0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81184490)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d51b0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811ea290)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811ed000)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (ffffffff811ed570)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811edc60)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff811ef890)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811f5d90)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811f6680)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffff811f7740)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/padata.c (ffffffff812133d0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/padata.c:cpumask_weight
```
```
In mm/vmstat.c (ffffffff8123dde5)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (ffffffff81240606)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/percpu.c (ffffffff8124390a)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/page_alloc.c (ffffffff81278cbb)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/hugetlb.c (ffffffff812870e0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/mempolicy.c (ffffffff81290076)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory_hotplug.c (ffffffff812a2030)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In fs/aio.c (ffffffff813319f0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff8149c915)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In lib/bitmap.c (ffffffff815167d0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
```
```
In lib/memweight.c (ffffffff8151d6d2)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/bucket_locks.c (ffffffff815209c0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In lib/sbitmap.c (ffffffff81550051)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
```
```
In drivers/acpi/x86/apple.c (ffffffff815e4e24)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa.c (ffffffff815e50fd)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/xen/time.c (ffffffff81659cb0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff816dceb7)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816e7f4a)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81749d90)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff817509cb)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/input/input.c (ffffffff8184ca52)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (ffffffff8189ddc5)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/md/dm-stats.c (ffffffff818aa060)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818bc680)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpumask_weight
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818bd4a0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpumask_weight
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818bf2b0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff818c0901)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818c3d80)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818dab00)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In net/core/dev.c (ffffffff8191f2c0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In net/core/ethtool.c (ffffffff8192d28a)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
```
```
In net/core/net-sysfs.c (ffffffff81955c10)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/net-sysfs.c:cpumask_weight
```
```
In net/core/bpf_sk_storage.c (ffffffff8197a920)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c2c20)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In lib/nodemask.c (ffffffff81abe0c0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/x86/events/amd/core.c (ffffffff81009664)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810239f0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/xen/trace.c (ffffffff8102bda0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:cpumask_weight
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102e213)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/xen/spinlock.c (ffffffff8102e49b)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102eb71)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102ed60)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:cpumask_weight
```
```
In arch/x86/kernel/alternative.c (ffffffff8103b542)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff8103cd80)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff8104a230)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:cpumask_weight
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81055050)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d4e5)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cbm_to_size
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpumask_weight
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064c20)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpumask_weight
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81066830)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:cpumask_weight
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810689db)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106f0e3)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106fdd2)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff8107783e)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81079222)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8107957e)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108d940)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:cpumask_weight
```
```
In arch/x86/mm/numa.c (ffffffff8108e334)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/mm/amdtopology.c (ffffffff8108e355)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81098ab0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_next
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_start
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a800)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:cpumask_weight
```
```
In kernel/workqueue.c (ffffffff810c4a89)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
```
```
In kernel/pid.c (ffffffff810c81cf)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/sched/core.c (ffffffff810deff5)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/rt.c (ffffffff810ef440)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/rt.c:cpumask_weight
```
```
In kernel/sched/deadline.c (ffffffff810f1ed0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/deadline.c:cpumask_weight
```
```
In kernel/sched/topology.c (ffffffff810f84f5)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/topology.c:sd_degenerate
```
```
In kernel/sched/debug.c (ffffffff810fdb50)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81101c30)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:cpumask_weight
```
```
In kernel/locking/qspinlock.c (ffffffff811066d7)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/printk/printk.c (ffffffff81116b9a)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/irq/affinity.c (ffffffff81123300)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/irq/affinity.c:cpumask_weight
```
```
In kernel/rcu/tree.c (ffffffff8112c4ab)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (ffffffff81148d10)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/time/clockevents.c:cpumask_weight
```
```
In kernel/time/tick-sched.c (ffffffff8114be90)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/futex.c (ffffffff81151693)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/smp.c (ffffffff811517b0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/smp.c:cpumask_weight
```
```
In kernel/kexec_file.c (ffffffff8115e740)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff8116f3f0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpumask_weight
```
```
In kernel/stop_machine.c (ffffffff811775a0)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpumask_weight
```
```
In kernel/kprobes.c (ffffffff81185bf0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118d5f0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81190810)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81191de0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811e34e0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/hashtab.c (ffffffff811f8670)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff811fb4b0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (ffffffff811fba40)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811fc130)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/local_storage.c (ffffffff811fdd70)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff812042f0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff81204bf0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffff81205cc0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In kernel/padata.c (ffffffff81222380)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - kernel/padata.c:cpumask_weight
```
```
In mm/vmstat.c (ffffffff8124d515)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (ffffffff8124fd59)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/percpu.c (ffffffff812530ca)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/page_alloc.c (ffffffff812888ab)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/hugetlb.c (ffffffff81297820)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In mm/mempolicy.c (ffffffff8129fea6)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory_hotplug.c (ffffffff812b22c0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In fs/aio.c (ffffffff81344650)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff814b4ea0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In lib/bitmap.c (ffffffff8152ff60)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
```
```
In lib/memweight.c (ffffffff81536f42)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/memweight.c:memweight
```
```
In lib/bucket_locks.c (ffffffff8153a340)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In lib/sbitmap.c (ffffffff81569e91)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbitmap_weight
  - lib/sbitmap.c:__sbitmap_weight
```
```
In drivers/acpi/x86/apple.c (ffffffff815fecd4)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
```
```
In drivers/acpi/numa.c (ffffffff815fefad)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/xen/time.c (ffffffff81674280)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f74f7)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_show_ndoms_used
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff8170264a)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81765210)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff8176be4b)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_nfree
```
```
In drivers/input/input.c (ffffffff81867d42)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (ffffffff818ba175)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/md/dm-stats.c (ffffffff818c6340)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818d8970)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpumask_weight
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818d9790)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:cpumask_weight
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818db5c0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff818dcc0b)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818e00f0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818f7620)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In net/core/dev.c (ffffffff81941020)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In net/core/ethtool.c (ffffffff8194e95a)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
```
```
In net/core/net-sysfs.c (ffffffff81977e00)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - net/core/net-sysfs.c:cpumask_weight
```
```
In net/core/bpf_sk_storage.c (ffffffff8199ce50)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cc6f0)
Location: include/linux/bitmap.h:382
Inline: True
```
```
In lib/nodemask.c (ffffffff81aca560)
Location: include/linux/bitmap.h:382
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
</details>
</li>
</ul>

## Differences
