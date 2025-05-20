# Function: <code>cpuhp_setup_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81f84cc0)
Location: include/linux/cpuhotplug.h:116
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
```
```
In arch/x86/events/core.c (ffffffff81f8530c)
Location: include/linux/cpuhotplug.h:116
Inline: True
```
```
In arch/x86/events/amd/uncore.c (ffffffff81f856d0)
Location: include/linux/cpuhotplug.h:116
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff81f859ba)
Location: include/linux/cpuhotplug.h:116
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/cqm.c (ffffffff81f8713e)
Location: include/linux/cpuhotplug.h:116
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81f87f0c)
Location: include/linux/cpuhotplug.h:116
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/kernel/tboot.c (ffffffff81f9273d)
Location: include/linux/cpuhotplug.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a14e)
Location: include/linux/cpuhotplug.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff81f9cafc)
Location: include/linux/cpuhotplug.h:116
Inline: True
```
```
In kernel/profile.c (ffffffff81892d2d)
Location: include/linux/cpuhotplug.h:116
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff81fe2169)
Location: include/linux/cpuhotplug.h:116
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
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
In arch/x86/entry/vdso/vma.c (ffffffff81fc00d1)
Location: include/linux/cpuhotplug.h:165
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
```
```
In arch/x86/events/core.c (ffffffff81fc0720)
Location: include/linux/cpuhotplug.h:165
Inline: True
```
```
In arch/x86/events/amd/uncore.c (ffffffff81fc0b01)
Location: include/linux/cpuhotplug.h:165
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff81fc0df4)
Location: include/linux/cpuhotplug.h:165
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/cqm.c (ffffffff81fc25b0)
Location: include/linux/cpuhotplug.h:165
Inline: True
```
```
In arch/x86/events/intel/uncore.c (ffffffff81fc3386)
Location: include/linux/cpuhotplug.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/kernel/tboot.c (ffffffff81fcda09)
Location: include/linux/cpuhotplug.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81fce0b6)
Location: include/linux/cpuhotplug.h:165
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81fce8cf)
Location: include/linux/cpuhotplug.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81fceade)
Location: include/linux/cpuhotplug.h:165
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105ce9e)
Location: include/linux/cpuhotplug.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff81fd8047)
Location: include/linux/cpuhotplug.h:165
Inline: True
```
```
In kernel/profile.c (ffffffff818c761d)
Location: include/linux/cpuhotplug.h:165
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/page-writeback.c (ffffffff81fedc75)
Location: include/linux/cpuhotplug.h:165
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/zswap.c (ffffffff81ff1e1f)
Location: include/linux/cpuhotplug.h:165
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff81ff4bcf)
Location: include/linux/cpuhotplug.h:165
Inline: True
```
```
In lib/percpu_counter.c (ffffffff820069ca)
Location: include/linux/cpuhotplug.h:165
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff82008fa2)
Location: include/linux/cpuhotplug.h:165
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff8201691a)
Location: include/linux/cpuhotplug.h:165
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
```
In drivers/base/topology.c (ffffffff815d13b6)
Location: include/linux/cpuhotplug.h:165
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff82017590)
Location: include/linux/cpuhotplug.h:165
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8201e75f)
Location: include/linux/cpuhotplug.h:165
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8201ff43)
Location: include/linux/cpuhotplug.h:165
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff82026f28)
Location: include/linux/cpuhotplug.h:165
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
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
In arch/x86/entry/vdso/vma.c (ffffffff820a0294)
Location: include/linux/cpuhotplug.h:169
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
```
```
In arch/x86/events/core.c (ffffffff820a0951)
Location: include/linux/cpuhotplug.h:169
Inline: True
```
```
In arch/x86/events/amd/uncore.c (ffffffff820a0dd5)
Location: include/linux/cpuhotplug.h:169
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff820a10da)
Location: include/linux/cpuhotplug.h:169
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff820a3617)
Location: include/linux/cpuhotplug.h:169
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/kernel/tboot.c (ffffffff820ae053)
Location: include/linux/cpuhotplug.h:169
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff820aea85)
Location: include/linux/cpuhotplug.h:169
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff820af293)
Location: include/linux/cpuhotplug.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff820af49f)
Location: include/linux/cpuhotplug.h:169
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c32e)
Location: include/linux/cpuhotplug.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff820b8e89)
Location: include/linux/cpuhotplug.h:169
Inline: True
```
```
In kernel/fork.c (ffffffff820c0905)
Location: include/linux/cpuhotplug.h:169
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/profile.c (ffffffff818fed6d)
Location: include/linux/cpuhotplug.h:169
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/page-writeback.c (ffffffff820cf8d2)
Location: include/linux/cpuhotplug.h:169
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffffffff811ec7ee)
Location: include/linux/cpuhotplug.h:169
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (ffffffff820d4401)
Location: include/linux/cpuhotplug.h:169
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff820d73b7)
Location: include/linux/cpuhotplug.h:169
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffffffff820e7a1f)
Location: include/linux/cpuhotplug.h:169
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff820ea2a9)
Location: include/linux/cpuhotplug.h:169
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff820f8542)
Location: include/linux/cpuhotplug.h:169
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
```
In drivers/base/topology.c (ffffffff815e5d96)
Location: include/linux/cpuhotplug.h:169
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff820f9327)
Location: include/linux/cpuhotplug.h:169
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8210134e)
Location: include/linux/cpuhotplug.h:169
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff821029d2)
Location: include/linux/cpuhotplug.h:169
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff82106af3)
Location: include/linux/cpuhotplug.h:169
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff8210a47c)
Location: include/linux/cpuhotplug.h:169
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
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
In arch/x86/entry/vdso/vma.c (ffffffff826a6294)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
```
```
In arch/x86/events/core.c (ffffffff826a6a9c)
Location: include/linux/cpuhotplug.h:197
Inline: True
```
```
In arch/x86/events/amd/uncore.c (ffffffff826a6f20)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff826a71d2)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff826a9931)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8102a24b)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tboot.c (ffffffff826b45a2)
Location: include/linux/cpuhotplug.h:197
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff826b52f2)
Location: include/linux/cpuhotplug.h:197
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff826b5b2c)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff826b5d2e)
Location: include/linux/cpuhotplug.h:197
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810605c2)
Location: include/linux/cpuhotplug.h:197
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff826bf6d3)
Location: include/linux/cpuhotplug.h:197
Inline: True
```
```
In kernel/fork.c (ffffffff826c8ae4)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/profile.c (ffffffff81988f4d)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/page-writeback.c (ffffffff826d830b)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffffffff81202b5e)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (ffffffff826dcfc7)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff826e0020)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffffffff826f078f)
Location: include/linux/cpuhotplug.h:197
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff826f3152)
Location: include/linux/cpuhotplug.h:197
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff82701bf0)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
```
In drivers/base/topology.c (ffffffff8164d096)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff82702a05)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8270aa46)
Location: include/linux/cpuhotplug.h:197
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8270c0ae)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff82710450)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff82713e07)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
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
In arch/x86/entry/vdso/vma.c (ffffffff826cf454)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
```
```
In arch/x86/events/core.c (ffffffff826cfc28)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff826d00ac)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff826d035e)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff826d2a74)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff826d885e)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tboot.c (ffffffff826dddc1)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff826df030)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff826df868)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff826dfa6b)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:thermal_throttle_init_device
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810636a0)
Location: include/linux/cpuhotplug.h:196
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff826e94a9)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In kernel/fork.c (ffffffff826f2c6f)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/profile.c (ffffffff819e58ad)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/page-writeback.c (ffffffff827027b7)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffffffff8124eabe)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (ffffffff827074f6)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff8270a51c)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffffffff8271abf9)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/idle/intel_idle.c (ffffffff8271d0d2)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff8272b8e7)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
```
In drivers/base/topology.c (ffffffff81688675)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff8272c74c)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82734c56)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8273632e)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff8273a6d1)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff8273e041)
Location: include/linux/cpuhotplug.h:196
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
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
In arch/x86/events/core.c (ffffffff82885c82)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff8288616b)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff8288641d)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff82888d90)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8288eae9)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tboot.c (ffffffff82894204)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8289581b)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff82895a23)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82898169)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810693a0)
Location: include/linux/cpuhotplug.h:202
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff828a0065)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828a0819)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In kernel/fork.c (ffffffff828a9a66)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/profile.c (ffffffff81a20aad)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/page-writeback.c (ffffffff828b9ee0)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffffffff81262f9e)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (ffffffff828be8c8)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff828c1700)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffffffff828d2b28)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/idle/intel_idle.c (ffffffff828d50e5)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff828e41d2)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
```
In drivers/base/topology.c (ffffffff816a8365)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff828e50a8)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff828eeb21)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff828f025a)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff828f46b2)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff828f8067)
Location: include/linux/cpuhotplug.h:202
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
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
In arch/x86/events/core.c (ffffffff8289cba4)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff8289d0ac)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff8289d364)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff828a00c5)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff828a6093)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tboot.c (ffffffff828ab9c3)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff828acbc8)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff828acd24)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff828ad3af)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff828ad59f)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828afd3e)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106cbf0)
Location: include/linux/cpuhotplug.h:207
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff828b8258)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828b89ff)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In kernel/fork.c (ffffffff828c212a)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/profile.c (ffffffff81a90ff2)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/page-writeback.c (ffffffff828d12ff)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffffffff8127df0e)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (ffffffff828d7a87)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff828daa90)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffffffff828ecb78)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/idle/intel_idle.c (ffffffff828ef1a8)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff828fe689)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
```
In drivers/base/topology.c (ffffffff816e1715)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff828ff808)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82909fe2)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8290b857)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff8290ff91)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff82913ac9)
Location: include/linux/cpuhotplug.h:207
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
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
In arch/x86/events/core.c (ffffffff8289fb94)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff828a011b)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff828a03d3)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff828a31a1)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff828a909b)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tboot.c (ffffffff828ae9d1)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff828afdd3)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff828b0068)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff828b06f3)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff828b08e3)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b3077)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e350)
Location: include/linux/cpuhotplug.h:208
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff828be756)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828beeed)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In kernel/fork.c (ffffffff828ca725)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/profile.c (ffffffff81ac8332)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/page-writeback.c (ffffffff828d977d)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffffffff8128d95e)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (ffffffff828dfef8)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff828e2f13)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffffffff828f5cc9)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/idle/intel_idle.c (ffffffff828f833c)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff829076f1)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
```
In drivers/base/topology.c (ffffffff817058c5)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff829089ab)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff829139d9)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff82915220)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff82919ca5)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff8291d858)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
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
In arch/x86/events/core.c (ffffffff82cc5e82)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff82cc6408)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff82cc6636)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff82cc91eb)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff82cce8fa)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tboot.c (ffffffff82cd38ca)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff82cd505e)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff82cd54b0)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82cd57d0)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff82cd59c3)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82cd8128)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075620)
Location: include/linux/cpuhotplug.h:214
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff82ce2b04)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff82ce31dd)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In kernel/fork.c (ffffffff82ceccc0)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/profile.c (ffffffff81bc0d32)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/page-writeback.c (ffffffff82cf88e8)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffffffff812c041e)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (ffffffff82cfd629)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff82d00211)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffffffff82d09383)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/idle/intel_idle.c (ffffffff82d0f3c7)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff82d1e1dd)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
```
In drivers/base/topology.c (ffffffff817c0035)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff82d1ed2e)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82d264f3)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff82d2757e)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff819c302a)
Location: include/linux/cpuhotplug.h:214
Inline: True
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff82d2c0e5)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff82d336bc)
Location: include/linux/cpuhotplug.h:214
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
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
In arch/x86/events/core.c (ffffffff82fb1790)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff82fb1d5e)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff82fb20ad)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff82fb503c)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff82fba774)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tboot.c (ffffffff82fbf6f3)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff82fc1004)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff82fc1468)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82fc1788)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff82fc196b)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82fc408a)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075c60)
Location: include/linux/cpuhotplug.h:219
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff82fcfda1)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff82fd04d6)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In kernel/fork.c (ffffffff82fd931a)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/profile.c (ffffffff81c39dc2)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/page-writeback.c (ffffffff82fe55e1)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffffffff812cbe6e)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (ffffffff82fea05a)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff82fecbd6)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffffffff82ff697e)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/idle/intel_idle.c (ffffffff82ffce46)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff8300bec2)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
```
In drivers/base/topology.c (ffffffff8300cb59)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff8300cbbd)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff83014afd)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_boost_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff83015c96)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff819c341a)
Location: include/linux/cpuhotplug.h:219
Inline: True
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff8301aaa0)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff830226ab)
Location: include/linux/cpuhotplug.h:219
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
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
In arch/x86/events/core.c (ffffffff831bb8de)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff831bbfc2)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff831bc1f0)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff831bf7a5)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff831c4e42)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tboot.c (ffffffff831c9e9c)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff831cb61f)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff831cbb53)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff831cbe73)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff831ce6d2)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81076710)
Location: include/linux/cpuhotplug.h:227
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff831da98d)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff831db169)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In kernel/fork.c (ffffffff831e3b8f)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/profile.c (ffffffff81c2c392)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/page-writeback.c (ffffffff831efcba)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffffffff812d2a1e)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (ffffffff831f4880)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff831f73f4)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffffffff83201666)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/idle/intel_idle.c (ffffffff83207c70)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/base/topology.c (ffffffff83217950)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff832179b4)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff8321d99c)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8321fc2e)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff83220cb8)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff819a7baf)
Location: include/linux/cpuhotplug.h:227
Inline: True
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff83225b0b)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
```
```
In drivers/powercap/dtpm_cpu.c (ffffffff819bb37c)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - drivers/powercap/dtpm_cpu.c:dtpm_register_cpu
```
```
In arch/x86/pci/amd_bus.c (ffffffff8322d76c)
Location: include/linux/cpuhotplug.h:227
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
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
In arch/x86/events/core.c (ffffffff8329be54)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/ibs.c (ffffffff8329c48c)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff8329fcd3)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff832a5b5d)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tboot.c (ffffffff832ab29d)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff832acd5d)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff832ad3a2)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff832ad6d7)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff832b09cb)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81083e10)
Location: include/linux/cpuhotplug.h:274
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff832bdbc7)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff832be4de)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In kernel/fork.c (ffffffff832c7714)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/profile.c (ffffffff81d4aa82)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In kernel/trace/trace_hwlat.c (ffffffff832d1dad)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
```
```
In mm/page-writeback.c (ffffffff832d5430)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffffffff8131838b)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (ffffffff832dab46)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/migrate.c (ffffffff832dd2e3)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - mm/migrate.c:migrate_on_reclaim_init
```
```
In mm/zsmalloc.c (ffffffff832de043)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffffffff832e8cd2)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/idle/intel_idle.c (ffffffff832efd16)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/base/topology.c (ffffffff83301366)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff833013ca)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff83306c12)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8330940b)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8330a69c)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81a55165)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff8330fd2d)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init
```
```
In drivers/powercap/dtpm_cpu.c (ffffffff81a6a56c)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - drivers/powercap/dtpm_cpu.c:dtpm_register_cpu
```
```
In arch/x86/pci/amd_bus.c (ffffffff833181b0)
Location: include/linux/cpuhotplug.h:274
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
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
In arch/x86/events/core.c (ffffffff8344a671)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/ibs.c (ffffffff8344afd7)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff8344ea99)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83454bff)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tboot.c (ffffffff8345b24a)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff8345dac5)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8345de5b)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8345e25e)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8345e569)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff83461b0d)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81094006)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff8346f5c1)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff834701f2)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In kernel/fork.c (ffffffff8347a58e)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/profile.c (ffffffff81f1a124)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In kernel/trace/trace_hwlat.c (ffffffff83486093)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
```
```
In mm/page-writeback.c (ffffffff83489c2d)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffffffff81383a2b)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (ffffffff8348fcc4)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff83493897)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffffffff834a0422)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/idle/intel_idle.c (ffffffff834a7e69)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/base/topology.c (ffffffff834ba161)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff834ba1e3)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff834bfe4a)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff834c2a85)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff834c3f36)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81bc4894)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff834c9b88)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff834d2f6d)
Location: include/linux/cpuhotplug.h:280
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
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
In arch/x86/events/core.c (ffffffff83e64d45)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/ibs.c (ffffffff83e65b23)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff83e6a214)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83e72815)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tboot.c (ffffffff83e7b56c)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff83e7e9d7)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff83e7ee53)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff83e7f2da)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff83e7f77e)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff83e83a5f)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a9a73)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff83e95c17)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff83e96cae)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In kernel/fork.c (ffffffff83ea4d81)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/profile.c (ffffffff820c1d64)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In kernel/trace/trace_hwlat.c (ffffffff83eb503c)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
```
```
In mm/page-writeback.c (ffffffff83eba44e)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffffffff814014db)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (ffffffff83ec252e)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff83ec7a65)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffffffff83ed9290)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/idle/intel_idle.c (ffffffff83edefe2)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/base/topology.c (ffffffff83ef7795)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff83ef7855)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff83efeadb)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff83f040da)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81d6a10a)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff83f0b47a)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff83f17a4d)
Location: include/linux/cpuhotplug.h:284
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
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
In arch/x86/events/core.c (ffffffff83685406)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/ibs.c (ffffffff836861a3)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff8368ab9a)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83693735)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tboot.c (ffffffff8369dbf6)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff836a172e)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff836a1baa)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff836a202a)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff836a24ce)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff836a6d22)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810ac7f3)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff836b9797)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff836ba85e)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In kernel/fork.c (ffffffff836c9101)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/profile.c (ffffffff82145aa4)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In kernel/trace/trace_hwlat.c (ffffffff836da4cc)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
```
```
In kernel/trace/trace_osnoise.c (ffffffff836da63b)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:init_osnoise_tracer
```
```
In mm/page-writeback.c (ffffffff836dfa5e)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffffffff814343bb)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (ffffffff81435777)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - mm/zswap.c:zswap_setup
```
```
In mm/zsmalloc.c (ffffffff836ecae5)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffffffff836fed00)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/idle/intel_idle.c (ffffffff83704a60)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/base/topology.c (ffffffff8371d335)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff8371d3f5)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff8372494b)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8372a0ba)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81dd54ca)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff837316da)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff8373e20d)
Location: include/linux/cpuhotplug.h:282
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
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
In arch/x86/events/core.c (ffffffff838b459e)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/ibs.c (ffffffff838b5333)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff838ba75a)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff838c3250)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tboot.c (ffffffff838cd7b6)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff838d182e)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff838d1caa)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff838d212a)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff838d25ce)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff838d60c9)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff838d7402)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b3473)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff838ea0c7)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff838eb281)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In kernel/fork.c (ffffffff838f9d3c)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/profile.c (ffffffff822281c4)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In kernel/trace/trace_hwlat.c (ffffffff8390ca3c)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
```
```
In kernel/trace/trace_osnoise.c (ffffffff8390cbab)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:init_osnoise_tracer
```
```
In mm/page-writeback.c (ffffffff839122de)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffffffff8146d7bb)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zsmalloc.c (ffffffff8391fae5)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffffffff83932640)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/idle/intel_idle.c (ffffffff83937f70)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/base/topology.c (ffffffff83950ea5)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff83950f65)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff839587bb)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:thermal_throttle_init_device
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8395e066)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/clocksource/hyperv_timer.c (ffffffff81e8d61a)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff83965b3a)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:itmt_legacy_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff83972c2d)
Location: include/linux/cpuhotplug.h:267
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
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
In arch/arm64/kernel/debug-monitors.c (ffff800010085cb8)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/arm64/kernel/debug-monitors.c:debug_monitors_init
```
```
In arch/arm64/kernel/cpuinfo.c (ffff800011434bc8)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/arm64/kernel/cpuinfo.c:cpuinfo_regs_init
```
```
In arch/arm64/kernel/hw_breakpoint.c (ffff800011435fb8)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/arm64/kernel/hw_breakpoint.c:arch_hw_breakpoint_init
```
```
In virt/kvm/arm/vgic/vgic-init.c (ffff8000100de45c)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_hyp_init
```
```
In virt/kvm/arm/arch_timer.c (ffff8000100eda74)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
```
```
In arch/arm/xen/enlighten.c (ffff80001143a978)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/arm/xen/enlighten.c:xen_guest_init
```
```
In kernel/fork.c (ffff800011441c84)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/profile.c (ffff800010d9c1d8)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/page-writeback.c (ffff800011452348)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffff800010329bc8)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (ffff800011459118)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffff80001145c24c)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffff80001146fe78)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/irqchip/irq-bcm2836.c (ffff800011470af8)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_l1_intc_of_init
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff800010725a10)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe
```
```
In drivers/base/topology.c (ffff8000108f2238)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffff8000114973a4)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffff8000114a3144)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/firmware/arm_sdei.c (ffff800010b4baa8)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/firmware/arm_sdei.c:sdei_probe
  - drivers/firmware/arm_sdei.c:sdei_device_thaw
```
```
In drivers/clocksource/arm_arch_timer.c (ffff8000114a8e08)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_register
```
```
In drivers/clocksource/dummy_timer.c (ffff8000114aa160)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/clocksource/dummy_timer.c:dummy_timer_register
```
```
In drivers/perf/arm_pmu_acpi.c (ffff800010b96040)
Location: include/linux/cpuhotplug.h:208
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
In arch/arm/mm/cache-l2x0.c (c150a078)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0.c:l2c310_enable
```
```
In kernel/profile.c (c0e9880c)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/page-writeback.c (c152ceb8)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (c054049c)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (c153304c)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (c15344e8)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (c1549018)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/irqchip/irq-hip04.c (c1549d14)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/irqchip/irq-hip04.c:hip04_of_init
```
```
In drivers/base/topology.c (c09deec4)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (c1598228)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (c15a5a10)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/clocksource/timer-armada-370-xp.c (c15ab548)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init
```
```
In drivers/clocksource/timer-tegra.c (c15abe44)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/clocksource/timer-tegra.c:tegra_init_timer
```
```
In drivers/clocksource/exynos_mct.c (c15ac228)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/clocksource/exynos_mct.c:mct_init_dt
```
```
In drivers/clocksource/timer-qcom.c (c15ac5c4)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/clocksource/timer-qcom.c:msm_dt_timer_init
```
```
In drivers/clocksource/arm_arch_timer.c (c15ad294)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arch_timer_of_init
```
```
In drivers/clocksource/arm_global_timer.c (c15ada5c)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/clocksource/arm_global_timer.c:global_timer_of_register
```
```
In drivers/clocksource/dummy_timer.c (c15ae0e8)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/clocksource/dummy_timer.c:dummy_timer_register
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
In arch/powerpc/kernel/sysfs.c (c000000001348978)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/powerpc/kernel/sysfs.c:topology_init
```
```
In arch/powerpc/platforms/pseries/lpar.c (c0000000000eacf4)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_write
```
```
In arch/powerpc/perf/core-book3s.c (c000000000129d20)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/powerpc/perf/core-book3s.c:register_power_pmu
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012d024)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
```
```
In kernel/profile.c (c0000000001f9720)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/page-writeback.c (c00000000137a2fc)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (c0000000004007b0)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (c000000001382b1c)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (c000000001386e34)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (c0000000013a03f0)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/base/topology.c (c00000000098bb2c)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (c0000000013aab64)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (c0000000013b9f1c)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/clocksource/dummy_timer.c (c0000000013ba030)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/clocksource/dummy_timer.c:dummy_timer_register
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
In kernel/profile.c (ffffffe0008c43ac)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/page-writeback.c (ffffffe0000118da)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffffffe000228f14)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (ffffffe0000176a4)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffe0000199a8)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffffffe00002a30e)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/base/topology.c (ffffffe000583e7c)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffe000030f9e)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffe00003a098)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/clocksource/timer-riscv.c (ffffffe00003a61e)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/clocksource/timer-riscv.c:riscv_timer_init_dt
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
In arch/x86/events/core.c (ffffffff8288db94)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff8288e11b)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff8288e3d3)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff828911a1)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff828970ab)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tboot.c (ffffffff8289c9f0)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff8289ddf2)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff8289e087)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8289e712)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8289e902)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828a1096)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d2f0)
Location: include/linux/cpuhotplug.h:208
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff828a972c)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828a9ec3)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In kernel/fork.c (ffffffff828b3518)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/profile.c (ffffffff81a671a2)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/page-writeback.c (ffffffff828c262e)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffffffff81285f3e)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (ffffffff828c8dac)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff828cbdc7)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffffffff828deb7d)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/idle/intel_idle.c (ffffffff828e10a8)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff828eeec2)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
```
In drivers/base/topology.c (ffffffff816cb015)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff828f017c)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff828f97ed)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff828fedae)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff8290255c)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
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
In arch/x86/events/core.c (ffffffff8288bae1)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff8288c068)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff8288c339)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff8288f086)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8288f3c5)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tboot.c (ffffffff82894b87)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff8289601f)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff82896258)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff828968e3)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff82896ad3)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82899248)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d630)
Location: include/linux/cpuhotplug.h:208
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff828a17d8)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828a21a4)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In kernel/fork.c (ffffffff828ab699)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/profile.c (ffffffff81a23c62)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/page-writeback.c (ffffffff828bad56)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffffffff81277dae)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (ffffffff828c14d1)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff828c44ec)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffffffff828d7299)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/idle/intel_idle.c (ffffffff828d953d)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff828e6365)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
```
In drivers/base/topology.c (ffffffff816a6345)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff828e7603)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff828f12d6)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff828f6911)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
```
```
In drivers/hv/vmbus_drv.c (ffffffff828f6de2)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/hv/vmbus_drv.c:hv_acpi_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff828fa8aa)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
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
In arch/x86/events/core.c (ffffffff828a0b94)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff828a111b)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff828a13d3)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff828a41a1)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff828aa09b)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tboot.c (ffffffff828af9b3)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff828b0db5)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff828b104a)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff828b16d5)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff828b18c5)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b4059)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d7a0)
Location: include/linux/cpuhotplug.h:208
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff828bc62b)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828bcdc2)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In kernel/fork.c (ffffffff828c6417)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/profile.c (ffffffff81ad35b2)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/page-writeback.c (ffffffff828d53b1)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffffffff81283d4e)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (ffffffff828dbb2c)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff828deb47)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffffffff828f191c)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/idle/intel_idle.c (ffffffff828f3f38)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff82902a14)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
```
In drivers/base/topology.c (ffffffff816f9585)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff82903cce)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8290e025)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff8290f855)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff82914040)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff82917b63)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
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
In arch/x86/events/core.c (ffffffff828a0b99)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/amd/uncore.c (ffffffff828a1120)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
  - arch/x86/events/amd/uncore.c:amd_uncore_init
```
```
In arch/x86/events/amd/ibs.c (ffffffff828a13e9)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff828a41b5)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
```
In arch/x86/hyperv/hv_init.c (ffffffff828aa0ab)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/tboot.c (ffffffff828af9e1)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/cpu/umwait.c (ffffffff828b0de3)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
```
```
In arch/x86/kernel/cpu/intel_epb.c (ffffffff828b1078)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_epb.c:intel_epb_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff828b1703)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff828b18f3)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_init_device
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b4087)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106fa20)
Location: include/linux/cpuhotplug.h:208
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff828bf783)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
```
In arch/x86/kernel/kvmclock.c (ffffffff828bff1a)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
```
In kernel/fork.c (ffffffff828cb762)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/profile.c (ffffffff81adfab2)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
```
```
In mm/page-writeback.c (ffffffff828da7d2)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/page-writeback.c:page_writeback_init
  - mm/page-writeback.c:page_writeback_init
```
```
In mm/swap_slots.c (ffffffff81293a3e)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/swap_slots.c:enable_swap_slots_cache
```
```
In mm/zswap.c (ffffffff828e0f4d)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/zswap.c:init_zswap
```
```
In mm/zsmalloc.c (ffffffff828e3f5e)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_init
```
```
In lib/percpu_counter.c (ffffffff828f6d1d)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In drivers/idle/intel_idle.c (ffffffff828f9390)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff82908753)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
```
In drivers/base/topology.c (ffffffff81713e25)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/base/topology.c:topology_sysfs_init
```
```
In drivers/base/cacheinfo.c (ffffffff82909a0d)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:cacheinfo_sysfs_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff82914a3b)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffff82916282)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff8291ad07)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:itmt_legacy_init
```
```
In arch/x86/pci/amd_bus.c (ffffffff8291e8ba)
Location: include/linux/cpuhotplug.h:208
Inline: True
Inline callers:
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
</details>
</li>
</ul>

## Differences
