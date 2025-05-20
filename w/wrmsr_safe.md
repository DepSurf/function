# Function: <code>wrmsr_safe</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
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
Location: arch/x86/include/asm/msr.h:287
Inline: True
Inline callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
```
In arch/x86/events/intel/core.c (ffffffff8100cd7d)
Location: arch/x86/include/asm/msr.h:287
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/knc.c (ffffffff81010fe6)
Location: arch/x86/include/asm/msr.h:287
Inline: True
Inline callers:
  - arch/x86/events/intel/knc.c:knc_pmu_enable_event
  - arch/x86/events/intel/knc.c:knc_pmu_disable_event
```
```
In arch/x86/events/intel/p4.c (ffffffff8288e73d)
Location: arch/x86/include/asm/msr.h:287
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
Location: arch/x86/include/asm/msr.h:287
Inline: True
Inline callers:
  - arch/x86/events/intel/p6.c:p6_pmu_enable_event
  - arch/x86/events/intel/p6.c:p6_pmu_disable_event
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103641b)
Location: arch/x86/include/asm/msr.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8103a97f)
Location: arch/x86/include/asm/msr.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103ff02)
Location: arch/x86/include/asm/msr.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81042513)
Location: arch/x86/include/asm/msr.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810457f5)
Location: arch/x86/include/asm/msr.h:287
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82899307)
Location: arch/x86/include/asm/msr.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81052417)
Location: arch/x86/include/asm/msr.h:287
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/lib/msr-smp.c (ffffffff815458f9)
Location: arch/x86/include/asm/msr.h:287
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu
```
```
In arch/x86/lib/msr.c (ffffffff8154628d)
Location: arch/x86/include/asm/msr.h:287
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:msr_clear_bit
  - arch/x86/lib/msr.c:msr_set_bit
```
```
In drivers/acpi/processor_throttling.c (ffffffff815f0924)
Location: arch/x86/include/asm/msr.h:287
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff8184b0e5)
Location: arch/x86/include/asm/msr.h:287
Inline: True
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
