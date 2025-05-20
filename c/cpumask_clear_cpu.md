# Function: <code>cpumask_clear_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void cpumask_clear_cpu(int cpu, struct cpumask *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff8100863e)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
  - arch/x86/events/amd/uncore.c:uncore_dead
```
```
In arch/x86/xen/mmu.c (ffffffff81021c32)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
```
```
In arch/x86/kernel/irq.c (ffffffff81030c9d)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/process.c (ffffffff81039676)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:amd_e400_remove_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044eba)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
```
```
In arch/x86/kernel/smp.c (ffffffff8105086f)
Location: include/linux/cpumask.h:280
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff81051d01)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055aea)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a135)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:update_clusterinfo
  - arch/x86/kernel/apic/x2apic_cluster.c:update_clusterinfo
```
```
In arch/x86/mm/tlb.c (ffffffff8107250e)
Location: include/linux/cpumask.h:280
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810747d6)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff81074c5f)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In kernel/cpu.c (ffffffff81081ae8)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/cpu.c:set_cpu_possible
  - kernel/cpu.c:set_cpu_present
  - kernel/cpu.c:set_cpu_online
  - kernel/cpu.c:set_cpu_active
```
```
In kernel/workqueue.c (ffffffff81097663)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (ffffffff810a6846)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_domains_numa_masks_update
  - kernel/sched/core.c:rq_attach_root
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:idle_task_exit
```
```
In kernel/sched/fair.c (ffffffff810b4784)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:trigger_load_balance
```
```
In kernel/sched/rt.c (ffffffff810c044b)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810c1b8c)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810c4210)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810c47b4)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
```
```
In kernel/irq/chip.c (ffffffff810de324)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/profile.c (ffffffff810ea6f5)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - kernel/profile.c:profile_cpu_callback
```
```
In kernel/time/tick-broadcast.c (ffffffff810fcd20)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
Direct callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
```
```
In kernel/smp.c (ffffffff81103cb0)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/padata.c (ffffffff8118aa07)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/page_alloc.c (ffffffff81192c34)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In mm/vmstat.c (ffffffff811ad849)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpuup_callback
```
```
In mm/mmu_context.c (ffffffff811afca0)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In fs/exec.c (ffffffff812137cc)
Location: include/linux/cpumask.h:280
Inline: True
```
```
In lib/nmi_backtrace.c (ffffffff813edad0)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
Direct callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
```
In lib/percpu_ida.c (ffffffff813ffb0b)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/base/cacheinfo.c (ffffffff815524f9)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:free_cache_attributes
  - drivers/base/cacheinfo.c:free_cache_attributes
  - drivers/base/cacheinfo.c:cacheinfo_cpu_callback
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816b0313)
Location: include/linux/cpumask.h:280
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_offline_prepare
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
```
**Symbols:**

```
ffffffff810fcd20-ffffffff810fcd2d: cpumask_clear_cpu (STB_LOCAL)
ffffffff813edad0-ffffffff813edae1: cpumask_clear_cpu.constprop.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void cpumask_clear_cpu(int cpu, struct cpumask *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff81008ee1)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/xen/mmu.c (ffffffff81020f5d)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
```
```
In arch/x86/xen/smp.c (ffffffff8102a030)
Location: include/linux/cpumask.h:284
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:stop_self
```
```
In arch/x86/kernel/irq.c (ffffffff8102fd39)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/process.c (ffffffff81038666)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:amd_e400_remove_cpu
Direct callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044e66)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff8104fb26)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smp.c (ffffffff81050a73)
Location: include/linux/cpumask.h:284
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff810525d4)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_cpu_up
Direct callers:
  - arch/x86/kernel/smpboot.c:prefill_possible_map
  - arch/x86/kernel/smpboot.c:smp_init_package_map
  - arch/x86/kernel/smpboot.c:smp_init_package_map
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:284
Inline: False
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055d08)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a37f)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/mm/tlb.c (ffffffff81072484)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81075db3)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff8107625f)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In kernel/cpu.c (ffffffff81084b04)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/workqueue.c (ffffffff8109ad50)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (ffffffff810b29b9)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:rq_attach_root
```
```
In kernel/sched/fair.c (ffffffff810c0e77)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810c4a91)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810c5f08)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810c7f06)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810c84d6)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/irq/chip.c (ffffffff810e3c74)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/profile.c (ffffffff810f1372)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff811050a8)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
Direct callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
```
```
In kernel/smp.c (ffffffff8110b0c9)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/padata.c (ffffffff8119d049)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/page_alloc.c (ffffffff811a8af1)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In lib/nmi_backtrace.c (ffffffff81433e54)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
Direct callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
```
In lib/percpu_ida.c (ffffffff814471fc)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81514e05)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cacheinfo.c (ffffffff815a48f9)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_cpu_callback
  - drivers/base/cacheinfo.c:free_cache_attributes
  - drivers/base/cacheinfo.c:free_cache_attributes
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81712eac)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
**Symbols:**

```
ffffffff8102a030-ffffffff8102a03d: cpumask_clear_cpu (STB_LOCAL)
ffffffff81037e30-ffffffff81037e3d: cpumask_clear_cpu (STB_LOCAL)
ffffffff81051040-ffffffff8105104d: cpumask_clear_cpu (STB_LOCAL)
ffffffff81104080-ffffffff8110408d: cpumask_clear_cpu (STB_LOCAL)
ffffffff81433d10-ffffffff81433d21: cpumask_clear_cpu.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cpumask_clear_cpu(int cpu, struct cpumask *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff81008f21)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/xen/mmu.c (ffffffff81021711)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_flush_tlb_others
```
```
In arch/x86/xen/smp.c (ffffffff8102a780)
Location: include/linux/cpumask.h:284
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:stop_self
  - arch/x86/xen/smp.c:xen_smp_prepare_cpus
```
```
In arch/x86/kernel/irq.c (ffffffff8102fd27)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/process.c (ffffffff81037ff7)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff8104311e)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045ee9)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81052296)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smp.c (ffffffff8105332f)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054ed7)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:284
Inline: False
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81058aa9)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d149)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/mm/tlb.c (ffffffff81076015)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107997b)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff81079e4f)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In kernel/cpu.c (ffffffff81089a94)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/workqueue.c (ffffffff810a12c9)
Location: include/linux/cpumask.h:284
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b8fa9)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:rq_attach_root
```
```
In kernel/sched/fair.c (ffffffff810c6e63)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810caae5)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810cbec2)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810cdeec)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810ce4d6)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/irq/chip.c (ffffffff810ea7a4)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (ffffffff810efcb1)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff810f82d1)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8110c7f8)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
Direct callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
```
```
In kernel/smp.c (ffffffff81112a9f)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/padata.c (ffffffff811ac8ba)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/page_alloc.c (ffffffff811b9093)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In lib/nmi_backtrace.c (ffffffff8144ffd3)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/percpu_ida.c (ffffffff81465a2d)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81541297)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cacheinfo.c (ffffffff815d2ab5)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:free_cache_attributes
  - drivers/base/cacheinfo.c:free_cache_attributes
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81744cea)
Location: include/linux/cpumask.h:284
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
```
**Symbols:**

```
ffffffff8102a780-ffffffff8102a78d: cpumask_clear_cpu (STB_LOCAL)
ffffffff8110b780-ffffffff8110b78d: cpumask_clear_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cpumask_clear_cpu(int cpu, struct cpumask *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff81008c61)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023cc6)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/smp_pv.c (ffffffff81029160)
Location: include/linux/cpumask.h:307
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/kernel/irq.c (ffffffff8102e114)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
  - arch/x86/kernel/irq.c:check_irq_vectors_for_cpu_disable
```
```
In arch/x86/kernel/process.c (ffffffff81036187)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81041280)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045bcc)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81051e66)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smp.c (ffffffff81052ee9)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff810547cd)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:307
Inline: False
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8190ece5)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c5b7)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/mm/tlb.c (ffffffff81074746)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81078229)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff810786ff)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In kernel/cpu.c (ffffffff810869a4)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/workqueue.c (ffffffff8109f262)
Location: include/linux/cpumask.h:307
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b3b32)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/sched/fair.c (ffffffff810c0a67)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810c45cb)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810c59db)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810ca859)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810cadd6)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffffffff810cc219)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/chip.c (ffffffff810e9e94)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (ffffffff810efc8b)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff810fa301)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8110e6c8)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
Direct callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
```
```
In kernel/events/core.c (ffffffff811a0d8c)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/padata.c (ffffffff811b3f85)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/page_alloc.c (ffffffff811c0fe7)
Location: include/linux/cpumask.h:307
Inline: True
```
```
In lib/percpu_ida.c (ffffffff8146a7de)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81555126)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cacheinfo.c (ffffffff815e762f)
Location: include/linux/cpumask.h:307
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817633aa)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In lib/nmi_backtrace.c (ffffffff818efd69)
Location: include/linux/cpumask.h:307
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81029160-ffffffff8102916d: cpumask_clear_cpu (STB_LOCAL)
ffffffff8110d670-ffffffff8110d67d: cpumask_clear_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cpumask_clear_cpu(int cpu, struct cpumask *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff810090f1)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102484a)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/smp_pv.c (ffffffff81029370)
Location: include/linux/cpumask.h:311
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In arch/x86/kernel/process.c (ffffffff81038515)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81044670)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810493ec)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81055ad6)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smp.c (ffffffff81056c0c)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff810585be)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:311
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106070a)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/mm/tlb.c (ffffffff8107a44c)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107e585)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff8107ea5f)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In kernel/cpu.c (ffffffff8108d75b)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/workqueue.c (ffffffff810a5952)
Location: include/linux/cpumask.h:311
Inline: True
```
```
In kernel/sched/core.c (ffffffff810badd2)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/sched/fair.c (ffffffff810c8108)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810cb9a6)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810cd0db)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810d2069)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810d2576)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffffffff810d4ad9)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/chip.c (ffffffff810f23eb)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (ffffffff810f8864)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In kernel/profile.c (ffffffff81104c81)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff81119948)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
Direct callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
```
```
In kernel/events/core.c (ffffffff811b468c)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/padata.c (ffffffff811c7c15)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/page_alloc.c (ffffffff811d55d2)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In lib/percpu_ida.c (ffffffff81496abc)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/xen/cpu_hotplug.c (ffffffff815b8c8a)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cacheinfo.c (ffffffff8164e9f5)
Location: include/linux/cpumask.h:311
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817d935a)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In lib/nmi_backtrace.c (ffffffff819761a9)
Location: include/linux/cpumask.h:311
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81029370-ffffffff8102937d: cpumask_clear_cpu (STB_LOCAL)
ffffffff81118900-ffffffff8111890d: cpumask_clear_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void cpumask_clear_cpu(int cpu, struct cpumask *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff81009703)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102576d)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/smp_pv.c (ffffffff81029dd0)
Location: include/linux/cpumask.h:313
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102c063)
Location: include/linux/cpumask.h:313
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81039a35)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810468b5)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104bc49)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81058959)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smp.c (ffffffff81059a80)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105b228)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:313
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810637d7)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/mm/tlb.c (ffffffff8107d1ec)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810815f5)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff81081b9c)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In kernel/cpu.c (ffffffff810912e4)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/workqueue.c (ffffffff810ab84a)
Location: include/linux/cpumask.h:313
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c22b2)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/sched/fair.c (ffffffff810d00d9)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810d32d3)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810d4b94)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810da0f7)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810da655)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffffffff810dc6b3)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/chip.c (ffffffff810fa837)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (ffffffff81100942)
Location: include/linux/cpumask.h:313
Inline: True
```
```
In kernel/profile.c (ffffffff8110fa11)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff811264b8)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/events/core.c (ffffffff811d369c)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/padata.c (ffffffff811e7e55)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/page_alloc.c (ffffffff811f6a22)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In lib/percpu_ida.c (ffffffff814cbe2a)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - lib/percpu_ida.c:percpu_ida_alloc
```
```
In drivers/xen/cpu_hotplug.c (ffffffff815f121a)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cacheinfo.c (ffffffff8168a153)
Location: include/linux/cpumask.h:313
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81821f1a)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In lib/nmi_backtrace.c (ffffffff819d2a49)
Location: include/linux/cpumask.h:313
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
Direct callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff81029dd0-ffffffff81029ddd: cpumask_clear_cpu (STB_LOCAL)
ffffffff819d28f0-ffffffff819d2901: cpumask_clear_cpu.constprop.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void cpumask_clear_cpu(int cpu, struct cpumask *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff81009723)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81024e0d)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a3b0)
Location: include/linux/cpumask.h:325
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102d063)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8103af65)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81049329)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81055846)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff8105e579)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smp.c (ffffffff8105f6fc)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_send_call_func_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff81060ea8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:325
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810694d7)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/kvm.c (ffffffff81072ebe)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/tlb.c (ffffffff81083c0e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81088205)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff810887ac)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In kernel/cpu.c (ffffffff810995c4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/workqueue.c (ffffffff810b4b10)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In kernel/sched/core.c (ffffffff810cb5c5)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/sched/fair.c (ffffffff810d9900)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810dcf73)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810de9e4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810e3c47)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810e41a5)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffffffff810e6313)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/chip.c (ffffffff81105ff7)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (ffffffff8110c101)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In kernel/profile.c (ffffffff8111b101)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff81131b98)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_shutdown_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/events/core.c (ffffffff811e3a3c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/padata.c (ffffffff811f8e25)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/page_alloc.c (ffffffff81208dba)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8160be5a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cacheinfo.c (ffffffff816a9653)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8184dd9a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In lib/nmi_backtrace.c (ffffffff81a0c0c9)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
Direct callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff8102a3b0-ffffffff8102a3bd: cpumask_clear_cpu (STB_LOCAL)
ffffffff81a0bf70-ffffffff81a0bf81: cpumask_clear_cpu.constprop.2 (STB_LOCAL)
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
In arch/x86/events/amd/uncore.c (ffffffff81009bd8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027024)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102c37e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102ee43)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8103d577)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c594)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058a97)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81061989)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff810644b5)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106c937)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff81076a3e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/tlb.c (ffffffff810878ba)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108be53)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff8108c3dc)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In kernel/cpu.c (ffffffff8109d8df)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/workqueue.c (ffffffff810ba902)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d35d5)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/sched/fair.c (ffffffff810e1fb2)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810e3f31)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810e5b64)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810ea85e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810eada5)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffffffff810ecf5b)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/chip.c (ffffffff8110f497)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (ffffffff8111587a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff811257e0)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8113b83a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/events/core.c (ffffffff811fabfe)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/padata.c (ffffffff81210b72)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:__padata_remove_cpu
  - kernel/padata.c:__padata_remove_cpu
```
```
In mm/page_alloc.c (ffffffff81270108)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8163fcdb)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cacheinfo.c (ffffffff816e2c57)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff816f1c9a)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81890e69)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In lib/nmi_backtrace.c (ffffffff81a7ba4e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
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
In arch/x86/events/amd/uncore.c (ffffffff81009fc8)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027604)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/smp_pv.c (ffffffff828a860c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f753)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cf54)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059367)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81062219)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064b35)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e093)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff81077aae)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/tlb.c (ffffffff810885aa)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108cac3)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff8108d03c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81099af7)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810a3e1b)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/workqueue.c (ffffffff810c0d52)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In kernel/sched/core.c (ffffffff810ddb45)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/sched/fair.c (ffffffff810ebeb2)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810eebb4)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810f0f94)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810f622e)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810f6775)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffffffff810f89fb)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/chip.c (ffffffff8111b757)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (ffffffff81121ccc)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff811317b0)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8114744a)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/events/core.c (ffffffff81207cce)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/padata.c (ffffffff8121df72)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/page_alloc.c (ffffffff8127ef48)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8166229b)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cacheinfo.c (ffffffff81706e07)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff8171641a)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c2f49)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In lib/nmi_backtrace.c (ffffffff81ab2dae)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
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
In arch/x86/events/amd/uncore.c (ffffffff8100b1a6)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810289db)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/smp_pv.c (ffffffff82ccdd52)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_filter_cpu_maps
  - arch/x86/xen/smp_pv.c:set_cpu_possible
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81031bc3)
Location: include/linux/cpumask.h:348
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105246f)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105e581)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff810681c9)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b49a)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:348
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075543)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff8107ed80)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/tlb.c (ffffffff8108afe6)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093ceb)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff8109467c)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ebda)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_cleanup_mask
```
```
In kernel/cpu.c (ffffffff810aaebc)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/workqueue.c (ffffffff810c84b7)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (ffffffff810e6305)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/sched/fair.c (ffffffff810f64e5)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_exit_idle
```
```
In kernel/sched/rt.c (ffffffff810f8be8)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810fa3e7)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810ffb7e)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
```
In kernel/sched/cpudeadline.c (ffffffff81100105)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffffffff811028ab)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/chip.c (ffffffff81127a07)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (ffffffff8112df9d)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/profile.c (ffffffff81140b21)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff811575bd)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/events/core.c (ffffffff81230a1e)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In mm/page_alloc.c (ffffffff812b1118)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In lib/nmi_backtrace.c (ffffffff815ed64f)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/xen/cpu_hotplug.c (ffffffff817116a7)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/base/cacheinfo.c (ffffffff817c1b81)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
```
```
In drivers/base/power/domain.c (ffffffff817d204a)
Location: include/linux/cpumask.h:348
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81995319)
Location: include/linux/cpumask.h:348
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
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
In arch/x86/events/amd/uncore.c (ffffffff8100a136)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102955b)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/smp_pv.c (ffffffff82fb9b82)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_filter_cpu_maps
  - arch/x86/xen/smp_pv.c:set_cpu_possible
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810328a3)
Location: include/linux/cpumask.h:354
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105164f)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105caae)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81069ec9)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d10a)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:354
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075b83)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e9b0)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/tlb.c (ffffffff8108b0f5)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8109323b)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff81093a7c)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a733)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_cleanup_mask
```
```
In kernel/cpu.c (ffffffff810a674c)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/workqueue.c (ffffffff810c3609)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (ffffffff810e40d4)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/sched/fair.c (ffffffff810f4655)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_exit_idle
```
```
In kernel/sched/rt.c (ffffffff810f6df8)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810f883e)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810fe657)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
```
In kernel/sched/cpudeadline.c (ffffffff810fec65)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff811014cb)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/chip.c (ffffffff81123607)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (ffffffff81129b8d)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/profile.c (ffffffff8113ce51)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8115368d)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/events/core.c (ffffffff8123a64e)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In mm/page_alloc.c (ffffffff812b9d48)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - mm/page_alloc.c:__drain_all_pages
```
```
In lib/nmi_backtrace.c (ffffffff81bf4c43)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8172e3d7)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/base/cacheinfo.c (ffffffff817d6da1)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
```
```
In drivers/base/power/domain.c (ffffffff817e685a)
Location: include/linux/cpumask.h:354
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff819999c9)
Location: include/linux/cpumask.h:354
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
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
In arch/x86/events/amd/uncore.c (ffffffff8100a8b6)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/events/intel/core.c (ffffffff81010502)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dead
```
```
In arch/x86/xen/smp_pv.c (ffffffff831c4260)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:set_cpu_possible
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81033d03)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052ebf)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d40e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff8106a999)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106dbaa)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81076633)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff8107fe80)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/tlb.c (ffffffff8108bc37)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093c3b)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff8109443c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109b582)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810a747c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
```
```
In kernel/workqueue.c (ffffffff810c4385)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (ffffffff810e60ac)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/sched/fair.c (ffffffff810f6615)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_exit_idle
```
```
In kernel/sched/rt.c (ffffffff810f8948)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810fab3e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff81100a3c)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
```
In kernel/sched/cpudeadline.c (ffffffff81101045)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff8110385b)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/chip.c (ffffffff81123967)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (ffffffff81129e27)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/profile.c (ffffffff8113e091)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff81154811)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/events/core.c (ffffffff8123ee9e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In mm/percpu.c (ffffffff831f0397)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/page_alloc.c (ffffffff812bedbe)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/page_alloc.c:__drain_all_pages
```
```
In lib/nmi_backtrace.c (ffffffff81be6b66)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81712077)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/base/cacheinfo.c (ffffffff817ba7ab)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
```
```
In drivers/base/power/domain.c (ffffffff817cac59)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197e4e9)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
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
In arch/x86/events/intel/core.c (ffffffff81011109)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dead
```
```
In arch/x86/xen/smp_pv.c (ffffffff832a4dd5)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:_get_smp_config
  - arch/x86/xen/smp_pv.c:set_cpu_possible
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105b405)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - arch/x86/kernel/cpu/mce/core.c:mce_start
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81066b0e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81075264)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff810793ba)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81083cde)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff8108ecc0)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/tlb.c (ffffffff8109b22a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810a3a1b)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff810a4371)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ab79b)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810b8eb8)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/workqueue.c (ffffffff810d6f77)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (ffffffff810fd2d2)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/sched/fair.c (ffffffff81110445)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_exit_idle
```
```
In kernel/sched/rt.c (ffffffff81113f28)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff81115b7e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff8111cae4)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
```
In kernel/sched/cpudeadline.c (ffffffff8111d1e5)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
  - kernel/sched/cpudeadline.c:cpudl_find
```
```
In kernel/sched/topology.c (ffffffff8112084b)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/chip.c (ffffffff81143f37)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (ffffffff8114a75f)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/profile.c (ffffffff81161365)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/clocksource.c (ffffffff8116d862)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff81179261)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/events/core.c (ffffffff812798b7)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In mm/percpu.c (ffffffff832d5bdb)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/page_alloc.c (ffffffff81301908)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - mm/page_alloc.c:__drain_all_pages
```
```
In fs/io-wq.c (ffffffff81cc5f6b)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In lib/nmi_backtrace.c (ffffffff81cdf47d)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8178eae7)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/base/cacheinfo.c (ffffffff8184456a)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
```
```
In drivers/base/power/domain.c (ffffffff81854d29)
Location: include/linux/cpumask.h:325
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a2763e)
Location: include/linux/cpumask.h:325
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
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
In arch/x86/events/intel/core.c (ffffffff81012843)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dead
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103b820)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810672f7)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8107383e)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81083c14)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81088226)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:360
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81093d3e)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff8109f805)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/tlb.c (ffffffff810ae3e6)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810b80fa)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff810b8b41)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c13db)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810cf816)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/workqueue.c (ffffffff810f3783)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (ffffffff81119ca0)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/sched/fair.c (ffffffff8112c578)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_exit_idle
```
```
In kernel/sched/build_policy.c (ffffffff8113675c)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:cpudl_clear_freecpu
  - kernel/sched/build_policy.c:cpudl_set
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:rq_offline_rt
```
```
In kernel/sched/build_utility.c (ffffffff8114ab32)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_domains_numa_masks_clear
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:cpupri_set
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
```
In kernel/irq/chip.c (ffffffff811679e7)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (ffffffff8116fbd0)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/profile.c (ffffffff81194175)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/clocksource.c (ffffffff811a1955)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff811ae3fe)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/events/core.c (ffffffff812cca8c)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In mm/percpu.c (ffffffff8348a474)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/page_alloc.c (ffffffff81368974)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - mm/page_alloc.c:__drain_all_pages
```
```
In io_uring/io-wq.c (ffffffff816d970f)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_affinity
```
```
In lib/nmi_backtrace.c (ffffffff81ea5c36)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In drivers/xen/cpu_hotplug.c (ffffffff818c6b04)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/base/cacheinfo.c (ffffffff819883f1)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
```
```
In drivers/base/power/domain.c (ffffffff8199b446)
Location: include/linux/cpumask.h:360
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81b52c13)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_offline
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b9076e)
Location: include/linux/cpumask.h:360
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink
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
In arch/x86/events/intel/core.c (ffffffff810167f3)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dead
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043ff0)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:_get_smp_config
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81076887)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81083c4e)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff810969d4)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109bc36)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:425
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a939e)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff810b7085)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/tlb.c (ffffffff810c86d6)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d37ec)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff810d43f1)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dddb3)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810edbaa)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/workqueue.c (ffffffff811158c3)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (ffffffff811415f0)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/sched/fair.c (ffffffff81156248)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_exit_idle
```
```
In kernel/sched/build_policy.c (ffffffff81160d8c)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:cpudl_clear_freecpu
  - kernel/sched/build_policy.c:cpudl_set
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:rq_offline_rt
```
```
In kernel/sched/build_utility.c (ffffffff811794c2)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_domains_numa_masks_clear
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:cpupri_set
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
```
In kernel/irq/chip.c (ffffffff8119bdf7)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (ffffffff811a6004)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_spread_init_one
```
```
In kernel/profile.c (ffffffff811d17e5)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/clocksource.c (ffffffff811e0b05)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff811eeb2e)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/events/core.c (ffffffff81334a81)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In mm/percpu.c (ffffffff83ebaee7)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/page_alloc.c (ffffffff813e5d42)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - mm/page_alloc.c:__drain_all_pages
```
```
In io_uring/io-wq.c (ffffffff817a55df)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_affinity
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81a17494)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/base/cacheinfo.c (ffffffff81af726b)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
```
```
In drivers/base/power/domain.c (ffffffff81b0c5f6)
Location: include/linux/cpumask.h:425
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81ceae63)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_offline
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d3097e)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink
```
```
In lib/nmi_backtrace.c (ffffffff82039105)
Location: include/linux/cpumask.h:425
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
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
In arch/x86/events/intel/core.c (ffffffff81016183)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dead
```
```
In arch/x86/xen/smp_pv.c (ffffffff81044158)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:_get_smp_config
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/process.c (ffffffff81060b3c)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106a2c5)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_offline
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81078b07)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810861ee)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81099af4)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smp.c (ffffffff8109b8de)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109cd1b)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:485
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810ac5fe)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff810ba23b)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/tlb.c (ffffffff810cbcac)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d6bcc)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff810d7931)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e93a8)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810f9c95)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/workqueue.c (ffffffff81122499)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (ffffffff81152356)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:sched_mm_cid_remote_clear
  - kernel/sched/core.c:sched_mm_cid_migrate_to
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:mm_cid_get
```
```
In kernel/sched/fair.c (ffffffff811663b3)
Location: include/linux/cpumask.h:485
Inline: True
```
```
In kernel/sched/build_policy.c (ffffffff811714dc)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:cpudl_clear_freecpu
  - kernel/sched/build_policy.c:cpudl_set
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:rq_offline_rt
```
```
In kernel/sched/build_utility.c (ffffffff8118a0b3)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_domains_numa_masks_clear
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:cpupri_set
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
```
In kernel/irq/chip.c (ffffffff811adc57)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/profile.c (ffffffff811e5a75)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/clocksource.c (ffffffff811f5065)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff8120325e)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/trace/trace.c (ffffffff8127b18e)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/trace/trace.c:close_pipe_on_cpu
```
```
In kernel/bpf/cpumask.c (ffffffff8135d7a1)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_clear_cpu
```
```
In kernel/events/core.c (ffffffff813657c1)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In mm/percpu.c (ffffffff836e350c)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/page_alloc.c (ffffffff8141aa72)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - mm/page_alloc.c:__drain_all_pages
```
```
In io_uring/io-wq.c (ffffffff817e65bf)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_affinity
```
```
In lib/group_cpus.c (ffffffff818e6a3f)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - lib/group_cpus.c:grp_spread_init_one
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81a60524)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/base/cacheinfo.c (ffffffff81b45540)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
```
```
In drivers/base/power/domain.c (ffffffff81b5a636)
Location: include/linux/cpumask.h:485
Inline: True
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81d53a73)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_offline
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d99bfe)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink
```
```
In lib/nmi_backtrace.c (ffffffff820b7415)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
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
In arch/x86/events/intel/core.c (ffffffff8101bcc3)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dead
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104a687)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:_get_smp_config
  - arch/x86/xen/smp_pv.c:_get_smp_config
```
```
In arch/x86/kernel/process.c (ffffffff81067bec)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81071795)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_offline
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810800b7)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d0ce)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff810a131f)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smp.c (ffffffff810a2e7e)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:native_stop_other_cpus
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a425b)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:485
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b32de)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff810c15eb)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/tlb.c (ffffffff810d433c)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810df3fc)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
```
In arch/x86/mm/numa.c (ffffffff810e01b1)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f15fb)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff811030a5)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_reset_state
```
```
In kernel/workqueue.c (ffffffff8112c350)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_pod_cpumask
```
```
In kernel/sched/core.c (ffffffff8115e208)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:sched_mm_cid_remote_clear
  - kernel/sched/core.c:sched_mm_cid_migrate_to
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:mm_cid_get
```
```
In kernel/sched/fair.c (ffffffff81173113)
Location: include/linux/cpumask.h:485
Inline: True
```
```
In kernel/sched/build_policy.c (ffffffff8117edec)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:cpudl_clear_freecpu
  - kernel/sched/build_policy.c:cpudl_set
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:rq_offline_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:dequeue_task_rt
```
```
In kernel/sched/build_utility.c (ffffffff811989b3)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_domains_numa_masks_clear
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:cpupri_set
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
```
In kernel/irq/chip.c (ffffffff811bd857)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/rcu/tree.c (ffffffff811def99)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_spawn_cpu_nocb_kthread
  - kernel/rcu/tree.c:rcu_nocb_cpu_deoffload
```
```
In kernel/profile.c (ffffffff811fb7c5)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/clocksource.c (ffffffff8120b205)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
```
```
In kernel/time/tick-broadcast.c (ffffffff8121981e)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/time/tick-sched.c (ffffffff839058bd)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_init
```
```
In kernel/trace/trace.c (ffffffff81295d6e)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/trace/trace.c:close_pipe_on_cpu
```
```
In kernel/bpf/cpumask.c (ffffffff81386541)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_clear_cpu
```
```
In kernel/events/core.c (ffffffff8138e8e1)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In mm/percpu.c (ffffffff83915d9c)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
```
```
In mm/page_alloc.c (ffffffff81447c72)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - mm/page_alloc.c:__drain_all_pages
```
```
In io_uring/io-wq.c (ffffffff8182c37f)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_worker_affinity
```
```
In lib/group_cpus.c (ffffffff8192da5f)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - lib/group_cpus.c:grp_spread_init_one
```
```
In drivers/pmdomain/core.c (ffffffff81aa2096)
Location: include/linux/cpumask.h:485
Inline: True
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81ab2d64)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:disable_hotplug_cpu
```
```
In drivers/base/cacheinfo.c (ffffffff81b9d5c0)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81e0a933)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_offline
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e5186e)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/cpufreq/cpufreq.c:remove_cpu_dev_symlink
```
```
In lib/nmi_backtrace.c (ffffffff821915c5)
Location: include/linux/cpumask.h:485
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
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
In arch/arm64/kernel/smp.c (ffff80001009d338)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:crash_smp_send_stop
  - arch/arm64/kernel/smp.c:smp_send_stop
  - arch/arm64/kernel/smp.c:cpu_die_early
```
```
In arch/arm64/mm/numa.c (ffff8000100b2164)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:numa_update_cpu
```
```
In virt/kvm/kvm_main.c (ffff8000100b8ae0)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:hardware_disable_nolock
  - virt/kvm/kvm_main.c:hardware_enable_nolock
```
```
In kernel/cpu.c (ffff8000100f9890)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/workqueue.c (ffff80001011d8f0)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (ffff80001013d3b4)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/sched/fair.c (ffff80001014c26c)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In kernel/sched/rt.c (ffff8000101502a4)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffff800010152bc8)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffff800010159f60)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffff80001015a824)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffff80001015d050)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/chip.c (ffff80001017f818)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (ffff800010187e78)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (ffff8000101988e8)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffff8000101b25e0)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/events/core.c (ffff800010295390)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/padata.c (ffff8000102aa52c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/page_alloc.c (ffff800010316cc0)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff80001067721c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline
```
```
In drivers/soc/fsl/qbman/qman.c (ffff8000108169ac)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman.c:qman_destroy_affine_portal
```
```
In drivers/xen/cpu_hotplug.c (ffff80001082b60c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cacheinfo.c (ffff8000108f42f4)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In drivers/base/power/domain.c (ffff800010909a28)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In drivers/base/arch_topology.c (ffff8000109207f0)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b1fec4)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/clocksource/arm_arch_timer.c (ffff800010b67898)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_dying_cpu
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b99b80)
Location: include/linux/cpumask.h:341
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
In arch/arm/kernel/smp.c (c03138ec)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:smp_send_stop
```
```
In arch/arm/kernel/devtree.c (0)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In arch/arm/common/bL_switcher.c (c0327510)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_active_store
  - arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus
  - arch/arm/common/bL_switcher.c:bL_switcher_halve_cpus
```
```
In arch/arm/mach-imx/platsmp.c (c150f434)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/arm/mach-imx/platsmp.c:imx_smp_init_cpus
```
```
In arch/arm/mach-omap2/omap-smp.c (0)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In arch/arm/mach-qcom/platsmp.c (c1518ed8)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/arm/mach-qcom/platsmp.c:qcom_smp_prepare_cpus
```
```
In kernel/cpu.c (c0357ae8)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In kernel/sched/core.c (c038d478)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/sched/fair.c (c0399e78)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In kernel/sched/rt.c (c039dfc8)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (c039fc84)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (c03a6d70)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (c03a74d0)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (c03a7d38)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/chip.c (c03cf9d0)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (c03d6900)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (c03e3ae0)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (c03fcd50)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/events/core.c (c04c31ec)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/padata.c (c04d8a7c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/mmu_context.c (0)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In mm/page_alloc.c (c0531234)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In fs/exec.c (0)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In drivers/base/cacheinfo.c (c09e08c4)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In drivers/base/power/domain.c (c09f1454)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In drivers/base/arch_topology.c (c0a05644)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
```
```
In drivers/cpufreq/cpufreq.c (c0bfaa74)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/cpuidle/coupled.c (c0c0533c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled
  - drivers/cpuidle/coupled.c:cpuidle_coupled_handle_poke
```
```
In drivers/firmware/qcom_scm-32.c (c0c36614)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-32.c:__qcom_scm_set_cold_boot_addr
```
```
In drivers/clocksource/arm_arch_timer.c (c0c4b33c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_dying_cpu
```
```
In lib/nmi_backtrace.c (c0e87458)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
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
In arch/powerpc/kernel/cacheinfo.c (c00000000002b278)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_offline
```
```
In arch/powerpc/kernel/setup-common.c (c00000000134a33c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
```
```
In arch/powerpc/kernel/watchdog.c (c000000000037508)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:stop_watchdog
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
```
```
In arch/powerpc/kernel/rtas.c (c00000000003cdb4)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas.c:rtas_cpu_state_change_mask
```
```
In arch/powerpc/kernel/smp.c (c000000000053f80)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:set_cpus_unrelated
  - arch/powerpc/kernel/smp.c:set_cpus_unrelated
  - arch/powerpc/kernel/smp.c:__smp_send_nmi_ipi
  - arch/powerpc/kernel/smp.c:smp_handle_nmi_ipi
```
```
In arch/powerpc/kernel/stacktrace.c (c000000000069620)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In arch/powerpc/mm/numa.c (c0000000000a3764)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:numa_update_cpu_topology
  - arch/powerpc/mm/numa.c:unmap_cpu_from_node
```
```
In arch/powerpc/platforms/pseries/smp.c (c0000000013639a8)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/smp.c:smp_init_pseries
  - arch/powerpc/platforms/pseries/smp.c:smp_setup_cpu
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000fa358)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In arch/powerpc/xmon/xmon.c (c000000000110d1c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:xmon_core
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011c7a8)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (c000000000120ed0)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_check_need_tlb_flush
```
```
In kernel/cpu.c (c00000000014077c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/workqueue.c (c000000000167b70)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_calc_node_cpumask
```
```
In kernel/sched/core.c (c00000000018c15c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/sched/fair.c (c00000000019eba8)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In kernel/sched/rt.c (c0000000001a3fb8)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (c0000000001a64d8)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (c0000000001ae228)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (c0000000001aeac8)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (c0000000001b1b30)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/chip.c (c0000000001da300)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (c0000000001e1bd0)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (c0000000001f8ed0)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (c000000000217d24)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/events/core.c (c00000000033ec78)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/padata.c (c00000000035dea0)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/page_alloc.c (c0000000003e9000)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In drivers/base/cacheinfo.c (c00000000098e250)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In drivers/base/power/domain.c (c0000000009a6e50)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (c000000000c1368c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In lib/nmi_backtrace.c (c000000000ecf05c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
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
In arch/riscv/kernel/smpboot.c (0)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In arch/riscv/kernel/smp.c (ffffffe0000b8064)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/riscv/kernel/smp.c:smp_send_stop
```
```
In arch/riscv/mm/cacheflush.c (ffffffe0000ba054)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/riscv/mm/cacheflush.c:flush_icache_mm
```
```
In arch/riscv/mm/context.c (ffffffe0000ba162)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/riscv/mm/context.c:switch_mm
  - arch/riscv/mm/context.c:switch_mm
```
```
In kernel/cpu.c (0)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In kernel/sched/core.c (ffffffe0000ec78a)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:set_rq_offline
```
```
In kernel/sched/fair.c (ffffffe0000f5852)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In kernel/sched/rt.c (ffffffe0000f87d2)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffe0000fa870)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffe0000ffa00)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffe000100094)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffffffe0001005fc)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/chip.c (ffffffe000117c2e)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (ffffffe00011d774)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffe0001298cc)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In mm/page_alloc.c (ffffffe00021cefc)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In drivers/base/cacheinfo.c (ffffffe000585876)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In drivers/base/power/domain.c (ffffffe00058eab2)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In drivers/base/arch_topology.c (ffffffe00059f1ec)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:remove_cpu_topology
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
In arch/x86/events/amd/uncore.c (ffffffff81009fc8)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027764)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/smp_pv.c (ffffffff8289661c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f8b3)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d0c4)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058ee7)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81061d99)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064625)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d033)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff81076aae)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/tlb.c (ffffffff810875aa)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108ba83)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff8108bffc)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In kernel/cpu.c (ffffffff8109d73b)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/workqueue.c (ffffffff810bb0c2)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d7d35)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/sched/fair.c (ffffffff810e6012)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810e83c1)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810ea394)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810ef62e)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810efb75)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffffffff810f1dfb)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/chip.c (ffffffff81113d37)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (ffffffff8111a2ac)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff81129f60)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8113fa6a)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/events/core.c (ffffffff812002ee)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/padata.c (ffffffff812165c2)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/page_alloc.c (ffffffff81277598)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8162810b)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cacheinfo.c (ffffffff816cc557)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff816dc74a)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81867669)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In lib/nmi_backtrace.c (ffffffff81a51bfe)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
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
In arch/x86/events/amd/uncore.c (ffffffff81008588)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101f0c3)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103c544)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810490e7)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81052169)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054915)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d433)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff81066a8e)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/tlb.c (ffffffff8107621b)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107a5a3)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff8107ab2c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In kernel/cpu.c (ffffffff8108c15b)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/workqueue.c (ffffffff810a9bb2)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In kernel/sched/core.c (ffffffff810c6655)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/sched/fair.c (ffffffff810d51b2)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810d7f74)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810da3c4)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810df69e)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810dfbe5)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffffffff810e1e6b)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/chip.c (ffffffff81104a47)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (ffffffff8110b31c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff8111c7f0)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff811327ea)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/time/tick-sched.c (ffffffff828b2627)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_init
```
```
In kernel/events/core.c (ffffffff811f2eee)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/padata.c (ffffffff81209322)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/page_alloc.c (ffffffff812694b8)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In drivers/base/cacheinfo.c (ffffffff816a7887)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff816b6dca)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81830319)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In drivers/hv/channel_mgmt.c (ffffffff818530fa)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:hv_process_channel_removal
```
```
In lib/nmi_backtrace.c (ffffffff81a0ecfe)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
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
In arch/x86/events/amd/uncore.c (ffffffff81009f88)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810275c4)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/smp_pv.c (ffffffff828a960c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f713)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cf04)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059317)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff810621b9)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064ad5)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d4e3)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff81076a5e)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/tlb.c (ffffffff8108755a)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108ba33)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff8108bfac)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In kernel/cpu.c (ffffffff8109d6eb)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/workqueue.c (ffffffff810ba622)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In kernel/sched/core.c (ffffffff810d4525)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/sched/fair.c (ffffffff810e23e2)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810e50e4)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810e74c4)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810ec75e)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810ecca5)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffffffff810eef2b)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/chip.c (ffffffff81111c27)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (ffffffff8111819c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff81127c80)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8113d91a)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/events/core.c (ffffffff811fe0be)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/padata.c (ffffffff81214362)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/page_alloc.c (ffffffff81275338)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In drivers/xen/cpu_hotplug.c (ffffffff816560db)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cacheinfo.c (ffffffff816faac7)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff8170a0da)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b83f9)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In lib/nmi_backtrace.c (ffffffff81abdfee)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
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
In arch/x86/events/amd/uncore.c (ffffffff8100a0e8)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_dead
  - arch/x86/events/amd/uncore.c:uncore_down_prepare
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028144)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
```
```
In arch/x86/xen/smp_pv.c (ffffffff828a961c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81030563)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e314)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105a7b7)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81063779)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff810660b5)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:cpu_disable_common
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f763)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_dead_cpu
```
```
In arch/x86/kernel/kvm.c (ffffffff81078bbe)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
```
```
In arch/x86/mm/tlb.c (ffffffff8108968a)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108dd93)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:enable_mmiotrace
```
```
In arch/x86/mm/numa.c (ffffffff8108e30c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_remove_cpu
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109afc5)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
```
```
In kernel/cpu.c (ffffffff810a5571)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/workqueue.c (ffffffff810c4a12)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In kernel/sched/core.c (ffffffff810df935)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
```
In kernel/sched/fair.c (ffffffff810edf82)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In kernel/sched/rt.c (ffffffff810f107d)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/rt.c:rq_offline_rt
```
```
In kernel/sched/deadline.c (ffffffff810f2484)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/deadline.c:rq_offline_dl
```
```
In kernel/sched/cpupri.c (ffffffff810f779e)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:cpupri_set
```
```
In kernel/sched/cpudeadline.c (ffffffff810f7ce5)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:cpudl_clear_freecpu
  - kernel/sched/cpudeadline.c:cpudl_set
```
```
In kernel/sched/topology.c (ffffffff810f9f6b)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_clear
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/irq/chip.c (ffffffff8111d1e7)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_percpu_disable
```
```
In kernel/irq/affinity.c (ffffffff8112382c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/profile.c (ffffffff81134300)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/profile.c:profile_dead_cpu
```
```
In kernel/time/tick-broadcast.c (ffffffff8114a42a)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:tick_broadcast_clear_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
  - kernel/time/tick-broadcast.c:tick_broadcast_control
  - kernel/time/tick-broadcast.c:tick_do_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
  - kernel/time/tick-broadcast.c:tick_device_uses_broadcast
```
```
In kernel/events/core.c (ffffffff8120cfce)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_cpu_context
```
```
In kernel/padata.c (ffffffff812235a2)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - kernel/padata.c:padata_remove_cpu
  - kernel/padata.c:padata_remove_cpu
```
```
In mm/page_alloc.c (ffffffff81284ef8)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_all_pages
```
```
In drivers/xen/cpu_hotplug.c (ffffffff816706bb)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cacheinfo.c (ffffffff81715367)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff81724c4a)
Location: include/linux/cpumask.h:341
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d46b9)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_remove_dev
  - drivers/cpufreq/cpufreq.c:cpufreq_offline
```
```
In lib/nmi_backtrace.c (ffffffff81aca48c)
Location: include/linux/cpumask.h:341
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
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
