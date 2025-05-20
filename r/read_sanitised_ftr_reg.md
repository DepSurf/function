# Function: <code>read_sanitised_ftr_reg</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
u64 read_sanitised_ftr_reg(u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/cpufeature.c (ffff80001009a3e8)
Location: arch/arm64/kernel/cpufeature.c:800
Inline: True
Direct callers:
  - arch/arm64/kernel/debug-monitors.c:debug_monitors_arch
  - arch/arm64/kernel/fpsimd.c:sve_setup
  - arch/arm64/kernel/cpufeature.c:check_local_cpu_capabilities
  - arch/arm64/kernel/cpufeature.c:compat_has_neon
  - arch/arm64/kernel/cpufeature.c:has_no_fpsimd
  - arch/arm64/kernel/cpufeature.c:has_cpuid_feature
  - arch/arm64/kernel/cpufeature.c:update_cpu_features
  - arch/arm64/kernel/cpufeature.c:update_cpu_features
  - arch/arm64/kernel/alternative.c:__apply_alternatives
  - arch/arm64/kernel/hw_breakpoint.c:arch_hw_breakpoint_init
  - arch/arm64/kernel/hw_breakpoint.c:arch_hw_breakpoint_init
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_slots
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_slots
  - arch/arm64/kernel/armv8_deprecated.c:armv8_deprecated_init
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - arch/arm64/kvm/debug.c:kvm_arm_clear_debug
  - arch/arm64/kvm/debug.c:kvm_arm_clear_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/reset.c:kvm_arm_setup_stage2
  - arch/arm64/kvm/reset.c:kvm_arm_setup_stage2
  - arch/arm64/kvm/reset.c:kvm_set_ipa_limit
  - arch/arm64/kvm/reset.c:kvm_reset_vcpu
  - arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension
  - arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension
  - arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension
  - arch/arm64/kvm/sys_regs.c:get_ctr_el0
  - arch/arm64/kvm/sys_regs.c:trap_loregion
```
**Symbols:**

```
ffff80001009a3e8-ffff80001009a440: read_sanitised_ftr_reg (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
