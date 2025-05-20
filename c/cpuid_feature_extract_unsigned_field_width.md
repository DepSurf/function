# Function: <code>cpuid_feature_extract_unsigned_field_width</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/debug-monitors.c (ffff800010086814)
Location: arch/arm64/include/asm/cpufeature.h:439
Inline: True
Inline callers:
  - arch/arm64/kernel/debug-monitors.c:debug_monitors_arch
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008f09c)
Location: arch/arm64/include/asm/cpufeature.h:439
Inline: True
```
```
In arch/arm64/kernel/cpuinfo.c (ffff800010097ff8)
Location: arch/arm64/include/asm/cpufeature.h:439
Inline: True
Inline callers:
  - arch/arm64/kernel/cpuinfo.c:__cpuinfo_store_cpu
  - arch/arm64/kernel/cpuinfo.c:__cpuinfo_store_cpu
```
```
In arch/arm64/kernel/cpu_errata.c (ffff8000100986fc)
Location: arch/arm64/include/asm/cpufeature.h:439
Inline: True
```
```
In arch/arm64/kernel/cpufeature.c (ffff80001009a92c)
Location: arch/arm64/include/asm/cpufeature.h:439
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:compat_has_neon
  - arch/arm64/kernel/cpufeature.c:compat_has_neon
  - arch/arm64/kernel/cpufeature.c:compat_has_neon
  - arch/arm64/kernel/cpufeature.c:update_cpu_features
  - arch/arm64/kernel/cpufeature.c:update_cpu_features
  - arch/arm64/kernel/cpufeature.c:update_cpu_features
  - arch/arm64/kernel/cpufeature.c:update_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
  - arch/arm64/kernel/cpufeature.c:init_cpu_features
```
```
In arch/arm64/kernel/alternative.c (ffff80001009b4c4)
Location: arch/arm64/include/asm/cpufeature.h:439
Inline: True
Inline callers:
  - arch/arm64/kernel/alternative.c:__apply_alternatives
```
```
In arch/arm64/kernel/perf_event.c (ffff8000100a3d6c)
Location: arch/arm64/include/asm/cpufeature.h:439
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_event.c:__armv8pmu_probe_pmu
```
```
In arch/arm64/kernel/hw_breakpoint.c (ffff800011435f38)
Location: arch/arm64/include/asm/cpufeature.h:439
Inline: True
Inline callers:
  - arch/arm64/kernel/hw_breakpoint.c:arch_hw_breakpoint_init
  - arch/arm64/kernel/hw_breakpoint.c:arch_hw_breakpoint_init
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_slots
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_slots
```
```
In arch/arm64/kernel/armv8_deprecated.c (ffff800011436550)
Location: arch/arm64/include/asm/cpufeature.h:439
Inline: True
Inline callers:
  - arch/arm64/kernel/armv8_deprecated.c:armv8_deprecated_init
  - arch/arm64/kernel/armv8_deprecated.c:armv8_deprecated_init
```
```
In arch/arm64/kernel/kexec_image.c (ffff8000100ab7d0)
Location: arch/arm64/include/asm/cpufeature.h:439
Inline: True
```
```
In arch/arm64/mm/context.c (ffff8000100af864)
Location: arch/arm64/include/asm/cpufeature.h:439
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:get_cpu_asid_bits
```
```
In virt/kvm/arm/arm.c (ffff8000100c7134)
Location: arch/arm64/include/asm/cpufeature.h:439
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
```
```
In arch/arm64/kvm/debug.c (ffff8000100d453c)
Location: arch/arm64/include/asm/cpufeature.h:439
Inline: True
Inline callers:
  - arch/arm64/kvm/debug.c:kvm_arm_clear_debug
  - arch/arm64/kvm/debug.c:kvm_arm_clear_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
```
```
In arch/arm64/kvm/reset.c (ffff8000100d4f88)
Location: arch/arm64/include/asm/cpufeature.h:439
Inline: True
Inline callers:
  - arch/arm64/kvm/reset.c:kvm_arm_setup_stage2
  - arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension
  - arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension
```
```
In arch/arm64/kvm/sys_regs.c (ffff8000100d67d4)
Location: arch/arm64/include/asm/cpufeature.h:439
Inline: True
```
```
In arch/arm64/kvm/hyp/debug-sr.c (ffff800010dadf68)
Location: arch/arm64/include/asm/cpufeature.h:439
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/debug-sr.c:__debug_switch_to_guest
```
</details>
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
