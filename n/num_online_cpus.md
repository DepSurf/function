# Function: <code>num_online_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102c96d)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/alternative.c (ffffffff8103ada3)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff8103c280)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81043bbc)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e7ca)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056a2e)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106285f)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81062e52)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81063302)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b64bd)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067a01)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/ipi.c:apic_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106e760)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:run_sync
```
```
In arch/x86/mm/pageattr.c (ffffffff828c31f3)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108cacb)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81099fc9)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810a4640)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/fair.c (ffffffff810ebe35)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/membarrier.c (ffffffff8110176a)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/power/swap.c (ffffffff8110e529)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk_safe.c (ffffffff81115753)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/rcu/tree.c (ffffffff81127752)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/tick-common.c (ffffffff8114725a)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/smp.c (ffffffff828d135c)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff811742ed)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In kernel/debug/debug_core.c (ffffffff81184735)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/trace.c (ffffffff811aa156)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/events/core.c (ffffffff81212d58)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/page-writeback.c (ffffffff8122ebbf)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff812478c1)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/vmalloc.c (ffffffff81277e2e)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/swap_slots.c (ffffffff8128dc6b)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/slub.c (ffffffff812a4b51)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/io_uring.c (ffffffff81344ddd)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (ffffffff828e65d1)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/verity/verify.c (ffffffff828e67ff)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_init_workqueue
```
```
In fs/proc/stat.c (ffffffff8137ba55)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In lib/percpu_counter.c (ffffffff81552d30)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In drivers/acpi/acpi_processor.c (ffffffff815e2d3b)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff8163535e)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/block/xen-blkfront.c (ffffffff8290954f)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff81756ab8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/xen-netfront.c (ffffffff8290c791)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netif_init
```
```
In drivers/usb/host/xhci.c (ffffffff8183133b)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818c9a28)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In net/core/dev.c (ffffffff81929aca)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In lib/cpumask.c (ffffffff81aae240)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
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
In arch/x86/xen/smp.c (ffffffff8102e9ed)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/alternative.c (ffffffff8103da29)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff8103f230)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
```
```
In arch/x86/kernel/tboot.c (ffffffff8104755c)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbe92d)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff82cd5a33)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105b6b5)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106883f)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81068ed2)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81069315)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b88e)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:impress_friends
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8106e737)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/ipi.c:apic_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff82ce69dc)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093cf3)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109f7ba)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810ab948)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/fair.c (ffffffff810f6465)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:update_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff8110c0b5)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/power/swap.c (ffffffff811195b9)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk_safe.c (ffffffff81121113)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/rcu/tree.c (ffffffff81137a0e)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/tick-common.c (ffffffff811570da)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/smp.c (ffffffff82cf21b4)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff8118612d)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
```
In kernel/debug/debug_core.c (ffffffff81198775)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/trace.c (ffffffff811c36ef)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_func_help_header_irq
```
```
In kernel/events/core.c (ffffffff8123edd6)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/page-writeback.c (ffffffff8125b4ff)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_cpu_online
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_ratio_handler
```
```
In mm/vmstat.c (ffffffff81275abe)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/vmalloc.c (ffffffff812a8d0e)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/swap_slots.c (ffffffff812c072e)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/slub.c (ffffffff812d92f8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/io_uring.c (ffffffff8137f066)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_offload_start
```
```
In fs/crypto/crypto.c (ffffffff82d0148d)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/verity/verify.c (ffffffff82d01698)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_init_workqueue
```
```
In fs/proc/stat.c (ffffffff813c51c5)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In security/apparmor/lsm.c (ffffffff82d065d8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In block/blk-crypto-fallback.c (ffffffff81582102)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In lib/percpu_counter.c (ffffffff815dc110)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In lib/cpumask.c (ffffffff815e7f60)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
```
In drivers/acpi/acpi_processor.c (ffffffff8168e24e)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff816e2120)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/block/xen-blkfront.c (ffffffff82d1f76f)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff818160a8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/xen-netfront.c (ffffffff82d21396)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netif_init
```
```
In drivers/usb/host/xhci.c (ffffffff8190365e)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_msix
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199caa4)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In net/core/dev.c (ffffffff819fdb0a)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In arch/x86/xen/smp.c (ffffffff8102f84d)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/alternative.c (ffffffff81bd3f48)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff8103f2f0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
```
```
In arch/x86/kernel/tboot.c (ffffffff81046d8c)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c371bd)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff82fc19db)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105a105)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106a4df)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff8106ab22)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff8106af35)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff81bd67e3)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:impress_friends
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8106fbb7)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/ipi.c:apic_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff82fd4322)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093243)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81bdaaf0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff81bdb5c6)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/fair.c (ffffffff810f45d5)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:sched_proc_update_handler
  - kernel/sched/fair.c:update_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff81109286)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/power/swap.c (ffffffff81114df7)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk_safe.c (ffffffff8111bd73)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/rcu/tree.c (ffffffff81133e95)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/tick-common.c (ffffffff811531c5)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/smp.c (ffffffff82fdec8d)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff811832bd)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
```
In kernel/debug/debug_core.c (ffffffff811958d5)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/trace.c (ffffffff811c12ff)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_func_help_header_irq
```
```
In kernel/events/core.c (ffffffff812491c6)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/page-writeback.c (ffffffff8126591f)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_cpu_online
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_ratio_handler
```
```
In mm/vmstat.c (ffffffff8128039e)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/vmalloc.c (ffffffff812b3fa2)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/swap_slots.c (ffffffff812cc1a5)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/slub.c (ffffffff812e48ef)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/io_uring.c (ffffffff81393ef3)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_offload_create
```
```
In fs/crypto/crypto.c (ffffffff82fee77c)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/verity/verify.c (ffffffff82fee987)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_init_workqueue
```
```
In fs/proc/stat.c (ffffffff813d7115)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In security/apparmor/lsm.c (ffffffff82ff3975)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In block/blk-crypto-fallback.c (ffffffff8159f0d2)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In lib/percpu_counter.c (ffffffff815f9dc4)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In lib/cpumask.c (ffffffff8160d0c0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
```
In drivers/acpi/acpi_processor.c (ffffffff816ac031)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff816ffe8d)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/block/xen-blkfront.c (ffffffff8300d562)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff81825238)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/xen-netfront.c (ffffffff8300f181)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netif_init
```
```
In drivers/usb/host/xhci.c (ffffffff8190bbce)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_msix
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199fb34)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In net/core/dev.c (ffffffff819fd6da)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In arch/x86/xen/smp.c (ffffffff8103036d)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/alternative.c (ffffffff81bc6429)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff81040910)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
```
```
In arch/x86/kernel/tboot.c (ffffffff810486ec)
Location: include/linux/cpumask.h:885
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c297ca)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff831cc030)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105aaa5)
Location: include/linux/cpumask.h:885
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106af9f)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff8106b5f2)
Location: include/linux/cpumask.h:885
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff8106bb42)
Location: include/linux/cpumask.h:885
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff831d2359)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810706e7)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/ipi.c:apic_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff831dee2b)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093c43)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81bccba6)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff81bcd6b8)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/fair.c (ffffffff810f6595)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:update_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff8110afd0)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/power/swap.c (ffffffff81115767)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk_safe.c (ffffffff8111c2f3)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/rcu/tree.c (ffffffff81134b25)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/tick-common.c (ffffffff811545c5)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/smp.c (ffffffff831e979f)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff811843dd)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
```
In kernel/debug/debug_core.c (ffffffff81196875)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/trace.c (ffffffff811c2323)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:print_trace_header
```
```
In kernel/events/core.c (ffffffff8124d39c)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/page-writeback.c (ffffffff8126a41f)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_cpu_online
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_ratio_handler
```
```
In mm/vmstat.c (ffffffff812854ae)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/vmalloc.c (ffffffff812b9682)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/swap_slots.c (ffffffff812d2d55)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/slub.c (ffffffff812ec173)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/io_uring.c (ffffffff8139246b)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_alloc_task_context
```
```
In fs/crypto/crypto.c (ffffffff831f903b)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/verity/verify.c (ffffffff831f9246)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_init_workqueue
```
```
In fs/proc/stat.c (ffffffff813de035)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In security/apparmor/lsm.c (ffffffff831fe492)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In block/blk-crypto-fallback.c (ffffffff815a5f02)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In lib/percpu_counter.c (ffffffff815dc9a4)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In lib/cpumask.c (ffffffff815f08d0)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
```
In drivers/acpi/acpi_processor.c (ffffffff8168e764)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff816e19ad)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/block/xen-blkfront.c (ffffffff832183bf)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff818085c8)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/xen-netfront.c (ffffffff8321a1d0)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netif_init
```
```
In drivers/usb/host/xhci.c (ffffffff818ef32a)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81984572)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In net/core/dev.c (ffffffff819e3f4a)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In arch/x86/xen/smp.c (ffffffff810351ad)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/alternative.c (ffffffff81c99474)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff81046a00)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
```
```
In arch/x86/kernel/tboot.c (ffffffff8104f02c)
Location: include/linux/cpumask.h:885
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81d47574)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff832ad894)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81063fe5)
Location: include/linux/cpumask.h:885
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810759c9)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff810760e2)
Location: include/linux/cpumask.h:885
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81076612)
Location: include/linux/cpumask.h:885
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff832b4b96)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8107c299)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/ipi.c:apic_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff832c231b)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810a3a23)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81ca3024)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff81ca3ff9)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/fair.c (ffffffff811103b5)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:update_sysctl
```
```
In kernel/sched/membarrier.c (ffffffff81129830)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/power/swap.c (ffffffff81135987)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/rcu/tree.c (ffffffff811572d5)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/clocksource.c (ffffffff8116d7a9)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-common.c (ffffffff81178de5)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/smp.c (ffffffff832cdda2)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff811ac6fd)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
```
In kernel/debug/debug_core.c (ffffffff811bfb75)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/trace.c (ffffffff811ecf63)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:trace_default_header
  - kernel/trace/trace.c:print_trace_header
```
```
In kernel/events/core.c (ffffffff81286fac)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/page-writeback.c (ffffffff812a70cf)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_cpu_online
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_ratio_handler
```
```
In mm/vmstat.c (ffffffff812c3d86)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/vmalloc.c (ffffffff812fbc22)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/page_alloc.c (ffffffff81301722)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
```
In mm/swap_slots.c (ffffffff81318794)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/slub.c (ffffffff8133344e)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In mm/memcontrol.c (ffffffff813538ec)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:memory_stat_format
```
```
In fs/io_uring.c (ffffffff813e0498)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_alloc_task_context
```
```
In fs/crypto/crypto.c (ffffffff832dff20)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/verity/verify.c (ffffffff832e0147)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_init_workqueue
```
```
In fs/proc/stat.c (ffffffff8142f815)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In security/apparmor/lsm.c (ffffffff832e57a4)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In block/blk-crypto-fallback.c (ffffffff8160ea1e)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In lib/percpu_counter.c (ffffffff816482de)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In lib/cpumask.c (ffffffff8165d9b0)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
```
In drivers/acpi/acpi_processor.c (ffffffff81703ffd)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff81759e51)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/block/xen-blkfront.c (ffffffff83301e1a)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff81892d92)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/xen-netfront.c (ffffffff83303ccb)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netif_init
```
```
In drivers/usb/host/xhci.c (ffffffff8198beea)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81a2dbe4)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In net/core/dev.c (ffffffff81a9485a)
Location: include/linux/cpumask.h:885
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In arch/x86/xen/smp.c (ffffffff8103af2d)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/alternative.c (ffffffff81e48a81)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff8104fb20)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
```
```
In arch/x86/kernel/tboot.c (ffffffff8105a28c)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_dying_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f15c3e)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8345e747)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81084659)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81084e11)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
```
```
In arch/x86/kernel/smp.c (ffffffff81085145)
Location: include/linux/cpumask.h:911
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff83466465)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8108b646)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/ipi.c:apic_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff83474a1a)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810b8101)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81e5281c)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff81e53875)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/fair.c (ffffffff8112c4c5)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:update_sysctl
```
```
In kernel/sched/build_utility.c (ffffffff81141b14)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
```
```
In kernel/power/swap.c (ffffffff81157de3)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/rcu/update.c (ffffffff81173e35)
Location: include/linux/cpumask.h:911
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff83480554)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_scheduler_starting
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
```
In kernel/time/clocksource.c (ffffffff811a1896)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-common.c (ffffffff811ae0b5)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/smp.c (ffffffff83481a50)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff811de1dc)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
```
In kernel/debug/debug_core.c (ffffffff811f3065)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/trace.c (ffffffff81223c7e)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/events/core.c (ffffffff812db8a8)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/page-writeback.c (ffffffff812ff6df)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_cpu_online
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_ratio_handler
```
```
In mm/vmstat.c (ffffffff81321541)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/vmalloc.c (ffffffff81360c51)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:drain_vmap_area_work
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/page_alloc.c (ffffffff81369032)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
```
In mm/swap_slots.c (ffffffff81383e52)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/slub.c (ffffffff813a4c12)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In mm/memcontrol.c (ffffffff813cb92c)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:mem_cgroup_flush_stats_delayed
```
```
In fs/crypto/crypto.c (ffffffff83495d07)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/verity/verify.c (ffffffff83495f60)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_init_workqueue
```
```
In fs/proc/stat.c (ffffffff814a9455)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In security/apparmor/lsm.c (ffffffff8349c5d5)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In block/blk-crypto-fallback.c (ffffffff816c31b6)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In io_uring/io_uring.c (ffffffff81e8ec44)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_alloc_task_context
```
```
In lib/percpu_counter.c (ffffffff8175e51c)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - lib/percpu_counter.c:__percpu_counter_compare
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In lib/cpumask.c (ffffffff81776f80)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
```
In drivers/acpi/acpi_processor.c (ffffffff818320b2)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff81f297ae)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/block/xen-blkfront.c (ffffffff834bae94)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff819dd02d)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/xen-netfront.c (ffffffff834bcce9)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netif_init
```
```
In drivers/usb/host/xhci.c (ffffffff81ae80d1)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81b97fb3)
Location: include/linux/cpumask.h:911
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
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
In arch/x86/xen/smp.c (ffffffff810435e1)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/alternative.c (ffffffff81059aeb)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff8105ce00)
Location: include/linux/cpumask.h:1020
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81067d6c)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_dying_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820bd367)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff83e7f985)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810975d9)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81098154)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
```
```
In arch/x86/kernel/smp.c (ffffffff810985b5)
Location: include/linux/cpumask.h:1020
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff83e89e0d)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8109fa26)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/ipi.c:apic_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff83e9cb25)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d37f3)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dd8ee)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810ee577)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/fair.c (ffffffff81156185)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:sched_init_granularity
```
```
In kernel/sched/build_utility.c (ffffffff8116e524)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
```
```
In kernel/power/swap.c (ffffffff81188d93)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/rcu/tree.c (ffffffff811b6227)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_scheduler_starting
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
```
In kernel/time/clocksource.c (ffffffff811e0a43)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-common.c (ffffffff811ee765)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/smp.c (ffffffff83eaeca1)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff81223d0c)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
```
In kernel/debug/debug_core.c (ffffffff81239e05)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/trace.c (ffffffff8126ed8e)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/bpf/hashtab.c (ffffffff812f91e9)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/events/core.c (ffffffff81343b6f)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/page-writeback.c (ffffffff81369a1f)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_cpu_online
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_ratio_handler
```
```
In mm/vmstat.c (ffffffff8139551a)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/vmalloc.c (ffffffff813dc4c5)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:drain_vmap_area_work
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/page_alloc.c (ffffffff813e51e3)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
```
In mm/swap_slots.c (ffffffff814018fd)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/slub.c (ffffffff81424ea9)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In mm/memcontrol.c (ffffffff8145063c)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_memcg_lruvec_state
  - mm/memcontrol.c:mem_cgroup_flush_stats_delayed
```
```
In fs/crypto/crypto.c (ffffffff83eca9a5)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/verity/verify.c (ffffffff83ecacf5)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_init_workqueue
```
```
In fs/proc/stat.c (ffffffff8153ef15)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In fs/squashfs/decompressor_multi.c (ffffffff815f2985)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi.c:squashfs_max_decompressors
```
```
In security/apparmor/lsm.c (ffffffff83ed3a79)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In block/blk-crypto-fallback.c (ffffffff81784637)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In io_uring/tctx.c (ffffffff8179bb2a)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In lib/percpu_counter.c (ffffffff8188bcec)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - lib/percpu_counter.c:__percpu_counter_compare
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In drivers/acpi/acpi_processor.c (ffffffff81965838)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff820d55ee)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/block/xen-blkfront.c (ffffffff83ef88b5)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff81b587b0)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/xen-netfront.c (ffffffff83efb202)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netif_init
```
```
In drivers/usb/host/xhci.c (ffffffff81c74091)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81d392c8)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In lib/cpumask.c (ffffffff8201f9a0)
Location: include/linux/cpumask.h:1020
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
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
In arch/x86/xen/smp.c (ffffffff81043816)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/alternative.c (ffffffff8105b08b)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff8105e300)
Location: include/linux/cpumask.h:1072
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8106961c)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_dying_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213ed77)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff836a26d5)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8109a6b9)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff8109b204)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff836ad4e4)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a29b6)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/ipi.c:apic_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff836c0645)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d6bd3)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e8ece)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810fa557)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/fair.c (ffffffff811662f5)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:sched_init_granularity
```
```
In kernel/sched/build_utility.c (ffffffff8117eb05)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
```
```
In kernel/power/swap.c (ffffffff81199f43)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/rcu/tree.c (ffffffff811c89b7)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_scheduler_starting
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:synchronize_rcu
```
```
In kernel/time/clocksource.c (ffffffff811f4fa3)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-common.c (ffffffff81202e95)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/smp.c (ffffffff836d3cd1)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff8123a36c)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
```
In kernel/debug/debug_core.c (ffffffff81250e15)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/trace.c (ffffffff81285fee)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/bpf/hashtab.c (ffffffff81327093)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/events/core.c (ffffffff81374bf5)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/page-writeback.c (ffffffff8139bbbf)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_cpu_online
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_ratio_handler
```
```
In mm/vmstat.c (ffffffff813c813a)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/vmalloc.c (ffffffff81410df5)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:drain_vmap_area_work
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/page_alloc.c (ffffffff81419c33)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
```
In mm/swap_slots.c (ffffffff814347dd)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/slub.c (ffffffff8145a259)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In mm/memcontrol.c (ffffffff8148609c)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_memcg_lruvec_state
  - mm/memcontrol.c:mem_cgroup_flush_stats_ratelimited
```
```
In fs/crypto/crypto.c (ffffffff836efa05)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/verity/verify.c (ffffffff836efd15)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_init_workqueue
```
```
In fs/proc/stat.c (ffffffff81577265)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In fs/squashfs/decompressor_multi.c (ffffffff8162aa75)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi.c:squashfs_max_decompressors
```
```
In security/apparmor/lsm.c (ffffffff836f88f9)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In block/blk-crypto-fallback.c (ffffffff817c49a2)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In io_uring/tctx.c (ffffffff817dcc5a)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In lib/percpu_counter.c (ffffffff818ce2d5)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - lib/percpu_counter.c:__percpu_counter_compare
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In drivers/acpi/acpi_processor.c (ffffffff819abd90)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff82143df9)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/block/xen-blkfront.c (ffffffff8371e555)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff81babd20)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/virtio_net.c (ffffffff81c51bf8)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
```
In drivers/net/xen-netfront.c (ffffffff83720fe2)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netif_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81da3d68)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In lib/cpumask.c (ffffffff8209f8d0)
Location: include/linux/cpumask.h:1072
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
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
In arch/x86/xen/smp.c (ffffffff81049d16)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/alternative.c (ffffffff8106238b)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff810653c0)
Location: include/linux/cpumask.h:1094
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81070a8c)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_dying_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82220d97)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff838d27d5)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810a1ee9)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff810a2844)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff838ddb43)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a962f)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/ipi.c:apic_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff838f1165)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810df403)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f1149)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff81103977)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_bringup_cpus_parallel
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/fair.c (ffffffff8116f945)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - kernel/sched/fair.c:rq_offline_fair
  - kernel/sched/fair.c:rq_online_fair
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:sched_update_scaling
  - kernel/sched/fair.c:sched_init_granularity
```
```
In kernel/sched/build_utility.c (ffffffff8118fa90)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
```
```
In kernel/power/swap.c (ffffffff811a8fa0)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/rcu/tree.c (ffffffff811daa27)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_scheduler_starting
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:synchronize_rcu
```
```
In kernel/time/clocksource.c (ffffffff8120b143)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-common.c (ffffffff81219455)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/smp.c (ffffffff83905cb1)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff8125403c)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
```
In kernel/debug/debug_core.c (ffffffff8126ac65)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/trace.c (ffffffff812a10fe)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/bpf/hashtab.c (ffffffff8134b716)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/events/core.c (ffffffff8139df25)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/page-writeback.c (ffffffff813c589f)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_cpu_online
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_ratio_handler
```
```
In mm/vmstat.c (ffffffff813f2bd8)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/vmalloc.c (ffffffff8143d5e5)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:drain_vmap_area_work
  - mm/vmalloc.c:__purge_vmap_area_lazy
```
```
In mm/page_alloc.c (ffffffff81446b45)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
```
In mm/slub.c (ffffffff81455329)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In mm/swap_slots.c (ffffffff8146dbd7)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/memcontrol.c (ffffffff814bafb1)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_memcg_lruvec_state
```
```
In fs/crypto/crypto.c (ffffffff83922a85)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/verity/verify.c (ffffffff83922da5)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_init_workqueue
```
```
In fs/proc/stat.c (ffffffff815afb75)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In fs/squashfs/decompressor_multi.c (ffffffff81663dc5)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi.c:squashfs_max_decompressors
```
```
In security/apparmor/lsm.c (ffffffff8392bee1)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In block/blk-crypto-fallback.c (ffffffff81809691)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In io_uring/tctx.c (ffffffff81820f3c)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In lib/percpu_counter.c (ffffffff8191ffa6)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - lib/percpu_counter.c:__percpu_counter_limited_add
  - lib/percpu_counter.c:__percpu_counter_compare
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In drivers/acpi/acpi_processor.c (ffffffff819f6130)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff82226519)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/iommu/iova.c (ffffffff81b7e1e0)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_depot_work_func
```
```
In drivers/block/xen-blkfront.c (ffffffff83951f25)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff81c00060)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/virtio_net.c (ffffffff81d07e6e)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_set_affinity
```
```
In drivers/net/xen-netfront.c (ffffffff83954df2)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netif_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5bdf8)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In lib/cpumask.c (ffffffff821777c0)
Location: include/linux/cpumask.h:1094
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
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
In arch/arm64/kernel/insn.c (ffff800010da79c4)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:aarch64_insn_patch_text_cb
```
```
In arch/arm64/kernel/cpufeature.c (ffff80001009a294)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings
```
```
In arch/arm64/kernel/smp.c (ffff80001009d2e8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:crash_smp_send_stop
  - arch/arm64/kernel/smp.c:crash_smp_send_stop
  - arch/arm64/kernel/smp.c:smp_send_stop
  - arch/arm64/kernel/smp.c:smp_send_stop
  - arch/arm64/kernel/smp.c:smp_send_stop
  - arch/arm64/kernel/smp.c:smp_cpus_done
```
```
In arch/arm64/kernel/machine_kexec.c (ffff8000100a9ec8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/arm64/kernel/machine_kexec.c:machine_kexec
```
```
In virt/kvm/arm/arm.c (ffff8000100c60c4)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_vm_ioctl_check_extension
```
```
In kernel/cpu.c (ffff8000100f9c48)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/fair.c (ffff80001014c1b8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/membarrier.c (ffff8000101661c8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
```
```
In kernel/printk/printk_safe.c (ffff800010176e30)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/rcu/tree.c (ffff80001018fc84)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/tick-common.c (ffff8000101b2248)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/smp.c (ffff8000114496d0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffff8000101e8b7c)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_cpuslocked
```
```
In kernel/debug/debug_core.c (ffff8000101fa108)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/trace.c (ffff800010226eb8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/events/core.c (ffff80001029d0bc)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/page-writeback.c (ffff8000102bdcd8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffff8000102dbd34)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/vmalloc.c (ffff80001030e3e4)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/swap_slots.c (ffff800010329e58)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/slub.c (ffff8000103454b4)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/io_uring.c (ffff8000104031f4)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (ffff80001145fe38)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/verity/verify.c (ffff8000114600e0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_init_workqueue
```
```
In fs/proc/stat.c (ffff8000104481c8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In lib/percpu_counter.c (ffff80001065e988)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffff8000114987f0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffff800010957f6c)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/xen-netfront.c (ffff80001149bfd4)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netif_init
```
```
In drivers/usb/host/xhci.c (ffff800010a6d85c)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In net/core/dev.c (ffff800010bc613c)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In lib/cpumask.c (ffff800010d845c0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
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
In arch/arm/kernel/reboot.c (c030d2e0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/arm/kernel/reboot.c:soft_restart
```
```
In arch/arm/kernel/hibernate.c (c0311e34)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/arm/kernel/hibernate.c:save_processor_state
```
```
In arch/arm/kernel/smp.c (c03138fc)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:smp_send_stop
  - arch/arm/kernel/smp.c:smp_send_stop
  - arch/arm/kernel/smp.c:smp_cpus_done
```
```
In arch/arm/kernel/machine_kexec.c (c031549c)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/arm/kernel/machine_kexec.c:machine_kexec
```
```
In arch/arm/mm/l2c-common.c (c0323038)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/arm/mm/l2c-common.c:outer_disable
```
```
In arch/arm/mach-imx/cpuidle-imx6q.c (c0332358)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/arm/mach-imx/cpuidle-imx6q.c:imx6q_enter_wait
  - arch/arm/mach-imx/cpuidle-imx6q.c:imx6q_enter_wait
```
```
In arch/arm/mach-tegra/cpuidle-tegra30.c (c034c760)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/arm/mach-tegra/cpuidle-tegra30.c:tegra30_idle_lp2
```
```
In kernel/cpu.c (c0357e9c)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/fair.c (c0399df0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/membarrier.c (c03b2758)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
```
```
In kernel/power/swap.c (c03c1448)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk_safe.c (c03c8bb8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/rcu/tree.c (c03dbbf4)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/tick-common.c (c03fc940)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/smp.c (c1523898)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (c0428bd8)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In kernel/debug/debug_core.c (c043a174)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/trace.c (c046454c)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/events/core.c (c04cc880)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/page-writeback.c (c04ea028)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (c0501e40)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/vmalloc.c (c0529e0c)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/swap_slots.c (c05406e8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/slub.c (c054a480)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/io_uring.c (c05d668c)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (c1537ef0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/verity/verify.c (c15381a8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_init_workqueue
```
```
In fs/proc/stat.c (c060d028)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In lib/percpu_counter.c (c0808268)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In drivers/usb/host/xhci.c (c0b41ee8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/cpuidle/cpuidle-exynos.c (c0c05e94)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In net/core/dev.c (c0ce17dc)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In lib/cpumask.c (c0e7fabc)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
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
In arch/powerpc/kernel/crash.c (c0000000000707ec)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/powerpc/xmon/xmon.c (c000000000110ad0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:xmon_core
```
```
In kernel/cpu.c (c000000000140c9c)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/fair.c (c00000000019eac0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/membarrier.c (c0000000001bda18)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/printk/printk_safe.c (c0000000001d0690)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/rcu/tree.c (c0000000001e8d7c)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/tick-common.c (c0000000002176a0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/smp.c (c00000000136e9a0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (c0000000002596d8)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In kernel/debug/debug_core.c (c000000000271a84)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/trace.c (c0000000002acff4)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/events/core.c (c00000000034da10)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/page-writeback.c (c000000000376a98)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (c00000000039b858)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/vmalloc.c (c0000000003df148)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/swap_slots.c (c000000000400c90)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/slub.c (c000000000423360)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/io_uring.c (c00000000050fac4)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (c00000000138b230)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/verity/verify.c (c00000000138b5d4)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_init_workqueue
```
```
In fs/proc/stat.c (c00000000055e6bc)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In lib/percpu_counter.c (c0000000008117f0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In drivers/nvdimm/region.c (c000000000a06350)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/usb/host/xhci.c (c000000000b418e0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In net/core/dev.c (c000000000ca0d08)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In lib/cpumask.c (c000000000ec3860)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
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
In arch/riscv/kernel/smp.c (ffffffe0000b804a)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/riscv/kernel/smp.c:smp_send_stop
  - arch/riscv/kernel/smp.c:smp_send_stop
  - arch/riscv/kernel/smp.c:smp_send_stop
```
```
In kernel/sched/fair.c (ffffffe0000f57ac)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/membarrier.c (ffffffe000108634)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
```
```
In kernel/printk/printk_safe.c (ffffffe000111eb8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/rcu/tree.c (ffffffe000122306)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/smp.c (ffffffe00000ab02)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffe00015db00)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In kernel/trace/trace.c (ffffffe000181ad0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/events/core.c (ffffffe0001ce0b4)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/page-writeback.c (ffffffe0001e084c)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffe0001f4efe)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_normal_threshold
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/vmalloc.c (ffffffe00021513e)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmalloc.c:lazy_max_pages
```
```
In mm/swap_slots.c (ffffffe000229164)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/slub.c (ffffffe000238e54)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/io_uring.c (ffffffe0002b0952)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (ffffffe00001c940)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/verity/verify.c (ffffffe00001cbd4)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_init_workqueue
```
```
In fs/proc/stat.c (ffffffe0002ddd5e)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In lib/percpu_counter.c (ffffffe00048c2fe)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/percpu_counter.c:compute_batch_value
```
```
In drivers/nvdimm/region.c (ffffffe0005c6e96)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/usb/host/xhci.c (ffffffe000686cc2)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In net/core/dev.c (ffffffe00075290e)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In lib/cpumask.c (ffffffe0008aeab6)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
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
In arch/x86/xen/smp.c (ffffffff8102cacd)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/alternative.c (ffffffff8103af03)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff8103c3e0)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81043d3c)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e92a)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810565ae)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106234f)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81062942)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81062df2)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff828a44c4)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810674f1)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/ipi.c:apic_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106d700)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:run_sync
```
```
In arch/x86/mm/pageattr.c (ffffffff828ae1c9)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108ba8b)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff8109df60)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/fair.c (ffffffff810e5f95)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/membarrier.c (ffffffff810faa7a)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/power/swap.c (ffffffff81106b01)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk_safe.c (ffffffff8110dd33)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/rcu/tree.c (ffffffff8111fd32)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/smp.c (ffffffff828ba20d)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff8116c90d)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In kernel/debug/debug_core.c (ffffffff8117cd55)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/trace.c (ffffffff811a2776)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/events/core.c (ffffffff8120b3a8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/page-writeback.c (ffffffff8122720f)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff8123ff11)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/vmalloc.c (ffffffff8127047e)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/swap_slots.c (ffffffff8128624b)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/slub.c (ffffffff8129d131)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/io_uring.c (ffffffff8133d3bd)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (ffffffff828cf485)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/verity/verify.c (ffffffff828cf6b3)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_init_workqueue
```
```
In fs/proc/stat.c (ffffffff81374035)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In lib/percpu_counter.c (ffffffff8154b310)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In drivers/acpi/acpi_processor.c (ffffffff815d4d93)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff81604b4e)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/block/xen-blkfront.c (ffffffff828f0d20)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff8170b1a8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/xen-netfront.c (ffffffff828f410a)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netif_init
```
```
In drivers/usb/host/xhci.c (ffffffff817e971b)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8186e148)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In net/core/dev.c (ffffffff818c9aca)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In lib/cpumask.c (ffffffff81a4d090)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
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
In arch/x86/kernel/alternative.c (ffffffff8102a713)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff8102bca0)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff8103336c)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103ddee)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810467be)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810527df)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81052d1c)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff810530a2)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff8289c606)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810578b1)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/ipi.c:apic_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In arch/x86/kernel/ftrace.c (ffffffff8105db30)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:run_sync
```
```
In arch/x86/mm/pageattr.c (ffffffff828a63bb)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107a5ab)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff8108c980)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/fair.c (ffffffff810d5135)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/membarrier.c (ffffffff810eacd9)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/power/swap.c (ffffffff810f79e9)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk_safe.c (ffffffff810fea93)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/rcu/tree.c (ffffffff81111732)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/tick-common.c (ffffffff811325fa)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/smp.c (ffffffff828b28a0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff8115facd)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In kernel/debug/debug_core.c (ffffffff8116fed5)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/trace.c (ffffffff81195746)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/events/core.c (ffffffff811fe178)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/page-writeback.c (ffffffff8121a37f)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff81232f11)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/vmalloc.c (ffffffff812623ee)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/swap_slots.c (ffffffff812780ab)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/slub.c (ffffffff8128ecc1)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/io_uring.c (ffffffff8132e07d)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (ffffffff828c7ba1)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/verity/verify.c (ffffffff828c7dcf)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_init_workqueue
```
```
In fs/proc/stat.c (ffffffff81364b05)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In lib/percpu_counter.c (ffffffff8153b5f0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In drivers/acpi/acpi_processor.c (ffffffff815be953)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff815efcbe)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/nvdimm/region.c (ffffffff816dec28)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/scsi/storvsc_drv.c (ffffffff81713a00)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/scsi/storvsc_drv.c:storvsc_probe
  - drivers/scsi/storvsc_drv.c:storvsc_channel_init
```
```
In drivers/usb/host/xhci.c (ffffffff817ae82b)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81837768)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In net/core/dev.c (ffffffff81883a0a)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In lib/cpumask.c (ffffffff81a0a1c0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
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
In arch/x86/xen/smp.c (ffffffff8102c92d)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/alternative.c (ffffffff8103ad63)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff8103c240)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81043b7c)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e77a)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810569de)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810627ff)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff81062df2)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff810632a2)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b73d4)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810679a1)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/ipi.c:apic_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106dbb0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:run_sync
```
```
In arch/x86/mm/pageattr.c (ffffffff828c10c8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108ba3b)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In kernel/cpu.c (ffffffff8109df10)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/fair.c (ffffffff810e2365)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/membarrier.c (ffffffff810f7c3a)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/power/swap.c (ffffffff811049f9)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk_safe.c (ffffffff8110bc23)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/rcu/tree.c (ffffffff8111dc22)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/tick-common.c (ffffffff8113d72a)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/smp.c (ffffffff828ccf90)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff8116a6dd)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In kernel/debug/debug_core.c (ffffffff8117ab25)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/trace.c (ffffffff811a0546)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/events/core.c (ffffffff81209148)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/page-writeback.c (ffffffff81224faf)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff8123dcb1)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/vmalloc.c (ffffffff8126e21e)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/swap_slots.c (ffffffff8128405b)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/slub.c (ffffffff8129af41)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/io_uring.c (ffffffff8133ae8d)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (ffffffff828e2205)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/verity/verify.c (ffffffff828e2433)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_init_workqueue
```
```
In fs/proc/stat.c (ffffffff81371b05)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In lib/percpu_counter.c (ffffffff81547050)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In drivers/acpi/acpi_processor.c (ffffffff815d701b)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff8162963e)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/block/xen-blkfront.c (ffffffff82904872)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff81749f78)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/xen-netfront.c (ffffffff82907b8c)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netif_init
```
```
In drivers/usb/host/xhci.c (ffffffff818261bb)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818beed8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In net/core/dev.c (ffffffff8191aaca)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In lib/cpumask.c (ffffffff81ab9480)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
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
In arch/x86/xen/smp.c (ffffffff8102d71d)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
```
```
In arch/x86/kernel/alternative.c (ffffffff8103bd63)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
```
```
In arch/x86/kernel/tsc.c (ffffffff8103d290)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/tboot.c (ffffffff81044f7c)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104fbba)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81057a0e)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81063dbf)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_power_init_bm_check
```
```
In arch/x86/kernel/reboot.c (ffffffff810643b2)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff81064862)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b74d5)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81068f81)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:native_send_call_func_ipi
  - arch/x86/kernel/apic/ipi.c:apic_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:apic_smt_update
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106e9a3)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:x2apic_get_apic_id
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106fe30)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:run_sync
```
```
In arch/x86/mm/pageattr.c (ffffffff828c4213)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108dd9b)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109b499)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810a5e15)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:_cpu_down
```
```
In kernel/sched/fair.c (ffffffff810edf05)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_max_interval
  - kernel/sched/fair.c:get_update_sysctl_factor
```
```
In kernel/sched/membarrier.c (ffffffff81102d7a)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/power/swap.c (ffffffff8110fdd9)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
```
```
In kernel/printk/printk_safe.c (ffffffff81117133)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_flush_on_panic
```
```
In kernel/rcu/tree.c (ffffffff8112c825)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_scheduler_starting
```
```
In kernel/time/tick-common.c (ffffffff8114a22a)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/smp.c (ffffffff828d238a)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
  - kernel/smp.c:smp_init
```
```
In kernel/stop_machine.c (ffffffff81177e4d)
Location: include/linux/cpumask.h:110
Inline: True
```
```
In kernel/debug/debug_core.c (ffffffff81188455)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/trace/trace.c (ffffffff811ae2d6)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/trace/trace.c:print_trace_header
  - kernel/trace/trace.c:print_event_info
```
```
In kernel/events/core.c (ffffffff81217ed8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
```
```
In mm/page-writeback.c (ffffffff8123428f)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/page-writeback.c:writeback_set_ratelimit
```
```
In mm/vmstat.c (ffffffff8124d3e1)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:calculate_pressure_threshold
```
```
In mm/vmalloc.c (ffffffff8127dbdc)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:set_iounmap_nonlazy
```
```
In mm/swap_slots.c (ffffffff81293d3b)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
```
In mm/slub.c (ffffffff812aae21)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In fs/io_uring.c (ffffffff8134e03d)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (ffffffff828e761b)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_init
```
```
In fs/verity/verify.c (ffffffff828e7849)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_init_workqueue
```
```
In fs/proc/stat.c (ffffffff813854e5)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - fs/proc/stat.c:stat_open
```
```
In lib/percpu_counter.c (ffffffff81560c10)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_cpu_dead
```
```
In drivers/acpi/acpi_processor.c (ffffffff815f0edb)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
```
In drivers/acpi/processor_idle.c (ffffffff816434de)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/block/xen-blkfront.c (ffffffff8290a5b1)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlblk_init
```
```
In drivers/nvdimm/region.c (ffffffff817653f8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/net/xen-netfront.c (ffffffff8290d7f3)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netif_init
```
```
In drivers/usb/host/xhci.c (ffffffff8184009b)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818db1e8)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In net/core/dev.c (ffffffff8193bcda)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
```
In lib/cpumask.c (ffffffff81ac58d0)
Location: include/linux/cpumask.h:110
Inline: True
Inline callers:
  - lib/cpumask.c:cpumask_local_spread
```
</details>
</li>
</ul>

## Differences
