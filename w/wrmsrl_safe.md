# Function: <code>wrmsrl_safe</code>

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
In arch/x86/events/core.c (ffffffff81f5d116)
Location: arch/x86/include/asm/msr.h:234
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8107c6ef)
Location: arch/x86/include/asm/msr.h:234
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/knc.c (ffffffff81010f21)
Location: arch/x86/include/asm/msr.h:234
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff81012311)
Location: arch/x86/include/asm/msr.h:234
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_pmu_disable_all
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
  - arch/x86/events/intel/p4.c:p4_pmu_init
```
```
In arch/x86/events/intel/p6.c (ffffffff81013161)
Location: arch/x86/include/asm/msr.h:234
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
```
```
In arch/x86/kernel/process_64.c (ffffffff8102dc43)
Location: arch/x86/include/asm/msr.h:234
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:do_arch_prctl
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104100d)
Location: arch/x86/include/asm/msr.h:234
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042f75)
Location: arch/x86/include/asm/msr.h:234
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049543)
Location: arch/x86/include/asm/msr.h:234
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/lib/msr.c (ffffffff8141bab9)
Location: arch/x86/include/asm/msr.h:234
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_set_bit
  - arch/x86/lib/msr.c:msr_clear_bit
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
In arch/x86/events/core.c (ffffffff81f85053)
Location: arch/x86/include/asm/msr.h:277
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8107e094)
Location: arch/x86/include/asm/msr.h:277
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/knc.c (ffffffff810108b6)
Location: arch/x86/include/asm/msr.h:277
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff81f8764c)
Location: arch/x86/include/asm/msr.h:277
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
Location: arch/x86/include/asm/msr.h:277
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/process_64.c (ffffffff8102ccc6)
Location: arch/x86/include/asm/msr.h:277
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:do_arch_prctl
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040f2d)
Location: arch/x86/include/asm/msr.h:277
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042baf)
Location: arch/x86/include/asm/msr.h:277
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff810496e3)
Location: arch/x86/include/asm/msr.h:277
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/lib/msr.c (ffffffff81464133)
Location: arch/x86/include/asm/msr.h:277
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
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
Location: arch/x86/include/asm/msr.h:291
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff81082634)
Location: arch/x86/include/asm/msr.h:291
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/knc.c (ffffffff81010a66)
Location: arch/x86/include/asm/msr.h:291
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff81fc2ac4)
Location: arch/x86/include/asm/msr.h:291
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
Location: arch/x86/include/asm/msr.h:291
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/process_64.c (ffffffff8102cb72)
Location: arch/x86/include/asm/msr.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl
  - arch/x86/kernel/process_64.c:do_arch_prctl
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104097d)
Location: arch/x86/include/asm/msr.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810426cf)
Location: arch/x86/include/asm/msr.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104970a)
Location: arch/x86/include/asm/msr.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104bae3)
Location: arch/x86/include/asm/msr.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/lib/msr.c (ffffffff814833d3)
Location: arch/x86/include/asm/msr.h:291
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
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
Location: arch/x86/include/asm/msr.h:302
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100ca42)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/knc.c (ffffffff8100f0a6)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff820a2d43)
Location: arch/x86/include/asm/msr.h:302
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
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/process_64.c (ffffffff8102ad72)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103e8fd)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810407bb)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81049089)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104b2a3)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/lib/msr.c (ffffffff8148cb13)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff81799756)
Location: arch/x86/include/asm/msr.h:302
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
Location: arch/x86/include/asm/msr.h:302
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8100cfe2)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/knc.c (ffffffff8100f8f6)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff826a9037)
Location: arch/x86/include/asm/msr.h:302
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
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/process_64.c (ffffffff8102bab2)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810415a0)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81043b2c)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104cb29)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104ec93)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/lib/msr.c (ffffffff814c8ad9)
Location: arch/x86/include/asm/msr.h:302
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_write
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff8180faf6)
Location: arch/x86/include/asm/msr.h:302
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
Location: arch/x86/include/asm/msr.h:313
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100d712)
Location: arch/x86/include/asm/msr.h:313
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/knc.c (ffffffff8101022d)
Location: arch/x86/include/asm/msr.h:313
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff826d22d2)
Location: arch/x86/include/asm/msr.h:313
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
Location: arch/x86/include/asm/msr.h:313
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/process_64.c (ffffffff8102caec)
Location: arch/x86/include/asm/msr.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81042e70)
Location: arch/x86/include/asm/msr.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104611e)
Location: arch/x86/include/asm/msr.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104f7c4)
Location: arch/x86/include/asm/msr.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff810519d3)
Location: arch/x86/include/asm/msr.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/lib/msr.c (ffffffff814f9a69)
Location: arch/x86/include/asm/msr.h:313
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_write
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff818599a3)
Location: arch/x86/include/asm/msr.h:313
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
Location: arch/x86/include/asm/msr.h:313
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100dbdd)
Location: arch/x86/include/asm/msr.h:313
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff8101084d)
Location: arch/x86/include/asm/msr.h:313
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff828885e2)
Location: arch/x86/include/asm/msr.h:313
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
Location: arch/x86/include/asm/msr.h:313
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104446d)
Location: arch/x86/include/asm/msr.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81047c16)
Location: arch/x86/include/asm/msr.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104ce84)
Location: arch/x86/include/asm/msr.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8104f073)
Location: arch/x86/include/asm/msr.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/lib/msr.c (ffffffff8150e309)
Location: arch/x86/include/asm/msr.h:313
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_write
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff81878c43)
Location: arch/x86/include/asm/msr.h:313
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
Location: arch/x86/include/asm/msr.h:325
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100bc15)
Location: arch/x86/include/asm/msr.h:325
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff81011a0d)
Location: arch/x86/include/asm/msr.h:325
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff8289f753)
Location: arch/x86/include/asm/msr.h:325
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
Location: arch/x86/include/asm/msr.h:325
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046a3b)
Location: arch/x86/include/asm/msr.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104aac0)
Location: arch/x86/include/asm/msr.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fdbc)
Location: arch/x86/include/asm/msr.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052133)
Location: arch/x86/include/asm/msr.h:325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/lib/msr.c (ffffffff8153c979)
Location: arch/x86/include/asm/msr.h:325
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_write
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff818bdf14)
Location: arch/x86/include/asm/msr.h:325
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
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100c025)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff810121cd)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff828a2825)
Location: arch/x86/include/asm/msr.h:324
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
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810471bb)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b3a8)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81050745)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052a23)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/lib/msr.c (ffffffff8155d789)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_write
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff818f0a64)
Location: arch/x86/include/asm/msr.h:324
Inline: True
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
In arch/x86/events/core.c (ffffffff81009880)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/intel/core.c (ffffffff8100efe5)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff810135cd)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff82cc8897)
Location: arch/x86/include/asm/msr.h:324
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
In arch/x86/events/intel/p6.c (ffffffff81015bed)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104afcb)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104ddc8)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104fde6)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:amd_detect_ppin
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054de5)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81057b40)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/lib/msr.c (ffffffff815e72f7)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff819c34c4)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:get_oc_core_priority
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
In arch/x86/events/core.c (ffffffff81bd1c7c)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/intel/core.c (ffffffff8100e355)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff8101317d)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/lbr.c (ffffffff82fb42fe)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/p4.c (ffffffff82fb46ae)
Location: arch/x86/include/asm/msr.h:322
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
In arch/x86/events/intel/p6.c (ffffffff8101608d)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a4bb)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104d2f8)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104f04f)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:amd_detect_ppin
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81053d6d)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff810568c0)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/lib/msr.c (ffffffff8160c507)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff819c3894)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:get_oc_core_priority
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
In arch/x86/events/core.c (ffffffff81006d43)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/intel/core.c (ffffffff8100f366)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff8101438d)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/lbr.c (ffffffff831be875)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/p4.c (ffffffff831bec22)
Location: arch/x86/include/asm/msr.h:322
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
In arch/x86/events/intel/p6.c (ffffffff8101737d)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104bd4b)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104ee7b)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810509d9)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81055642)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/lib/msr.c (ffffffff815ef7a7)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff819470f3)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff819a7dd4)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - drivers/platform/x86/intel_turbo_max_3.c:get_oc_core_priority
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
In arch/x86/events/core.c (ffffffff81007561)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/intel/core.c (ffffffff81010130)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff8101570d)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/lbr.c (ffffffff8329ecd3)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/p4.c (ffffffff8329f08e)
Location: arch/x86/include/asm/msr.h:322
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
In arch/x86/events/intel/p6.c (ffffffff8101912d)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810530db)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81056f6b)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81058d6b)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105dfe2)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/lib/msr.c (ffffffff8165c8b7)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff819ebd55)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:notify_hwp_interrupt
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81a57384)
Location: arch/x86/include/asm/msr.h:322
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority
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
In arch/x86/events/core.c (ffffffff81006a9f)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/intel/core.c (ffffffff81e44bb6)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff8101777d)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/lbr.c (ffffffff8344da06)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/p4.c (ffffffff8344de4e)
Location: arch/x86/include/asm/msr.h:303
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
In arch/x86/events/intel/p6.c (ffffffff8101b31d)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105eb13)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:ppin_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810632c1)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81065674)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8106a738)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/lib/msr.c (ffffffff81775aab)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81b51e15)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:notify_hwp_interrupt
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81b96e00)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:pstate_enable
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9f1c7)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81bc6e14)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - drivers/platform/x86/intel/turbo_max_3.c:get_oc_core_priority
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
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/intel/core.c (ffffffff81014f52)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff8101b9dd)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/lbr.c (ffffffff83e68e7f)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/p4.c (ffffffff83e692f2)
Location: arch/x86/include/asm/msr.h:303
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
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106d243)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:ppin_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810722c1)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81074975)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107a588)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/lib/msr.c (ffffffff818a678b)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81ce9f95)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:notify_hwp_interrupt
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81d37b30)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:pstate_enable
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d40ba7)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81d6f634)
Location: arch/x86/include/asm/msr.h:303
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
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/intel/core.c (ffffffff810147b2)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff8101b6ad)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/lbr.c (ffffffff8368981f)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/p4.c (ffffffff83689c82)
Location: arch/x86/include/asm/msr.h:303
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
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106ebd3)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:ppin_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81073ea1)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81076baf)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:cpu_has_ibpb_brtype_microcode
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_spectral_chicken
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107c838)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/lib/msr.c (ffffffff818e95fb)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81d52ad5)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:notify_hwp_interrupt
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81dab727)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81ddd2e4)
Location: arch/x86/include/asm/msr.h:303
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
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/core.c:check_hw_exists
```
```
In arch/x86/events/intel/core.c (ffffffff8101a262)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:check_msr
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff8102120d)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/lbr.c (ffffffff838b9311)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
```
```
In arch/x86/events/intel/p4.c (ffffffff838b97e2)
Location: arch/x86/include/asm/msr.h:303
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
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81075ede)
Location: arch/x86/include/asm/msr.h:303
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
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_verify_msr
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107dcaf)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81083d28)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/lib/msr.c (ffffffff81930a9b)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81e09835)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:notify_hwp_interrupt
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e637c7)
Location: arch/x86/include/asm/msr.h:303
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81e92ff4)
Location: arch/x86/include/asm/msr.h:303
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
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100c025)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff810121cd)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff82890825)
Location: arch/x86/include/asm/msr.h:324
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
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104733b)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b518)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81050845)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052b23)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/lib/msr.c (ffffffff81555d79)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_write
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff81891d94)
Location: arch/x86/include/asm/msr.h:324
Inline: True
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
In arch/x86/events/core.c (ffffffff8288b894)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100cd7d)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff81010fe6)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff8288e73d)
Location: arch/x86/include/asm/msr.h:324
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
In arch/x86/events/intel/p6.c (ffffffff81013853)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103641b)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8103a97f)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103ff02)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81042513)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/lib/msr.c (ffffffff8154628d)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff8184b0e5)
Location: arch/x86/include/asm/msr.h:324
Inline: True
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
In arch/x86/events/core.c (ffffffff828a096d)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100bfe5)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff8101218d)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff828a3825)
Location: arch/x86/include/asm/msr.h:324
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
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104717b)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b358)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810506f5)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff810529d3)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/lib/msr.c (ffffffff81551ab9)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_write
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff818e5894)
Location: arch/x86/include/asm/msr.h:324
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
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100c215)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff810123ad)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff828a3839)
Location: arch/x86/include/asm/msr.h:324
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
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104857b)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104c768)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81051b35)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81053e53)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/lib/msr.c (ffffffff8156b949)
Location: arch/x86/include/asm/msr.h:324
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_write
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff819024f4)
Location: arch/x86/include/asm/msr.h:324
Inline: True
```
</details>
</li>
</ul>

## Differences
