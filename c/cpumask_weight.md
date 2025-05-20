# Function: <code>cpumask_weight</code>

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
In arch/x86/events/intel/core.c (ffffffff81f5deea)
Location: include/linux/cpumask.h:474
Inline: True
```
```
In arch/x86/xen/trace.c (ffffffff8102a840)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp.c (ffffffff81f6501a)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/alternative.c (ffffffff810369bb)
Location: include/linux/cpumask.h:474
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
Location: include/linux/cpumask.h:474
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8103e08f)
Location: include/linux/cpumask.h:474
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff8104160b)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045ac9)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8104fea3)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81050518)
Location: include/linux/cpumask.h:474
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81050971)
Location: include/linux/cpumask.h:474
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105139f)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:smp_announce
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81052a84)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81f71367)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a403)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/crash.c (ffffffff8105dce5)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/kernel/hpet.c (ffffffff8107d368)
Location: include/linux/cpumask.h:474
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810747e1)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/cpu.c (ffffffff81081515)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:disable_nonboot_cpus
```
```
In kernel/workqueue.c (ffffffff81097702)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
  - kernel/workqueue.c:workqueue_cpu_up_callback
  - kernel/workqueue.c:init_workqueues
```
```
In kernel/pid.c (ffffffff81f7c7e6)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/pid.c:pidmap_init
  - kernel/pid.c:pidmap_init
```
```
In kernel/sched/core.c (ffffffff810a58a6)
Location: include/linux/cpumask.h:474
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
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_update_sysctl_factor
  - kernel/sched/fair.c:update_max_interval
```
```
In kernel/sched/rt.c (ffffffff810bf941)
Location: include/linux/cpumask.h:474
Inline: True
```
```
In kernel/locking/qspinlock.c (ffffffff81f7e61e)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/power/swap.c (ffffffff810d32ee)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk.c (ffffffff81f7ed55)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/rcu/tree.c (ffffffff810e58d1)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/clockevents.c (ffffffff810fb98f)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
```
```
In kernel/time/tick-common.c (ffffffff810fcbaa)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_freeze
  - kernel/time/tick-common.c:tick_unfreeze
```
```
In kernel/time/tick-sched.c (ffffffff810fede8)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff81f80b36)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff81103cba)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_announce
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff81120111)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/stop_machine.c:__stop_cpus
  - kernel/stop_machine.c:stop_machine
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
```
```
In kernel/kprobes.c (ffffffff8112f40b)
Location: include/linux/cpumask.h:474
Inline: True
```
```
In kernel/debug/debug_core.c (ffffffff8112fc7b)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81136b7f)
Location: include/linux/cpumask.h:474
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81138296)
Location: include/linux/cpumask.h:474
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8113935a)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/trace/trace.c (ffffffff8114cb10)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_event_info
  - kernel/trace/trace.c:print_trace_header
```
```
In kernel/events/core.c (ffffffff811813f0)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/padata.c (ffffffff81189966)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_reorder
```
```
In kernel/membarrier.c (ffffffff8118b4bf)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - kernel/membarrier.c:SyS_membarrier
```
```
In mm/page-writeback.c (ffffffff8119b6ae)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff811ad6a6)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - mm/vmstat.c:calculate_pressure_threshold
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/mm_init.c (ffffffff8181d842)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff81208d28)
Location: include/linux/cpumask.h:474
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
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/hugetlb.c (ffffffff81f8c241)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/slub.c (ffffffff811eccb6)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/aio.c (ffffffff8125c94c)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:SyS_io_setup
```
```
In fs/proc/stat.c (ffffffff81283346)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In lib/cpumask.c (ffffffff813e91f6)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
```
In lib/percpu_ida.c (ffffffff813ffa7b)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/rhashtable.c (ffffffff8140010b)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_alloc
```
```
In lib/percpu_counter.c (ffffffff81f9e5be)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/acpi/acpi_processor.c (ffffffff814823e4)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/processor_idle.c (ffffffff814ace98)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/nvdimm/region.c (ffffffff8159acdb)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/virtio_net.c (ffffffff815f16b0)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
```
In drivers/net/xen-netfront.c (ffffffff81fb01b1)
Location: include/linux/cpumask.h:474
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff8164cf64)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/thermal/thermal_core.c (ffffffff81684c89)
Location: include/linux/cpumask.h:474
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
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff816b3829)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_timer
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff816b47e4)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_timer
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff816b551e)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_timer
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff816b688c)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff816b7788)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81fb4963)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In net/core/dev.c (ffffffff81715c56)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In net/core/flow.c (ffffffff81735242)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/core/net-sysfs.c (ffffffff817369a7)
Location: include/linux/cpumask.h:474
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/inet_hashtables.c (ffffffff817620b6)
Location: include/linux/cpumask.h:474
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
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101550c)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_cpu_starting
```
```
In arch/x86/xen/trace.c (ffffffff81028aff)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp.c (ffffffff8102b0d3)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/alternative.c (ffffffff81f90d0f)
Location: include/linux/cpumask.h:478
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
Location: include/linux/cpumask.h:478
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8103deb3)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81041562)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045848)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81050023)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81050693)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81050b41)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff810525e1)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:smp_announce
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81052ce2)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81f99b27)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a793)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/crash.c (ffffffff8105dbb4)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/kernel/hpet.c (ffffffff8107ee54)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81075f8c)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff81084df0)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/cpu.c:disable_nonboot_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/workqueue.c (ffffffff81fa5422)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:wq_clamp_max_active
```
```
In kernel/pid.c (ffffffff81fa55a9)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/pid.c:pidmap_init
  - kernel/pid.c:pidmap_init
```
```
In kernel/sched/core.c (ffffffff810b1f90)
Location: include/linux/cpumask.h:478
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
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/rt.c (ffffffff810c3272)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810cb346)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/locking/qspinlock.c (ffffffff81fa7507)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/power/swap.c (ffffffff810d809e)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk.c (ffffffff81fa7ce9)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/nmi.c (ffffffff810df3e8)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/printk/nmi.c:printk_nmi_flush_on_panic
```
```
In kernel/irq/affinity.c (ffffffff810e8e4f)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_mask
  - kernel/irq/affinity.c:irq_create_affinity_mask
```
```
In kernel/rcu/tree.c (ffffffff810eed36)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/clockevents.c (ffffffff81103707)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff81103fea)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff81106187)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff81fa9b68)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff8110b556)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/smp.c:smp_announce
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff81128842)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffffffff811376cb)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In kernel/debug/debug_core.c (ffffffff81137f85)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8113f00f)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8114078a)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8114184f)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/trace/trace.c (ffffffff81159976)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/bpf/syscall.c (ffffffff81180b9a)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffff81186390)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff81187869)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffff81187f4b)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/events/core.c (ffffffff811931c3)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/padata.c (ffffffff8119c3aa)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/membarrier.c (ffffffff8119dbbf)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/membarrier.c:SyS_membarrier
```
```
In mm/page-writeback.c (ffffffff811b075e)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff811c6a13)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/mm_init.c (ffffffff81897c2a)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff81fb24aa)
Location: include/linux/cpumask.h:478
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
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/hugetlb.c (ffffffff81fb5f38)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In mm/slub.c (ffffffff8120c40c)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/aio.c (ffffffff81285a0d)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:SyS_io_setup
```
```
In fs/proc/stat.c (ffffffff812b03a6)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff813257c6)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_max_decompressors
```
```
In lib/cpumask.c (ffffffff8142f43e)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
```
In lib/percpu_ida.c (ffffffff8144716b)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/rhashtable.c (ffffffff81447892)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_alloc
```
```
In lib/percpu_counter.c (ffffffff81fc9a47)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/acpi/acpi_processor.c (ffffffff814d0ef2)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/processor_idle.c (ffffffff814fca18)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/block/xen-blkfront.c (ffffffff81fda48f)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff815f0d22)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/virtio_net.c (ffffffff816510d0)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81fdcd16)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff816ad894)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/thermal/thermal_core.c (ffffffff816e6f02)
Location: include/linux/cpumask.h:478
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
In drivers/md/dm-stats.c (ffffffff8170e069)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81716db1)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817183d6)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81719266)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81fe159f)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In net/core/dev.c (ffffffff8177ea36)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In net/core/flow.c (ffffffff817a13cb)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
```
In net/core/net-sysfs.c (ffffffff817a2b79)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ce876)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81fc09f0)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/trace.c (ffffffff8102a6dd)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp.c (ffffffff8102b7a3)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
```
```
In arch/x86/kernel/alternative.c (ffffffff81035a06)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff810375f2)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8103d763)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81040fb3)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810444ac)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104748e)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81052b03)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81052f03)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff810533f9)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054ee0)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055948)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81083070)
Location: include/linux/cpumask.h:478
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d693)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/crash.c (ffffffff81060c3c)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/kernel/hpet.c (ffffffff810834fa)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81079b78)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
Direct callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff81089d94)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/workqueue.c (ffffffff810a34e2)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffffffff811ae2f7)
Location: include/linux/cpumask.h:478
Inline: True
Direct callers:
  - kernel/pid.c:pidmap_init
  - kernel/pid.c:pidmap_init
```
```
In kernel/sched/core.c (ffffffff810b8352)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:build_sched_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:sd_degenerate
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/fair.c (ffffffff810bc260)
Location: include/linux/cpumask.h:478
Inline: True
Direct callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/rt.c (ffffffff810c92d9)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810d1376)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d45af)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/locking/qspinlock.c (ffffffff81fe31e8)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/power/swap.c (ffffffff810deb9e)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk.c (ffffffff811ae4c2)
Location: include/linux/cpumask.h:478
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/nmi.c (ffffffff810e59d8)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/printk/nmi.c:printk_nmi_flush_on_panic
```
```
In kernel/irq/affinity.c (ffffffff810efdef)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff810f5ea6)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/clockevents.c (ffffffff8110adfa)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff8110b6ea)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8110d8e7)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff81fe5b1f)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff81112aac)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
Direct callers:
  - kernel/smp.c:smp_init
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff811324f2)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffffffff8114144b)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In kernel/debug/debug_core.c (ffffffff81141d15)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81148ddf)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8114a57a)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8114b633)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/trace/trace.c (ffffffff81164196)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/bpf/syscall.c (ffffffff8118ccc0)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffff811950aa)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff81195aac)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffff81195f0b)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81196c94)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_percpu_lru_populate
```
```
In kernel/events/core.c (ffffffff811a29a3)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/padata.c (ffffffff811ac194)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/membarrier.c (ffffffff811ad5df)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - kernel/membarrier.c:SyS_membarrier
```
```
In mm/page-writeback.c (ffffffff811c0d4e)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff811d6c55)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_pressure_threshold
Direct callers:
  - mm/vmstat.c:setup_vmstat
```
```
In mm/mm_init.c (ffffffff818cc2c8)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff81240f43)
Location: include/linux/cpumask.h:478
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/vmalloc.c (ffffffff811fb364)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/hugetlb.c (ffffffff81ff28bb)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In mm/slub.c (ffffffff8121e42b)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/aio.c (ffffffff81299b6e)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/proc/stat.c (ffffffff812c5d96)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In lib/cpumask.c (ffffffff8144b65d)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
```
In lib/percpu_ida.c (ffffffff81465995)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/rhashtable.c (ffffffff8146626e)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In lib/percpu_counter.c (ffffffff814783c9)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In drivers/acpi/acpi_processor.c (ffffffff814f2fa8)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/processor_idle.c (ffffffff8151f1cf)
Location: include/linux/cpumask.h:478
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/block/xen-blkfront.c (ffffffff82017ef3)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff8161e0db)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/xen-netfront.c (ffffffff8201a92c)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff816dac1c)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_msix
```
```
In drivers/thermal/thermal_core.c (ffffffff8171794b)
Location: include/linux/cpumask.h:478
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
In drivers/md/dm-stats.c (ffffffff8173f80e)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81748b88)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8174a2c8)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8174b8aa)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8201f2b1)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In net/core/dev.c (ffffffff817adca6)
Location: include/linux/cpumask.h:478
Inline: True
```
```
In net/core/flow.c (ffffffff817cfcf8)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_lookup
```
```
In net/core/net-sysfs.c (ffffffff817d1597)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fe686)
Location: include/linux/cpumask.h:478
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffff8102a940-ffffffff8102a951: cpumask_weight (STB_LOCAL)
ffffffff81034da0-ffffffff81034db1: cpumask_weight (STB_LOCAL)
ffffffff81053950-ffffffff81053961: cpumask_weight (STB_LOCAL)
ffffffff81083070-ffffffff81083088: cpumask_weight.constprop.19 (STB_LOCAL)
ffffffff81079540-ffffffff81079551: cpumask_weight (STB_LOCAL)
ffffffff810a0040-ffffffff810a0058: cpumask_weight.constprop.34 (STB_LOCAL)
ffffffff811ae2f7-ffffffff811ae30f: cpumask_weight.constprop.3 (STB_LOCAL)
ffffffff810afdf0-ffffffff810afe01: cpumask_weight (STB_LOCAL)
ffffffff810bc260-ffffffff810bc278: cpumask_weight.constprop.91 (STB_LOCAL)
ffffffff811ae4c2-ffffffff811ae4da: cpumask_weight.constprop.29 (STB_LOCAL)
ffffffff811122e0-ffffffff811122f1: cpumask_weight (STB_LOCAL)
ffffffff811937c0-ffffffff811937d8: cpumask_weight.constprop.15 (STB_LOCAL)
ffffffff811d5720-ffffffff811d5731: cpumask_weight (STB_LOCAL)
ffffffff81240f43-ffffffff81240f5b: cpumask_weight.constprop.21 (STB_LOCAL)
ffffffff8151f1cf-ffffffff8151f1e7: cpumask_weight.constprop.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff820a0c0f)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/trace.c (ffffffff810289eb)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp.c (ffffffff8102907b)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/xen/smp_pv.c (ffffffff81029abb)
Location: include/linux/cpumask.h:506
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/kernel/alternative.c (ffffffff810339b6)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff81035689)
Location: include/linux/cpumask.h:506
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8103b653)
Location: include/linux/cpumask.h:506
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff8103f0d5)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043457)
Location: include/linux/cpumask.h:506
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
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104c66f)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81052623)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81052a13)
Location: include/linux/cpumask.h:506
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81052f8a)
Location: include/linux/cpumask.h:506
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff810547d6)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055256)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056f5f)
Location: include/linux/cpumask.h:506
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105cd93)
Location: include/linux/cpumask.h:506
Inline: True
```
```
In arch/x86/kernel/ftrace.c (ffffffff8105d101)
Location: include/linux/cpumask.h:506
Inline: True
```
```
In arch/x86/kernel/crash.c (ffffffff8105fc1f)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/kernel/hpet.c (ffffffff81065178)
Location: include/linux/cpumask.h:506
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81078428)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
Direct callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff81086c5b)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/workqueue.c (ffffffff810a07f2)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffffffff810a3ea1)
Location: include/linux/cpumask.h:506
Inline: True
Direct callers:
  - kernel/pid.c:pidmap_init
  - kernel/pid.c:pidmap_init
```
```
In kernel/sched/core.c (ffffffff810b36ee)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
Direct callers:
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/sched/fair.c (ffffffff810b6cc0)
Location: include/linux/cpumask.h:506
Inline: True
Direct callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/rt.c (ffffffff810c3369)
Location: include/linux/cpumask.h:506
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810c92bd)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
```
```
In kernel/sched/topology.c (ffffffff810ccd1c)
Location: include/linux/cpumask.h:506
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
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d37fd)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/locking/qspinlock.c (ffffffff820c3be4)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/power/swap.c (ffffffff810ddc4e)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk.c (ffffffff810e4a9f)
Location: include/linux/cpumask.h:506
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_safe.c (ffffffff810e4f28)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/affinity.c (ffffffff810efda3)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff810f6b96)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/clockevents.c (ffffffff8110ccfb)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff8110d5da)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8110f7e7)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff820c6430)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff81113f7d)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
Direct callers:
  - kernel/smp.c:smp_init
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff81133ad2)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffffffff81142dc3)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff81143555)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8114abef)
Location: include/linux/cpumask.h:506
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8114c47b)
Location: include/linux/cpumask.h:506
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8114d598)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/trace/trace.c (ffffffff81168784)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:print_trace_header
```
```
In kernel/bpf/syscall.c (ffffffff8119301b)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/bpf/hashtab.c (ffffffff8119c253)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff8119cf87)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffff8119d47b)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8119e094)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/events/core.c (ffffffff811aa012)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/padata.c (ffffffff811b37c0)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/membarrier.c (ffffffff811b4abf)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - kernel/membarrier.c:SyS_membarrier
```
```
In mm/page-writeback.c (ffffffff811c8ebe)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff811dfab5)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_pressure_threshold
Direct callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/mm_init.c (ffffffff81903843)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff811e4bb7)
Location: include/linux/cpumask.h:506
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/swap_slots.c (ffffffff811ec9ca)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/vmalloc.c (ffffffff812060a4)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/hugetlb.c (ffffffff820d4f70)
Location: include/linux/cpumask.h:506
Inline: True
```
```
In mm/slub.c (ffffffff81229f37)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/aio.c (ffffffff812a78ce)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/proc/stat.c (ffffffff812d2fa6)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In lib/percpu_ida.c (ffffffff8146a768)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/rhashtable.c (ffffffff8146b3eb)
Location: include/linux/cpumask.h:506
Inline: True
```
```
In lib/percpu_counter.c (ffffffff81481709)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In drivers/acpi/acpi_processor.c (ffffffff81500be2)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff81530a28)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/block/xen-blkfront.c (ffffffff820f9cde)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff8163263b)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/xen-netfront.c (ffffffff820fc9d4)
Location: include/linux/cpumask.h:506
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff816f02cb)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/thermal/thermal_core.c (ffffffff8172fbfb)
Location: include/linux/cpumask.h:506
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
In drivers/md/dm-stats.c (ffffffff8175959e)
Location: include/linux/cpumask.h:506
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81767248)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817687d4)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8176a0ad)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff82101da3)
Location: include/linux/cpumask.h:506
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff817836e0)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (ffffffff817cc806)
Location: include/linux/cpumask.h:506
Inline: True
```
```
In net/core/flow.c (ffffffff817ef0f6)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_lookup
```
```
In net/core/net-sysfs.c (ffffffff817f0969)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181ecb6)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In lib/cpumask.c (ffffffff818ebd1d)
Location: include/linux/cpumask.h:506
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
**Symbols:**

```
ffffffff81029abb-ffffffff81029ad3: cpumask_weight.constprop.3 (STB_LOCAL)
ffffffff81032dc0-ffffffff81032dd1: cpumask_weight (STB_LOCAL)
ffffffff810532d0-ffffffff810532e1: cpumask_weight (STB_LOCAL)
ffffffff81056f5f-ffffffff81056f77: cpumask_weight.constprop.18 (STB_LOCAL)
ffffffff81077e00-ffffffff81077e11: cpumask_weight (STB_LOCAL)
ffffffff8109ddd0-ffffffff8109dde8: cpumask_weight.constprop.35 (STB_LOCAL)
ffffffff810a3ea1-ffffffff810a3eb9: cpumask_weight.constprop.3 (STB_LOCAL)
ffffffff810ac4d0-ffffffff810ac4e1: cpumask_weight (STB_LOCAL)
ffffffff810b6cc0-ffffffff810b6cd8: cpumask_weight.constprop.98 (STB_LOCAL)
ffffffff810e4a9f-ffffffff810e4ab7: cpumask_weight.constprop.30 (STB_LOCAL)
ffffffff81113920-ffffffff81113931: cpumask_weight (STB_LOCAL)
ffffffff8119abe0-ffffffff8119abf8: cpumask_weight.constprop.15 (STB_LOCAL)
ffffffff811de470-ffffffff811de481: cpumask_weight (STB_LOCAL)
ffffffff811e4bb7-ffffffff811e4bcf: cpumask_weight.constprop.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff826a6d5a)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102473a)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/trace.c (ffffffff81028c01)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp.c (ffffffff8102928b)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/xen/smp_pv.c (ffffffff81029cdb)
Location: include/linux/cpumask.h:510
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102a211)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102ae69)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/alternative.c (ffffffff81035d06)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff810379d9)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8103e073)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff8104230a)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81046ac2)
Location: include/linux/cpumask.h:510
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
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104ff1f)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052adf)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81056273)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81056703)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81056cba)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff810585ce)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81059026)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105abcc)
Location: include/linux/cpumask.h:510
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81060a53)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In arch/x86/kernel/ftrace.c (ffffffff81060da1)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In arch/x86/kernel/crash.c (ffffffff81063c6f)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
```
In arch/x86/kernel/hpet.c (ffffffff8106930a)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107e778)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
Direct callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff8108d9f8)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/workqueue.c (ffffffff810a7082)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffffffff810aa47f)
Location: include/linux/cpumask.h:510
Inline: True
Direct callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/sched/core.c (ffffffff810ba95e)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/fair.c (ffffffff810be030)
Location: include/linux/cpumask.h:510
Inline: True
Direct callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/rt.c (ffffffff810ca636)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810d09ad)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
```
```
In kernel/sched/topology.c (ffffffff810d352b)
Location: include/linux/cpumask.h:510
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
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810db3d5)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/sched/membarrier.c (ffffffff810dbe52)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:SyS_membarrier
  - kernel/sched/membarrier.c:SyS_membarrier
```
```
In kernel/locking/qspinlock.c (ffffffff826cbe33)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/power/swap.c (ffffffff810e5ebe)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk.c (ffffffff810ecd3e)
Location: include/linux/cpumask.h:510
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_safe.c (ffffffff810ed188)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/affinity.c (ffffffff810f8953)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff81100bb6)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/clockevents.c (ffffffff81117f7b)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff8111885a)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8111aac7)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff826ceab0)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff8111f50d)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
Direct callers:
  - kernel/smp.c:smp_init
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff81140882)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffffffff8114fa73)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff81150205)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81157b6f)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81158d1b)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81159e19)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/trace/trace.c (ffffffff81175714)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:print_trace_header
```
```
In kernel/bpf/syscall.c (ffffffff811a0cc2)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In kernel/bpf/hashtab.c (ffffffff811abb61)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811acb70)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffff811ad02b)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811adca4)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/devmap.c (ffffffff811af498)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811afad7)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In kernel/events/core.c (ffffffff811bd905)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/padata.c (ffffffff811c7d0f)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder_timer
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In mm/page-writeback.c (ffffffff811ddcbe)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff811f58c5)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_pressure_threshold
Direct callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/mm_init.c (ffffffff8198d84e)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff811fae19)
Location: include/linux/cpumask.h:510
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/swap_slots.c (ffffffff81202d2a)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/vmalloc.c (ffffffff8121edc4)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/hugetlb.c (ffffffff826ddb36)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In mm/slub.c (ffffffff812450e7)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/aio.c (ffffffff812cae5e)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/proc/stat.c (ffffffff812f77a6)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In lib/percpu_ida.c (ffffffff81496a54)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/rhashtable.c (ffffffff814976db)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In lib/percpu_counter.c (ffffffff814bd549)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In drivers/acpi/acpi_processor.c (ffffffff81542fb7)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff81591a5a)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/xen/time.c (ffffffff815bc674)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/block/xen-blkfront.c (ffffffff827034c1)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff8169afab)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/xen-netfront.c (ffffffff82706149)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff8175c48b)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/md/dm-stats.c (ffffffff817cb7fe)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff817dd165)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff817de6c4)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817dff8d)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8270b3f3)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff817f9aa0)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (ffffffff81845e86)
Location: include/linux/cpumask.h:510
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff8186bf69)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189dc66)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In lib/cpumask.c (ffffffff81971cfd)
Location: include/linux/cpumask.h:510
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
**Symbols:**

```
ffffffff81029cdb-ffffffff81029cf3: cpumask_weight.constprop.4 (STB_LOCAL)
ffffffff81035010-ffffffff81035021: cpumask_weight (STB_LOCAL)
ffffffff81057060-ffffffff81057071: cpumask_weight (STB_LOCAL)
ffffffff8105abcc-ffffffff8105abe4: cpumask_weight.constprop.14 (STB_LOCAL)
ffffffff8107e160-ffffffff8107e171: cpumask_weight (STB_LOCAL)
ffffffff810a4550-ffffffff810a4568: cpumask_weight.constprop.37 (STB_LOCAL)
ffffffff810aa47f-ffffffff810aa497: cpumask_weight.constprop.1 (STB_LOCAL)
ffffffff810b3250-ffffffff810b3261: cpumask_weight (STB_LOCAL)
ffffffff810be030-ffffffff810be048: cpumask_weight.constprop.100 (STB_LOCAL)
ffffffff810ecd3e-ffffffff810ecd56: cpumask_weight.constprop.30 (STB_LOCAL)
ffffffff8111eeb0-ffffffff8111eec1: cpumask_weight (STB_LOCAL)
ffffffff811aa3f0-ffffffff811aa408: cpumask_weight.constprop.17 (STB_LOCAL)
ffffffff811f3f20-ffffffff811f3f31: cpumask_weight (STB_LOCAL)
ffffffff811fae19-ffffffff811fae31: cpumask_weight.constprop.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff826cfee6)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025645)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/trace.c (ffffffff81029643)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp.c (ffffffff81029cef)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a777)
Location: include/linux/cpumask.h:512
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102afe0)
Location: include/linux/cpumask.h:512
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102ba2f)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/alternative.c (ffffffff81036c82)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff81038912)
Location: include/linux/cpumask.h:512
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8103f613)
Location: include/linux/cpumask.h:512
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff810441f9)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81049013)
Location: include/linux/cpumask.h:512
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
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff81052b85)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055929)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810590d6)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81059524)
Location: include/linux/cpumask.h:512
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81059b1b)
Location: include/linux/cpumask.h:512
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105b24a)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8105be94)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105dada)
Location: include/linux/cpumask.h:512
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81063b42)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/ftrace.c (ffffffff81063ec0)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:run_sync
```
```
In arch/x86/kernel/hpet.c (ffffffff8106bf78)
Location: include/linux/cpumask.h:512
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810817a9)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
Direct callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff810917f6)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/workqueue.c (ffffffff810ad361)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffffffff810b10af)
Location: include/linux/cpumask.h:512
Inline: True
Direct callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/sched/core.c (ffffffff810ba360)
Location: include/linux/cpumask.h:512
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/fair.c (ffffffff810c5d60)
Location: include/linux/cpumask.h:512
Inline: True
Direct callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/rt.c (ffffffff810d3376)
Location: include/linux/cpumask.h:512
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810d8ee6)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
```
```
In kernel/sched/topology.c (ffffffff810db1f1)
Location: include/linux/cpumask.h:512
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
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810e362d)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/sched/membarrier.c (ffffffff810e4492)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/locking/qspinlock.c (ffffffff826f5f9b)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/power/swap.c (ffffffff810ee36f)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk.c (ffffffff810f4e88)
Location: include/linux/cpumask.h:512
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_safe.c (ffffffff810f5413)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/affinity.c (ffffffff81100ed0)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
```
```
In kernel/rcu/tree.c (ffffffff8110731e)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/clockevents.c (ffffffff81124a5a)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff811253fa)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff81127848)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff826f91ed)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff8112c844)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
Direct callers:
  - kernel/smp.c:smp_init
  - kernel/smp.c:smp_init
```
```
In kernel/kexec_file.c (ffffffff8113a025)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/stop_machine.c (ffffffff8114f1c2)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffffffff8115e5b3)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff8115ed95)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81166765)
Location: include/linux/cpumask.h:512
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81167931)
Location: include/linux/cpumask.h:512
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81168a48)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/trace/trace.c (ffffffff811847cb)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:print_trace_header
```
```
In kernel/bpf/syscall.c (ffffffff811b4271)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffff811c3038)
Location: include/linux/cpumask.h:512
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
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffff811c4595)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811c5217)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/devmap.c (ffffffff811c9cde)
Location: include/linux/cpumask.h:512
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811ca5d7)
Location: include/linux/cpumask.h:512
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffff811cb13e)
Location: include/linux/cpumask.h:512
Inline: True
```
```
In kernel/events/core.c (ffffffff811ddb7d)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/padata.c (ffffffff811e8131)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder_timer
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In mm/page-writeback.c (ffffffff811ff242)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff81216b45)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_pressure_threshold
Direct callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/mm_init.c (ffffffff819ea10d)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff8121c0bd)
Location: include/linux/cpumask.h:512
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/vmalloc.c (ffffffff81241694)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/swap_slots.c (ffffffff8124eddc)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/hugetlb.c (ffffffff827080aa)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/slub.c (ffffffff81269253)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/aio.c (ffffffff812f5376)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/crypto.c (ffffffff8270d81c)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/proc/stat.c (ffffffff81324b45)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In lib/percpu_ida.c (ffffffff814cbdcf)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In lib/bucket_locks.c (ffffffff814cdcc0)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - lib/bucket_locks.c:alloc_bucket_spinlocks
```
```
In lib/percpu_counter.c (ffffffff814efda0)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In drivers/acpi/acpi_processor.c (ffffffff81578d06)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff815c8dc8)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/xen/time.c (ffffffff815f4d24)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/block/xen-blkfront.c (ffffffff8272d241)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff816d7538)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/xen-netfront.c (ffffffff8272ff8a)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netif_init
```
```
In drivers/usb/host/xhci.c (ffffffff8179ce91)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/md/dm-stats.c (ffffffff818145f4)
Location: include/linux/cpumask.h:512
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81825dd8)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81827342)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81828f22)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff827356d1)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818430f4)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (ffffffff8188f525)
Location: include/linux/cpumask.h:512
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff818bc6d9)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f1865)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In lib/cpumask.c (ffffffff819ce0a0)
Location: include/linux/cpumask.h:512
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
**Symbols:**

```
ffffffff8102a777-ffffffff8102a78f: cpumask_weight.constprop.3 (STB_LOCAL)
ffffffff8102afe0-ffffffff8102aff8: cpumask_weight.constprop.5 (STB_LOCAL)
ffffffff81036190-ffffffff810361a1: cpumask_weight (STB_LOCAL)
ffffffff81059ed0-ffffffff81059ee1: cpumask_weight (STB_LOCAL)
ffffffff8105dada-ffffffff8105daf2: cpumask_weight.constprop.17 (STB_LOCAL)
ffffffff810811d0-ffffffff810811e1: cpumask_weight (STB_LOCAL)
ffffffff810aaa50-ffffffff810aaa68: cpumask_weight.constprop.42 (STB_LOCAL)
ffffffff810b10af-ffffffff810b10c7: cpumask_weight.constprop.5 (STB_LOCAL)
ffffffff810ba360-ffffffff810ba371: cpumask_weight (STB_LOCAL)
ffffffff810c5d60-ffffffff810c5d78: cpumask_weight.constprop.106 (STB_LOCAL)
ffffffff810f4e88-ffffffff810f4ea0: cpumask_weight.constprop.30 (STB_LOCAL)
ffffffff8112c1f0-ffffffff8112c201: cpumask_weight (STB_LOCAL)
ffffffff81215370-ffffffff81215381: cpumask_weight (STB_LOCAL)
ffffffff8121c0bd-ffffffff8121c0d5: cpumask_weight.constprop.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff82885f57)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81024ce5)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/trace.c (ffffffff81029c23)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp.c (ffffffff8102a2cf)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102adb7)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/xen/spinlock.c (ffffffff8288e1fb)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102b710)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102c47b)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/alternative.c (ffffffff81037e92)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff81039b82)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81040d63)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81045bf9)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104af1a)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810501f5)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052fc9)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81058ff5)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
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
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff8105f1d4)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff8105f79b)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff81060eca)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81061b74)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106376b)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81069842)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/ftrace.c (ffffffff81069b70)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:run_sync
```
```
In arch/x86/kernel/hpet.c (ffffffff81071d08)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff828a038d)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81073924)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo
  - arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo
```
```
In arch/x86/mm/pageattr.c (ffffffff81080f34)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810883b9)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
Direct callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff81099ad6)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/workqueue.c (ffffffff810b6d31)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffffffff810ba1ef)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/sched/core.c (ffffffff810c3460)
Location: include/linux/cpumask.h:524
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/fair.c (ffffffff810ce700)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/rt.c (ffffffff810dc716)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In kernel/sched/deadline.c (ffffffff810e29e6)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
```
```
In kernel/sched/topology.c (ffffffff810e4dee)
Location: include/linux/cpumask.h:524
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
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810edcfd)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/sched/membarrier.c (ffffffff810eec63)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/locking/qspinlock.c (ffffffff828aceac)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/power/swap.c (ffffffff810f99df)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk.c (ffffffff81100648)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_safe.c (ffffffff81100bb3)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/affinity.c (ffffffff8110c7e4)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
```
```
In kernel/rcu/tree.c (ffffffff811130fe)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/clockevents.c (ffffffff8113015a)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff81130aea)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff81132f38)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff828b00c7)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff81138114)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
Direct callers:
  - kernel/smp.c:smp_init
  - kernel/smp.c:smp_init
```
```
In kernel/kexec_file.c (ffffffff811458f5)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cpuset.c (ffffffff811577a6)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/stop_machine.c (ffffffff8115bea2)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffffffff8116b12b)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff8116bac5)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811734c5)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81174761)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8117588f)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/trace/trace.c (ffffffff81190deb)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/bpf/syscall.c (ffffffff811c5488)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/hashtab.c (ffffffff811d4b04)
Location: include/linux/cpumask.h:524
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
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffff811d6165)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811d6e17)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffff811d82f6)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811dd5de)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811ddef7)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffff811dea4e)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In kernel/events/core.c (ffffffff811edf7d)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/padata.c (ffffffff811f8e77)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder_timer
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In mm/page-writeback.c (ffffffff81211b02)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff81229a55)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_pressure_threshold
Direct callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/mm_init.c (ffffffff81a25390)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff8122f0ba)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/vmalloc.c (ffffffff81255d94)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/swap_slots.c (ffffffff812632c4)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/hugetlb.c (ffffffff828bf47c)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/slub.c (ffffffff81278c6b)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/aio.c (ffffffff8130a466)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/crypto/crypto.c (ffffffff828c4a42)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/proc/stat.c (ffffffff8133bce5)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In lib/bucket_locks.c (ffffffff814e2590)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/percpu_counter.c (ffffffff81503cc0)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In drivers/acpi/acpi_processor.c (ffffffff8159095f)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff815e2398)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/xen/time.c (ffffffff8160fb84)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/block/xen-blkfront.c (ffffffff828e5bc1)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff816f9408)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/xen-netfront.c (ffffffff828e8c47)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netif_init
```
```
In drivers/usb/host/xhci.c (ffffffff817c3271)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/md/dm-stats.c (ffffffff818405fc)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81851cb8)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81853242)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81854fb2)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff828ef118)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff828ef5fd)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8186f0f9)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (ffffffff818b2dd2)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffffffff818e3839)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191f445)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In lib/cpumask.c (ffffffff81a07560)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
**Symbols:**

```
ffffffff8102adb7-ffffffff8102adcf: cpumask_weight.constprop.4 (STB_LOCAL)
ffffffff8102b710-ffffffff8102b728: cpumask_weight.constprop.5 (STB_LOCAL)
ffffffff81037380-ffffffff81037391: cpumask_weight (STB_LOCAL)
ffffffff8105fb50-ffffffff8105fb61: cpumask_weight (STB_LOCAL)
ffffffff8106376b-ffffffff81063783: cpumask_weight.constprop.18 (STB_LOCAL)
ffffffff81073924-ffffffff8107393c: cpumask_weight.constprop.3 (STB_LOCAL)
ffffffff81080f34-ffffffff81080f4c: cpumask_weight.constprop.27 (STB_LOCAL)
ffffffff81087de0-ffffffff81087df1: cpumask_weight (STB_LOCAL)
ffffffff810b3bd0-ffffffff810b3be8: cpumask_weight.constprop.44 (STB_LOCAL)
ffffffff810ba1ef-ffffffff810ba207: cpumask_weight.constprop.5 (STB_LOCAL)
ffffffff810c3460-ffffffff810c3471: cpumask_weight (STB_LOCAL)
ffffffff810ce700-ffffffff810ce718: cpumask_weight.constprop.113 (STB_LOCAL)
ffffffff81100648-ffffffff81100660: cpumask_weight.constprop.31 (STB_LOCAL)
ffffffff81137ac0-ffffffff81137ad1: cpumask_weight (STB_LOCAL)
ffffffff81228250-ffffffff81228261: cpumask_weight (STB_LOCAL)
ffffffff8122f0ba-ffffffff8122f0d2: cpumask_weight.constprop.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009144)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81022c40)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/trace.c (ffffffff8102a6f0)
Location: include/linux/cpumask.h:524
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp.c (ffffffff8102baf0)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cb8d)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/xen/spinlock.c (ffffffff8102ce1b)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102d4b1)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102d6a0)
Location: include/linux/cpumask.h:524
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/alternative.c (ffffffff81039da2)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff8103b290)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81043440)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff810485a0)
Location: include/linux/cpumask.h:524
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cb20)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81053260)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056070)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059b90)
Location: include/linux/cpumask.h:524
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81062126)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81062290)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff810629f0)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063010)
Location: include/linux/cpumask.h:524
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81064c40)
Location: include/linux/cpumask.h:524
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066de6)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d022)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106d420)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:run_sync
```
```
In arch/x86/kernel/hpet.c (ffffffff8107585e)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvm.c (ffffffff810771a3)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8107749e)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/pageattr.c (ffffffff81084b25)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108ba20)
Location: include/linux/cpumask.h:524
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff8109c1b0)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/workqueue.c (ffffffff810bd1a9)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffffffff810c00ff)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/sched/core.c (ffffffff810d2d95)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810e1f25)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/rt.c (ffffffff810e2c50)
Location: include/linux/cpumask.h:524
Inline: False
```
```
In kernel/sched/deadline.c (ffffffff810e55e0)
Location: include/linux/cpumask.h:524
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
```
```
In kernel/sched/topology.c (ffffffff810eb5e5)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/sched/topology.c:sd_degenerate
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/sched/debug.c (ffffffff810f0970)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f4a10)
Location: include/linux/cpumask.h:524
Inline: False
```
```
In kernel/sched/membarrier.c (ffffffff810f5710)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/locking/qspinlock.c (ffffffff810f9247)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/power/swap.c (ffffffff81102090)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk.c (ffffffff81108e2a)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/printk/printk_safe.c (ffffffff81109373)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/irq/affinity.c (ffffffff811155a0)
Location: include/linux/cpumask.h:524
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff8111db55)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_scheduler_starting
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
```
In kernel/time/clockevents.c (ffffffff8113a0f0)
Location: include/linux/cpumask.h:524
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-common.c (ffffffff8113aea0)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8113cda0)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff8114293f)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff81142bf0)
Location: include/linux/cpumask.h:524
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_many
  - kernel/smp.c:smp_init
  - kernel/smp.c:smp_init
```
```
In kernel/kexec_file.c (ffffffff8114f770)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cpuset.c (ffffffff8115fea0)
Location: include/linux/cpumask.h:524
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/stop_machine.c (ffffffff81167bb0)
Location: include/linux/cpumask.h:524
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffffffff81176080)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
```
In kernel/debug/debug_core.c (ffffffff81178400)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8117da60)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81180c70)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81182230)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/trace/trace.c (ffffffff8119a210)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/bpf/syscall.c (ffffffff811d2ae0)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffff811e7740)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811ea4b0)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffff811eaa20)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811eb110)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffff811ecd50)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811f2be0)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811f34f0)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffff811f4320)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In kernel/events/core.c (ffffffff811fe590)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - kernel/events/core.c:perf_mmap
```
```
In kernel/padata.c (ffffffff8120f9b0)
Location: include/linux/cpumask.h:524
Inline: False
Direct callers:
  - kernel/padata.c:padata_reorder_timer
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In mm/page-writeback.c (ffffffff81221112)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff812396f5)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_pressure_threshold
Direct callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:refresh_zone_stat_thresholds
```
```
In mm/mm_init.c (ffffffff8123bdc5)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff8123f0ba)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/vmalloc.c (ffffffff81268ee9)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:set_iounmap_nonlazy
Direct callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/swap_slots.c (ffffffff8127dd00)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/hugetlb.c (ffffffff812883c6)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/slub.c (ffffffff81293aa0)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - mm/slub.c:list_locations
```
```
In fs/aio.c (ffffffff81328b90)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/io_uring.c (ffffffff8132df70)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (ffffffff81337094)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/proc/stat.c (ffffffff81363f25)
Location: include/linux/cpumask.h:524
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In lib/bucket_locks.c (ffffffff8150e430)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/percpu_counter.c (ffffffff81531e20)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In drivers/acpi/acpi_processor.c (ffffffff815c1450)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff81613ca0)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/xen/time.c (ffffffff816438c0)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816d046a)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/block/xen-blkfront.c (ffffffff8170fcec)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff81732cb0)
Location: include/linux/cpumask.h:524
Inline: False
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/xen-netfront.c (ffffffff817ac3ff)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:netif_init
```
```
In drivers/usb/host/xhci.c (ffffffff81802410)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/md/dm-stats.c (ffffffff81882d10)
Location: include/linux/cpumask.h:524
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818951b0)
Location: include/linux/cpumask.h:524
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81895fe0)
Location: include/linux/cpumask.h:524
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81897860)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81899461)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8189c5fb)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818b3380)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (ffffffff818fa030)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffffffff819320d0)
Location: include/linux/cpumask.h:524
Inline: False
Direct callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/bpf_sk_storage.c (ffffffff81953570)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff81981d90)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In lib/cpumask.c (ffffffff81a76ec0)
Location: include/linux/cpumask.h:524
Inline: True
Direct callers:
  - lib/cpumask.c:cpumask_local_spread
```
**Symbols:**

```
ffffffff81009144-ffffffff8100915c: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81022c40-ffffffff81022c58: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102a6f0-ffffffff8102a701: cpumask_weight (STB_LOCAL)
ffffffff8102baf0-ffffffff8102bb08: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102cb8d-ffffffff8102cba5: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102ce1b-ffffffff8102ce33: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102d4b1-ffffffff8102d4c9: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102d6a0-ffffffff8102d6b1: cpumask_weight (STB_LOCAL)
ffffffff810395b0-ffffffff810395c1: cpumask_weight (STB_LOCAL)
ffffffff8103b290-ffffffff8103b2a1: cpumask_weight (STB_LOCAL)
ffffffff81043440-ffffffff81043458: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810485a0-ffffffff810485b1: cpumask_weight (STB_LOCAL)
ffffffff8104cb20-ffffffff8104cb38: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81053260-ffffffff81053278: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81056070-ffffffff81056088: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81059b90-ffffffff81059ba1: cpumask_weight (STB_LOCAL)
ffffffff81062290-ffffffff810622a8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810629f0-ffffffff81062a08: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81063010-ffffffff81063021: cpumask_weight (STB_LOCAL)
ffffffff81064c40-ffffffff81064c51: cpumask_weight (STB_LOCAL)
ffffffff81066de6-ffffffff81066dfe: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8107585e-ffffffff81075876: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810771a3-ffffffff810771bb: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8107749e-ffffffff810774b6: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81084b25-ffffffff81084b3d: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8108ba20-ffffffff8108ba31: cpumask_weight (STB_LOCAL)
ffffffff8109c1b0-ffffffff8109c1c8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810b98d0-ffffffff810b98e8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810c00ff-ffffffff810c0117: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810c9540-ffffffff810c9551: cpumask_weight (STB_LOCAL)
ffffffff810e2c50-ffffffff810e2c61: cpumask_weight (STB_LOCAL)
ffffffff810e55e0-ffffffff810e55f1: cpumask_weight (STB_LOCAL)
ffffffff810eb0d0-ffffffff810eb0e1: cpumask_weight (STB_LOCAL)
ffffffff810f0970-ffffffff810f0988: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810f4a10-ffffffff810f4a21: cpumask_weight (STB_LOCAL)
ffffffff810f5710-ffffffff810f5728: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810f9247-ffffffff810f925f: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81102090-ffffffff811020a8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81108e2a-ffffffff81108e42: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811155a0-ffffffff811155b1: cpumask_weight (STB_LOCAL)
ffffffff8111a4f0-ffffffff8111a508: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8113a0f0-ffffffff8113a101: cpumask_weight (STB_LOCAL)
ffffffff8113aea0-ffffffff8113aeb8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8113cda0-ffffffff8113cdb8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8114293f-ffffffff81142957: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81142bf0-ffffffff81142c01: cpumask_weight (STB_LOCAL)
ffffffff8114f770-ffffffff8114f788: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8115fea0-ffffffff8115feb1: cpumask_weight (STB_LOCAL)
ffffffff81167bb0-ffffffff81167bc1: cpumask_weight (STB_LOCAL)
ffffffff81176080-ffffffff81176098: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81178400-ffffffff81178418: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8117da60-ffffffff8117da78: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81180c70-ffffffff81180c88: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81182230-ffffffff81182248: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8119a210-ffffffff8119a228: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811d2ae0-ffffffff811d2af8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811e7740-ffffffff811e7758: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811ea4b0-ffffffff811ea4c8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811eaa20-ffffffff811eaa38: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811eb110-ffffffff811eb128: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811ecd50-ffffffff811ecd68: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811f2be0-ffffffff811f2bf8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811f34f0-ffffffff811f3508: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811f4320-ffffffff811f4338: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811fe590-ffffffff811fe5a8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8120f9b0-ffffffff8120f9c1: cpumask_weight (STB_LOCAL)
ffffffff81237e60-ffffffff81237e71: cpumask_weight (STB_LOCAL)
ffffffff8123bdc5-ffffffff8123bddd: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8123f0ba-ffffffff8123f0d2: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812674f0-ffffffff81267508: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8127dd00-ffffffff8127dd18: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812883c6-ffffffff812883de: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81293aa0-ffffffff81293ab8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81328b90-ffffffff81328ba8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8132df70-ffffffff8132df88: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81337094-ffffffff813370ac: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8150e430-ffffffff8150e448: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81531e20-ffffffff81531e38: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff815c1450-ffffffff815c1468: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81613ca0-ffffffff81613cb8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff816438c0-ffffffff816438d8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff816d046a-ffffffff816d0482: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8170fcec-ffffffff8170fd04: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81732cb0-ffffffff81732cc1: cpumask_weight (STB_LOCAL)
ffffffff817ac3ff-ffffffff817ac417: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81802410-ffffffff81802428: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81882d10-ffffffff81882d28: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818951b0-ffffffff818951c1: cpumask_weight (STB_LOCAL)
ffffffff81895fe0-ffffffff81895ff1: cpumask_weight (STB_LOCAL)
ffffffff81897860-ffffffff81897878: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81899461-ffffffff81899479: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8189c5fb-ffffffff8189c613: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818b3380-ffffffff818b3398: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818fa030-ffffffff818fa041: cpumask_weight (STB_LOCAL)
ffffffff819320d0-ffffffff819320e1: cpumask_weight (STB_LOCAL)
ffffffff81953570-ffffffff81953588: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81981d90-ffffffff81981da8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81a76ec0-ffffffff81a76ed8: cpumask_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009544)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023580)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/trace.c (ffffffff8102aff0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d463)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/xen/spinlock.c (ffffffff8102d6eb)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102ddc1)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102dfb0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a582)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff8103bd70)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81048e70)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81053b50)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a480)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff810636c0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810652b0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106745b)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106da2a)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106e702)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff8107682e)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvm.c (ffffffff81078202)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8107852e)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108c690)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff810975e0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_next
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_start
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81099330)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/workqueue.c (ffffffff810c2e29)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffffffff810c64cf)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/sched/core.c (ffffffff810dd225)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/rt.c (ffffffff810ed3d0)
Location: include/linux/cpumask.h:554
Inline: False
```
```
In kernel/sched/deadline.c (ffffffff810f0a00)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (ffffffff810f6f85)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/topology.c:sd_degenerate
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/debug.c (ffffffff810fc620)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81100680)
Location: include/linux/cpumask.h:554
Inline: False
```
```
In kernel/locking/qspinlock.c (ffffffff81105037)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/printk/printk.c (ffffffff8111520a)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/irq/affinity.c (ffffffff811217a0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/clockevents.c (ffffffff81145d60)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (ffffffff81148b40)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff8114e62c)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff8114e760)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/kexec_file.c (ffffffff8115b450)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cpuset.c (ffffffff8116bb70)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/stop_machine.c (ffffffff81173a70)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffffffff81181f30)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811898e0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8118cae0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8118e0a0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/bpf/syscall.c (ffffffff811dedc0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffff811f3ea0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811f6c10)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffff811f7180)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811f7870)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffff811f94a0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811ff9a0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff81200290)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffff81201350)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/padata.c (ffffffff8121cfe0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmstat.c (ffffffff812479f5)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
Direct callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/mm_init.c (ffffffff8124a216)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff8124d51a)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/hugetlb.c (ffffffff81297fc6)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/aio.c (ffffffff8133b940)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In lib/bucket_locks.c (ffffffff8152c350)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/xen/time.c (ffffffff81665e70)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816f428a)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/nvdimm/region.c (ffffffff817568d0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/dm-stats.c (ffffffff818b4bb0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818c71d0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818c7ff0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff818cb451)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818ce8d0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818e5ca0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (ffffffff8192e2c0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffffffff81964c10)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/bpf_sk_storage.c (ffffffff81989920)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b85e0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffff81009544-ffffffff8100955c: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81023580-ffffffff81023598: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102aff0-ffffffff8102b001: cpumask_weight (STB_LOCAL)
ffffffff8102d463-ffffffff8102d47b: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102d6eb-ffffffff8102d703: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102ddc1-ffffffff8102ddd9: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102dfb0-ffffffff8102dfc1: cpumask_weight (STB_LOCAL)
ffffffff81039d80-ffffffff81039d91: cpumask_weight (STB_LOCAL)
ffffffff8103bd70-ffffffff8103bd88: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81048e70-ffffffff81048e81: cpumask_weight (STB_LOCAL)
ffffffff81053b50-ffffffff81053b68: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8105a480-ffffffff8105a491: cpumask_weight (STB_LOCAL)
ffffffff810636c0-ffffffff810636d1: cpumask_weight (STB_LOCAL)
ffffffff810652b0-ffffffff810652c1: cpumask_weight (STB_LOCAL)
ffffffff8106745b-ffffffff81067473: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8106da2a-ffffffff8106da42: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8107682e-ffffffff81076846: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81078202-ffffffff8107821a: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8107852e-ffffffff81078546: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8108c690-ffffffff8108c6a1: cpumask_weight (STB_LOCAL)
ffffffff810958d0-ffffffff810958e8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81099330-ffffffff81099341: cpumask_weight (STB_LOCAL)
ffffffff810bfd50-ffffffff810bfd68: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810c64cf-ffffffff810c64e7: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810d2610-ffffffff810d2621: cpumask_weight (STB_LOCAL)
ffffffff810ed3d0-ffffffff810ed3e1: cpumask_weight (STB_LOCAL)
ffffffff810f0a00-ffffffff810f0a11: cpumask_weight (STB_LOCAL)
ffffffff810f6a70-ffffffff810f6a81: cpumask_weight (STB_LOCAL)
ffffffff810fc620-ffffffff810fc638: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81100680-ffffffff81100691: cpumask_weight (STB_LOCAL)
ffffffff81105037-ffffffff8110504f: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8111520a-ffffffff81115222: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811217a0-ffffffff811217b1: cpumask_weight (STB_LOCAL)
ffffffff81145d60-ffffffff81145d71: cpumask_weight (STB_LOCAL)
ffffffff81148b40-ffffffff81148b58: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8114e62c-ffffffff8114e644: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8114e760-ffffffff8114e771: cpumask_weight (STB_LOCAL)
ffffffff8115b450-ffffffff8115b468: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8116bb70-ffffffff8116bb81: cpumask_weight (STB_LOCAL)
ffffffff81173a70-ffffffff81173a81: cpumask_weight (STB_LOCAL)
ffffffff81181f30-ffffffff81181f48: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811898e0-ffffffff811898f8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8118cae0-ffffffff8118caf8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8118e0a0-ffffffff8118e0b8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811dedc0-ffffffff811dedd8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811f3ea0-ffffffff811f3eb8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811f6c10-ffffffff811f6c28: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811f7180-ffffffff811f7198: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811f7870-ffffffff811f7888: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811f94a0-ffffffff811f94b8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811ff9a0-ffffffff811ff9b8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81200290-ffffffff812002a8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81201350-ffffffff81201368: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8121cfe0-ffffffff8121cff1: cpumask_weight (STB_LOCAL)
ffffffff81247020-ffffffff81247031: cpumask_weight (STB_LOCAL)
ffffffff8124a216-ffffffff8124a22e: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8124d51a-ffffffff8124d532: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81297fc6-ffffffff81297fde: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8133b940-ffffffff8133b958: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8152c350-ffffffff8152c368: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81665e70-ffffffff81665e88: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff816f428a-ffffffff816f42a2: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff817568d0-ffffffff817568e8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818b4bb0-ffffffff818b4bc8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818c71d0-ffffffff818c71e1: cpumask_weight (STB_LOCAL)
ffffffff818c7ff0-ffffffff818c8001: cpumask_weight (STB_LOCAL)
ffffffff818cb451-ffffffff818cb469: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818ce8d0-ffffffff818ce8e8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818e5ca0-ffffffff818e5cb8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8192e2c0-ffffffff8192e2d8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81964c10-ffffffff81964c21: cpumask_weight (STB_LOCAL)
ffffffff81989920-ffffffff81989938: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff819b85e0-ffffffff819b85f8: cpumask_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100a6e9)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025c20)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/trace.c (ffffffff8102cdf0)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102f593)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/xen/spinlock.c (ffffffff8102f81b)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8103018b)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff81030460)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/alternative.c (ffffffff8103c910)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff8103eb60)
Location: include/linux/cpumask.h:561
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff8104cf70)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81058b50)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f740)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff810698a0)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:announce_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106bbf0)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106e06f)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074eef)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81075bb0)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff8107dabb)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f534)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8107f92f)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093c40)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109a590)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:make_per_cpu_thp
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_next
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_start
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ea40)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/workqueue.c (ffffffff810c6e60)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_clamp_max_active
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffffffff810ce40f)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/sched/core.c (ffffffff810dc520)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/fair.c (ffffffff810e9050)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/rt.c (ffffffff810f71f0)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - kernel/sched/rt.c:do_balance_runtime
```
```
In kernel/sched/deadline.c (ffffffff810f9d60)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (ffffffff81100700)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:init_sched_groups_capacity
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:init_overlap_sched_group
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:update_top_cache_domain
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/sched/debug.c (ffffffff81105cd0)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110acd0)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/locking/qspinlock.c (ffffffff8110fe22)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/printk/printk.c (ffffffff81120bba)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/irq/affinity.c (ffffffff8112ddc0)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In kernel/rcu/update.c (ffffffff81130190)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_rude_wait_gp
```
```
In kernel/time/clockevents.c (ffffffff81155bd0)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (ffffffff81158930)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff8115eec9)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff8115f000)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/kexec_file.c (ffffffff8116c2d0)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cpuset.c (ffffffff8117d650)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/stop_machine.c (ffffffff81185960)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
```
In kernel/kprobes.c (ffffffff81195740)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119d980)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_pid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811a1490)
Location: include/linux/cpumask.h:561
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811a29f0)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
```
In kernel/bpf/syscall.c (ffffffff811fc440)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:bpf_map_value_size
```
```
In kernel/bpf/hashtab.c (ffffffff81217480)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
```
```
In kernel/bpf/arraymap.c (ffffffff8121a4e0)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffff8121ae70)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8121b490)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffff8121cf00)
Location: include/linux/cpumask.h:561
Inline: True
```
```
In kernel/padata.c (ffffffff812493f0)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_init
```
```
In mm/vmstat.c (ffffffff812748a0)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (ffffffff8127851c)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff8127b8aa)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/hugetlb.c (ffffffff812cb66c)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/aio.c (ffffffff813751b0)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In lib/bucket_locks.c (ffffffff8158fcc0)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/xen/time.c (ffffffff81715570)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff817ac97a)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/nvdimm/region.c (ffffffff81815ec0)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/dm-stats.c (ffffffff819855a0)
Location: include/linux/cpumask.h:561
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff819994b0)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199a0f0)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff8199d7f1)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a0d99)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff819b8f50)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (ffffffff81a00840)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffffffff81a377c0)
Location: include/linux/cpumask.h:561
Inline: False
Direct callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/bpf_sk_storage.c (ffffffff81a610b0)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa2f00)
Location: include/linux/cpumask.h:561
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffff8100a6e9-ffffffff8100a701: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81025c20-ffffffff81025c38: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102cdf0-ffffffff8102ce01: cpumask_weight (STB_LOCAL)
ffffffff8102f593-ffffffff8102f5ab: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102f81b-ffffffff8102f833: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8103018b-ffffffff810301a3: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81030460-ffffffff81030471: cpumask_weight (STB_LOCAL)
ffffffff8103c910-ffffffff8103c921: cpumask_weight (STB_LOCAL)
ffffffff8103eb60-ffffffff8103eb78: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8104cf70-ffffffff8104cf81: cpumask_weight (STB_LOCAL)
ffffffff81058b50-ffffffff81058b68: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8105f740-ffffffff8105f751: cpumask_weight (STB_LOCAL)
ffffffff810698a0-ffffffff810698b1: cpumask_weight (STB_LOCAL)
ffffffff8106bbf0-ffffffff8106bc01: cpumask_weight (STB_LOCAL)
ffffffff8106e06f-ffffffff8106e087: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81074eef-ffffffff81074f07: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81075bb0-ffffffff81075bc8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8107dabb-ffffffff8107dad3: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8107f534-ffffffff8107f54c: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8107f92f-ffffffff8107f947: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81093c40-ffffffff81093c51: cpumask_weight (STB_LOCAL)
ffffffff8109a590-ffffffff8109a5a8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8109ea40-ffffffff8109ea51: cpumask_weight (STB_LOCAL)
ffffffff810c6e60-ffffffff810c6e78: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810ce40f-ffffffff810ce427: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810dc520-ffffffff810dc531: cpumask_weight (STB_LOCAL)
ffffffff810e9050-ffffffff810e9061: cpumask_weight (STB_LOCAL)
ffffffff810f71f0-ffffffff810f7201: cpumask_weight (STB_LOCAL)
ffffffff810f9d60-ffffffff810f9d71: cpumask_weight (STB_LOCAL)
ffffffff81100700-ffffffff81100711: cpumask_weight (STB_LOCAL)
ffffffff81105cd0-ffffffff81105ce8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8110acd0-ffffffff8110ace1: cpumask_weight (STB_LOCAL)
ffffffff8110fe22-ffffffff8110fe3a: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81120bba-ffffffff81120bd2: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8112ddc0-ffffffff8112ddd1: cpumask_weight (STB_LOCAL)
ffffffff81130190-ffffffff811301a8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81155bd0-ffffffff81155be1: cpumask_weight (STB_LOCAL)
ffffffff81158930-ffffffff81158948: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8115eec9-ffffffff8115eee1: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8115f000-ffffffff8115f011: cpumask_weight (STB_LOCAL)
ffffffff8116c2d0-ffffffff8116c2e8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8117d650-ffffffff8117d661: cpumask_weight (STB_LOCAL)
ffffffff81185960-ffffffff81185971: cpumask_weight (STB_LOCAL)
ffffffff81195740-ffffffff81195758: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8119d980-ffffffff8119d998: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811a1490-ffffffff811a14a8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811a29f0-ffffffff811a2a08: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811fc440-ffffffff811fc458: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81217480-ffffffff81217498: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8121a4e0-ffffffff8121a4f8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8121ae70-ffffffff8121ae88: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8121b490-ffffffff8121b4a8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8121cf00-ffffffff8121cf18: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812493f0-ffffffff81249401: cpumask_weight (STB_LOCAL)
ffffffff812748a0-ffffffff812748b1: cpumask_weight (STB_LOCAL)
ffffffff8127851c-ffffffff81278534: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8127b8aa-ffffffff8127b8c2: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812cb66c-ffffffff812cb684: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff813751b0-ffffffff813751c8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8158fcc0-ffffffff8158fcd8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81715570-ffffffff81715588: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff817ac97a-ffffffff817ac992: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81815ec0-ffffffff81815ed8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff819855a0-ffffffff819855b8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff819994b0-ffffffff819994c1: cpumask_weight (STB_LOCAL)
ffffffff8199a0f0-ffffffff8199a101: cpumask_weight (STB_LOCAL)
ffffffff8199d7f1-ffffffff8199d809: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff819a0d99-ffffffff819a0db1: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff819b8f50-ffffffff819b8f68: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81a00840-ffffffff81a00858: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81a377c0-ffffffff81a377d1: cpumask_weight (STB_LOCAL)
ffffffff81a610b0-ffffffff81a610c8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81aa2f00-ffffffff81aa2f18: cpumask_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81bd203e)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026340)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/trace.c (ffffffff8102dda0)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp_pv.c (ffffffff81bd2d43)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/xen/spinlock.c (ffffffff81bd2d5b)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81bd2ee3)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff810311d0)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/alternative.c (ffffffff8103cdb0)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff8103ec10)
Location: include/linux/cpumask.h:567
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff8104c3d0)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81057960)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105dae0)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b4b0)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:announce_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106d4d0)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81bd6dd7)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81bd7954)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810761e0)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff81bd7f60)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In arch/x86/kernel/kvm.c (ffffffff81bd80ba)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81bd8132)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093190)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a5a0)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/workqueue.c (ffffffff810c1f70)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_clamp_max_active
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffffffff81bdc130)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/reboot.c (ffffffff810d3300)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/reboot.c:cpu_store
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/sched/core.c (ffffffff810d8d40)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:init_idle
```
```
In kernel/sched/fair.c (ffffffff810e6e00)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/rt.c (ffffffff810f5380)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - kernel/sched/rt.c:do_balance_runtime
```
```
In kernel/sched/deadline.c (ffffffff810f8120)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/sched/topology.c (ffffffff810ff250)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:init_sched_groups_capacity
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:init_overlap_sched_group
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:update_top_cache_domain
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/sched/debug.c (ffffffff81104320)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81107be0)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/locking/qspinlock.c (ffffffff81bde8a9)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/printk/printk.c (ffffffff81be11c8)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/irq/affinity.c (ffffffff811299b0)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In kernel/rcu/update.c (ffffffff8112bfd0)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_rude_wait_gp
```
```
In kernel/time/clockevents.c (ffffffff81151d70)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (ffffffff81154940)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff81be3daa)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff8115afa0)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_many_cond
```
```
In kernel/kexec_file.c (ffffffff81168910)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cpuset.c (ffffffff8117a4a0)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/stop_machine.c (ffffffff81182a70)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
```
In kernel/kprobes.c (ffffffff81192400)
Location: include/linux/cpumask.h:567
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119a9c0)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_pid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119e5e0)
Location: include/linux/cpumask.h:567
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8119fb40)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
```
In kernel/bpf/syscall.c (ffffffff811fb840)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:bpf_map_value_size
```
```
In kernel/bpf/map_iter.c (ffffffff812181b0)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/bpf/map_iter.c:bpf_iter_attach_map
```
```
In kernel/bpf/hashtab.c (ffffffff81219580)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:bpf_iter_init_hash_map
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
```
```
In kernel/bpf/arraymap.c (ffffffff8121d160)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/bpf/arraymap.c:bpf_iter_init_array_map
```
```
In kernel/bpf/percpu_freelist.c (ffffffff8121dc00)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8121e410)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffff8121fd60)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8122f890)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/padata.c (ffffffff812538f0)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_init
```
```
In mm/vmstat.c (ffffffff8127f0f0)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (ffffffff81282b00)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff812841a0)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_free_hook
  - mm/percpu.c:pcpu_memcg_free_hook
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/mmap_lock.c (ffffffff81295fd0)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - mm/mmap_lock.c:trace_mmap_lock_reg
```
```
In mm/hugetlb.c (ffffffff81be8a33)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/slub.c (ffffffff812e3890)
Location: include/linux/cpumask.h:567
Inline: True
```
```
In fs/aio.c (ffffffff81383060)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In lib/bucket_locks.c (ffffffff815ac830)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/xen/time.c (ffffffff81731f40)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81c0d857)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/nvdimm/region.c (ffffffff81825050)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/dm-stats.c (ffffffff81989620)
Location: include/linux/cpumask.h:567
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8199c590)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8199d250)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81c29f72)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81c29f8a)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff819bb3c0)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (ffffffff81a00c50)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffffffff81a39bd0)
Location: include/linux/cpumask.h:567
Inline: False
Direct callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aad430)
Location: include/linux/cpumask.h:567
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffff81bd203e-ffffffff81bd2056: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81026340-ffffffff81026358: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102dda0-ffffffff8102ddb1: cpumask_weight (STB_LOCAL)
ffffffff81bd2d43-ffffffff81bd2d5b: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81bd2d5b-ffffffff81bd2d73: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81bd2ee3-ffffffff81bd2efb: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810311d0-ffffffff810311e1: cpumask_weight (STB_LOCAL)
ffffffff8103cdb0-ffffffff8103cdc1: cpumask_weight (STB_LOCAL)
ffffffff8103ec10-ffffffff8103ec28: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8104c3d0-ffffffff8104c3e1: cpumask_weight (STB_LOCAL)
ffffffff81057960-ffffffff81057978: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8105dae0-ffffffff8105daf1: cpumask_weight (STB_LOCAL)
ffffffff8106b4b0-ffffffff8106b4c1: cpumask_weight (STB_LOCAL)
ffffffff8106d4d0-ffffffff8106d4e1: cpumask_weight (STB_LOCAL)
ffffffff81bd6dd7-ffffffff81bd6def: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81bd7954-ffffffff81bd796c: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810761e0-ffffffff810761f8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81bd7f60-ffffffff81bd7f78: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81bd80ba-ffffffff81bd80d2: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81bd8132-ffffffff81bd814a: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81093190-ffffffff810931a1: cpumask_weight (STB_LOCAL)
ffffffff8109a5a0-ffffffff8109a5b1: cpumask_weight (STB_LOCAL)
ffffffff810c1f70-ffffffff810c1f88: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81bdc130-ffffffff81bdc148: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810d3300-ffffffff810d3318: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810d8d40-ffffffff810d8d51: cpumask_weight (STB_LOCAL)
ffffffff810e6e00-ffffffff810e6e11: cpumask_weight (STB_LOCAL)
ffffffff810f5380-ffffffff810f5391: cpumask_weight (STB_LOCAL)
ffffffff810f8120-ffffffff810f8131: cpumask_weight (STB_LOCAL)
ffffffff810ff250-ffffffff810ff261: cpumask_weight (STB_LOCAL)
ffffffff81104320-ffffffff81104338: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81107be0-ffffffff81107bf1: cpumask_weight (STB_LOCAL)
ffffffff81bde8a9-ffffffff81bde8c1: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81be11c8-ffffffff81be11e0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811299b0-ffffffff811299c1: cpumask_weight (STB_LOCAL)
ffffffff8112bfd0-ffffffff8112bfe8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81151d70-ffffffff81151d81: cpumask_weight (STB_LOCAL)
ffffffff81154940-ffffffff81154958: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81be3daa-ffffffff81be3dc2: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8115afa0-ffffffff8115afb1: cpumask_weight (STB_LOCAL)
ffffffff81168910-ffffffff81168928: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8117a4a0-ffffffff8117a4b1: cpumask_weight (STB_LOCAL)
ffffffff81182a70-ffffffff81182a81: cpumask_weight (STB_LOCAL)
ffffffff81192400-ffffffff81192418: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8119a9c0-ffffffff8119a9d8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8119e5e0-ffffffff8119e5f8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8119fb40-ffffffff8119fb58: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811fb840-ffffffff811fb858: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812181b0-ffffffff812181c8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81219580-ffffffff81219598: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8121d160-ffffffff8121d178: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8121dc00-ffffffff8121dc18: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8121e410-ffffffff8121e428: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8121fd60-ffffffff8121fd78: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8122f890-ffffffff8122f8a8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812538f0-ffffffff81253901: cpumask_weight (STB_LOCAL)
ffffffff8127f0f0-ffffffff8127f101: cpumask_weight (STB_LOCAL)
ffffffff81282b00-ffffffff81282b18: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812841a0-ffffffff812841b8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81295fd0-ffffffff81295fe8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81be8a33-ffffffff81be8a4b: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812e3890-ffffffff812e38a8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81383060-ffffffff81383078: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff815ac830-ffffffff815ac848: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81731f40-ffffffff81731f58: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81c0d857-ffffffff81c0d86f: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81825050-ffffffff81825068: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81989620-ffffffff81989638: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8199c590-ffffffff8199c5a1: cpumask_weight (STB_LOCAL)
ffffffff8199d250-ffffffff8199d261: cpumask_weight (STB_LOCAL)
ffffffff81c29f72-ffffffff81c29f8a: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81c29f8a-ffffffff81c29fa2: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff819bb3c0-ffffffff819bb3d8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81a00c50-ffffffff81a00c68: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81a39bd0-ffffffff81a39be1: cpumask_weight (STB_LOCAL)
ffffffff81aad430-ffffffff81aad448: cpumask_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81bc40ce)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028240)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/xen/trace.c (ffffffff8102e810)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_multi
```
```
In arch/x86/xen/smp_pv.c (ffffffff81bc5092)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/xen/spinlock.c (ffffffff81bc50aa)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81bc524b)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff81031d30)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/kernel/alternative.c (ffffffff8103e6a0)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff810404c0)
Location: include/linux/cpumask.h:538
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff8104df10)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810582c0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e300)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106bf50)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:announce_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8106df40)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81bc8eda)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81bc990a)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81076c70)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff81bc9e0f)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In arch/x86/kernel/kvm.c (ffffffff81bc9ed9)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81bc9f51)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093b90)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ad60)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/workqueue.c (ffffffff810c3650)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_clamp_max_active
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffffffff81bce255)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/reboot.c (ffffffff810d4ff0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/reboot.c:cpu_store
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/sched/core.c (ffffffff810da6c0)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:init_idle
```
```
In kernel/sched/fair.c (ffffffff810e8eb0)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/rt.c (ffffffff810f7450)
Location: include/linux/cpumask.h:538
Inline: False
```
```
In kernel/sched/deadline.c (ffffffff810fa280)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/sched/topology.c (ffffffff811013e0)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:update_top_cache_domain
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81109d20)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/locking/qspinlock.c (ffffffff81bd0a4a)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/printk/printk.c (ffffffff81bd3249)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/irq/affinity.c (ffffffff81129c40)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In kernel/rcu/update.c (ffffffff8112c500)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_rude_wait_gp
```
```
In kernel/time/clockevents.c (ffffffff81153120)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (ffffffff81155dc0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff81bd5cc4)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/futex.c:futex_init
```
```
In kernel/kexec_file.c (ffffffff811696c0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cpuset.c (ffffffff8117b020)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/stop_machine.c (ffffffff81183bc0)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
```
In kernel/kprobes.c (ffffffff811932d0)
Location: include/linux/cpumask.h:538
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119b800)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_pid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119f2d0)
Location: include/linux/cpumask.h:538
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811a07a0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
```
In kernel/bpf/syscall.c (ffffffff811fc560)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
```
In kernel/bpf/map_iter.c (ffffffff8121b600)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/bpf/map_iter.c:bpf_iter_attach_map
```
```
In kernel/bpf/hashtab.c (ffffffff8121cf80)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:bpf_iter_init_hash_map
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
```
```
In kernel/bpf/arraymap.c (ffffffff81220c70)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/bpf/arraymap.c:bpf_iter_init_array_map
```
```
In kernel/bpf/percpu_freelist.c (ffffffff81221710)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81221e00)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffff812237f0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81224e30)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/padata.c (ffffffff81257f10)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_init
```
```
In mm/vmstat.c (ffffffff81284240)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (ffffffff81287c30)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff831f0466)
Location: include/linux/cpumask.h:538
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
Direct callers:
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_free_hook
  - mm/percpu.c:pcpu_memcg_free_hook
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/mmap_lock.c (ffffffff8129b8f0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - mm/mmap_lock.c:trace_mmap_lock_reg
```
```
In mm/hugetlb.c (ffffffff81bdaa4f)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/slub.c (ffffffff812eb040)
Location: include/linux/cpumask.h:538
Inline: True
```
```
In fs/aio.c (ffffffff8138a0d0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In lib/bucket_locks.c (ffffffff815b74a0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/xen/time.c (ffffffff81715a10)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81bffbc6)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/nvdimm/region.c (ffffffff818083e0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/dm-stats.c (ffffffff8196dd00)
Location: include/linux/cpumask.h:538
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81981260)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81981d90)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81c1c356)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81c1c36e)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8199fbd0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/powercap/dtpm_cpu.c (ffffffff819badc0)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_offline
  - drivers/powercap/dtpm_cpu.c:get_pd_power_uw
  - drivers/powercap/dtpm_cpu.c:set_pd_power_limit
```
```
In net/core/dev.c (ffffffff819e7420)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffffffff81a20f90)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a98510)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffff81bc40ce-ffffffff81bc40e6: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81028240-ffffffff81028258: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102e810-ffffffff8102e821: cpumask_weight (STB_LOCAL)
ffffffff81bc5092-ffffffff81bc50aa: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81bc50aa-ffffffff81bc50c2: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81bc524b-ffffffff81bc5263: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81031d30-ffffffff81031d41: cpumask_weight (STB_LOCAL)
ffffffff8103e6a0-ffffffff8103e6b1: cpumask_weight (STB_LOCAL)
ffffffff810404c0-ffffffff810404d8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8104df10-ffffffff8104df21: cpumask_weight (STB_LOCAL)
ffffffff810582c0-ffffffff810582d8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8105e300-ffffffff8105e311: cpumask_weight (STB_LOCAL)
ffffffff8106bf50-ffffffff8106bf61: cpumask_weight (STB_LOCAL)
ffffffff8106df40-ffffffff8106df51: cpumask_weight (STB_LOCAL)
ffffffff81bc8eda-ffffffff81bc8ef2: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81bc990a-ffffffff81bc9922: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81076c70-ffffffff81076c88: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81bc9e0f-ffffffff81bc9e27: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81bc9ed9-ffffffff81bc9ef1: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81bc9f51-ffffffff81bc9f69: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81093b90-ffffffff81093ba1: cpumask_weight (STB_LOCAL)
ffffffff8109ad60-ffffffff8109ad71: cpumask_weight (STB_LOCAL)
ffffffff810c3650-ffffffff810c3668: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81bce255-ffffffff81bce26d: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810d4ff0-ffffffff810d5008: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810da6c0-ffffffff810da6d1: cpumask_weight (STB_LOCAL)
ffffffff810e8eb0-ffffffff810e8ec1: cpumask_weight (STB_LOCAL)
ffffffff810f7450-ffffffff810f7461: cpumask_weight (STB_LOCAL)
ffffffff810fa280-ffffffff810fa291: cpumask_weight (STB_LOCAL)
ffffffff811013e0-ffffffff811013f1: cpumask_weight (STB_LOCAL)
ffffffff81109d20-ffffffff81109d31: cpumask_weight (STB_LOCAL)
ffffffff81bd0a4a-ffffffff81bd0a62: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81bd3249-ffffffff81bd3261: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81129c40-ffffffff81129c51: cpumask_weight (STB_LOCAL)
ffffffff8112c500-ffffffff8112c518: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81153120-ffffffff81153131: cpumask_weight (STB_LOCAL)
ffffffff81155dc0-ffffffff81155dd8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81bd5cc4-ffffffff81bd5cdc: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811696c0-ffffffff811696d8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8117b020-ffffffff8117b031: cpumask_weight (STB_LOCAL)
ffffffff81183bc0-ffffffff81183bd1: cpumask_weight (STB_LOCAL)
ffffffff811932d0-ffffffff811932e8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8119b800-ffffffff8119b818: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8119f2d0-ffffffff8119f2e8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811a07a0-ffffffff811a07b8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811fc560-ffffffff811fc578: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8121b600-ffffffff8121b618: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8121cf80-ffffffff8121cf98: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81220c70-ffffffff81220c88: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81221710-ffffffff81221728: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81221e00-ffffffff81221e18: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812237f0-ffffffff81223808: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81224e30-ffffffff81224e48: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81257f10-ffffffff81257f21: cpumask_weight (STB_LOCAL)
ffffffff81284240-ffffffff81284251: cpumask_weight (STB_LOCAL)
ffffffff81287c30-ffffffff81287c48: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81288de0-ffffffff81288df8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8129b8f0-ffffffff8129b908: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81bdaa4f-ffffffff81bdaa67: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812eb040-ffffffff812eb058: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8138a0d0-ffffffff8138a0e8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff815b74a0-ffffffff815b74b8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81715a10-ffffffff81715a28: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81bffbc6-ffffffff81bffbde: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818083e0-ffffffff818083f8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8196dd00-ffffffff8196dd18: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81981260-ffffffff81981271: cpumask_weight (STB_LOCAL)
ffffffff81981d90-ffffffff81981da1: cpumask_weight (STB_LOCAL)
ffffffff81c1c356-ffffffff81c1c36e: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81c1c36e-ffffffff81c1c386: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8199fbd0-ffffffff8199fbe8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff819badc0-ffffffff819badd1: cpumask_weight (STB_LOCAL)
ffffffff819e7420-ffffffff819e7438: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81a20f90-ffffffff81a20fa1: cpumask_weight (STB_LOCAL)
ffffffff81a98510-ffffffff81a98528: cpumask_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81c954a1)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102c8a0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/xen/trace.c (ffffffff81033080)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_multi
```
```
In arch/x86/xen/smp_pv.c (ffffffff81c97be1)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/xen/spinlock.c (ffffffff81c97bf9)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81c97da9)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff81036eb0)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81038a80)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/alternative.c (ffffffff81044410)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff81046330)
Location: include/linux/cpumask.h:538
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81055710)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81061190)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81067b00)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_ctrl_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:cpus_mon_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff81076b30)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:announce_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81079760)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c9d92e)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81c9e652)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81084450)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff81c9ed7c)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In arch/x86/kernel/kvm.c (ffffffff81c9f068)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:pv_ipi_supported
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81c9f1cc)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810a3790)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ab040)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/workqueue.c (ffffffff810d61f0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_clamp_max_active
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffffffff81ca54d8)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/reboot.c (ffffffff810e81c0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/reboot.c:cpu_store
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/sched/core.c (ffffffff810ee090)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:sched_core_cpu_starting
```
```
In kernel/sched/fair.c (ffffffff811005d0)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/rt.c (ffffffff811119c0)
Location: include/linux/cpumask.h:538
Inline: False
```
```
In kernel/sched/deadline.c (ffffffff811150f0)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/sched/topology.c (ffffffff8111d5e0)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:sd_init
  - kernel/sched/topology.c:get_group
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:update_top_cache_domain
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:sched_domain_debug_one
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff811280b0)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/locking/qspinlock.c (ffffffff81ca9641)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/printk/printk.c (ffffffff81cac187)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/irq/affinity.c (ffffffff8114a570)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In kernel/rcu/update.c (ffffffff8114d200)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_rude_wait_gp
```
```
In kernel/time/clocksource.c (ffffffff8116cb20)
Location: include/linux/cpumask.h:538
Inline: True
```
```
In kernel/time/clockevents.c (ffffffff811776f0)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (ffffffff8117aa50)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff81cb230e)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/futex.c:futex_init
```
```
In kernel/kexec_file.c (ffffffff8118f260)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cpuset.c (ffffffff811a2b90)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/stop_machine.c (ffffffff811abc20)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
```
In kernel/kprobes.c (ffffffff811bc180)
Location: include/linux/cpumask.h:538
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811c5760)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_pid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811c90e0)
Location: include/linux/cpumask.h:538
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811c9ec0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
```
In kernel/bpf/syscall.c (ffffffff8122de90)
Location: include/linux/cpumask.h:538
Inline: True
```
```
In kernel/bpf/map_iter.c (ffffffff81252500)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/bpf/map_iter.c:bpf_iter_attach_map
```
```
In kernel/bpf/hashtab.c (ffffffff81253f00)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:bpf_iter_init_hash_map
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
```
```
In kernel/bpf/arraymap.c (ffffffff81258630)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/bpf/arraymap.c:bpf_iter_init_array_map
```
```
In kernel/bpf/percpu_freelist.c (ffffffff81259110)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff812598e0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffff8125b620)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125cd70)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/padata.c (ffffffff81293a80)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_init
```
```
In mm/vmstat.c (ffffffff812c2a60)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (ffffffff812c73d0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff832d5d5f)
Location: include/linux/cpumask.h:538
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
Direct callers:
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_free_hook
  - mm/percpu.c:pcpu_memcg_free_hook
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/mmap_lock.c (ffffffff812dc3e0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - mm/mmap_lock.c:trace_mmap_lock_reg
```
```
In mm/page_alloc.c (ffffffff81301520)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
```
In mm/hugetlb.c (ffffffff81cbf20c)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/slub.c (ffffffff813330a0)
Location: include/linux/cpumask.h:538
Inline: True
```
```
In fs/aio.c (ffffffff813d73e0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In lib/bucket_locks.c (ffffffff8161dad0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/xen/time.c (ffffffff81792b20)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81d0213f)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/nvdimm/region.c (ffffffff81892bb0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/dm-stats.c (ffffffff81a16450)
Location: include/linux/cpumask.h:538
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81a2a4d0)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81a2b050)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81d2c8ea)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d2c993)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81a4c870)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/hv/hv_common.c (ffffffff81d32ec2)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - drivers/hv/hv_common.c:hv_common_init
  - drivers/hv/hv_common.c:hv_common_init
```
```
In drivers/powercap/dtpm_cpu.c (ffffffff81a69ec0)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - drivers/powercap/dtpm_cpu.c:cpuhp_dtpm_cpu_offline
  - drivers/powercap/dtpm_cpu.c:get_pd_power_uw
  - drivers/powercap/dtpm_cpu.c:set_pd_power_limit
```
```
In net/core/dev.c (ffffffff81a97e10)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffffffff81ad5410)
Location: include/linux/cpumask.h:538
Inline: False
Direct callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b539e0)
Location: include/linux/cpumask.h:538
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffff81c954a1-ffffffff81c954b9: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102c8a0-ffffffff8102c8b8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81033080-ffffffff81033091: cpumask_weight (STB_LOCAL)
ffffffff81c97be1-ffffffff81c97bf9: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81c97bf9-ffffffff81c97c11: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81c97da9-ffffffff81c97dc1: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81036eb0-ffffffff81036ec1: cpumask_weight (STB_LOCAL)
ffffffff81038a80-ffffffff81038a91: cpumask_weight (STB_LOCAL)
ffffffff81044410-ffffffff81044421: cpumask_weight (STB_LOCAL)
ffffffff81046330-ffffffff81046348: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81055710-ffffffff81055721: cpumask_weight (STB_LOCAL)
ffffffff81061190-ffffffff810611a8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81067b00-ffffffff81067b11: cpumask_weight (STB_LOCAL)
ffffffff81076b30-ffffffff81076b41: cpumask_weight (STB_LOCAL)
ffffffff81079760-ffffffff81079771: cpumask_weight (STB_LOCAL)
ffffffff81c9d92e-ffffffff81c9d946: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81c9e652-ffffffff81c9e66a: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81084450-ffffffff81084468: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81c9ed7c-ffffffff81c9ed94: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81c9f068-ffffffff81c9f080: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81c9f1cc-ffffffff81c9f1e4: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810a3790-ffffffff810a37a1: cpumask_weight (STB_LOCAL)
ffffffff810ab040-ffffffff810ab051: cpumask_weight (STB_LOCAL)
ffffffff810d61f0-ffffffff810d6208: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81ca54d8-ffffffff81ca54f0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810e81c0-ffffffff810e81d8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810ee090-ffffffff810ee0a1: cpumask_weight (STB_LOCAL)
ffffffff811005d0-ffffffff811005e1: cpumask_weight (STB_LOCAL)
ffffffff811119c0-ffffffff811119d1: cpumask_weight (STB_LOCAL)
ffffffff811150f0-ffffffff81115101: cpumask_weight (STB_LOCAL)
ffffffff8111d5e0-ffffffff8111d5f1: cpumask_weight (STB_LOCAL)
ffffffff811280b0-ffffffff811280c1: cpumask_weight (STB_LOCAL)
ffffffff81ca9641-ffffffff81ca9659: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81cac187-ffffffff81cac19f: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8114a570-ffffffff8114a581: cpumask_weight (STB_LOCAL)
ffffffff8114d200-ffffffff8114d218: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8116cb20-ffffffff8116cb38: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811776f0-ffffffff81177701: cpumask_weight (STB_LOCAL)
ffffffff8117aa50-ffffffff8117aa68: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81cb230e-ffffffff81cb2326: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8118f260-ffffffff8118f278: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811a2b90-ffffffff811a2ba1: cpumask_weight (STB_LOCAL)
ffffffff811abc20-ffffffff811abc31: cpumask_weight (STB_LOCAL)
ffffffff811bc180-ffffffff811bc198: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811c5760-ffffffff811c5778: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811c90e0-ffffffff811c90f8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811c9ec0-ffffffff811c9ed8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8122de90-ffffffff8122dea8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81252500-ffffffff81252518: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81253f00-ffffffff81253f18: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81258630-ffffffff81258648: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81259110-ffffffff81259128: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812598e0-ffffffff812598f8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8125b620-ffffffff8125b638: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8125cd70-ffffffff8125cd88: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81293a80-ffffffff81293a91: cpumask_weight (STB_LOCAL)
ffffffff812c2a60-ffffffff812c2a71: cpumask_weight (STB_LOCAL)
ffffffff812c73d0-ffffffff812c73e8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812c8880-ffffffff812c8898: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812dc3e0-ffffffff812dc3f8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81301520-ffffffff81301531: cpumask_weight (STB_LOCAL)
ffffffff81cbf20c-ffffffff81cbf224: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff813330a0-ffffffff813330b8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff813d73e0-ffffffff813d73f8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8161dad0-ffffffff8161dae8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81792b20-ffffffff81792b38: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81d0213f-ffffffff81d02157: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81892bb0-ffffffff81892bc8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81a16450-ffffffff81a16468: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81a2a4d0-ffffffff81a2a4e1: cpumask_weight (STB_LOCAL)
ffffffff81a2b050-ffffffff81a2b061: cpumask_weight (STB_LOCAL)
ffffffff81d2c8ea-ffffffff81d2c902: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81d2c993-ffffffff81d2c9ab: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81a4c870-ffffffff81a4c888: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81d32ec2-ffffffff81d32eda: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81a69ec0-ffffffff81a69ed1: cpumask_weight (STB_LOCAL)
ffffffff81a97e10-ffffffff81a97e28: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81ad5410-ffffffff81ad5421: cpumask_weight (STB_LOCAL)
ffffffff81b539e0-ffffffff81b539f8: cpumask_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81e4472d)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810318a0)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/xen/trace.c (ffffffff81039ba0)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_multi
```
```
In arch/x86/xen/smp_pv.c (ffffffff81e46fd7)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/xen/spinlock.c (ffffffff81e4700b)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81e471e2)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8103cf90)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103f700)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/alternative.c (ffffffff8104c700)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff8104efa0)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:unsynchronized_tsc
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81061710)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8106db40)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff810859d0)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:announce_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810884e0)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81e4cdee)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81e4dab2)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81094620)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff81e4e1c2)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In arch/x86/kernel/kvm.c (ffffffff81e4e7aa)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:pv_ipi_supported
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81e4e922)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c0a50)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/workqueue.c (ffffffff810efad0)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_clamp_max_active
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffffffff81e54dac)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/reboot.c (ffffffff81102600)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - kernel/reboot.c:cpu_store
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/sched/core.c (ffffffff8110a8f0)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:init_idle
  - kernel/sched/core.c:sched_core_cpu_starting
```
```
In kernel/sched/fair.c (ffffffff8111b7d0)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/build_policy.c (ffffffff8112e160)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:task_non_contending
```
```
In kernel/sched/build_utility.c (ffffffff8113cbb0)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:update_top_cache_domain
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:sugov_start
```
```
In kernel/locking/qspinlock.c (ffffffff81e59634)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/power/energy_model.c (ffffffff8115a2c0)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/printk/printk.c (ffffffff81e5c655)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/irq/affinity.c (ffffffff8116fb70)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In kernel/rcu/update.c (ffffffff81173e10)
Location: include/linux/cpumask.h:573
Inline: True
```
```
In kernel/time/clockevents.c (ffffffff811ac790)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (ffffffff811b0300)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex/core.c (ffffffff81e638ba)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - kernel/futex/core.c:futex_init
```
```
In kernel/kexec_file.c (ffffffff811be9d0)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cpuset.c (ffffffff811d38d0)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/stop_machine.c (ffffffff811dd3f0)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
```
In kernel/kprobes.c (ffffffff811ef9e0)
Location: include/linux/cpumask.h:573
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811f9500)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_pid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fcc00)
Location: include/linux/cpumask.h:573
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811fdaf0)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
```
In kernel/trace/fprobe.c (ffffffff812687c0)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - kernel/trace/fprobe.c:fprobe_init_rethook
```
```
In kernel/bpf/syscall.c (ffffffff8126ffa0)
Location: include/linux/cpumask.h:573
Inline: True
```
```
In kernel/bpf/map_iter.c (ffffffff8129a310)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - kernel/bpf/map_iter.c:bpf_iter_attach_map
```
```
In kernel/bpf/hashtab.c (ffffffff8129c4a0)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:bpf_iter_init_hash_map
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_free_timers
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
```
```
In kernel/bpf/arraymap.c (ffffffff812a1410)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - kernel/bpf/arraymap.c:bpf_iter_init_array_map
```
```
In kernel/bpf/percpu_freelist.c (ffffffff812a2030)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff812a28b0)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffff812a5020)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812a6e20)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/padata.c (ffffffff812e98b0)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_init
```
```
In mm/mm_init.c (ffffffff81324720)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff8348a5df)
Location: include/linux/cpumask.h:573
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
Direct callers:
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/mmap_lock.c (ffffffff8133c450)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - mm/mmap_lock.c:trace_mmap_lock_reg
```
```
In mm/page_alloc.c (ffffffff81368d60)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
```
In mm/hugetlb.c (ffffffff81e71517)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/slub.c (ffffffff813a48e0)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - mm/slub.c:calculate_sizes
```
```
In fs/aio.c (ffffffff81460fe0)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff81551a50)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_max_decompressors
```
```
In lib/bucket_locks.c (ffffffff816eb690)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/xen/time.c (ffffffff818cb410)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81eca606)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/nvdimm/region.c (ffffffff819dce70)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81b525b0)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
```
```
In drivers/md/dm-stats.c (ffffffff81b7f810)
Location: include/linux/cpumask.h:573
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81b947f0)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81b95490)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81ef8bf9)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81ef8cbf)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81bbb000)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/hv/hv_common.c (ffffffff81eff303)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - drivers/hv/hv_common.c:hv_common_init
  - drivers/hv/hv_common.c:hv_common_init
```
```
In net/core/dev.c (ffffffff81c0f5e0)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffffffff81c55780)
Location: include/linux/cpumask.h:573
Inline: False
Direct callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce1530)
Location: include/linux/cpumask.h:573
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffff81e4472d-ffffffff81e4474d: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810318a0-ffffffff810318c0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81039ba0-ffffffff81039bb9: cpumask_weight (STB_LOCAL)
ffffffff81e46fd7-ffffffff81e46ff7: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81e4700b-ffffffff81e4702b: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81e471e2-ffffffff81e47202: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8103cf90-ffffffff8103cfa9: cpumask_weight (STB_LOCAL)
ffffffff8103f700-ffffffff8103f719: cpumask_weight (STB_LOCAL)
ffffffff8104c700-ffffffff8104c719: cpumask_weight (STB_LOCAL)
ffffffff8104efa0-ffffffff8104efc0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81061710-ffffffff81061729: cpumask_weight (STB_LOCAL)
ffffffff8106db40-ffffffff8106db60: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810859d0-ffffffff810859e9: cpumask_weight (STB_LOCAL)
ffffffff810884e0-ffffffff810884f9: cpumask_weight (STB_LOCAL)
ffffffff81e4cdee-ffffffff81e4ce0e: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81e4dab2-ffffffff81e4dad2: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81094620-ffffffff81094640: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81e4e1c2-ffffffff81e4e1e2: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81e4e7aa-ffffffff81e4e7ca: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81e4e922-ffffffff81e4e942: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810c0a50-ffffffff810c0a69: cpumask_weight (STB_LOCAL)
ffffffff810efad0-ffffffff810efaf0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81e54dac-ffffffff81e54dcc: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81102600-ffffffff81102620: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8110a8f0-ffffffff8110a909: cpumask_weight (STB_LOCAL)
ffffffff8111b7d0-ffffffff8111b7e9: cpumask_weight (STB_LOCAL)
ffffffff8112e160-ffffffff8112e179: cpumask_weight (STB_LOCAL)
ffffffff8113cbb0-ffffffff8113cbc9: cpumask_weight (STB_LOCAL)
ffffffff81e59634-ffffffff81e59654: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8115a2c0-ffffffff8115a2d9: cpumask_weight (STB_LOCAL)
ffffffff81e5c655-ffffffff81e5c675: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8116fb70-ffffffff8116fb89: cpumask_weight (STB_LOCAL)
ffffffff81173e10-ffffffff81173e30: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811ac790-ffffffff811ac7a9: cpumask_weight (STB_LOCAL)
ffffffff811b0300-ffffffff811b0320: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81e638ba-ffffffff81e638da: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811be9d0-ffffffff811be9f0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811d38d0-ffffffff811d38e9: cpumask_weight (STB_LOCAL)
ffffffff811dd3f0-ffffffff811dd409: cpumask_weight (STB_LOCAL)
ffffffff811ef9e0-ffffffff811efa00: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811f9500-ffffffff811f9520: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811fcc00-ffffffff811fcc20: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811fdaf0-ffffffff811fdb10: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812687c0-ffffffff812687e0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8126ffa0-ffffffff8126ffc0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8129a310-ffffffff8129a330: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8129c4a0-ffffffff8129c4c0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812a1410-ffffffff812a1430: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812a2030-ffffffff812a2050: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812a28b0-ffffffff812a28d0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812a5020-ffffffff812a5040: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812a6e20-ffffffff812a6e40: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812e98b0-ffffffff812e98c9: cpumask_weight (STB_LOCAL)
ffffffff81324720-ffffffff81324740: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81326250-ffffffff81326270: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8133c450-ffffffff8133c470: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81368d60-ffffffff81368d79: cpumask_weight (STB_LOCAL)
ffffffff81e71517-ffffffff81e71537: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff813a48e0-ffffffff813a4900: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81460fe0-ffffffff81461000: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81551a50-ffffffff81551a70: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff816eb690-ffffffff816eb6b0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818cb410-ffffffff818cb430: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81eca606-ffffffff81eca626: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff819dce70-ffffffff819dce90: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81b525b0-ffffffff81b525c9: cpumask_weight (STB_LOCAL)
ffffffff81b7f810-ffffffff81b7f830: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81b947f0-ffffffff81b94809: cpumask_weight (STB_LOCAL)
ffffffff81b95490-ffffffff81b954a9: cpumask_weight (STB_LOCAL)
ffffffff81ef8bf9-ffffffff81ef8c19: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81ef8cbf-ffffffff81ef8cdf: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81bbb000-ffffffff81bbb020: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81eff303-ffffffff81eff323: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81c0f5e0-ffffffff81c0f600: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81c55780-ffffffff81c55799: cpumask_weight (STB_LOCAL)
ffffffff81ce1530-ffffffff81ce1550: cpumask_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100bfb0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81038ec0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/xen/trace.c (ffffffff81041ca0)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_multi
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043aa0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/xen/spinlock.c (ffffffff81044820)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81044d50)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff81045c80)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810488a0)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/alternative.c (ffffffff810589b0)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff8105bf50)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:unsynchronized_tsc
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81070160)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8107dde0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff81098ba0)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:announce_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109bfb0)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109d080)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a82f0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810a9fe0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff810b48a0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In arch/x86/kernel/kvm.c (ffffffff810b64d0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810b7c20)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dcc00)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/workqueue.c (ffffffff81111400)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_clamp_max_active
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffffffff811187e0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/reboot.c (ffffffff81127950)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/reboot.c:cpu_store
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/sched/core.c (ffffffff8112f5a0)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_starting
```
```
In kernel/sched/fair.c (ffffffff811432e0)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/build_policy.c (ffffffff81158070)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:task_non_contending
```
```
In kernel/sched/build_utility.c (ffffffff81167580)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:update_top_cache_domain
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:sugov_start
```
```
In kernel/locking/qspinlock.c (ffffffff8117e2c0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/power/energy_model.c (ffffffff8118c5f0)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/printk/printk.c (ffffffff8118ecf0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/irq/affinity.c (ffffffff811a5f90)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In kernel/rcu/update.c (ffffffff811a9e40)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_rude_wait_gp
```
```
In kernel/dma/swiotlb.c (ffffffff811c4170)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_remap
```
```
In kernel/time/clockevents.c (ffffffff811ecbd0)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (ffffffff811f0dc0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex/core.c (ffffffff811f3090)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/futex/core.c:futex_init
```
```
In kernel/kexec_file.c (ffffffff81200b20)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cpuset.c (ffffffff81217620)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/stop_machine.c (ffffffff81222e10)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
```
In kernel/kprobes.c (ffffffff81236420)
Location: include/linux/cpumask.h:638
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81240a10)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_pid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81244130)
Location: include/linux/cpumask.h:638
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81245300)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
```
In kernel/trace/fprobe.c (ffffffff812ba970)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/trace/fprobe.c:fprobe_init_rethook
```
```
In kernel/bpf/syscall.c (ffffffff812c5a20)
Location: include/linux/cpumask.h:638
Inline: True
```
```
In kernel/bpf/map_iter.c (ffffffff812f62f0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/bpf/map_iter.c:bpf_iter_attach_map
```
```
In kernel/bpf/hashtab.c (ffffffff812f8980)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:bpf_iter_init_hash_map
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
```
```
In kernel/bpf/arraymap.c (ffffffff812fe210)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/bpf/arraymap.c:bpf_iter_init_array_map
```
```
In kernel/bpf/percpu_freelist.c (ffffffff812ff740)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff813003a0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffff81302df0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81305760)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/padata.c (ffffffff813536b0)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_init
```
```
In mm/mm_init.c (ffffffff81399080)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mm_init.c:mm_compute_batch_notifier
```
```
In mm/percpu.c (ffffffff83ebb287)
Location: include/linux/cpumask.h:638
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
Direct callers:
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/mmap_lock.c (ffffffff813b3fb0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - mm/mmap_lock.c:trace_mmap_lock_reg
```
```
In mm/page_alloc.c (ffffffff813e4d00)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
```
In mm/hugetlb.c (ffffffff81406900)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/slub.c (ffffffff81424c90)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - mm/slub.c:calculate_sizes
```
```
In fs/aio.c (ffffffff814f0f60)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff815f2f20)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_max_decompressors
```
```
In lib/bucket_locks.c (ffffffff817dbdc0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/xen/time.c (ffffffff81a1c6f0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/char/random.c (ffffffff81a92aa0)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81ad9780)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/nvdimm/region.c (ffffffff81b585a0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81cea7b0)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
```
```
In drivers/md/dm-stats.c (ffffffff81d1d100)
Location: include/linux/cpumask.h:638
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d34b30)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d35d50)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81d3b400)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3d2a0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81d60680)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/hv/hv_common.c (ffffffff81d7d140)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - drivers/hv/hv_common.c:hv_common_init
  - drivers/hv/hv_common.c:hv_common_init
```
```
In net/core/dev.c (ffffffff81dbf3e0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffffffff81e0b230)
Location: include/linux/cpumask.h:638
Inline: False
Direct callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea25d0)
Location: include/linux/cpumask.h:638
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffff8100bfb0-ffffffff8100bfd0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81038ec0-ffffffff81038ee0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81041ca0-ffffffff81041cb9: cpumask_weight (STB_LOCAL)
ffffffff81043aa0-ffffffff81043ac0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81044820-ffffffff81044840: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81044d50-ffffffff81044d70: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81045c80-ffffffff81045c99: cpumask_weight (STB_LOCAL)
ffffffff810488a0-ffffffff810488b9: cpumask_weight (STB_LOCAL)
ffffffff810589b0-ffffffff810589c9: cpumask_weight (STB_LOCAL)
ffffffff8105bf50-ffffffff8105bf70: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81070160-ffffffff81070179: cpumask_weight (STB_LOCAL)
ffffffff8107dde0-ffffffff8107de00: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81098ba0-ffffffff81098bb9: cpumask_weight (STB_LOCAL)
ffffffff8109bfb0-ffffffff8109bfc9: cpumask_weight (STB_LOCAL)
ffffffff8109d080-ffffffff8109d0a0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810a82f0-ffffffff810a8310: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810a9fe0-ffffffff810aa000: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810b48a0-ffffffff810b48c0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810b64d0-ffffffff810b64f0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810b7c20-ffffffff810b7c40: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810dcc00-ffffffff810dcc19: cpumask_weight (STB_LOCAL)
ffffffff81111400-ffffffff81111420: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811187e0-ffffffff81118800: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81127950-ffffffff81127970: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8112f5a0-ffffffff8112f5b9: cpumask_weight (STB_LOCAL)
ffffffff811432e0-ffffffff811432f9: cpumask_weight (STB_LOCAL)
ffffffff81158070-ffffffff81158089: cpumask_weight (STB_LOCAL)
ffffffff81167580-ffffffff81167599: cpumask_weight (STB_LOCAL)
ffffffff8117e2c0-ffffffff8117e2e0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8118c5f0-ffffffff8118c609: cpumask_weight (STB_LOCAL)
ffffffff8118ecf0-ffffffff8118ed10: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811a5f90-ffffffff811a5fa9: cpumask_weight (STB_LOCAL)
ffffffff811a9e40-ffffffff811a9e60: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811c4170-ffffffff811c4190: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811ecbd0-ffffffff811ecbe9: cpumask_weight (STB_LOCAL)
ffffffff811f0dc0-ffffffff811f0de0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811f3090-ffffffff811f30b0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81200b20-ffffffff81200b40: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81217620-ffffffff81217639: cpumask_weight (STB_LOCAL)
ffffffff81222e10-ffffffff81222e29: cpumask_weight (STB_LOCAL)
ffffffff81236420-ffffffff81236440: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81240a10-ffffffff81240a30: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81244130-ffffffff81244150: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81245300-ffffffff81245320: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812ba970-ffffffff812ba990: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812c5a20-ffffffff812c5a40: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812f62f0-ffffffff812f6310: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812f8980-ffffffff812f89a0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812fe210-ffffffff812fe230: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812ff740-ffffffff812ff760: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff813003a0-ffffffff813003c0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81302df0-ffffffff81302e10: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81305760-ffffffff81305780: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff813536b0-ffffffff813536c9: cpumask_weight (STB_LOCAL)
ffffffff81399080-ffffffff813990a0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8139aff0-ffffffff8139b010: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff813b3fb0-ffffffff813b3fd0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff813e4d00-ffffffff813e4d19: cpumask_weight (STB_LOCAL)
ffffffff81406900-ffffffff81406920: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81424c90-ffffffff81424cb0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff814f0f60-ffffffff814f0f80: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff815f2f20-ffffffff815f2f40: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff817dbdc0-ffffffff817dbde0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81a1c6f0-ffffffff81a1c710: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81a92aa0-ffffffff81a92ab9: cpumask_weight (STB_LOCAL)
ffffffff81ad9780-ffffffff81ad97a0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81b585a0-ffffffff81b585c0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81cea7b0-ffffffff81cea7c9: cpumask_weight (STB_LOCAL)
ffffffff81d1d100-ffffffff81d1d120: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81d34b30-ffffffff81d34b49: cpumask_weight (STB_LOCAL)
ffffffff81d35d50-ffffffff81d35d69: cpumask_weight (STB_LOCAL)
ffffffff81d3b400-ffffffff81d3b420: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81d3d2a0-ffffffff81d3d2c0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81d60680-ffffffff81d606a0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81d7d140-ffffffff81d7d160: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81dbf3e0-ffffffff81dbf400: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81e0b230-ffffffff81e0b249: cpumask_weight (STB_LOCAL)
ffffffff81ea25d0-ffffffff81ea25f0: cpumask_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100b750)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81038df0)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/xen/trace.c (ffffffff81041de0)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_multi
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043bc0)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/xen/spinlock.c (ffffffff81044960)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81044e90)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff81045e30)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048b50)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/alternative.c (ffffffff81059a70)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff8105d700)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:unsynchronized_tsc
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81071d70)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810801c0)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109be70)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:announce_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff8109ef10)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a0020)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810ab560)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810ad3a0)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff810b7970)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In arch/x86/kernel/kvm.c (ffffffff810b95d0)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810bae10)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e81e0)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/workqueue.c (ffffffff8111d7e0)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_clamp_max_active
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffffffff81125a20)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/reboot.c (ffffffff81134df0)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/reboot.c:cpu_store
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/sched/core.c (ffffffff8113d020)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - kernel/sched/core.c:task_mm_cid_work
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_starting
```
```
In kernel/sched/fair.c (ffffffff811532c0)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/build_policy.c (ffffffff81168170)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:task_non_contending
```
```
In kernel/sched/build_utility.c (ffffffff81177a70)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:update_top_cache_domain
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:sugov_start
```
```
In kernel/locking/qspinlock.c (ffffffff8118ef60)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/power/energy_model.c (ffffffff8119dd10)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/printk/printk.c (ffffffff811a0460)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/irq/affinity.c (ffffffff811b8300)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
```
```
In kernel/rcu/update.c (ffffffff811bbd30)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_rude_wait_gp
```
```
In kernel/dma/swiotlb.c (ffffffff811d6d10)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_remap
```
```
In kernel/time/clockevents.c (ffffffff81201300)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (ffffffff812057f0)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex/core.c (ffffffff81207810)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/futex/core.c:futex_init
```
```
In kernel/kexec_file.c (ffffffff81215f30)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cpuset.c (ffffffff8122cf50)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/stop_machine.c (ffffffff812394e0)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
```
In kernel/kprobes.c (ffffffff8124d240)
Location: include/linux/cpumask.h:690
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81257aa0)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_pid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8125b210)
Location: include/linux/cpumask.h:690
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8125c390)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
```
In kernel/trace/fprobe.c (ffffffff812de2a0)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/trace/fprobe.c:fprobe_init_rethook
```
```
In kernel/bpf/syscall.c (ffffffff812ecb30)
Location: include/linux/cpumask.h:690
Inline: True
```
```
In kernel/bpf/map_iter.c (ffffffff813241a0)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/bpf/map_iter.c:bpf_iter_attach_map
```
```
In kernel/bpf/hashtab.c (ffffffff813269b0)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_mem_usage
  - kernel/bpf/hashtab.c:htab_map_mem_usage
  - kernel/bpf/hashtab.c:htab_map_mem_usage
  - kernel/bpf/hashtab.c:htab_map_mem_usage
  - kernel/bpf/hashtab.c:htab_map_mem_usage
  - kernel/bpf/hashtab.c:bpf_iter_init_hash_map
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
```
```
In kernel/bpf/arraymap.c (ffffffff8132ce20)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/bpf/arraymap.c:array_map_mem_usage
  - kernel/bpf/arraymap.c:bpf_iter_init_array_map
```
```
In kernel/bpf/percpu_freelist.c (ffffffff8132e2a0)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff8132ef00)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffff81331890)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813340c0)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/padata.c (ffffffff813848b0)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_init
```
```
In mm/mm_init.c (ffffffff813cbfe0)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mm_init.c:mm_compute_batch_notifier
```
```
In mm/percpu.c (ffffffff836e38d2)
Location: include/linux/cpumask.h:690
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
Direct callers:
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/mmap_lock.c (ffffffff813e8920)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - mm/mmap_lock.c:trace_mmap_lock_reg
```
```
In mm/vmalloc.c (ffffffff81410b50)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - mm/vmalloc.c:vmap_ram_vread_iter
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:free_vmap_block
```
```
In mm/page_alloc.c (ffffffff81419840)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
```
In mm/hugetlb.c (ffffffff81439f50)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/slub.c (ffffffff81459f30)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - mm/slub.c:calculate_sizes
```
```
In fs/aio.c (ffffffff815282c0)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff8162b010)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_max_decompressors
```
```
In lib/bucket_locks.c (ffffffff8181b180)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/group_cpus.c (ffffffff818e69d0)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:alloc_nodes_groups
```
```
In drivers/xen/time.c (ffffffff81a658b0)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/char/random.c (ffffffff81ade320)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81b27900)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/nvdimm/region.c (ffffffff81babb10)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81d533c0)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
```
```
In drivers/md/dm-stats.c (ffffffff81d862f0)
Location: include/linux/cpumask.h:690
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d9dea0)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d9f0c0)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81da5f00)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81da7e30)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81dcb740)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/hv/hv_common.c (ffffffff81deb530)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - drivers/hv/hv_common.c:hv_common_init
  - drivers/hv/hv_common.c:hv_common_init
```
```
In net/core/dev.c (ffffffff81e2f090)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffffffff81e7e5e0)
Location: include/linux/cpumask.h:690
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f00df0)
Location: include/linux/cpumask.h:690
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffff8100b750-ffffffff8100b770: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81038df0-ffffffff81038e10: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81041de0-ffffffff81041df9: cpumask_weight (STB_LOCAL)
ffffffff81043bc0-ffffffff81043be0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81044960-ffffffff81044980: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81044e90-ffffffff81044eb0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81045e30-ffffffff81045e49: cpumask_weight (STB_LOCAL)
ffffffff81048b50-ffffffff81048b69: cpumask_weight (STB_LOCAL)
ffffffff81059a70-ffffffff81059a89: cpumask_weight (STB_LOCAL)
ffffffff8105d700-ffffffff8105d720: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81071d70-ffffffff81071d89: cpumask_weight (STB_LOCAL)
ffffffff810801c0-ffffffff810801e0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8109be70-ffffffff8109be89: cpumask_weight (STB_LOCAL)
ffffffff8109ef10-ffffffff8109ef29: cpumask_weight (STB_LOCAL)
ffffffff810a0020-ffffffff810a0040: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810ab560-ffffffff810ab580: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810ad3a0-ffffffff810ad3c0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810b7970-ffffffff810b7990: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810b95d0-ffffffff810b95f0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810bae10-ffffffff810bae30: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810e81e0-ffffffff810e81f9: cpumask_weight (STB_LOCAL)
ffffffff8111d7e0-ffffffff8111d800: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81125a20-ffffffff81125a40: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81134df0-ffffffff81134e10: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8113d020-ffffffff8113d039: cpumask_weight (STB_LOCAL)
ffffffff811532c0-ffffffff811532d9: cpumask_weight (STB_LOCAL)
ffffffff81168170-ffffffff81168189: cpumask_weight (STB_LOCAL)
ffffffff81177a70-ffffffff81177a89: cpumask_weight (STB_LOCAL)
ffffffff8118ef60-ffffffff8118ef80: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8119dd10-ffffffff8119dd29: cpumask_weight (STB_LOCAL)
ffffffff811a0460-ffffffff811a0480: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811b8300-ffffffff811b8320: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811bbd30-ffffffff811bbd50: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811d6d10-ffffffff811d6d30: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81201300-ffffffff81201319: cpumask_weight (STB_LOCAL)
ffffffff812057f0-ffffffff81205810: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81207810-ffffffff81207830: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81215f30-ffffffff81215f50: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8122cf50-ffffffff8122cf69: cpumask_weight (STB_LOCAL)
ffffffff812394e0-ffffffff812394f9: cpumask_weight (STB_LOCAL)
ffffffff8124d240-ffffffff8124d260: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81257aa0-ffffffff81257ac0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8125b210-ffffffff8125b230: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8125c390-ffffffff8125c3b0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812de2a0-ffffffff812de2c0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812ecb30-ffffffff812ecb50: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff813241a0-ffffffff813241c0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff813269b0-ffffffff813269d0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8132ce20-ffffffff8132ce40: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8132e2a0-ffffffff8132e2c0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8132ef00-ffffffff8132ef20: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81331890-ffffffff813318b0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff813340c0-ffffffff813340e0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff813848b0-ffffffff813848c9: cpumask_weight (STB_LOCAL)
ffffffff813cbfe0-ffffffff813cc000: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff813ce0b0-ffffffff813ce0d0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff813e8920-ffffffff813e8940: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81410b50-ffffffff81410b70: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81419840-ffffffff81419859: cpumask_weight (STB_LOCAL)
ffffffff81439f50-ffffffff81439f70: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81459f30-ffffffff81459f50: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff815282c0-ffffffff815282e0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8162b010-ffffffff8162b030: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8181b180-ffffffff8181b1a0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818e69d0-ffffffff818e69e9: cpumask_weight (STB_LOCAL)
ffffffff81a658b0-ffffffff81a658d0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81ade320-ffffffff81ade339: cpumask_weight (STB_LOCAL)
ffffffff81b27900-ffffffff81b27920: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81babb10-ffffffff81babb30: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81d533c0-ffffffff81d533d9: cpumask_weight (STB_LOCAL)
ffffffff81d862f0-ffffffff81d86310: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81d9dea0-ffffffff81d9deb9: cpumask_weight (STB_LOCAL)
ffffffff81d9f0c0-ffffffff81d9f0d9: cpumask_weight (STB_LOCAL)
ffffffff81da5f00-ffffffff81da5f20: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81da7e30-ffffffff81da7e50: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81dcb740-ffffffff81dcb760: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81deb530-ffffffff81deb550: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81e2f090-ffffffff81e2f0b0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81e7e5e0-ffffffff81e7e5f9: cpumask_weight (STB_LOCAL)
ffffffff81f00df0-ffffffff81f00e10: cpumask_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81010ed0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103f2a0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
```
```
In arch/x86/xen/trace.c (ffffffff810482b0)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_multi
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_multi
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104a0c0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/xen/spinlock.c (ffffffff8104ae90)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8104b4f0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8104c500)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_multi
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8104fbd0)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/alternative.c (ffffffff81060be0)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff810647c0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:unsynchronized_tsc
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81079590)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81087cd0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a3470)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:announce_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a6390)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a7690)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810b23d0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810b3f20)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff810bedb0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In arch/x86/kernel/kvm.c (ffffffff810c09f0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_apic_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:pv_tlb_flush_supported
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810c2250)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f0370)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/pid.c (ffffffff81130020)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/reboot.c (ffffffff8113fde0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/reboot.c:cpu_store
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/sched/core.c (ffffffff81148190)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - kernel/sched/core.c:task_mm_cid_work
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_starting
```
```
In kernel/sched/fair.c (ffffffff8115eda0)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/build_policy.c (ffffffff81174f40)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:dl_add_task_root_domain
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:dl_task_offline_migration
  - kernel/sched/build_policy.c:task_non_contending
```
```
In kernel/sched/build_utility.c (ffffffff81185790)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sd_init
  - kernel/sched/build_utility.c:init_sched_groups_capacity
  - kernel/sched/build_utility.c:get_group
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:update_top_cache_domain
  - kernel/sched/build_utility.c:sugov_start
```
```
In kernel/locking/qspinlock.c (ffffffff8119d910)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/power/energy_model.c (ffffffff811ace80)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/printk/printk.c (ffffffff811af480)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/irq/affinity.c (ffffffff811c81c0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
```
```
In kernel/rcu/update.c (ffffffff811cc1d0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_rude_wait_gp
```
```
In kernel/dma/swiotlb.c (ffffffff811ebec0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_remap
```
```
In kernel/time/clockevents.c (ffffffff812177a0)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (ffffffff8121bcb0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex/core.c (ffffffff8121ea20)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/futex/core.c:futex_init
```
```
In kernel/crash_core.c (ffffffff8122a4e0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/crash_core.c:crash_prepare_elf64_headers
```
```
In kernel/stop_machine.c (ffffffff812531b0)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
```
In kernel/kprobes.c (ffffffff81267140)
Location: include/linux/cpumask.h:704
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81271990)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_pid
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff812750e0)
Location: include/linux/cpumask.h:704
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff812762d0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
```
```
In kernel/trace/trace_events_filter.c (ffffffff812c6480)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/fprobe.c (ffffffff812fc460)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/trace/fprobe.c:fprobe_init_rethook
```
```
In kernel/bpf/syscall.c (ffffffff8130b2e0)
Location: include/linux/cpumask.h:704
Inline: True
```
```
In kernel/bpf/map_iter.c (ffffffff81348170)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/bpf/map_iter.c:bpf_iter_attach_map
```
```
In kernel/bpf/hashtab.c (ffffffff8134b000)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_mem_usage
  - kernel/bpf/hashtab.c:htab_map_mem_usage
  - kernel/bpf/hashtab.c:htab_map_mem_usage
  - kernel/bpf/hashtab.c:htab_map_mem_usage
  - kernel/bpf/hashtab.c:htab_map_mem_usage
  - kernel/bpf/hashtab.c:bpf_iter_init_hash_map
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
```
```
In kernel/bpf/arraymap.c (ffffffff81351180)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/bpf/arraymap.c:array_map_mem_usage
  - kernel/bpf/arraymap.c:bpf_iter_init_array_map
```
```
In kernel/bpf/percpu_freelist.c (ffffffff813527c0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff81353420)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffff81355e30)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813587b0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
```
```
In kernel/bpf/cpumask.c (ffffffff81386260)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_weight
```
```
In kernel/padata.c (ffffffff813adcc0)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_init
```
```
In mm/mm_init.c (ffffffff813f6950)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - mm/mm_init.c:mm_compute_batch_init
  - mm/mm_init.c:mm_compute_batch_notifier
```
```
In mm/percpu.c (ffffffff83916162)
Location: include/linux/cpumask.h:704
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
Direct callers:
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/mmap_lock.c (ffffffff81413590)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - mm/mmap_lock.c:trace_mmap_lock_reg
```
```
In mm/vmalloc.c (ffffffff8143d4b0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - mm/vmalloc.c:vmap_ram_vread_iter
  - mm/vmalloc.c:vb_free
  - mm/vmalloc.c:free_vmap_block
```
```
In mm/page_alloc.c (ffffffff81446580)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
```
In mm/slub.c (ffffffff81455000)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - mm/slub.c:calculate_sizes
```
```
In mm/hugetlb.c (ffffffff814739c0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/aio.c (ffffffff8155d340)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff816643e0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_max_decompressors
```
```
In lib/bucket_locks.c (ffffffff818604c0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/group_cpus.c (ffffffff8192d9f0)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:alloc_nodes_groups
```
```
In drivers/xen/time.c (ffffffff81ab8110)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/char/random.c (ffffffff81b31740)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81b7e7c0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/base/cacheinfo.c (ffffffff81b9d000)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - drivers/base/cacheinfo.c:update_per_cpu_data_slice_size
```
```
In drivers/nvdimm/region.c (ffffffff81bffe50)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81e0a100)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_offline
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_online
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
```
```
In drivers/md/dm-stats.c (ffffffff81e3da30)
Location: include/linux/cpumask.h:704
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81e55c20)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e56ed0)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81e5df90)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e5fb60)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81e84280)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/hv/hv_common.c (ffffffff81ea16d0)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - drivers/hv/hv_common.c:hv_common_init
  - drivers/hv/hv_common.c:hv_common_init
```
```
In net/core/dev.c (ffffffff81eedd10)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffffffff81f3f4f0)
Location: include/linux/cpumask.h:704
Inline: False
Direct callers:
  - net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc5150)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204cb90)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - net/ipv4/tcp_sigpool.c:sigpool_reserve_scratch
```
```
In lib/objpool.c (ffffffff82191840)
Location: include/linux/cpumask.h:704
Inline: True
Direct callers:
  - lib/objpool.c:objpool_pop
  - lib/objpool.c:objpool_init_percpu_slots
  - lib/objpool.c:objpool_init_percpu_slots
```
**Symbols:**

```
ffffffff81010ed0-ffffffff81010ef0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8103f2a0-ffffffff8103f2c0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810482b0-ffffffff810482c9: cpumask_weight (STB_LOCAL)
ffffffff8104a0c0-ffffffff8104a0e0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8104ae90-ffffffff8104aeb0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8104b4f0-ffffffff8104b510: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8104c500-ffffffff8104c519: cpumask_weight (STB_LOCAL)
ffffffff8104fbd0-ffffffff8104fbe9: cpumask_weight (STB_LOCAL)
ffffffff81060be0-ffffffff81060bf9: cpumask_weight (STB_LOCAL)
ffffffff810647c0-ffffffff810647e0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81079590-ffffffff810795a9: cpumask_weight (STB_LOCAL)
ffffffff81087cd0-ffffffff81087cf0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810a3470-ffffffff810a3489: cpumask_weight (STB_LOCAL)
ffffffff810a6390-ffffffff810a63a9: cpumask_weight (STB_LOCAL)
ffffffff810a7690-ffffffff810a76b0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810b23d0-ffffffff810b23f0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810b3f20-ffffffff810b3f40: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810bedb0-ffffffff810bedd0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810c09f0-ffffffff810c0a10: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810c2250-ffffffff810c2270: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810f0370-ffffffff810f0389: cpumask_weight (STB_LOCAL)
ffffffff81130020-ffffffff81130040: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8113fde0-ffffffff8113fe00: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81148190-ffffffff811481a9: cpumask_weight (STB_LOCAL)
ffffffff8115eda0-ffffffff8115edb9: cpumask_weight (STB_LOCAL)
ffffffff81174f40-ffffffff81174f59: cpumask_weight (STB_LOCAL)
ffffffff81185790-ffffffff811857a9: cpumask_weight (STB_LOCAL)
ffffffff8119d910-ffffffff8119d930: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811ace80-ffffffff811ace99: cpumask_weight (STB_LOCAL)
ffffffff811af480-ffffffff811af4a0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811c81c0-ffffffff811c81e0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811cc1d0-ffffffff811cc1f0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811ebec0-ffffffff811ebee0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812177a0-ffffffff812177b9: cpumask_weight (STB_LOCAL)
ffffffff8121bcb0-ffffffff8121bcd0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8121ea20-ffffffff8121ea40: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8122a4e0-ffffffff8122a500: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812531b0-ffffffff812531c9: cpumask_weight (STB_LOCAL)
ffffffff81267140-ffffffff81267160: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81271990-ffffffff812719b0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812750e0-ffffffff81275100: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812762d0-ffffffff812762f0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812c6480-ffffffff812c6499: cpumask_weight (STB_LOCAL)
ffffffff812fc460-ffffffff812fc480: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8130b2e0-ffffffff8130b300: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81348170-ffffffff81348190: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8134b000-ffffffff8134b020: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81351180-ffffffff813511a0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff813527c0-ffffffff813527e0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81353420-ffffffff81353440: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81355e30-ffffffff81355e50: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff813587b0-ffffffff813587d0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81386260-ffffffff81386279: cpumask_weight (STB_LOCAL)
ffffffff813adcc0-ffffffff813adcd9: cpumask_weight (STB_LOCAL)
ffffffff813f6950-ffffffff813f6970: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff813f8a20-ffffffff813f8a40: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81413590-ffffffff814135b0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8143d4b0-ffffffff8143d4d0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81446580-ffffffff81446599: cpumask_weight (STB_LOCAL)
ffffffff81455000-ffffffff81455020: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff814739c0-ffffffff814739e0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8155d340-ffffffff8155d360: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff816643e0-ffffffff81664400: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818604c0-ffffffff818604e0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8192d9f0-ffffffff8192da09: cpumask_weight (STB_LOCAL)
ffffffff81ab8110-ffffffff81ab8130: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81b31740-ffffffff81b31759: cpumask_weight (STB_LOCAL)
ffffffff81b7e7c0-ffffffff81b7e7e0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81b9d000-ffffffff81b9d019: cpumask_weight (STB_LOCAL)
ffffffff81bffe50-ffffffff81bffe70: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81e0a100-ffffffff81e0a119: cpumask_weight (STB_LOCAL)
ffffffff81e3da30-ffffffff81e3da50: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81e55c20-ffffffff81e55c39: cpumask_weight (STB_LOCAL)
ffffffff81e56ed0-ffffffff81e56ee9: cpumask_weight (STB_LOCAL)
ffffffff81e5df90-ffffffff81e5dfb0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81e5fb60-ffffffff81e5fb80: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81e84280-ffffffff81e842a0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81ea16d0-ffffffff81ea16f0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81eedd10-ffffffff81eedd30: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81f3f4f0-ffffffff81f3f509: cpumask_weight (STB_LOCAL)
ffffffff81fc5150-ffffffff81fc5170: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8204cb90-ffffffff8204cbb0: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff82191840-ffffffff82191860: cpumask_weight.constprop.0 (STB_LOCAL)
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
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:setup_arch
```
```
In arch/arm64/kernel/smp.c (ffff80001009d4b0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:cpus_are_stuck_in_kernel
```
```
In arch/arm64/mm/context.c (ffff8000100af910)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:asids_init
```
```
In kernel/workqueue.c (ffff80001011bc38)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffff800011443640)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/sched/core.c (ffff80001013d3e8)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/rt.c (ffff80001014f4f0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/sched/deadline.c (ffff8000101577e8)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (ffff80001015bd18)
Location: include/linux/cpumask.h:554
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
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffff800010164f10)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/printk/printk.c (ffff8000114460d4)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/irq/affinity.c (ffff8000101884f4)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/clockevents.c (ffff8000101b145c)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (ffff8000101b5c70)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffff8000114494c0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffff8000101bd368)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/kexec_file.c (ffff8000101cb4f0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cpuset.c (ffff8000101e3cf0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/stop_machine.c (ffff8000101e8cf8)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffff8000101f9428)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffff800010202cac)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffff8000102047d8)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffff800010205990)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/bpf/syscall.c (ffff800010263680)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffff8000102779d4)
Location: include/linux/cpumask.h:554
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
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffff80001027bf40)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffff80001027d148)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffff80001027e770)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/devmap.c (ffff800010286900)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/cpumap.c (ffff800010287d18)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/xskmap.c (ffff800010288e14)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/padata.c (ffff8000102aa108)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmstat.c (ffff800011453490)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (ffff800010d9f920)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffff8000102e40dc)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_embed_first_chunk
```
```
In mm/hugetlb.c (ffff800011459d70)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/aio.c (ffff8000103fea8c)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In lib/bucket_locks.c (ffff8000106382c8)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/irqchip/irq-gic.c (ffff80001066bef4)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff8000106771e4)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b574)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff8000107258e0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff80001072606c)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
```
```
In drivers/dma/mv_xor.c (ffff800010808064)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/soc/fsl/qbman/qman.c (ffff800010817370)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_enable_irqs
```
```
In drivers/xen/time.c (ffff80001082fa54)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/base/arch_topology.c (ffff80001149801c)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:topology_parse_cpu_capacity
```
```
In drivers/nvdimm/region.c (ffff800010957f78)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/thermal/thermal_core.c (ffff800010ad4200)
Location: include/linux/cpumask.h:554
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
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/cpu_cooling.c:cpufreq_state2power
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
```
```
In drivers/md/dm-stats.c (ffff800010b0d188)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffff800010b255ac)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffff800010b4b214)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/perf/arm_pmu.c (ffff800010b95488)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_request_irq
```
```
In net/core/dev.c (ffff800010bca830)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffff800010c09ff4)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/bpf_sk_storage.c (ffff800010c31008)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffff800010c69898)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm/kernel/setup.c (c1504e00)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_arch
```
```
In arch/arm/kernel/smp.c (c1505ca8)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:smp_prepare_cpus
```
```
In arch/arm/kernel/machine_kexec.c (c03151cc)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/arm/kernel/machine_kexec.c:machine_kexec_prepare
```
```
In arch/arm/mach-exynos/exynos.c (c032cbf4)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/arm/mach-exynos/exynos.c:exynos_set_delayed_reset_assertion
```
```
In arch/arm/mach-mvebu/platsmp.c (c150e588)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_smp_init_cpus
```
```
In kernel/workqueue.c (c0371710)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (c0377d94)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/sched/core.c (c038d180)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/rt.c (c039b8d4)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/sched/deadline.c (c03a55ac)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (c03a873c)
Location: include/linux/cpumask.h:554
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
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (c03b1560)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/printk/printk.c (c03c85a4)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/irq/affinity.c (c03d6e50)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/clockevents.c (c03fbe80)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (c03ffc6c)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (c1523684)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (c0405524)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (c04248c0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/stop_machine.c (c0428d78)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (c04396d4)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (c0441cd4)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (c04434c0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (c0444670)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/bpf/syscall.c (c0493c74)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (c04aaab8)
Location: include/linux/cpumask.h:554
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
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (c04adce8)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (c04aeb18)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (c04b0180)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/devmap.c (c04b6f8c)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/cpumap.c (c04b7af0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/xskmap.c (c04b8d00)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/padata.c (c04d81d0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmstat.c (c0501f08)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
Direct callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/mm_init.c (c152e4a0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch_init
```
```
In mm/percpu.c (c0508180)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In fs/aio.c (c05d096c)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
```
```
In lib/bucket_locks.c (c07ddc10)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/irqchip/irq-gic.c (c08152bc)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_get_cpumask
```
```
In drivers/dma/mv_xor.c (c0925318)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/soc/tegra/flowctrl.c (c093ad48)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/soc/tegra/flowctrl.c:flowctrl_cpu_suspend_enter
```
```
In drivers/base/arch_topology.c (c1598d24)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:topology_parse_cpu_capacity
```
```
In drivers/thermal/thermal_core.c (c0bb57ec)
Location: include/linux/cpumask.h:554
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
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/cpu_cooling.c:cpufreq_state2power
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
```
```
In drivers/md/dm-stats.c (c0beb2d8)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (c0bff58c)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpuidle/coupled.c (c0c05088)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:coupled_cpu_online
  - drivers/cpuidle/coupled.c:cpuidle_coupled_register_device
```
```
In drivers/leds/trigger/ledtrig-cpu.c (c0c344e4)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/perf/arm_pmu.c (c0c7eb04)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_request_irq
```
```
In net/core/dev.c (c0cea738)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (c0d2377c)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/bpf_sk_storage.c (c0d48534)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (c0d78d04)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
c0371680-c03716a4: cpumask_weight.constprop.0 (STB_LOCAL)
c0377d94-c0377db8: cpumask_weight.constprop.0 (STB_LOCAL)
c03a760c-c03a7628: cpumask_weight (STB_LOCAL)
c03c85a4-c03c85c8: cpumask_weight.constprop.0 (STB_LOCAL)
c050182c-c0501850: cpumask_weight.constprop.0 (STB_LOCAL)
c0508180-c05081a4: cpumask_weight.constprop.0 (STB_LOCAL)
c0925318-c092533c: cpumask_weight.constprop.0 (STB_LOCAL)
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
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
```
```
In arch/powerpc/kernel/watchdog.c (c000000000036d78)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:start_watchdog
  - arch/powerpc/kernel/watchdog.c:watchdog_timer_fn
```
```
In arch/powerpc/kernel/crash.c (c00000000007081c)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In arch/powerpc/mm/numa.c (c0000000000a33e4)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
```
```
In arch/powerpc/sysdev/mpic.c (c0000000013591ac)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:smp_mpic_probe
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000bcdf4)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_find_target_in_mask
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (c0000000000dfae0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-imc.c:disable_nest_pmu_counters
```
```
In arch/powerpc/platforms/pseries/lpar.c (c0000000000eab88)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write
```
```
In arch/powerpc/platforms/pseries/setup.c (c0000000013622b4)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000f8e9c)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_online_cpu
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
```
```
In arch/powerpc/xmon/xmon.c (c00000000010f6a0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:symbol_lookup
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:wait_for_other_cpus
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012cf5c)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:cleanup_all_core_imc_memory
```
```
In kernel/workqueue.c (c000000000163c10)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (c0000000013676e8)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/sched/core.c (c00000000018c1b0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/rt.c (c0000000001a17ac)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/sched/deadline.c (c0000000001ac39c)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (c0000000001b04c0)
Location: include/linux/cpumask.h:554
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
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (c0000000001bc058)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/printk/printk.c (c00000000136ad74)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/irq/affinity.c (c0000000001e2570)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/clockevents.c (c000000000216558)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (c00000000021b650)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (c00000000136e6d0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (c00000000022373c)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/kexec_file.c (c0000000002353a4)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cpuset.c (c000000000252f2c)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_cpumask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/stop_machine.c (c0000000002598dc)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (c000000000270b40)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (c00000000027cf48)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (c00000000027f3a8)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (c000000000281324)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/bpf/syscall.c (c000000000305b98)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (c000000000320a20)
Location: include/linux/cpumask.h:554
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
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (c0000000003257b0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (c000000000326bd0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (c000000000328d80)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/devmap.c (c000000000331f00)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/cpumap.c (c000000000333134)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/xskmap.c (c000000000334940)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/padata.c (c00000000035c28c)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmstat.c (c00000000137b8bc)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (c000000000eec21c)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (c0000000003a4680)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_embed_first_chunk
```
```
In mm/hugetlb.c (c000000001383a2c)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/aio.c (c0000000005084e0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In lib/bucket_locks.c (c0000000007de578)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/nvdimm/region.c (c000000000a06364)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/thermal/thermal_core.c (c000000000bb8d88)
Location: include/linux/cpumask.h:554
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
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/cpu_cooling.c:cpufreq_state2power
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
```
```
In drivers/md/dm-stats.c (c000000000bffa78)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (c000000000c1a4c0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/powernv-cpufreq.c (c0000000013b8760)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (c000000000c40478)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (c000000000cad82c)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (c000000000cf67c0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/bpf_sk_storage.c (c000000000d2b274)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (c000000000d6e634)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d7104)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffffffe0000dcd74)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/sched/core.c (ffffffe0000ec4f8)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/rt.c (ffffffe0000f7b10)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/rt.c:do_balance_runtime
```
```
In kernel/sched/deadline.c (ffffffe0000fe568)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (ffffffe000100e8a)
Location: include/linux/cpumask.h:554
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
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/printk/printk.c (ffffffe0001119da)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/irq/affinity.c (ffffffe00011db8a)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/clockevents.c (ffffffe000139864)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (ffffffe00013be36)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffe00000a92a)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffe0001409f0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffe00015a1aa)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/stop_machine.c (ffffffe00015dc24)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/bpf/syscall.c (ffffffe00019e324)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffe0001b03aa)
Location: include/linux/cpumask.h:554
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
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffe0001b3990)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffe0001b4628)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffe0001b5ba0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffe0001bbda6)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/cpumap.c (ffffffe0001bc7dc)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffe0001bd736)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/padata.c (ffffffe0001d2fec)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmstat.c (ffffffe000012788)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (ffffffe000012aa0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch_init
```
```
In mm/percpu.c (ffffffe0001fa756)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/hugetlb.c (ffffffe000018142)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/aio.c (ffffffe0002aba50)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
```
```
In lib/bucket_locks.c (ffffffe0004650c0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/irqchip/irq-sifive-plic.c (ffffffe00002abd2)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/irqchip/irq-sifive-plic.c:plic_init
```
```
In drivers/base/arch_topology.c (ffffffe0000317d8)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:topology_parse_cpu_capacity
```
```
In drivers/nvdimm/region.c (ffffffe0005c6e96)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/dm-stats.c (ffffffe0006fa83e)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffe00071e1f6)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (ffffffe00075a824)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffffffe00078906c)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a7916)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007cf862)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffe0000d6bc2-ffffffe0000d6be4: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffe0000dcd74-ffffffe0000dcd96: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffe000100398-ffffffe0001003b6: cpumask_weight (STB_LOCAL)
ffffffe0001119da-ffffffe0001119fc: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffe0001fa756-ffffffe0001fa778: cpumask_weight.constprop.0 (STB_LOCAL)
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
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009544)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810236e0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/trace.c (ffffffff8102b150)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d5c3)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/xen/spinlock.c (ffffffff8102d84b)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102df21)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102e110)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a6e2)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff8103bed0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81048fe0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810536d0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a000)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff810631b0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81064da0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066f4b)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d6a2)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff8107582e)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvm.c (ffffffff81077202)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8107752e)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108b650)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810bd199)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffffffff810c084f)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/sched/core.c (ffffffff810d7415)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/rt.c (ffffffff810e7480)
Location: include/linux/cpumask.h:554
Inline: False
```
```
In kernel/sched/deadline.c (ffffffff810e9e00)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (ffffffff810f0385)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/topology.c:sd_degenerate
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/debug.c (ffffffff810f5950)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f9990)
Location: include/linux/cpumask.h:554
Inline: False
```
```
In kernel/locking/qspinlock.c (ffffffff810fe347)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/printk/printk.c (ffffffff8110d7ea)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/irq/affinity.c (ffffffff81119d80)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/clockevents.c (ffffffff8113e510)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (ffffffff81141160)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff81146c4c)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff81146d80)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/kexec_file.c (ffffffff81153a70)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cpuset.c (ffffffff81164190)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/stop_machine.c (ffffffff8116c090)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffffffff8117a550)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81181f00)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81185100)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811866c0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/bpf/syscall.c (ffffffff811d73e0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffff811ec4c0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811ef230)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffff811ef7a0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811efe90)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffff811f1ac0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811f7fc0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811f88b0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffff811f9970)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/padata.c (ffffffff81215630)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmstat.c (ffffffff81240045)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
Direct callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/mm_init.c (ffffffff81242866)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff81245b6a)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/hugetlb.c (ffffffff812905a6)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/aio.c (ffffffff81333f20)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In lib/bucket_locks.c (ffffffff81524930)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/xen/time.c (ffffffff8162bae0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816b9a7a)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/nvdimm/region.c (ffffffff8170afc0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvme/host/pci.c (ffffffff817507ae)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_dbbuf_dma_free
Direct callers:
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_setup_io_queues
```
```
In drivers/md/dm-stats.c (ffffffff8185aa30)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8186b8f0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8186c710)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818724d0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In net/core/dev.c (ffffffff818ce2c0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffffffff81904be0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/bpf_sk_storage.c (ffffffff81929790)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff81958450)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffff81009544-ffffffff8100955c: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810236e0-ffffffff810236f8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102b150-ffffffff8102b161: cpumask_weight (STB_LOCAL)
ffffffff8102d5c3-ffffffff8102d5db: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102d84b-ffffffff8102d863: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102df21-ffffffff8102df39: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102e110-ffffffff8102e121: cpumask_weight (STB_LOCAL)
ffffffff81039ee0-ffffffff81039ef1: cpumask_weight (STB_LOCAL)
ffffffff8103bed0-ffffffff8103bee8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81048fe0-ffffffff81048ff1: cpumask_weight (STB_LOCAL)
ffffffff810536d0-ffffffff810536e8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8105a000-ffffffff8105a011: cpumask_weight (STB_LOCAL)
ffffffff810631b0-ffffffff810631c1: cpumask_weight (STB_LOCAL)
ffffffff81064da0-ffffffff81064db1: cpumask_weight (STB_LOCAL)
ffffffff81066f4b-ffffffff81066f63: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8107582e-ffffffff81075846: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81077202-ffffffff8107721a: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8107752e-ffffffff81077546: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8108b650-ffffffff8108b661: cpumask_weight (STB_LOCAL)
ffffffff810ba0c0-ffffffff810ba0d8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810c084f-ffffffff810c0867: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810cc990-ffffffff810cc9a1: cpumask_weight (STB_LOCAL)
ffffffff810e7480-ffffffff810e7491: cpumask_weight (STB_LOCAL)
ffffffff810e9e00-ffffffff810e9e11: cpumask_weight (STB_LOCAL)
ffffffff810efe70-ffffffff810efe81: cpumask_weight (STB_LOCAL)
ffffffff810f5950-ffffffff810f5968: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810f9990-ffffffff810f99a1: cpumask_weight (STB_LOCAL)
ffffffff810fe347-ffffffff810fe35f: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8110d7ea-ffffffff8110d802: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81119d80-ffffffff81119d91: cpumask_weight (STB_LOCAL)
ffffffff8113e510-ffffffff8113e521: cpumask_weight (STB_LOCAL)
ffffffff81141160-ffffffff81141178: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81146c4c-ffffffff81146c64: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81146d80-ffffffff81146d91: cpumask_weight (STB_LOCAL)
ffffffff81153a70-ffffffff81153a88: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81164190-ffffffff811641a1: cpumask_weight (STB_LOCAL)
ffffffff8116c090-ffffffff8116c0a1: cpumask_weight (STB_LOCAL)
ffffffff8117a550-ffffffff8117a568: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81181f00-ffffffff81181f18: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81185100-ffffffff81185118: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811866c0-ffffffff811866d8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811d73e0-ffffffff811d73f8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811ec4c0-ffffffff811ec4d8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811ef230-ffffffff811ef248: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811ef7a0-ffffffff811ef7b8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811efe90-ffffffff811efea8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811f1ac0-ffffffff811f1ad8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811f7fc0-ffffffff811f7fd8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811f88b0-ffffffff811f88c8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811f9970-ffffffff811f9988: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81215630-ffffffff81215641: cpumask_weight (STB_LOCAL)
ffffffff8123f670-ffffffff8123f681: cpumask_weight (STB_LOCAL)
ffffffff81242866-ffffffff8124287e: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81245b6a-ffffffff81245b82: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812905a6-ffffffff812905be: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81333f20-ffffffff81333f38: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81524930-ffffffff81524948: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8162bae0-ffffffff8162baf8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff816b9a7a-ffffffff816b9a92: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8170afc0-ffffffff8170afd8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8174db10-ffffffff8174db28: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8185aa30-ffffffff8185aa48: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8186b8f0-ffffffff8186b901: cpumask_weight (STB_LOCAL)
ffffffff8186c710-ffffffff8186c721: cpumask_weight (STB_LOCAL)
ffffffff818724d0-ffffffff818724e8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818ce2c0-ffffffff818ce2d8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81904be0-ffffffff81904bf1: cpumask_weight (STB_LOCAL)
ffffffff81929790-ffffffff819297a8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81958450-ffffffff81958468: cpumask_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81007d84)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8101d8e4)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8101dad0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/alternative.c (ffffffff81029f12)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff8102bdf0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff810383b0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810437a0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104a080)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff810534c0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81055070)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81057308)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105dad2)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff8106581e)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvm.c (ffffffff810672ee)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8106760e)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107a180)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810ab9c9)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffffffff810af04f)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/sched/core.c (ffffffff810c5d35)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/rt.c (ffffffff810d66d0)
Location: include/linux/cpumask.h:554
Inline: False
```
```
In kernel/sched/deadline.c (ffffffff810d9dc0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (ffffffff810e03f5)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/topology.c:sd_degenerate
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/debug.c (ffffffff810e5b10)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810e9b70)
Location: include/linux/cpumask.h:554
Inline: False
```
```
In kernel/locking/qspinlock.c (ffffffff810ee547)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/printk/printk.c (ffffffff810fe54a)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/irq/affinity.c (ffffffff8110adf0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffff8110f680)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_init_nohz
```
```
In kernel/time/clockevents.c (ffffffff81131030)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (ffffffff81133f80)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff81139f4c)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff8113a080)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/kexec_file.c (ffffffff81146d90)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cpuset.c (ffffffff811573e0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/stop_machine.c (ffffffff8115f290)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffffffff8116d6f0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81175040)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81178240)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81179800)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/bpf/syscall.c (ffffffff811ca1a0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffff811df250)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811e1fc0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffff811e2530)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811e2be0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffff811e4810)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811ead10)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811eb600)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffff811ec6c0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/padata.c (ffffffff81208390)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmstat.c (ffffffff81233045)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
Direct callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/mm_init.c (ffffffff81235836)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff81238b1a)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/hugetlb.c (ffffffff81282236)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/aio.c (ffffffff81324b90)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In lib/bucket_locks.c (ffffffff81514c10)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816976ba)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/nvdimm/region.c (ffffffff816dea40)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/scsi/storvsc_drv.c (ffffffff81712c50)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - drivers/scsi/storvsc_drv.c:storvsc_probe
  - drivers/scsi/storvsc_drv.c:storvsc_channel_init
```
```
In drivers/nvme/host/pci.c (ffffffff8173064e)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_dbbuf_dma_free
Direct callers:
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_setup_io_queues
```
```
In drivers/md/dm-stats.c (ffffffff818225f0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818345a0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81835230)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff81838901)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8183c176)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/hv/channel_mgmt.c (ffffffff81852490)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - drivers/hv/channel_mgmt.c:init_vp_index
  - drivers/hv/channel_mgmt.c:init_vp_index
```
```
In net/core/dev.c (ffffffff818883e0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffffffff818bea10)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/bpf_sk_storage.c (ffffffff818e3540)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff81911f40)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffff81007d84-ffffffff81007d9c: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8101d8e4-ffffffff8101d8fc: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8101dad0-ffffffff8101dae1: cpumask_weight (STB_LOCAL)
ffffffff810297f0-ffffffff81029801: cpumask_weight (STB_LOCAL)
ffffffff8102bdf0-ffffffff8102be08: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810383b0-ffffffff810383c1: cpumask_weight (STB_LOCAL)
ffffffff810437a0-ffffffff810437b8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8104a080-ffffffff8104a091: cpumask_weight (STB_LOCAL)
ffffffff810534c0-ffffffff810534d1: cpumask_weight (STB_LOCAL)
ffffffff81055070-ffffffff81055081: cpumask_weight (STB_LOCAL)
ffffffff81057308-ffffffff81057320: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8106581e-ffffffff81065836: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810672ee-ffffffff81067306: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8106760e-ffffffff81067626: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8107a180-ffffffff8107a191: cpumask_weight (STB_LOCAL)
ffffffff810a8a00-ffffffff810a8a18: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810af04f-ffffffff810af067: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810bb190-ffffffff810bb1a1: cpumask_weight (STB_LOCAL)
ffffffff810d66d0-ffffffff810d66e1: cpumask_weight (STB_LOCAL)
ffffffff810d9dc0-ffffffff810d9dd1: cpumask_weight (STB_LOCAL)
ffffffff810dfee0-ffffffff810dfef1: cpumask_weight (STB_LOCAL)
ffffffff810e5b10-ffffffff810e5b28: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810e9b70-ffffffff810e9b81: cpumask_weight (STB_LOCAL)
ffffffff810ee547-ffffffff810ee55f: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810fe54a-ffffffff810fe562: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8110adf0-ffffffff8110ae01: cpumask_weight (STB_LOCAL)
ffffffff8110f680-ffffffff8110f691: cpumask_weight (STB_LOCAL)
ffffffff81131030-ffffffff81131041: cpumask_weight (STB_LOCAL)
ffffffff81133f80-ffffffff81133f98: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81139f4c-ffffffff81139f64: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8113a080-ffffffff8113a091: cpumask_weight (STB_LOCAL)
ffffffff81146d90-ffffffff81146da8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811573e0-ffffffff811573f1: cpumask_weight (STB_LOCAL)
ffffffff8115f290-ffffffff8115f2a1: cpumask_weight (STB_LOCAL)
ffffffff8116d6f0-ffffffff8116d708: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81175040-ffffffff81175058: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81178240-ffffffff81178258: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81179800-ffffffff81179818: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811ca1a0-ffffffff811ca1b8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811df250-ffffffff811df268: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811e1fc0-ffffffff811e1fd8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811e2530-ffffffff811e2548: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811e2be0-ffffffff811e2bf8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811e4810-ffffffff811e4828: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811ead10-ffffffff811ead28: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811eb600-ffffffff811eb618: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811ec6c0-ffffffff811ec6d8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81208390-ffffffff812083a1: cpumask_weight (STB_LOCAL)
ffffffff81232670-ffffffff81232681: cpumask_weight (STB_LOCAL)
ffffffff81235836-ffffffff8123584e: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81238b1a-ffffffff81238b32: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81282236-ffffffff8128224e: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81324b90-ffffffff81324ba8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81514c10-ffffffff81514c28: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff816976ba-ffffffff816976d2: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff816dea40-ffffffff816dea58: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81712c50-ffffffff81712c61: cpumask_weight (STB_LOCAL)
ffffffff8172d9b0-ffffffff8172d9c8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818225f0-ffffffff81822608: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818345a0-ffffffff818345b1: cpumask_weight (STB_LOCAL)
ffffffff81835230-ffffffff81835241: cpumask_weight (STB_LOCAL)
ffffffff81838901-ffffffff81838919: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8183c176-ffffffff8183c18e: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81852490-ffffffff818524a1: cpumask_weight (STB_LOCAL)
ffffffff818883e0-ffffffff818883f8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818bea10-ffffffff818bea21: cpumask_weight (STB_LOCAL)
ffffffff818e3540-ffffffff818e3558: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81911f40-ffffffff81911f58: cpumask_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009504)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023540)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/trace.c (ffffffff8102afb0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d423)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/xen/spinlock.c (ffffffff8102d6ab)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102dd81)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102df70)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a542)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff8103bd30)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff81048e20)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81053b00)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a430)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063660)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81065250)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810673fb)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106db52)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff810757de)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvm.c (ffffffff810771b2)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff810774de)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108b600)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In kernel/workqueue.c (ffffffff810bc6f9)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffffffff810bfd9f)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/sched/core.c (ffffffff810d4075)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/rt.c (ffffffff810e3900)
Location: include/linux/cpumask.h:554
Inline: False
```
```
In kernel/sched/deadline.c (ffffffff810e6f30)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (ffffffff810ed4b5)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/topology.c:sd_degenerate
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/debug.c (ffffffff810f2b50)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f6bb0)
Location: include/linux/cpumask.h:554
Inline: False
```
```
In kernel/locking/qspinlock.c (ffffffff810fb507)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/printk/printk.c (ffffffff8110b6da)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/irq/affinity.c (ffffffff81117c70)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/clockevents.c (ffffffff8113c230)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (ffffffff8113f010)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff81144afc)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff81144c30)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/kexec_file.c (ffffffff81151920)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cpuset.c (ffffffff81161f60)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/stop_machine.c (ffffffff81169e60)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffffffff81178320)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8117fcd0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81182ed0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81184490)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/bpf/syscall.c (ffffffff811d51b0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffff811ea290)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811ed000)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffff811ed570)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811edc60)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffff811ef890)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811f5d90)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811f6680)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffff811f7740)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/padata.c (ffffffff812133d0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmstat.c (ffffffff8123dde5)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
Direct callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/mm_init.c (ffffffff81240606)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff8124390a)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/hugetlb.c (ffffffff8128e3b6)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/aio.c (ffffffff813319f0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In lib/bucket_locks.c (ffffffff815209c0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/xen/time.c (ffffffff81659cb0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816e7f4a)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/nvdimm/region.c (ffffffff81749d90)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/dm-stats.c (ffffffff818aa060)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818bc680)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818bd4a0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff818c0901)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818c3d80)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818dab00)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (ffffffff8191f2c0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffffffff81955c10)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/bpf_sk_storage.c (ffffffff8197a920)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c2c20)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffff81009504-ffffffff8100951c: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81023540-ffffffff81023558: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102afb0-ffffffff8102afc1: cpumask_weight (STB_LOCAL)
ffffffff8102d423-ffffffff8102d43b: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102d6ab-ffffffff8102d6c3: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102dd81-ffffffff8102dd99: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102df70-ffffffff8102df81: cpumask_weight (STB_LOCAL)
ffffffff81039d40-ffffffff81039d51: cpumask_weight (STB_LOCAL)
ffffffff8103bd30-ffffffff8103bd48: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81048e20-ffffffff81048e31: cpumask_weight (STB_LOCAL)
ffffffff81053b00-ffffffff81053b18: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8105a430-ffffffff8105a441: cpumask_weight (STB_LOCAL)
ffffffff81063660-ffffffff81063671: cpumask_weight (STB_LOCAL)
ffffffff81065250-ffffffff81065261: cpumask_weight (STB_LOCAL)
ffffffff810673fb-ffffffff81067413: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810757de-ffffffff810757f6: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810771b2-ffffffff810771ca: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810774de-ffffffff810774f6: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8108b600-ffffffff8108b611: cpumask_weight (STB_LOCAL)
ffffffff810b9620-ffffffff810b9638: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810bfd9f-ffffffff810bfdb7: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810cbeb0-ffffffff810cbec1: cpumask_weight (STB_LOCAL)
ffffffff810e3900-ffffffff810e3911: cpumask_weight (STB_LOCAL)
ffffffff810e6f30-ffffffff810e6f41: cpumask_weight (STB_LOCAL)
ffffffff810ecfa0-ffffffff810ecfb1: cpumask_weight (STB_LOCAL)
ffffffff810f2b50-ffffffff810f2b68: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810f6bb0-ffffffff810f6bc1: cpumask_weight (STB_LOCAL)
ffffffff810fb507-ffffffff810fb51f: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8110b6da-ffffffff8110b6f2: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81117c70-ffffffff81117c81: cpumask_weight (STB_LOCAL)
ffffffff8113c230-ffffffff8113c241: cpumask_weight (STB_LOCAL)
ffffffff8113f010-ffffffff8113f028: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81144afc-ffffffff81144b14: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81144c30-ffffffff81144c41: cpumask_weight (STB_LOCAL)
ffffffff81151920-ffffffff81151938: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81161f60-ffffffff81161f71: cpumask_weight (STB_LOCAL)
ffffffff81169e60-ffffffff81169e71: cpumask_weight (STB_LOCAL)
ffffffff81178320-ffffffff81178338: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8117fcd0-ffffffff8117fce8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81182ed0-ffffffff81182ee8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81184490-ffffffff811844a8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811d51b0-ffffffff811d51c8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811ea290-ffffffff811ea2a8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811ed000-ffffffff811ed018: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811ed570-ffffffff811ed588: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811edc60-ffffffff811edc78: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811ef890-ffffffff811ef8a8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811f5d90-ffffffff811f5da8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811f6680-ffffffff811f6698: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811f7740-ffffffff811f7758: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812133d0-ffffffff812133e1: cpumask_weight (STB_LOCAL)
ffffffff8123d410-ffffffff8123d421: cpumask_weight (STB_LOCAL)
ffffffff81240606-ffffffff8124061e: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8124390a-ffffffff81243922: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8128e3b6-ffffffff8128e3ce: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff813319f0-ffffffff81331a08: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff815209c0-ffffffff815209d8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81659cb0-ffffffff81659cc8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff816e7f4a-ffffffff816e7f62: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81749d90-ffffffff81749da8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818aa060-ffffffff818aa078: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818bc680-ffffffff818bc691: cpumask_weight (STB_LOCAL)
ffffffff818bd4a0-ffffffff818bd4b1: cpumask_weight (STB_LOCAL)
ffffffff818c0901-ffffffff818c0919: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818c3d80-ffffffff818c3d98: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818dab00-ffffffff818dab18: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8191f2c0-ffffffff8191f2d8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81955c10-ffffffff81955c21: cpumask_weight (STB_LOCAL)
ffffffff8197a920-ffffffff8197a938: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff819c2c20-ffffffff819c2c38: cpumask_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
unsigned int cpumask_weight(const struct cpumask *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009664)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810239f0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/trace.c (ffffffff8102bda0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/xen/trace.c:perf_trace_xen_mmu_flush_tlb_others
  - arch/x86/xen/trace.c:trace_event_raw_event_xen_mmu_flush_tlb_others
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102e213)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/xen/spinlock.c (ffffffff8102e49b)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/xen/spinlock.c:xen_init_spinlocks
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102eb71)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102ed60)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:perf_trace_hyperv_mmu_flush_tlb_others
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_send_ipi_mask
  - arch/x86/hyperv/mmu.c:trace_event_raw_event_hyperv_mmu_flush_tlb_others
```
```
In arch/x86/kernel/alternative.c (ffffffff8103b542)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tsc.c (ffffffff8103cd80)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (ffffffff8104a230)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:show_cpuinfo
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81055050)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b8f0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064c20)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff81066830)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_target
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810689db)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106f0fa)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106fdd2)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:physflat_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff8107783e)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvm.c (ffffffff81079222)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_spinlock_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff8107957e)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
  - arch/x86/kernel/kvmclock.c:kvmclock_init_mem
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108d940)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81098ab0)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_next
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_start
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a800)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/workqueue.c (ffffffff810c4a89)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/pid.c (ffffffff810c81cf)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/pid.c:pid_idr_init
  - kernel/pid.c:pid_idr_init
```
```
In kernel/sched/core.c (ffffffff810deff5)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/rt.c (ffffffff810ef440)
Location: include/linux/cpumask.h:554
Inline: False
```
```
In kernel/sched/deadline.c (ffffffff810f1ed0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (ffffffff810f84f5)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - kernel/sched/topology.c:sd_degenerate
Direct callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
```
In kernel/sched/debug.c (ffffffff810fdb50)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81101c30)
Location: include/linux/cpumask.h:554
Inline: False
```
```
In kernel/locking/qspinlock.c (ffffffff811066d7)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_init_lock_hash
```
```
In kernel/printk/printk.c (ffffffff81116b9a)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/printk/printk.c:setup_log_buf
  - kernel/printk/printk.c:setup_log_buf
```
```
In kernel/irq/affinity.c (ffffffff81123300)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/time/clockevents.c (ffffffff81148d10)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (ffffffff8114be90)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffff81151693)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffff811517b0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/kexec_file.c (ffffffff8115e740)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/kexec_file.c:crash_prepare_elf64_headers
```
```
In kernel/cgroup/cpuset.c (ffffffff8116f3f0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/stop_machine.c (ffffffff811775a0)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (ffffffff81185bf0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118d5f0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81190810)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81191de0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/bpf/syscall.c (ffffffff811e34e0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffff811f8670)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffff811fb4b0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffff811fba40)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffff811fc130)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffff811fdd70)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff812042f0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff81204bf0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffff81205cc0)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In kernel/padata.c (ffffffff81222380)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmstat.c (ffffffff8124d515)
Location: include/linux/cpumask.h:554
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
Direct callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/mm_init.c (ffffffff8124fd59)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - mm/mm_init.c:mm_compute_batch
```
```
In mm/percpu.c (ffffffff812530ca)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
```
In mm/hugetlb.c (ffffffff8129e147)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In fs/aio.c (ffffffff81344650)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
```
```
In lib/bucket_locks.c (ffffffff8153a340)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In drivers/xen/time.c (ffffffff81674280)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff8170264a)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
```
```
In drivers/nvdimm/region.c (ffffffff81765210)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/dm-stats.c (ffffffff818c6340)
Location: include/linux/cpumask.h:554
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818d8970)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818d9790)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/pcc-cpufreq.c (ffffffff818dcc0b)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818e00f0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff818f7620)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (ffffffff81941020)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/net-sysfs.c (ffffffff81977e00)
Location: include/linux/cpumask.h:554
Inline: False
Direct callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/bpf_sk_storage.c (ffffffff8199ce50)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cc6f0)
Location: include/linux/cpumask.h:554
Inline: True
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
**Symbols:**

```
ffffffff81009664-ffffffff8100967c: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810239f0-ffffffff81023a08: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102bda0-ffffffff8102bdb1: cpumask_weight (STB_LOCAL)
ffffffff8102e213-ffffffff8102e22b: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102e49b-ffffffff8102e4b3: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102eb71-ffffffff8102eb89: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8102ed60-ffffffff8102ed71: cpumask_weight (STB_LOCAL)
ffffffff8103ad40-ffffffff8103ad51: cpumask_weight (STB_LOCAL)
ffffffff8103cd80-ffffffff8103cd98: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8104a230-ffffffff8104a241: cpumask_weight (STB_LOCAL)
ffffffff81055050-ffffffff81055068: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8105b8f0-ffffffff8105b901: cpumask_weight (STB_LOCAL)
ffffffff81064c20-ffffffff81064c31: cpumask_weight (STB_LOCAL)
ffffffff81066830-ffffffff81066841: cpumask_weight (STB_LOCAL)
ffffffff810689db-ffffffff810689f3: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8106f0fa-ffffffff8106f112: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8107783e-ffffffff81077856: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81079222-ffffffff8107923a: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8107957e-ffffffff81079596: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8108d940-ffffffff8108d951: cpumask_weight (STB_LOCAL)
ffffffff81096e60-ffffffff81096e78: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8109a800-ffffffff8109a811: cpumask_weight (STB_LOCAL)
ffffffff810c2630-ffffffff810c2648: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810c81cf-ffffffff810c81e7: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff810d44c0-ffffffff810d44d1: cpumask_weight (STB_LOCAL)
ffffffff810ef440-ffffffff810ef451: cpumask_weight (STB_LOCAL)
ffffffff810f1ed0-ffffffff810f1ee1: cpumask_weight (STB_LOCAL)
ffffffff810f7fe0-ffffffff810f7ff1: cpumask_weight (STB_LOCAL)
ffffffff810fdb50-ffffffff810fdb68: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81101c30-ffffffff81101c41: cpumask_weight (STB_LOCAL)
ffffffff811066d7-ffffffff811066ef: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81116b9a-ffffffff81116bb2: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81123300-ffffffff81123311: cpumask_weight (STB_LOCAL)
ffffffff81148d10-ffffffff81148d21: cpumask_weight (STB_LOCAL)
ffffffff8114be90-ffffffff8114bea8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81151693-ffffffff811516ab: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811517b0-ffffffff811517c1: cpumask_weight (STB_LOCAL)
ffffffff8115e740-ffffffff8115e758: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8116f3f0-ffffffff8116f401: cpumask_weight (STB_LOCAL)
ffffffff811775a0-ffffffff811775b1: cpumask_weight (STB_LOCAL)
ffffffff81185bf0-ffffffff81185c08: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8118d5f0-ffffffff8118d608: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81190810-ffffffff81190828: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81191de0-ffffffff81191df8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811e34e0-ffffffff811e34f8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811f8670-ffffffff811f8688: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811fb4b0-ffffffff811fb4c8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811fba40-ffffffff811fba58: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811fc130-ffffffff811fc148: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff811fdd70-ffffffff811fdd88: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812042f0-ffffffff81204308: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81204bf0-ffffffff81204c08: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81205cc0-ffffffff81205cd8: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81222380-ffffffff81222391: cpumask_weight (STB_LOCAL)
ffffffff8124cb40-ffffffff8124cb51: cpumask_weight (STB_LOCAL)
ffffffff8124fd59-ffffffff8124fd71: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff812530ca-ffffffff812530e2: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8129e147-ffffffff8129e15f: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81344650-ffffffff81344668: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8153a340-ffffffff8153a358: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81674280-ffffffff81674298: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff8170264a-ffffffff81702662: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81765210-ffffffff81765228: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818c6340-ffffffff818c6358: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818d8970-ffffffff818d8981: cpumask_weight (STB_LOCAL)
ffffffff818d9790-ffffffff818d97a1: cpumask_weight (STB_LOCAL)
ffffffff818dcc0b-ffffffff818dcc23: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818e00f0-ffffffff818e0108: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff818f7620-ffffffff818f7638: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81941020-ffffffff81941038: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff81977e00-ffffffff81977e11: cpumask_weight (STB_LOCAL)
ffffffff8199ce50-ffffffff8199ce68: cpumask_weight.constprop.0 (STB_LOCAL)
ffffffff819cc6f0-ffffffff819cc708: cpumask_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
