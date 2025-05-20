# Function: <code>rdmsrl_safe</code>

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
In arch/x86/events/core.c (ffffffff81f5cfe5)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
```
```
In arch/x86/events/msr.c (ffffffff81f5dbfa)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_init
```
```
In arch/x86/events/intel/core.c (ffffffff8107c6b3)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/events/intel/cstate.c (ffffffff8107c8ef)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/events/intel/cstate.c:cstate_probe_msr
```
```
In arch/x86/events/intel/rapl.c (ffffffff81f5fd6b)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/events/intel/rapl.c:rapl_pmu_init
```
```
In arch/x86/kernel/tsc.c (ffffffff81f69208)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040134)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:__print_cpu_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810426bd)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044750)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107cea7)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f72003)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81f72dd0)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810585af)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059995)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059f7d)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
```
```
In arch/x86/lib/msr.c (ffffffff8141ba56)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_set_bit
  - arch/x86/lib/msr.c:msr_clear_bit
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153ddf1)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff816b9cac)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In arch/x86/power/cpu.c (ffffffff816fb02a)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/events/core.c (ffffffff81f84f74)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
```
```
In arch/x86/events/msr.c (ffffffff81f85ac3)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_init
```
```
In arch/x86/events/intel/core.c (ffffffff8107e029)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/kernel/tsc.c (ffffffff81f91114)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103ffa2)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:__print_cpu_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042b8d)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104479a)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107e983)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f9a769)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81f9b5f8)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810588de)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059c15)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a24d)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
```
```
In arch/x86/lib/msr.c (ffffffff814640e7)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81592dc5)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8171b7b4)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In arch/x86/power/cpu.c (ffffffff8176023e)
Location: arch/x86/include/asm/paravirt.h:178
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/events/core.c (ffffffff81fc0388)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
```
```
In arch/x86/events/msr.c (ffffffff81fc0f00)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_init
```
```
In arch/x86/events/intel/core.c (ffffffff810825c9)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810426ad)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104634a)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff810496df)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8108301a)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81fd5c30)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81fd6b41)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105b66e)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c9d5)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cf9d)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
```
```
In arch/x86/lib/msr.c (ffffffff81483387)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815c0685)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8174d654)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In arch/x86/power/cpu.c (ffffffff8178d23e)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/events/core.c (ffffffff820a0586)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
```
```
In arch/x86/events/msr.c (ffffffff820a13bb)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100c9e5)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8103fe26)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81040799)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045fea)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104905e)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056f09)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff820b6a27)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff820b784c)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105adc4)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c0e5)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c413)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
```
```
In arch/x86/lib/msr.c (ffffffff8148cac7)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d60df)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8176ba68)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff81799817)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff817ab3ae)
Location: arch/x86/include/asm/paravirt.h:169
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/events/core.c (ffffffff826a66a4)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
```
In arch/x86/events/msr.c (ffffffff826a74f8)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100cf85)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104319b)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81043a3f)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104980a)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104ca74)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105ab76)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff826bd348)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff826be1f7)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105f2dd)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105ffa5)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81060583)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
```
In arch/x86/lib/msr.c (ffffffff814c8a76)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff815500a9)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163ce8f)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff817e18d8)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff8180fbb7)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff8182289d)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/events/core.c (ffffffff826cf837)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/msr.c (ffffffff826d0699)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_init
```
```
In arch/x86/events/intel/core.c (ffffffff8100d6cf)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81044fbb)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104602d)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104c04a)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104f74e)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105d9c6)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff826e7294)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff826e7fb9)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810623ed)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81063175)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81063663)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff8106e953)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In arch/x86/lib/msr.c (ffffffff814f9a26)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff81586979)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8167830e)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8182a614)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff818599c2)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff8186cae8)
Location: arch/x86/include/asm/paravirt.h:165
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/events/core.c (ffffffff82885891)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/msr.c (ffffffff82886758)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_init
```
```
In arch/x86/events/intel/core.c (ffffffff8100db9a)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810469cd)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81047a1a)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104861d)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104973a)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104ce0e)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81063656)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289dddd)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289eb02)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810680ed)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068d75)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81069363)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81074973)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In arch/x86/lib/msr.c (ffffffff8150e2c6)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff8159ec99)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816973ee)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818564e4)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff81878c62)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff8188caf8)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/events/core.c (ffffffff8289c887)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/probe.c (ffffffff8100866c)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100e466)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810493c8)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a7b3)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b39e)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c6fc)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fd69)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066cd1)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b5c77)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b69f0)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106b8dd)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c599)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106cbb3)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81078554)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:apic_is_x2apic_enabled
```
```
In arch/x86/lib/msr.c (ffffffff8153c936)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff815d01d9)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816c1a46)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cfd4d)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81899bb4)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818bd73c)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff818bdf33)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff818d7468)
Location: arch/x86/include/asm/paravirt.h:227
Inline: True
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
In arch/x86/events/core.c (ffffffff8289f877)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/probe.c (ffffffff8100896c)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100eaa6)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f810)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049c9c)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b38a)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b712)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d0bc)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810506f9)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81067341)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b913b)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b9ec5)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c39e)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106dc99)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e313)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810795a4)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:apic_is_x2apic_enabled
```
```
In arch/x86/lib/msr.c (ffffffff8155d746)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff815f1449)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816e4966)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f3b8d)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818cbba4)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818f025c)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff818f0a83)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff81909aea)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/events/core.c (ffffffff810097b1)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/probe.c (ffffffff81009aeb)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100fe45)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81031f36)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff8104d6b4)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104dda0)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel_misc_features
  - arch/x86/kernel/cpu/intel.c:init_intel_misc_features
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104fdc0)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:amd_detect_ppin
  - arch/x86/kernel/cpu/amd.c:amd_detect_ppin
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81050592)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051c9f)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054db0)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106a20b)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106e031)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82cde141)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff82cdf1a7)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810736b4)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:__irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075105)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075780)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81080934)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
```
```
In arch/x86/lib/msr.c (ffffffff815e71c6)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff8169d45a)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
```
```
In drivers/iommu/amd/init.c (ffffffff8179b1d4)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817abb8a)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a0704)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff819c34df)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:get_oc_core_priority
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c486d)
Location: arch/x86/include/asm/paravirt.h:221
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show
```
```
In arch/x86/power/cpu.c (ffffffff81bba21a)
Location: arch/x86/include/asm/paravirt.h:221
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
In arch/x86/events/core.c (ffffffff81bd1bad)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/probe.c (ffffffff8100896b)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff81bd21a8)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81bd2f55)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff8104cb39)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104d2d0)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel_misc_features
  - arch/x86/kernel/cpu/intel.c:init_intel_misc_features
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104f029)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:amd_detect_ppin
  - arch/x86/kernel/cpu/amd.c:amd_detect_ppin
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104f891)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81053d1c)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106bedb)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81bd6d99)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82fca4ff)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff82fcb546)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075735)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075dc0)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81bd820d)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
```
```
In arch/x86/lib/msr.c (ffffffff8160c3d6)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff816bad4a)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b7f6a)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a35b4)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff819c38af)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:get_oc_core_priority
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c4b5e)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show
```
```
In arch/x86/power/cpu.c (ffffffff81bcea8f)
Location: arch/x86/include/asm/paravirt.h:219
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
In arch/x86/events/core.c (ffffffff81006ca8)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/probe.c (ffffffff81009304)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff81bc4410)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81bc5331)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff8104e639)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104ee50)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810509a7)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81050e3d)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810555ee)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106c8fb)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81bc8e9c)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff831d4e24)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff831d5ddd)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d9766)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810761d5)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81076840)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81bca047)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
```
```
In arch/x86/lib/msr.c (ffffffff815ef336)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff8169ce9b)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179b9ad)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819881c4)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff819a7def)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:get_oc_core_priority
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819a9a3e)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show
```
```
In arch/x86/power/cpu.c (ffffffff81bc243f)
Location: arch/x86/include/asm/paravirt.h:236
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
In arch/x86/events/core.c (ffffffff810074c8)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/probe.c (ffffffff8100a22c)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff81c95950)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81c97f01)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff81056029)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81056f40)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81058d3a)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8105925d)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105df8e)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff810778fb)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:intel_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio
  - arch/x86/kernel/smpboot.c:skx_set_max_freq_ratio
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c9d8f0)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff832b798c)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff832b8a40)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bc085)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810837d5)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81083fb0)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81c9f356)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
```
```
In arch/x86/lib/msr.c (ffffffff8165c446)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff81713204)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff818245bd)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81a31ee4)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81a57198)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81a5739f)
Location: arch/x86/include/asm/paravirt.h:236
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority
```
```
In arch/x86/power/cpu.c (ffffffff81c92aab)
Location: arch/x86/include/asm/paravirt.h:236
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
In arch/x86/events/core.c (ffffffff81006a01)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/probe.c (ffffffff81009953)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff81e44b71)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81e47382)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:x2apic_enabled
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105d675)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:ppin_init
  - arch/x86/kernel/cpu/common.c:ppin_init
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8345d80a)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff81062030)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81063290)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81065647)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81065906)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8106a6e9)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81e4cd9f)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83469603)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8346a7d9)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346d9c3)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81093703)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810940b3)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81e4ea96)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:x2apic_enabled
```
```
In arch/x86/lib/msr.c (ffffffff817754d6)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff8184288c)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81964364)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (ffffffff81b3a5dc)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_dw_amdpsp_probe_lock_support
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9e5f4)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81bc69ba)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81bc6e32)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority
```
```
In arch/x86/power/cpu.c (ffffffff81e421f5)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:msr_build_context
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
In arch/x86/events/core.c (ffffffff810081ae)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/probe.c (ffffffff8100ae33)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff81014f17)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff83e72cd9)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106bbb4)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:ppin_init
  - arch/x86/kernel/cpu/common.c:ppin_init
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff83e7e689)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff81070ab0)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81072290)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81074948)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81074c32)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107a539)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff83e8ce95)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83e8e3ac)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff83e8f81a)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e915d4)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a8d23)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a96d3)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff83e97433)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In arch/x86/lib/msr.c (ffffffff818a60f6)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff8197981c)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acd40a)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (ffffffff81cd0150)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_dw_amdpsp_probe_lock_support
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d40b22)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81d6ebae)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81d6f652)
Location: arch/x86/include/asm/paravirt.h:242
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority
```
```
In arch/x86/power/cpu.c (ffffffff8201ca04)
Location: arch/x86/include/asm/paravirt.h:242
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
In arch/x86/events/core.c (ffffffff8100799e)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/probe.c (ffffffff8100a623)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff81014777)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff83693c89)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106d564)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:ppin_init
  - arch/x86/kernel/cpu/common.c:ppin_init
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff836a13e9)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff810726a0)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81073e70)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81076890)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_spectral_chicken
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81076da2)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107c7e9)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff836b0725)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff836b1c4c)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff836b30c0)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b5e1a)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810abf53)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810ac8e3)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff836bafe3)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In arch/x86/lib/msr.c (ffffffff818e8f26)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff819c02ac)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b19f7a)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81dab6a2)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81ddc8cd)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume_common
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81ddd302)
Location: arch/x86/include/asm/paravirt.h:244
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority
```
```
In arch/x86/power/cpu.c (ffffffff8209d094)
Location: arch/x86/include/asm/paravirt.h:244
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
In arch/x86/events/core.c (ffffffff8100d0be)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/probe.c (ffffffff8100fd3e)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8101a227)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff838c3b6d)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810747b4)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:ppin_init
  - arch/x86/kernel/cpu/common.c:ppin_init
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff838d1499)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:intel_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio
  - arch/x86/kernel/cpu/aperfmperf.c:skx_set_max_freq_ratio
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff81079fa0)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107b3b0)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107dc8e)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107e322)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81083cd9)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff838e0e55)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff838e2006)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff838e39a0)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e599a)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2cb3)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b3563)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff838eb9d3)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In arch/x86/lib/msr.c (ffffffff819303c6)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff81a0ad2c)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e6fc)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e63742)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81e93012)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority
```
```
In arch/x86/power/cpu.c (ffffffff821746e4)
Location: arch/x86/include/asm/paravirt.h:246
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/events/core.c (ffffffff8288d877)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/probe.c (ffffffff8100896c)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100eaa6)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f970)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049e0c)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b4fa)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b882)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d22c)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810507f9)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066e31)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828a7142)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828a7edd)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106be8e)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cc39)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d2b3)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810785a4)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:apic_is_x2apic_enabled
```
```
In arch/x86/lib/msr.c (ffffffff81555d36)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff815e00d9)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816aa446)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b937d)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8186f7a4)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8189158c)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff81891db3)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff818a8eaa)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/events/core.c (ffffffff8288b79c)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/probe.c (ffffffff81007170)
Location: arch/x86/include/asm/msr.h:302
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100d80b)
Location: arch/x86/include/asm/msr.h:302
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101f329)
Location: arch/x86/include/asm/msr.h:302
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81039166)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8103a94b)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8103b225)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103c6be)
Location: arch/x86/include/asm/msr.h:302
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103fe32)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810572bd)
Location: arch/x86/include/asm/msr.h:302
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289f239)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289ff97)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105c18c)
Location: arch/x86/include/asm/msr.h:302
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105cf35)
Location: arch/x86/include/asm/msr.h:302
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d776)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81067d9e)
Location: arch/x86/include/asm/msr.h:302
Inline: True
```
```
In arch/x86/lib/msr.c (ffffffff81546265)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/acpi/acpi_lpit.c (ffffffff815cb76f)
Location: arch/x86/include/asm/msr.h:302
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816883b2)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696f95)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8183ade1)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81849e4e)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff8184b12c)
Location: arch/x86/include/asm/msr.h:302
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff81863641)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/events/core.c (ffffffff828a0877)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/probe.c (ffffffff8100892c)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100ea66)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f7d0)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049c4c)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b33a)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b6c2)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d06c)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810506a9)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810672e1)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828ba052)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828baddc)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c33e)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106d0e9)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d763)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81078554)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:apic_is_x2apic_enabled
```
```
In arch/x86/lib/msr.c (ffffffff81551a76)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff815e5729)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816d8626)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e784d)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818c1054)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818e508c)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff818e58b3)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff818fa50a)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/events/core.c (ffffffff828a087c)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/probe.c (ffffffff81008a8c)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100ec36)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81030620)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104b05c)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104c74a)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104cad2)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e47c)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81051ae9)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810688c1)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828ba168)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828baef2)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106da3e)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f369)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f9e3)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff8107a654)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:apic_is_x2apic_enabled
```
```
In arch/x86/lib/msr.c (ffffffff8156b906)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff815ff5d9)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816f2bd6)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701f4d)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818dd364)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81901cec)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff81902513)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff8191b66a)
Location: arch/x86/include/asm/paravirt.h:215
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
```
</details>
</li>
</ul>

## Differences
