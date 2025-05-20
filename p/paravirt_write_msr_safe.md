# Function: <code>paravirt_write_msr_safe</code>

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
In arch/x86/events/core.c (ffffffff81f85053)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8107e097)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/knc.c (ffffffff810108b6)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff81f8764c)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
```
```
In arch/x86/events/intel/p6.c (ffffffff81012add)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/xen/enlighten.c (ffffffff81f88af6)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff8102ccc9)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:do_arch_prctl
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040f2d)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042baf)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff810496e3)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104c0dd)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8104fd9c)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff8146358d)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff81464133)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/acpi/processor_throttling.c (ffffffff814fd2fe)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
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
In arch/x86/events/core.c (ffffffff81fc0467)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff81082637)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/knc.c (ffffffff81010a66)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff81fc2ac4)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
```
```
In arch/x86/events/intel/p6.c (ffffffff81012bcd)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/xen/enlighten.c (ffffffff81fc3ee4)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff8102cb75)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:do_arch_prctl
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104097d)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810426cf)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81fce00a)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104970a)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104bae3)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104e52d)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810525bc)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff8148282d)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff814833d3)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/acpi/processor_throttling.c (ffffffff8152008f)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
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
In arch/x86/events/core.c (ffffffff820a067c)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100ca45)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/knc.c (ffffffff8100f0a6)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff820a2d43)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
```
```
In arch/x86/events/intel/p6.c (ffffffff8101115d)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff820a3c4c)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff820a76ac)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In arch/x86/kernel/process_64.c (ffffffff8102ad75)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103e8fd)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810407bb)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff820ae784)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81049089)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104b2a3)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104e49d)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810520dc)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/kvm.c (ffffffff810664b0)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
```
```
In arch/x86/lib/msr-smp.c (ffffffff8148bf5d)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff8148cb13)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/acpi/processor_throttling.c (ffffffff81531559)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff81799756)
Location: arch/x86/include/asm/paravirt.h:129
Inline: True
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
In arch/x86/events/core.c (ffffffff826a679a)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100cfe5)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/knc.c (ffffffff8100f8f6)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff826a9037)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
```
```
In arch/x86/events/intel/p6.c (ffffffff810118dd)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff826aa34b)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff826ade5c)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In arch/x86/kernel/process_64.c (ffffffff8102bab5)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810415a0)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81043b2c)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff826b4fdf)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104cb29)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104ec93)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81051e0d)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81055d48)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff814c804d)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff814c8ad9)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_write
```
```
In drivers/acpi/processor_throttling.c (ffffffff81592a29)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff8180faf6)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
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
In arch/x86/events/core.c (ffffffff826cf930)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100d712)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/knc.c (ffffffff8101022d)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff826d22d2)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
```
```
In arch/x86/events/intel/p6.c (ffffffff810122ad)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff826d34ae)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff826d71e0)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_prepare_pvh
```
```
In arch/x86/kernel/process_64.c (ffffffff8102caec)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81042e70)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104611e)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff826dec7e)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104f7c4)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff810519d3)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81054ab5)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81058bc6)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff814f8f55)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff814f9a69)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_write
```
```
In drivers/acpi/processor_throttling.c (ffffffff815c9b12)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff818599a3)
Location: arch/x86/include/asm/paravirt.h:125
Inline: True
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
In arch/x86/events/core.c (ffffffff8288598a)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100dbdd)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff8101084d)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff828885e2)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
```
```
In arch/x86/events/intel/p6.c (ffffffff8101292d)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828893d2)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff8288d272)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104446d)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81047c16)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104ce84)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8104f073)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81052165)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8289822a)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8105e80c)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff8150d7f5)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff8150e309)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_write
```
```
In drivers/acpi/processor_throttling.c (ffffffff815e30f2)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff81878c43)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
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
In arch/x86/events/core.c (ffffffff8289c97d)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100bc15)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff81011a0d)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff8289f753)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
```
```
In arch/x86/events/intel/p6.c (ffffffff81013ccd)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a0753)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a4702)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046a3b)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104aac0)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fdbc)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052133)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055265)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828afdf9)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81061b63)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff8153bea5)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff8153c979)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_write
```
```
In drivers/acpi/processor_throttling.c (ffffffff81614c94)
Location: arch/x86/include/asm/paravirt.h:187
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff818bdf14)
Location: arch/x86/include/asm/paravirt.h:187
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
In arch/x86/events/core.c (ffffffff8289f96d)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100c025)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff810121cd)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff828a2825)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
```
```
In arch/x86/events/intel/p6.c (ffffffff8101447d)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a3843)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a7792)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810471bb)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b3a8)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81050745)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052a23)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055b65)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b3132)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81062413)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff8155ccb5)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff8155d789)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_write
```
```
In drivers/acpi/processor_throttling.c (ffffffff81636184)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff818f0a64)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int paravirt_write_msr_safe(unsigned int msr, unsigned int low, unsigned int high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81009880)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/intel/core.c (ffffffff8100efe5)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff810135cd)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff810159ba)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/intel/p6.c (ffffffff81015bed)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff82cc9af8)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82ccdb71)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104afcb)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104ddc8)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104fde6)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:amd_detect_ppin
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054de5)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81057b40)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105abf5)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82cd7f5c)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:__check_quirks_intel
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81068494)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff815e66d5)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff815e72f7)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e3054)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff819c34c4)
Location: arch/x86/include/asm/paravirt.h:181
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:get_oc_core_priority
```
**Symbols:**

```
ffffffff8100fdb1-ffffffff8100fdc4: paravirt_write_msr_safe (STB_LOCAL)
ffffffff81014f20-ffffffff81014f33: paravirt_write_msr_safe.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int paravirt_write_msr_safe(unsigned int msr, unsigned int low, unsigned int high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81bd1c7c)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/intel/core.c (ffffffff8100e355)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff8101317d)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/lbr.c (ffffffff82fb42fe)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/p4.c (ffffffff81015e5a)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/intel/p6.c (ffffffff8101608d)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff82fb595d)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff82fb99a1)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a4bb)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104d2f8)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104f04f)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:amd_detect_ppin
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81053d6d)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff810568c0)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105975c)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82fc3ebb)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:__check_quirks_intel
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106a174)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff8160b825)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff8160c507)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/acpi/processor_throttling.c (ffffffff81700cb4)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff819c3894)
Location: arch/x86/include/asm/paravirt.h:179
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:get_oc_core_priority
```
**Symbols:**

```
ffffffff81bd2114-ffffffff81bd2127: paravirt_write_msr_safe (STB_LOCAL)
ffffffff810153c0-ffffffff810153d3: paravirt_write_msr_safe.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int paravirt_write_msr_safe(unsigned int msr, unsigned int low, unsigned int high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006d43)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/intel/core.c (ffffffff8100f366)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff8101438d)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/lbr.c (ffffffff831be875)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/p4.c (ffffffff810169c8)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/intel/p6.c (ffffffff8101737d)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff831c0168)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff831c4061)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104bd4b)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104ee7b)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810509d9)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81055642)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105a0cc)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff831ce7ba)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106ac44)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff815eeb05)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff815ef7a7)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e25e4)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff819470f3)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff819a7dd4)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:get_oc_core_priority
```
**Symbols:**

```
ffffffff81bc4231-ffffffff81bc4244: paravirt_write_msr_safe (STB_LOCAL)
ffffffff81016630-ffffffff81016643: paravirt_write_msr_safe.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int paravirt_write_msr_safe(unsigned int msr, unsigned int low, unsigned int high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007561)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/intel/core.c (ffffffff81010130)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff8101570d)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/lbr.c (ffffffff8329ecd3)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/p4.c (ffffffff8101852f)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/intel/p6.c (ffffffff8101912d)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff832a0936)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff832a4bc1)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810530db)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81056f6b)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81058d6b)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105dfe2)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8106351c)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff832b0789)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:check_quirks
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810755c4)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff8165bc15)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff8165c8b7)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/acpi/processor_throttling.c (ffffffff8175ae60)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff819ebd55)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:notify_hwp_interrupt
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81a57384)
Location: arch/x86/include/asm/paravirt.h:196
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority
```
**Symbols:**

```
ffffffff81c9568f-ffffffff81c956a2: paravirt_write_msr_safe (STB_LOCAL)
ffffffff810180e0-ffffffff810180f3: paravirt_write_msr_safe.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int paravirt_write_msr_safe(unsigned int msr, unsigned int low, unsigned int high);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006a9f)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/intel/core.c (ffffffff81011748)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
Direct callers:
  - arch/x86/events/intel/core.c:check_msr
```
```
In arch/x86/events/intel/knc.c (ffffffff8101777d)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/lbr.c (ffffffff8344da06)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/p4.c (ffffffff8101a6d7)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/intel/p6.c (ffffffff8101b31d)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8344f916)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff83453d8d)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105eb13)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:ppin_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810632c1)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81065674)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8106a738)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8107016c)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8346188e)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:check_quirks
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81084041)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff81774ad5)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff81775aab)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/acpi/processor_throttling.c (ffffffff8188ea4e)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81b51e15)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:notify_hwp_interrupt
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81b96e00)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:pstate_enable
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9f1c7)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81bc6e14)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority
```
**Symbols:**

```
ffffffff81e449b0-ffffffff81e449da: paravirt_write_msr_safe (STB_LOCAL)
ffffffff8101a210-ffffffff8101a23c: paravirt_write_msr_safe.constprop.0.isra.0 (STB_LOCAL)
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
In arch/x86/events/core.c (ffffffff810082a5)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/intel/core.c (ffffffff81014f52)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff8101b9dd)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/lbr.c (ffffffff83e68e7f)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/p4.c (ffffffff83e692f2)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
```
```
In arch/x86/events/intel/p6.c (ffffffff8101f51d)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff83e6b4be)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff83e71525)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106d243)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:ppin_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810722c1)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81074975)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107a588)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81080b63)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_enable
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff83e83bfa)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81096ed1)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff818a5595)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff818a678b)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/acpi/processor_throttling.c (ffffffff819d617e)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81ce9f95)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:notify_hwp_interrupt
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81d37b30)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:pstate_enable
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d40ba7)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81d6f634)
Location: arch/x86/include/asm/paravirt.h:202
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority
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
In arch/x86/events/core.c (ffffffff81007a95)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/intel/core.c (ffffffff810147b2)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff8101b6ad)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/lbr.c (ffffffff8368981f)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/p4.c (ffffffff83689c82)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
```
```
In arch/x86/events/intel/p6.c (ffffffff8101f22d)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff8368bf5e)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff8369239e)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106ebd3)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:ppin_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81073ea1)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81076baf)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_has_ibpb_brtype_microcode
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_spectral_chicken
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107c838)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81082fb3)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_enable
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff836a6f13)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81099fc4)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff818e83b5)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff818e95fb)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a1dabe)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/thermal/intel/intel_tcc.c (ffffffff81d519e7)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_tcc.c:intel_tcc_set_offset
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81d52ad5)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:notify_hwp_interrupt
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81dab727)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81ddd2e4)
Location: arch/x86/include/asm/paravirt.h:204
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority
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
In arch/x86/events/core.c (ffffffff8100d1b5)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/intel/core.c (ffffffff8101a262)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff8102120d)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/lbr.c (ffffffff838b9311)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/p4.c (ffffffff838b97e2)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:__p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
```
```
In arch/x86/events/intel/p6.c (ffffffff810252ed)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff838bbb1e)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:init_hvm_pv_info
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff838c1eae)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81075ede)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:ppin_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107b3e1)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107dcaf)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81083d28)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8108a37c)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff838d6df2)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:__check_quirks_intel
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810a17f4)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff8192f855)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff81930a9b)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a68dce)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/thermal/intel/intel_tcc.c (ffffffff81e08767)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_tcc.c:intel_tcc_set_offset
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81e09835)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:notify_hwp_interrupt
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e637c7)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81e92ff4)
Location: arch/x86/include/asm/paravirt.h:206
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority
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
In arch/x86/events/core.c (ffffffff8288d96d)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100c025)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff810121cd)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff82890825)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
```
```
In arch/x86/events/intel/p6.c (ffffffff8101447d)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff82891864)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828957a2)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104733b)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b518)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81050845)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052b23)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810556e5)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828a1151)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81061f93)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff815552a5)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff81555d79)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_write
```
```
In drivers/acpi/processor_throttling.c (ffffffff81605744)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff81891d94)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
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
In arch/x86/events/core.c (ffffffff828a096d)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100bfe5)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff8101218d)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff828a3825)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
```
```
In arch/x86/events/intel/p6.c (ffffffff8101443d)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a4843)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a8792)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104717b)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b358)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810506f5)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff810529d3)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055b15)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b4114)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810623b3)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff81550fe5)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff81551ab9)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_write
```
```
In drivers/acpi/processor_throttling.c (ffffffff8162a464)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff818e5894)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
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
In arch/x86/events/core.c (ffffffff828a0972)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100c215)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff810123ad)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff828a3839)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_init
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
```
```
In arch/x86/events/intel/p6.c (ffffffff8101467d)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/xen/enlighten_hvm.c (ffffffff828a4817)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff828a87a2)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104857b)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104c768)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81051b35)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81053e53)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81056fb5)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b4142)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81063973)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff8156ae25)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff8156b949)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_write
```
```
In drivers/acpi/processor_throttling.c (ffffffff81644304)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff819024f4)
Location: arch/x86/include/asm/paravirt.h:175
Inline: True
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
