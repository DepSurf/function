# Function: <code>paravirt_read_msr_safe</code>

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
In arch/x86/events/core.c (ffffffff81f84f74)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
```
```
In arch/x86/events/msr.c (ffffffff81f85ac3)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_init
```
```
In arch/x86/events/intel/core.c (ffffffff8107e029)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/kernel/tsc.c (ffffffff81f91114)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103ffa2)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:__print_cpu_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042cc9)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104479a)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce-severity.c (ffffffff81046ed2)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-severity.c:mce_severity_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104851a)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81f94c7c)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8104fcd1)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107e983)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81f9a769)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81f9b5f8)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810588de)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059c15)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a24d)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
```
```
In arch/x86/lib/msr-smp.c (ffffffff8146352d)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff814640e7)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/acpi/processor_throttling.c (ffffffff814fda1c)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81592dc5)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8171b7b4)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff81fe69e2)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff8176023e)
Location: arch/x86/include/asm/paravirt.h:133
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
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
```
```
In arch/x86/events/msr.c (ffffffff81fc0f00)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_init
```
```
In arch/x86/events/intel/core.c (ffffffff810825c9)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810427cd)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104634a)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce-severity.c (ffffffff81048a52)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-severity.c:mce_severity_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff810496df)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104a700)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81fd0288)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810524f1)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8108301a)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81fd5c30)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff81fd6b41)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105b66e)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c9d5)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cf9d)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
```
```
In arch/x86/lib/msr-smp.c (ffffffff814827cd)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff81483387)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/acpi/processor_throttling.c (ffffffff81520715)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815c0685)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8174d654)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff82025226)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff8178d23e)
Location: arch/x86/include/asm/paravirt.h:124
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
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
```
```
In arch/x86/events/msr.c (ffffffff820a13bb)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100c9e5)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8103fe26)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810408a8)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045fea)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce-severity.c (ffffffff810483fb)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-severity.c:mce_severity_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104905e)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff810494aa)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff820b0cf2)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81052011)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81056f09)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff820b6a27)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff820b784c)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105adc4)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c0e5)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c413)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
```
```
In arch/x86/lib/msr-smp.c (ffffffff8148befd)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff8148cac7)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/acpi/processor_throttling.c (ffffffff8153196a)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d60df)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8176ba68)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff81799817)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff82108705)
Location: arch/x86/include/asm/paravirt.h:124
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff817ab3ae)
Location: arch/x86/include/asm/paravirt.h:124
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
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
```
```
In arch/x86/events/msr.c (ffffffff826a74f8)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100cf85)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104319b)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81043a3f)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104980a)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce-severity.c (ffffffff8104be32)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-severity.c:mce_severity_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104ca74)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104ceea)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff826b7501)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81055c7d)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105ab76)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff826bd348)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff826be1f7)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105f2dd)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105ffa5)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81060583)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
```
```
In arch/x86/lib/msr-smp.c (ffffffff814c7fed)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff814c8a76)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff815500a9)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff81592b4a)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163ce8f)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff817e18d8)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff8180fbb7)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff82712057)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff8182289d)
Location: arch/x86/include/asm/paravirt.h:120
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
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/msr.c (ffffffff826d0699)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_init
```
```
In arch/x86/events/intel/core.c (ffffffff8100d6cf)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81044fbb)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104602d)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104c04a)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce-severity.c (ffffffff8104eb15)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-severity.c:mce_severity_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104f74e)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81050c91)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff826e1219)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81058afd)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105d9c6)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff826e7294)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff826e7fb9)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810623ed)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81063175)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81063663)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff8106e953)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In arch/x86/lib/msr-smp.c (ffffffff814f9436)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff814f9a26)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff81586979)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff815ca01b)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8167830e)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8182a614)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff818599c2)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8273c30b)
Location: arch/x86/include/asm/paravirt.h:120
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff8186cae8)
Location: arch/x86/include/asm/paravirt.h:120
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
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/msr.c (ffffffff82886758)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/events/msr.c:msr_init
```
```
In arch/x86/events/intel/core.c (ffffffff8100db9a)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810469cd)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81047a1a)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104861d)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104973a)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
```
```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff8104c1e5)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104ce0e)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8104d3f1)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828971db)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8105e73d)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81063656)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8289dddd)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8289eb02)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810680ed)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068d75)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81069363)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81074973)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In arch/x86/lib/msr-smp.c (ffffffff8150dcd6)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff8150e2c6)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff8159ec99)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff815e35fb)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816973ee)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818564e4)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff81878c62)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff828f631f)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff8188caf8)
Location: arch/x86/include/asm/paravirt.h:182
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
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/probe.c (ffffffff8100866c)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100e466)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810493c8)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a7b3)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b39e)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c6fc)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
```
```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff8104f0e5)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fd69)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81050341)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828aed83)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81061b3d)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066cd1)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b5c77)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b69f0)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106b8dd)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c599)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106cbb3)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81078554)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:apic_is_x2apic_enabled
```
```
In arch/x86/lib/msr-smp.c (ffffffff8153c356)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff8153c936)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff815d01d9)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff816150e3)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816c1a46)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cfd4d)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81899bb4)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818bd73c)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff818bdf33)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff82911d66)
Location: arch/x86/include/asm/paravirt.h:182
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff818d7468)
Location: arch/x86/include/asm/paravirt.h:182
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
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/probe.c (ffffffff8100896c)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100eaa6)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f810)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049c9c)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b38a)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104ba68)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d0bc)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff8104fa65)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810506f9)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81050cb1)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828b20c8)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810623ed)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81067341)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b913b)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828b9ec5)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c39e)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106dc99)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e313)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810795a4)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:apic_is_x2apic_enabled
```
```
In arch/x86/lib/msr-smp.c (ffffffff8155d166)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff8155d746)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff815f1449)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff816365d3)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816e4966)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f3b8d)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818cbba4)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818f025c)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff818f0a83)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8291baff)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff81909aea)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 paravirt_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81009738)
Location: arch/x86/include/asm/paravirt.h:176
Inline: False
Direct callers:
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/probe.c (ffffffff81009aeb)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100fda2)
Location: arch/x86/include/asm/paravirt.h:176
Inline: False
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81031f36)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff8104d6b4)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104dda0)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel_misc_features
  - arch/x86/kernel/cpu/intel.c:init_intel_misc_features
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104fdc0)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:amd_detect_ppin
  - arch/x86/kernel/cpu/amd.c:amd_detect_ppin
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81050344)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051c9f)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
```
```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff81053f69)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054db0)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810562cb)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff82cd721a)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810683cb)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106a20b)
Location: arch/x86/include/asm/paravirt.h:176
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
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82cde141)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff82cdf1a7)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810736b4)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:__irq_msi_compose_msg
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075105)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075780)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81080934)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
```
```
In arch/x86/lib/msr-smp.c (ffffffff815e6b46)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff815e71c6)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff8169d45a)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e2f6b)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
```
```
In drivers/iommu/amd/init.c (ffffffff8179b1d4)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817abb8a)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a0704)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff819c34df)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:get_oc_core_priority
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c486d)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff82d31884)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff81bba21a)
Location: arch/x86/include/asm/paravirt.h:176
Inline: True
```
**Symbols:**

```
ffffffff81009738-ffffffff81009747: paravirt_read_msr_safe (STB_LOCAL)
ffffffff8100fda2-ffffffff8100fdb1: paravirt_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 paravirt_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81bd1b40)
Location: arch/x86/include/asm/paravirt.h:174
Inline: False
Direct callers:
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/probe.c (ffffffff8100896b)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff81bd2105)
Location: arch/x86/include/asm/paravirt.h:174
Inline: False
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81bd2f55)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff8104cb39)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104d2d0)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel_misc_features
  - arch/x86/kernel/cpu/intel.c:init_intel_misc_features
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104f029)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:amd_detect_ppin
  - arch/x86/kernel/cpu/amd.c:amd_detect_ppin
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104f414)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff81052ea7)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81053d1c)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810551db)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff82fc31ed)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106a0ab)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106bedb)
Location: arch/x86/include/asm/paravirt.h:174
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
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff82fca4ff)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff82fcb546)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075735)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075dc0)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81bd820d)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
```
```
In arch/x86/lib/msr-smp.c (ffffffff8160bc96)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff8160c3d6)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff816bad4a)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff81700bcb)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b7f6a)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a35b4)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff819c38af)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:get_oc_core_priority
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c4b5e)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8302080e)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff81bcea8f)
Location: arch/x86/include/asm/paravirt.h:174
Inline: True
```
**Symbols:**

```
ffffffff81bd1b40-ffffffff81bd1b4f: paravirt_read_msr_safe (STB_LOCAL)
ffffffff81bd2105-ffffffff81bd2114: paravirt_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 paravirt_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006ca8)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/probe.c (ffffffff81009304)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff81bc4222)
Location: arch/x86/include/asm/paravirt.h:191
Inline: False
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81bc5331)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff8104e639)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104ee50)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810509a7)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81050ed4)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff81054796)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810555ee)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810568cb)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff831cd81d)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106ab7b)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106c8fb)
Location: arch/x86/include/asm/paravirt.h:191
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
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff831d4e24)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff831d5ddd)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d9766)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810761d5)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81076840)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81bca047)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
```
```
In arch/x86/lib/msr-smp.c (ffffffff815eef76)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff815ef336)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff8169ce9b)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e2bca)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179b9ad)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819881c4)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff819a7def)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:get_oc_core_priority
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819a9a3e)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8322b9da)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff81bc243f)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
```
**Symbols:**

```
ffffffff81bc4222-ffffffff81bc4231: paravirt_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 paravirt_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810074c8)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/probe.c (ffffffff8100a22c)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff81c95680)
Location: arch/x86/include/asm/paravirt.h:191
Inline: False
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81c97f01)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
```
```
In arch/x86/kernel/cpu/feat_ctl.c (ffffffff81056029)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81056f40)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81058d3a)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810592fa)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff8105d0e6)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105df8e)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105f4eb)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff832af7fe)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810754db)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff810778fb)
Location: arch/x86/include/asm/paravirt.h:191
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
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
```
```
In arch/x86/kernel/apic/vector.c (ffffffff832b798c)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff832b8a40)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bc085)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810837d5)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81083fb0)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81c9f356)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
```
```
In arch/x86/lib/msr-smp.c (ffffffff8165c086)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff8165c446)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff81713204)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff8175b8a8)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff818245bd)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81a31ee4)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81a57198)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81a5739f)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff833161ff)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff81c92aab)
Location: arch/x86/include/asm/paravirt.h:191
Inline: True
```
**Symbols:**

```
ffffffff81c95680-ffffffff81c9568f: paravirt_read_msr_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 paravirt_read_msr_safe(unsigned int msr, int *err);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006a01)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/probe.c (ffffffff8100995a)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff81e4498a)
Location: arch/x86/include/asm/paravirt.h:197
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81e47390)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:x2apic_enabled
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105d67c)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:ppin_init
  - arch/x86/kernel/cpu/common.c:ppin_init
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81e4a200)
Location: arch/x86/include/asm/paravirt.h:197
Inline: False
Direct callers:
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
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81063297)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81065654)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810659b6)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8106a6f5)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106bdd6)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff8346087a)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81083f47)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81e4cdad)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83469611)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff8346a7e7)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346d9cd)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8109370a)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810940ba)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81e4eaa4)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:x2apic_enabled
```
```
In arch/x86/lib/msr-smp.c (ffffffff8177501d)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff817754dd)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff81842893)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff8188f196)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8196436b)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (ffffffff81b3a5dc)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_dw_amdpsp_probe_lock_support
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9e5ff)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81bc69c1)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81bc6e39)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff834d0b40)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff81e421f5)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:msr_build_context
```
**Symbols:**

```
ffffffff81e4498a-ffffffff81e449b0: paravirt_read_msr_safe (STB_LOCAL)
ffffffff81e4a200-ffffffff81e4a226: paravirt_read_msr_safe (STB_LOCAL)
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
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/probe.c (ffffffff8100ae3a)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff81014f1e)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff83e72ce0)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106bbbb)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:ppin_init
  - arch/x86/kernel/cpu/common.c:ppin_init
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff83e7e690)
Location: arch/x86/include/asm/paravirt.h:197
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
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81072297)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81074955)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81074ce6)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107a545)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107bdd6)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff83e82536)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81096dd7)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/apic/apic.c (ffffffff83e8ce9c)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83e8e3b3)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff83e8f828)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e915db)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a8d2a)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a96da)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff83e9743a)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In arch/x86/lib/msr-smp.c (ffffffff818a5b7d)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff818a60fd)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff81979823)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff819d6d60)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acd411)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (ffffffff81cd0150)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_dw_amdpsp_probe_lock_support
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d40b29)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81d6ebb5)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81d6f659)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff83f14c17)
Location: arch/x86/include/asm/paravirt.h:197
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff8201ca04)
Location: arch/x86/include/asm/paravirt.h:197
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
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/probe.c (ffffffff8100a62a)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8101477e)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff83693c90)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106d56b)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:ppin_init
  - arch/x86/kernel/cpu/common.c:ppin_init
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff836a13f0)
Location: arch/x86/include/asm/paravirt.h:199
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
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81073e77)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107689d)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_spectral_chicken
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81076e56)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107c7f5)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107e0d6)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff836a5856)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81099ef7)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/apic/apic.c (ffffffff836b072c)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff836b1c53)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff836b30ce)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b5e21)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810abf5a)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810ac8ea)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff836bafea)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In arch/x86/lib/msr-smp.c (ffffffff818e899d)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff818e8f2d)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff819c02b3)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a1e720)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b19f81)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/thermal/intel/intel_tcc.c (ffffffff81d51c6d)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_tcc.c:intel_tcc_get_temp
  - drivers/thermal/intel/intel_tcc.c:intel_tcc_set_offset
  - drivers/thermal/intel/intel_tcc.c:intel_tcc_get_offset
  - drivers/thermal/intel/intel_tcc.c:intel_tcc_get_tjmax
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81dab6a9)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81ddc8cd)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume_common
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81ddd309)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8373b397)
Location: arch/x86/include/asm/paravirt.h:199
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff8209d094)
Location: arch/x86/include/asm/paravirt.h:199
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
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/probe.c (ffffffff8100fd45)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8101a22e)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff838c3b74)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
  - arch/x86/hyperv/hv_apic.c:hv_apic_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810747bb)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:ppin_init
  - arch/x86/kernel/cpu/common.c:ppin_init
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff838d14a0)
Location: arch/x86/include/asm/paravirt.h:201
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
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
  - arch/x86/kernel/cpu/feat_ctl.c:init_vmx_capabilities
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107b3b7)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107dc9b)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107e3d6)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81083ce5)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81085586)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
  - arch/x86/kernel/cpu/mce/amd.c:smca_configure
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff838d58d6)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810a1727)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/apic/apic.c (ffffffff838e0e5c)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:check_x2apic
```
```
In arch/x86/kernel/apic/vector.c (ffffffff838e200d)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff838e39ae)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e59a1)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2cba)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b356a)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check
```
```
In arch/x86/kernel/jailhouse.c (ffffffff838eb9da)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_x2apic_available
  - arch/x86/kernel/jailhouse.c:jailhouse_get_smp_config
```
```
In arch/x86/lib/msr-smp.c (ffffffff8192fe3d)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff819303cd)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff81a0ad33)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a69a40)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e703)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:dmar_ir_add
```
```
In drivers/thermal/intel/intel_tcc.c (ffffffff81e089ed)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_tcc.c:intel_tcc_get_temp
  - drivers/thermal/intel/intel_tcc.c:intel_tcc_set_offset
  - drivers/thermal/intel/intel_tcc.c:intel_tcc_get_offset
  - drivers/thermal/intel/intel_tcc.c:intel_tcc_get_tjmax
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e63749)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81e93019)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8396fd17)
Location: arch/x86/include/asm/paravirt.h:201
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff821746e4)
Location: arch/x86/include/asm/paravirt.h:201
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
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/probe.c (ffffffff8100896c)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100eaa6)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f970)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049e0c)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b4fa)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bbd8)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d22c)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff8104fb65)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810507f9)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81050db1)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828a00e7)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81061f6d)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81066e31)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828a7142)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828a7edd)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106be8e)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cc39)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d2b3)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff810785a4)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:apic_is_x2apic_enabled
```
```
In arch/x86/lib/msr-smp.c (ffffffff81555756)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff81555d36)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff815e00d9)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff81605b53)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816aa446)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b937d)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8186f7a4)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8189158c)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff81891db3)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff82900803)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff818a8eaa)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
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
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/probe.c (ffffffff8100892c)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100ea66)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f7d0)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049c4c)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b33a)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104ba18)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d06c)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff8104fa15)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810506a9)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81050c61)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828b30aa)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106238d)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810672e1)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828ba052)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828baddc)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c33e)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106d0e9)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d763)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff81078554)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:apic_is_x2apic_enabled
```
```
In arch/x86/lib/msr-smp.c (ffffffff81551496)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff81551a76)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff815e5729)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff8162a8b3)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816d8626)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e784d)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818c1054)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818e508c)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff818e58b3)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff82915e0a)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff818fa50a)
Location: arch/x86/include/asm/paravirt.h:170
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
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/probe.c (ffffffff81008a8c)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100ec36)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81030620)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104b05c)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104c74a)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
  - arch/x86/kernel/cpu/amd.c:bsp_init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104ce28)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:early_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
  - arch/x86/kernel/cpu/hygon.c:bsp_init_hygon
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e47c)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff81050e55)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81051ae9)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810520a1)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828b30d8)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106394d)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810688c1)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:apic_is_x2apic_enabled
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828ba168)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_local_APIC
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff828baef2)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106da3e)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f369)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f9e3)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/kernel/jailhouse.c (ffffffff8107a654)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:apic_is_x2apic_enabled
```
```
In arch/x86/lib/msr-smp.c (ffffffff8156b2f6)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff8156b906)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_read
```
```
In drivers/acpi/acpi_lpit.c (ffffffff815ff5d9)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In drivers/acpi/processor_throttling.c (ffffffff81644753)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816f2bd6)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701f4d)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818dd364)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
  - drivers/cpufreq/intel_pstate.c:core_get_max_pstate
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81901cec)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff81902513)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8291cb61)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
```
In arch/x86/power/cpu.c (ffffffff8191b66a)
Location: arch/x86/include/asm/paravirt.h:170
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
  - arch/x86/power/cpu.c:save_processor_state
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
