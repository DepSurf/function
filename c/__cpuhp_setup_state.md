# Function: <code>__cpuhp_setup_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81084220)
Location: kernel/cpu.c:1484
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff81084220-ffffffff81084467: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810891e0)
Location: kernel/cpu.c:1479
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:trace_init
  - kernel/padata.c:padata_driver_init
  - mm/page_alloc.c:page_alloc_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
  - mm/compaction.c:kcompactd_init
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - fs/buffer.c:buffer_init
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
  - lib/radix-tree.c:radix_tree_init
  - lib/irq_poll.c:irq_poll_setup
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - net/core/flow.c:flow_cache_hp_init
```
**Symbols:**

```
ffffffff810891e0-ffffffff81089365: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810864c0)
Location: kernel/cpu.c:1474
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/fork.c:fork_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:early_trace_init
  - kernel/padata.c:padata_driver_init
  - mm/page_alloc.c:page_alloc_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init
  - lib/irq_poll.c:irq_poll_setup
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - net/core/flow.c:flow_cache_hp_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff810864c0-ffffffff81086575: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108d130)
Location: kernel/cpu.c:1662
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/fork.c:fork_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:early_trace_init
  - kernel/padata.c:padata_driver_init
  - mm/page_alloc.c:page_alloc_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init
  - lib/irq_poll.c:irq_poll_setup
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff8108d130-ffffffff8108d1e5: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81090ae0)
Location: kernel/cpu.c:1744
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/fork.c:fork_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:early_trace_init
  - kernel/padata.c:padata_driver_init
  - mm/page_alloc.c:page_alloc_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmscan.c:kswapd_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - net/core/dev.c:net_dev_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff81090ae0-ffffffff81090b69: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81098ba0)
Location: kernel/cpu.c:1766
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/fork.c:fork_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:early_trace_init
  - kernel/padata.c:padata_driver_init
  - mm/page_alloc.c:page_alloc_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmscan.c:kswapd_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - net/core/dev.c:net_dev_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff81098ba0-ffffffff81098c29: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d130)
Location: kernel/cpu.c:1792
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/fork.c:fork_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/padata.c:padata_driver_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmscan.c:kswapd_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - net/core/dev.c:net_dev_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff8109d130-ffffffff8109d1b8: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a3680)
Location: kernel/cpu.c:1807
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/fork.c:fork_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/padata.c:padata_driver_init
  - kernel/padata.c:padata_driver_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmscan.c:kswapd_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - net/core/dev.c:net_dev_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff810a3680-ffffffff810a3708: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810aa6f0)
Location: kernel/cpu.c:1938
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/vmware.c:vmware_paravirt_ops_setup
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/fork.c:fork_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - lib/radix-tree.c:radix_tree_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - net/core/dev.c:net_dev_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff810aa6f0-ffffffff810aa7a9: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5f80)
Location: kernel/cpu.c:1949
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/vmware.c:vmware_paravirt_ops_setup
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/fork.c:fork_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - fs/io-wq.c:io_wq_init
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - lib/radix-tree.c:radix_tree_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - net/core/dev.c:net_dev_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff810a5f80-ffffffff810a6039: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a6dd0)
Location: kernel/cpu.c:2052
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/fork.c:fork_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - fs/io-wq.c:io_wq_init
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - lib/radix-tree.c:radix_tree_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/iommu/iova.c:iova_cache_get
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - drivers/powercap/dtpm_cpu.c:dtpm_register_cpu
  - net/core/dev.c:net_dev_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff810a6dd0-ffffffff810a6e89: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b8730)
Location: kernel/cpu.c:2083
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/fork.c:fork_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/migrate.c:migrate_on_reclaim_init
  - mm/migrate.c:migrate_on_reclaim_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - fs/io-wq.c:io_wq_init
  - block/bio.c:init_bio
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - lib/radix-tree.c:radix_tree_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/iommu/iova.c:iova_cache_get
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init
  - drivers/powercap/dtpm_cpu.c:dtpm_register_cpu
  - net/core/dev.c:net_dev_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff810b8730-ffffffff810b87e9: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cefa0)
Location: kernel/cpu.c:2105
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel.c:sld_setup
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/fork.c:fork_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - block/bio.c:init_bio
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
  - io_uring/io-wq.c:io_wq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - lib/radix-tree.c:radix_tree_init
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/iommu/iova.c:iova_cache_get
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init
  - net/core/dev.c:net_dev_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff810cefa0-ffffffff810cf097: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ed3d0)
Location: kernel/cpu.c:2129
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel.c:sld_setup
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/fork.c:fork_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - block/bio.c:init_bio
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
  - io_uring/io-wq.c:io_wq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/iommu/iova.c:iova_cache_get
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init
  - net/core/dev.c:net_dev_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff810ed3d0-ffffffff810ed4c7: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f8f60)
Location: kernel/cpu.c:2514
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel.c:sld_setup
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/fork.c:fork_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_osnoise.c:init_osnoise_tracer
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_init_cpuhp
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:zswap_setup
  - mm/zswap.c:zswap_setup
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - block/bio.c:init_bio
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
  - io_uring/io-wq.c:io_wq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/iommu/intel/perfmon.c:iommu_pmu_register
  - drivers/iommu/iova.c:iova_cache_get
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/net/virtio_net.c:virtio_net_driver_init
  - drivers/net/virtio_net.c:virtio_net_driver_init
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init
  - net/core/dev.c:net_dev_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff810f8f60-ffffffff810f9057: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81102370)
Location: kernel/cpu.c:2560
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel.c:sld_setup
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/fork.c:fork_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/time/tick-sched.c:tick_nohz_init
  - kernel/crash_core.c:crash_hotplug_init
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_osnoise.c:init_osnoise_tracer
  - kernel/padata.c:padata_init
  - kernel/padata.c:padata_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_init_cpuhp
  - mm/slub.c:kmem_cache_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:zswap_setup
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - block/bio.c:init_bio
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
  - io_uring/io-wq.c:io_wq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/iommu/intel/perfmon.c:iommu_pmu_register
  - drivers/iommu/iova.c:iova_cache_get
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/net/virtio_net.c:virtio_net_driver_init
  - drivers/net/virtio_net.c:virtio_net_driver_init
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
  - drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init
  - net/core/dev.c:net_dev_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff81102370-ffffffff81102467: __cpuhp_setup_state (STB_GLOBAL)
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
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f8df0)
Location: kernel/cpu.c:1807
Inline: False
Direct callers:
  - arch/arm64/kernel/debug-monitors.c:debug_monitors_init
  - arch/arm64/kernel/fpsimd.c:fpsimd_init
  - arch/arm64/kernel/cpuinfo.c:cpuinfo_regs_init
  - arch/arm64/kernel/hw_breakpoint.c:arch_hw_breakpoint_init
  - arch/arm64/kernel/armv8_deprecated.c:armv8_deprecated_init
  - virt/kvm/kvm_main.c:kvm_init
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_hyp_init
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
  - arch/arm/xen/enlighten.c:xen_guest_init
  - kernel/fork.c:fork_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/padata.c:padata_driver_init
  - kernel/padata.c:padata_driver_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmscan.c:kswapd_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_l1_intc_of_init
  - drivers/irqchip/irq-gic.c:__gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_driver_init
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_driver_init
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/firmware/arm_sdei.c:sdei_probe
  - drivers/firmware/arm_sdei.c:sdei_device_thaw
  - drivers/clocksource/arm_arch_timer.c:arch_timer_register
  - drivers/clocksource/dummy_timer.c:dummy_timer_register
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-ccn.c:arm_ccn_init
  - drivers/perf/arm_pmu.c:arm_pmu_hp_init
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_module_init
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_module_init
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_module_init
  - drivers/perf/qcom_l2_pmu.c:register_l2_cache_pmu_driver
  - drivers/perf/qcom_l3_pmu.c:register_qcom_l3_cache_pmu_driver
  - net/core/dev.c:net_dev_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffff8000100f8df0-ffff8000100f8ee0: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0357054)
Location: kernel/cpu.c:1807
Inline: False
Direct callers:
  - arch/arm/vfp/vfpmodule.c:vfp_init
  - arch/arm/kernel/smp_twd.c:twd_local_timer_of_register
  - arch/arm/mm/cache-l2x0.c:l2c310_enable
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_init
  - arch/arm/common/bL_switcher.c:bL_switcher_init
  - arch/arm/common/bL_switcher.c:bL_switcher_init
  - arch/arm/mach-mvebu/coherency.c:coherency_init
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_smp_prepare_cpus
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init
  - arch/arm/mach-shmobile/platsmp-scu.c:shmobile_smp_scu_prepare_cpus
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/padata.c:padata_driver_init
  - kernel/padata.c:padata_driver_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmscan.c:kswapd_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - drivers/irqchip/irq-hip04.c:hip04_of_init
  - drivers/irqchip/irq-gic.c:__gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/cpuidle/coupled.c:cpuidle_coupled_init
  - drivers/cpuidle/coupled.c:cpuidle_coupled_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init
  - drivers/clocksource/timer-tegra.c:tegra_init_timer
  - drivers/clocksource/exynos_mct.c:mct_init_dt
  - drivers/clocksource/timer-qcom.c:msm_dt_timer_init
  - drivers/clocksource/arm_arch_timer.c:arch_timer_of_init
  - drivers/clocksource/arm_global_timer.c:global_timer_of_register
  - drivers/clocksource/dummy_timer.c:dummy_timer_register
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-ccn.c:arm_ccn_init
  - drivers/perf/arm_pmu.c:arm_pmu_hp_init
  - net/core/dev.c:net_dev_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
c0357054-c0357124: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c00000000013f960)
Location: kernel/cpu.c:1807
Inline: False
Direct callers:
  - arch/powerpc/kernel/sysfs.c:topology_init
  - arch/powerpc/kernel/watchdog.c:watchdog_nmi_probe
  - arch/powerpc/mm/numa.c:initmem_init
  - arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write
  - arch/powerpc/perf/core-book3s.c:register_power_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/padata.c:padata_driver_init
  - kernel/padata.c:padata_driver_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmscan.c:kswapd_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/cpuidle/cpuidle-pseries.c:pseries_processor_idle_init
  - drivers/cpuidle/cpuidle-pseries.c:pseries_processor_idle_init
  - drivers/cpuidle/cpuidle-powernv.c:powernv_processor_idle_init
  - drivers/cpuidle/cpuidle-powernv.c:powernv_processor_idle_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/clocksource/dummy_timer.c:dummy_timer_register
  - net/core/dev.c:net_dev_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
c00000000013f960-c00000000013fabc: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c3aa4)
Location: kernel/cpu.c:1807
Inline: False
Direct callers:
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:tracer_alloc_buffers
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmscan.c:kswapd_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/clocksource/timer-riscv.c:riscv_timer_init_dt
  - net/core/dev.c:net_dev_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffe0000c3aa4-ffffffe0000c3af6: __cpuhp_setup_state (STB_GLOBAL)
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
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109cfa0)
Location: kernel/cpu.c:1807
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/fork.c:fork_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/padata.c:padata_driver_init
  - kernel/padata.c:padata_driver_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmscan.c:kswapd_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - net/core/dev.c:net_dev_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff8109cfa0-ffffffff8109d028: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108b9d0)
Location: kernel/cpu.c:1807
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/fork.c:fork_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/time/tick-sched.c:tick_nohz_init
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/padata.c:padata_driver_init
  - kernel/padata.c:padata_driver_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmscan.c:kswapd_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - drivers/hv/vmbus_drv.c:hv_acpi_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - net/core/dev.c:net_dev_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff8108b9d0-ffffffff8108ba58: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109cf50)
Location: kernel/cpu.c:1807
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/fork.c:fork_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/padata.c:padata_driver_init
  - kernel/padata.c:padata_driver_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmscan.c:kswapd_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - net/core/dev.c:net_dev_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff8109cf50-ffffffff8109cfd8: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __cpuhp_setup_state(enum cpuhp_state state, const char *name, bool invoke, int (*startup)(unsigned int), int (*teardown)(unsigned int), bool multi_instance);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a4d30)
Location: kernel/cpu.c:1807
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - kernel/fork.c:fork_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/padata.c:padata_driver_init
  - kernel/padata.c:padata_driver_init
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmscan.c:kswapd_init
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_init
  - mm/swap_slots.c:enable_swap_slots_cache
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/zsmalloc.c:zs_init
  - fs/buffer.c:buffer_init
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/base/topology.c:topology_sysfs_init
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - net/core/dev.c:net_dev_init
  - lib/radix-tree.c:radix_tree_init
```
**Symbols:**

```
ffffffff810a4d30-ffffffff810a4e03: __cpuhp_setup_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool multi_instance</code>
</li>
</ul>
</details>
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
