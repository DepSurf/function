# Function: <code>system_supports_sve</code>

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
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool system_supports_sve();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/fpsimd.c (ffff80001008881c)
Location: arch/arm64/include/asm/cpufeature.h:578
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_end
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_begin
  - arch/arm64/kernel/fpsimd.c:fpsimd_update_current_state
  - arch/arm64/kernel/fpsimd.c:fpsimd_bind_task_to_cpu
  - arch/arm64/kernel/fpsimd.c:fpsimd_signal_preserve_current_state
  - arch/arm64/kernel/fpsimd.c:fpsimd_flush_thread
  - arch/arm64/kernel/fpsimd.c:do_sve_acc
  - arch/arm64/kernel/fpsimd.c:sve_get_current_vl
  - arch/arm64/kernel/fpsimd.c:sve_set_current_vl
  - arch/arm64/kernel/fpsimd.c:sve_to_fpsimd
  - arch/arm64/kernel/fpsimd.c:fpsimd_to_sve
  - arch/arm64/kernel/fpsimd.c:fpsimd_save
  - arch/arm64/kernel/fpsimd.c:task_fpsimd_load
Direct callers:
  - arch/arm64/kernel/fpsimd.c:fpsimd_init
  - arch/arm64/kernel/fpsimd.c:sve_setup
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008d2b8)
Location: arch/arm64/include/asm/cpufeature.h:578
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:sve_set
  - arch/arm64/kernel/ptrace.c:sve_get
```
```
In arch/arm64/kernel/signal.c (ffff8000100912c8)
Location: arch/arm64/include/asm/cpufeature.h:578
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
```
```
In arch/arm64/kernel/cpufeature.c (ffff80001009ae48)
Location: arch/arm64/include/asm/cpufeature.h:578
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:check_local_cpu_capabilities
```
```
In arch/arm64/kernel/syscall.c (ffff80001009daf0)
Location: arch/arm64/include/asm/cpufeature.h:578
Inline: True
Inline callers:
  - arch/arm64/kernel/syscall.c:el0_svc_handler
```
```
In virt/kvm/arm/arm.c (ffff8000100c7ed8)
Location: arch/arm64/include/asm/cpufeature.h:578
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_init
```
```
In arch/arm64/kvm/guest.c (ffff8000100d3710)
Location: arch/arm64/include/asm/cpufeature.h:578
Inline: True
Inline callers:
  - arch/arm64/kvm/guest.c:kvm_arm_set_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_num_regs
```
```
In arch/arm64/kvm/reset.c (ffff8000100d4ce0)
Location: arch/arm64/include/asm/cpufeature.h:578
Inline: True
Inline callers:
  - arch/arm64/kvm/reset.c:kvm_reset_vcpu
  - arch/arm64/kvm/reset.c:kvm_reset_vcpu
  - arch/arm64/kvm/reset.c:kvm_arm_vcpu_is_finalized
  - arch/arm64/kvm/reset.c:kvm_arm_vcpu_finalize
  - arch/arm64/kvm/reset.c:kvm_arm_init_sve
  - arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension
```
```
In arch/arm64/kvm/sys_regs.c (ffff8000100d8478)
Location: arch/arm64/include/asm/cpufeature.h:578
Inline: True
Inline callers:
  - arch/arm64/kvm/sys_regs.c:set_id_aa64zfr0_el1
  - arch/arm64/kvm/sys_regs.c:get_id_aa64zfr0_el1
```
```
In arch/arm64/kvm/fpsimd.c (ffff8000100dad44)
Location: arch/arm64/include/asm/cpufeature.h:578
Inline: True
Inline callers:
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_put_fp
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_put_fp
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_ctxsync_fp
```
```
In arch/arm64/kvm/hyp/switch.c (ffff800010dae798)
Location: arch/arm64/include/asm/cpufeature.h:578
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/switch.c:fixup_guest_exit
  - arch/arm64/kvm/hyp/switch.c:fixup_guest_exit
  - arch/arm64/kvm/hyp/switch.c:activate_traps_vhe
```
**Symbols:**

```
ffff800010086fd8-ffff800010087000: system_supports_sve (STB_LOCAL)
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
