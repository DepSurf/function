# Function: <code>uaccess_disable_not_uao</code>

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
void uaccess_disable_not_uao();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/debug-monitors.c (ffff8000100865d4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - arch/arm64/kernel/debug-monitors.c:aarch32_break_handler
  - arch/arm64/kernel/debug-monitors.c:aarch32_break_handler
  - arch/arm64/kernel/debug-monitors.c:aarch32_break_handler
  - arch/arm64/kernel/debug-monitors.c:aarch32_break_handler
  - arch/arm64/kernel/debug-monitors.c:aarch32_break_handler
  - arch/arm64/kernel/debug-monitors.c:aarch32_break_handler
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008bce8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:compat_tls_set
  - arch/arm64/kernel/ptrace.c:compat_tls_set
  - arch/arm64/kernel/ptrace.c:compat_tls_get
  - arch/arm64/kernel/ptrace.c:compat_tls_get
  - arch/arm64/kernel/ptrace.c:compat_vfp_set
  - arch/arm64/kernel/ptrace.c:compat_vfp_set
  - arch/arm64/kernel/ptrace.c:compat_vfp_get
  - arch/arm64/kernel/ptrace.c:compat_vfp_get
  - arch/arm64/kernel/ptrace.c:compat_gpr_set
  - arch/arm64/kernel/ptrace.c:compat_gpr_set
  - arch/arm64/kernel/ptrace.c:compat_gpr_get
  - arch/arm64/kernel/ptrace.c:compat_gpr_get
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_set
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_set
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_get
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_get
  - arch/arm64/kernel/ptrace.c:pac_address_keys_set
  - arch/arm64/kernel/ptrace.c:pac_address_keys_set
  - arch/arm64/kernel/ptrace.c:pac_address_keys_get
  - arch/arm64/kernel/ptrace.c:pac_address_keys_get
  - arch/arm64/kernel/ptrace.c:pac_mask_get
  - arch/arm64/kernel/ptrace.c:pac_mask_get
  - arch/arm64/kernel/ptrace.c:system_call_set
  - arch/arm64/kernel/ptrace.c:system_call_set
  - arch/arm64/kernel/ptrace.c:system_call_get
  - arch/arm64/kernel/ptrace.c:system_call_get
  - arch/arm64/kernel/ptrace.c:tls_set
  - arch/arm64/kernel/ptrace.c:tls_set
  - arch/arm64/kernel/ptrace.c:tls_get
  - arch/arm64/kernel/ptrace.c:tls_get
  - arch/arm64/kernel/ptrace.c:fpr_get
  - arch/arm64/kernel/ptrace.c:fpr_get
  - arch/arm64/kernel/ptrace.c:gpr_set
  - arch/arm64/kernel/ptrace.c:gpr_set
  - arch/arm64/kernel/ptrace.c:gpr_get
  - arch/arm64/kernel/ptrace.c:gpr_get
  - arch/arm64/kernel/ptrace.c:hw_break_set
  - arch/arm64/kernel/ptrace.c:hw_break_set
  - arch/arm64/kernel/ptrace.c:hw_break_set
  - arch/arm64/kernel/ptrace.c:hw_break_set
  - arch/arm64/kernel/ptrace.c:hw_break_get
  - arch/arm64/kernel/ptrace.c:hw_break_get
  - arch/arm64/kernel/ptrace.c:hw_break_get
  - arch/arm64/kernel/ptrace.c:hw_break_get
Direct callers:
  - arch/arm64/kernel/ptrace.c:compat_arch_ptrace
  - arch/arm64/kernel/ptrace.c:compat_arch_ptrace
  - arch/arm64/kernel/ptrace.c:sve_set
  - arch/arm64/kernel/ptrace.c:sve_get
  - arch/arm64/kernel/ptrace.c:sve_get
  - arch/arm64/kernel/ptrace.c:hw_break_get
  - arch/arm64/kernel/ptrace.c:hw_break_get
```
```
In arch/arm64/kernel/signal.c (ffff800010090fd4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
Direct callers:
  - arch/arm64/kernel/signal.c:setup_rt_frame
  - arch/arm64/kernel/signal.c:setup_rt_frame
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:setup_sigframe
```
```
In arch/arm64/kernel/traps.c (ffff800010094674)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:call_undef_hook
```
```
In arch/arm64/kernel/signal32.c (ffff8000100a14c4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - arch/arm64/kernel/signal32.c:compat_setup_frame
  - arch/arm64/kernel/signal32.c:compat_setup_frame
  - arch/arm64/kernel/signal32.c:compat_setup_rt_frame
  - arch/arm64/kernel/signal32.c:compat_setup_rt_frame
  - arch/arm64/kernel/signal32.c:compat_setup_rt_frame
  - arch/arm64/kernel/signal32.c:compat_setup_rt_frame
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_restore_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
  - arch/arm64/kernel/signal32.c:compat_preserve_vfp_context
Direct callers:
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
```
```
In arch/arm64/kernel/perf_callchain.c (ffff8000100a35d4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
```
```
In arch/arm64/kernel/crash_dump.c (ffff8000100ab9f4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - arch/arm64/kernel/crash_dump.c:copy_oldmem_page
```
```
In virt/kvm/kvm_main.c (ffff8000100bdb68)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_read_guest_cached
  - virt/kvm/kvm_main.c:kvm_read_guest_cached
  - virt/kvm/kvm_main.c:kvm_write_guest_offset_cached
  - virt/kvm/kvm_main.c:kvm_write_guest_offset_cached
  - virt/kvm/kvm_main.c:__kvm_write_guest_page
  - virt/kvm/kvm_main.c:__kvm_write_guest_page
  - virt/kvm/kvm_main.c:__kvm_read_guest_atomic
  - virt/kvm/kvm_main.c:__kvm_read_guest_atomic
  - virt/kvm/kvm_main.c:__kvm_read_guest_page
  - virt/kvm/kvm_main.c:__kvm_read_guest_page
  - virt/kvm/kvm_main.c:kvm_get_dirty_log_protect
  - virt/kvm/kvm_main.c:kvm_get_dirty_log_protect
  - virt/kvm/kvm_main.c:kvm_get_dirty_log
  - virt/kvm/kvm_main.c:kvm_get_dirty_log
  - virt/kvm/kvm_main.c:_copy_from_user
  - virt/kvm/kvm_main.c:_copy_from_user
```
```
In virt/kvm/vfio.c (ffff8000100c2298)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - virt/kvm/vfio.c:kvm_vfio_set_group
  - virt/kvm/vfio.c:kvm_vfio_set_group
  - virt/kvm/vfio.c:kvm_vfio_set_group
  - virt/kvm/vfio.c:kvm_vfio_set_group
```
```
In virt/kvm/arm/arm.c (ffff8000100c78b0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl
  - virt/kvm/arm/arm.c:_copy_to_user
  - virt/kvm/arm/arm.c:_copy_to_user
  - virt/kvm/arm/arm.c:_copy_from_user
  - virt/kvm/arm/arm.c:_copy_from_user
```
```
In virt/kvm/arm/psci.c (ffff8000100cee28)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - virt/kvm/arm/psci.c:kvm_arm_set_fw_reg
  - virt/kvm/arm/psci.c:kvm_arm_set_fw_reg
  - virt/kvm/arm/psci.c:kvm_arm_get_fw_reg
  - virt/kvm/arm/psci.c:kvm_arm_get_fw_reg
  - virt/kvm/arm/psci.c:kvm_arm_copy_fw_reg_indices
  - virt/kvm/arm/psci.c:kvm_arm_copy_fw_reg_indices
  - virt/kvm/arm/psci.c:kvm_arm_copy_fw_reg_indices
  - virt/kvm/arm/psci.c:kvm_arm_copy_fw_reg_indices
  - virt/kvm/arm/psci.c:kvm_arm_copy_fw_reg_indices
  - virt/kvm/arm/psci.c:kvm_arm_copy_fw_reg_indices
```
```
In arch/arm64/kvm/guest.c (ffff8000100d3074)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices
  - arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices
  - arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices
  - arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices
  - arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices
  - arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices
  - arch/arm64/kvm/guest.c:copy_core_reg_indices
  - arch/arm64/kvm/guest.c:copy_core_reg_indices
  - arch/arm64/kvm/guest.c:_copy_from_user
  - arch/arm64/kvm/guest.c:_copy_from_user
```
```
In arch/arm64/kvm/sys_regs.c (ffff8000100d9e54)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - arch/arm64/kvm/sys_regs.c:kvm_arm_copy_sys_reg_indices
  - arch/arm64/kvm/sys_regs.c:kvm_arm_copy_sys_reg_indices
  - arch/arm64/kvm/sys_regs.c:kvm_arm_copy_sys_reg_indices
  - arch/arm64/kvm/sys_regs.c:kvm_arm_copy_sys_reg_indices
  - arch/arm64/kvm/sys_regs.c:walk_one_sys_reg
  - arch/arm64/kvm/sys_regs.c:walk_one_sys_reg
  - arch/arm64/kvm/sys_regs.c:kvm_arm_sys_reg_set_reg
  - arch/arm64/kvm/sys_regs.c:kvm_arm_sys_reg_set_reg
  - arch/arm64/kvm/sys_regs.c:kvm_arm_sys_reg_get_reg
  - arch/arm64/kvm/sys_regs.c:kvm_arm_sys_reg_get_reg
  - arch/arm64/kvm/sys_regs.c:reg_to_user
  - arch/arm64/kvm/sys_regs.c:reg_to_user
  - arch/arm64/kvm/sys_regs.c:get_wcr
  - arch/arm64/kvm/sys_regs.c:get_wcr
  - arch/arm64/kvm/sys_regs.c:get_wvr
  - arch/arm64/kvm/sys_regs.c:get_wvr
  - arch/arm64/kvm/sys_regs.c:get_bcr
  - arch/arm64/kvm/sys_regs.c:get_bcr
  - arch/arm64/kvm/sys_regs.c:get_bvr
  - arch/arm64/kvm/sys_regs.c:get_bvr
  - arch/arm64/kvm/sys_regs.c:_copy_from_user
  - arch/arm64/kvm/sys_regs.c:_copy_from_user
```
```
In virt/kvm/arm/vgic/vgic-kvm-device.c (ffff8000100e6290)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-kvm-device.c:vgic_v2_get_attr
  - virt/kvm/arm/vgic/vgic-kvm-device.c:vgic_v2_get_attr
  - virt/kvm/arm/vgic/vgic-kvm-device.c:vgic_v2_set_attr
  - virt/kvm/arm/vgic/vgic-kvm-device.c:vgic_v2_set_attr
```
```
In virt/kvm/arm/vgic/vgic-its.c (ffff8000100e99c8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_set_attr
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_set_attr
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_set_attr
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_set_attr
```
```
In virt/kvm/arm/arch_timer.c (ffff8000100ee208)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - virt/kvm/arm/arch_timer.c:kvm_arm_timer_get_attr
  - virt/kvm/arm/arch_timer.c:kvm_arm_timer_get_attr
  - virt/kvm/arm/arch_timer.c:kvm_arm_timer_set_attr
  - virt/kvm/arm/arch_timer.c:kvm_arm_timer_set_attr
```
```
In virt/kvm/arm/pmu.c (ffff8000100ef7c8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - virt/kvm/arm/pmu.c:kvm_arm_pmu_v3_get_attr
  - virt/kvm/arm/pmu.c:kvm_arm_pmu_v3_get_attr
  - virt/kvm/arm/pmu.c:kvm_arm_pmu_v3_set_attr
  - virt/kvm/arm/pmu.c:kvm_arm_pmu_v3_set_attr
```
```
In kernel/fork.c (ffff8000100f2118)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
  - kernel/fork.c:mm_release
```
```
In kernel/exit.c (ffff8000100fc834)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/sysctl.c (ffff800010102d64)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:_proc_do_string
  - kernel/sysctl.c:_proc_do_string
  - kernel/sysctl.c:_proc_do_string
  - kernel/sysctl.c:_proc_do_string
  - kernel/sysctl.c:_proc_do_string
  - kernel/sysctl.c:_proc_do_string
```
```
In kernel/sysctl_binary.c (ffff800010105624)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:__arm64_compat_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_compat_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_compat_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_compat_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_compat_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_compat_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_sys_sysctl
```
```
In kernel/capability.c (ffff8000101063e8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/capability.c:__arm64_sys_capset
  - kernel/capability.c:__arm64_sys_capset
  - kernel/capability.c:__arm64_sys_capset
  - kernel/capability.c:__arm64_sys_capset
  - kernel/capability.c:__arm64_sys_capget
  - kernel/capability.c:__arm64_sys_capget
  - kernel/capability.c:__arm64_sys_capget
  - kernel/capability.c:__arm64_sys_capget
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
  - kernel/capability.c:cap_validate_magic
```
```
In kernel/ptrace.c (ffff800010109c54)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:generic_ptrace_peekdata
  - kernel/ptrace.c:generic_ptrace_peekdata
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_writedata
  - kernel/ptrace.c:ptrace_writedata
  - kernel/ptrace.c:ptrace_readdata
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (ffff80001010e638)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_rt_sigsuspend
  - kernel/signal.c:__arm64_sys_rt_sigsuspend
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__arm64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__arm64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__arm64_sys_rt_sigtimedwait
  - kernel/signal.c:__arm64_sys_rt_sigtimedwait
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
Direct callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__arm64_sys_rt_sigaction
  - kernel/signal.c:__arm64_sys_sigprocmask
  - kernel/signal.c:__arm64_sys_sigprocmask
  - kernel/signal.c:__arm64_compat_sys_sigpending
  - kernel/signal.c:__arm64_sys_sigpending
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__save_altstack
  - kernel/signal.c:__arm64_sys_sigaltstack
  - kernel/signal.c:__arm64_sys_sigaltstack
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__arm64_compat_sys_rt_sigpending
  - kernel/signal.c:__arm64_sys_rt_sigpending
  - kernel/signal.c:__arm64_compat_sys_rt_sigprocmask
  - kernel/signal.c:__arm64_sys_rt_sigprocmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:_copy_from_user
```
```
In kernel/sys.c (ffff8000101176e4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__arm64_sys_getcpu
  - kernel/sys.c:__arm64_sys_getcpu
  - kernel/sys.c:__arm64_sys_getcpu
  - kernel/sys.c:__arm64_sys_getcpu
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__arm64_sys_setrlimit
  - kernel/sys.c:__arm64_sys_setrlimit
  - kernel/sys.c:__arm64_sys_prlimit64
  - kernel/sys.c:__arm64_sys_prlimit64
  - kernel/sys.c:__arm64_compat_sys_getrlimit
  - kernel/sys.c:__arm64_compat_sys_getrlimit
  - kernel/sys.c:__arm64_compat_sys_setrlimit
  - kernel/sys.c:__arm64_compat_sys_setrlimit
  - kernel/sys.c:__arm64_sys_setdomainname
  - kernel/sys.c:__arm64_sys_setdomainname
  - kernel/sys.c:__arm64_sys_gethostname
  - kernel/sys.c:__arm64_sys_gethostname
  - kernel/sys.c:__arm64_sys_sethostname
  - kernel/sys.c:__arm64_sys_sethostname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__arm64_compat_sys_times
  - kernel/sys.c:__arm64_compat_sys_times
  - kernel/sys.c:__arm64_sys_times
  - kernel/sys.c:__arm64_sys_times
  - kernel/sys.c:__arm64_sys_getresgid
  - kernel/sys.c:__arm64_sys_getresgid
  - kernel/sys.c:__arm64_sys_getresuid
  - kernel/sys.c:__arm64_sys_getresuid
Direct callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__arm64_sys_prctl
  - kernel/sys.c:__arm64_sys_prctl
  - kernel/sys.c:__arm64_sys_prctl
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__arm64_sys_prlimit64
  - kernel/sys.c:__arm64_sys_getrlimit
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__arm64_sys_getresgid
  - kernel/sys.c:__arm64_sys_getresgid
  - kernel/sys.c:__arm64_sys_getresuid
  - kernel/sys.c:__arm64_sys_getresuid
```
```
In kernel/groups.c (ffff80001013100c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/groups.c:groups_from_user
  - kernel/groups.c:groups_from_user
  - kernel/groups.c:groups_to_user
  - kernel/groups.c:groups_to_user
```
```
In kernel/sched/core.c (ffff80001013ca38)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/sched/core.c:__arm64_sys_sched_getaffinity
  - kernel/sched/core.c:__arm64_sys_sched_getaffinity
  - kernel/sched/core.c:__arm64_sys_sched_getattr
  - kernel/sched/core.c:__arm64_sys_sched_getattr
  - kernel/sched/core.c:__arm64_sys_sched_getparam
  - kernel/sched/core.c:__arm64_sys_sched_getparam
  - kernel/sched/core.c:__arm64_sys_sched_setattr
  - kernel/sched/core.c:__arm64_sys_sched_setattr
  - kernel/sched/core.c:__arm64_sys_sched_setattr
  - kernel/sched/core.c:__arm64_sys_sched_setattr
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/core.c:_copy_from_user
  - kernel/sched/core.c:_copy_from_user
```
```
In kernel/sched/debug.c (ffff800010160c90)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/sched/psi.c (ffff8000101681c4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
```
```
In kernel/power/qos.c (ffff80001016d884)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_write
```
```
In kernel/printk/printk.c (ffff800010173734)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/kcmp.c (ffff800010197a3c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/profile.c (ffff8000101994f4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/profile.c:write_profile
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
  - kernel/profile.c:read_profile
  - kernel/profile.c:read_profile
  - kernel/profile.c:read_profile
```
```
In kernel/time/time.c (ffff80001019b448)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_old_timespec32
  - kernel/time/time.c:put_old_timespec32
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__arm64_compat_sys_gettimeofday
  - kernel/time/time.c:__arm64_compat_sys_gettimeofday
  - kernel/time/time.c:__arm64_compat_sys_gettimeofday
  - kernel/time/time.c:__arm64_compat_sys_gettimeofday
  - kernel/time/time.c:__arm64_compat_sys_gettimeofday
  - kernel/time/time.c:__arm64_compat_sys_gettimeofday
  - kernel/time/time.c:__arm64_sys_gettimeofday
  - kernel/time/time.c:__arm64_sys_gettimeofday
  - kernel/time/time.c:__arm64_sys_gettimeofday
  - kernel/time/time.c:__arm64_sys_gettimeofday
  - kernel/time/time.c:__arm64_sys_gettimeofday
  - kernel/time/time.c:__arm64_sys_gettimeofday
  - kernel/time/time.c:_copy_from_user
  - kernel/time/time.c:_copy_from_user
```
```
In kernel/time/posix-timers.c (ffff8000101acd0c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:_copy_from_user
  - kernel/time/posix-timers.c:_copy_from_user
```
```
In kernel/time/itimer.c (ffff8000101b0110)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/time/itimer.c:__arm64_sys_setitimer
  - kernel/time/itimer.c:__arm64_sys_setitimer
```
```
In kernel/futex.c (ffff8000101b734c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/futex.c:__arm64_compat_sys_get_robust_list
  - kernel/futex.c:__arm64_compat_sys_get_robust_list
  - kernel/futex.c:__arm64_compat_sys_get_robust_list
  - kernel/futex.c:__arm64_compat_sys_get_robust_list
  - kernel/futex.c:compat_fetch_robust_entry
  - kernel/futex.c:compat_fetch_robust_entry
  - kernel/futex.c:fetch_robust_entry
  - kernel/futex.c:fetch_robust_entry
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:__arm64_sys_get_robust_list
  - kernel/futex.c:__arm64_sys_get_robust_list
  - kernel/futex.c:__arm64_sys_get_robust_list
  - kernel/futex.c:__arm64_sys_get_robust_list
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:get_futex_value_locked
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
```
In kernel/uid16.c (ffff8000101be0f0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/uid16.c:__arm64_sys_setgroups16
  - kernel/uid16.c:__arm64_sys_setgroups16
  - kernel/uid16.c:__arm64_sys_getgroups16
  - kernel/uid16.c:__arm64_sys_getgroups16
  - kernel/uid16.c:__arm64_sys_getresgid16
  - kernel/uid16.c:__arm64_sys_getresgid16
  - kernel/uid16.c:__arm64_sys_getresgid16
  - kernel/uid16.c:__arm64_sys_getresgid16
  - kernel/uid16.c:__arm64_sys_getresgid16
  - kernel/uid16.c:__arm64_sys_getresgid16
  - kernel/uid16.c:__arm64_sys_getresuid16
  - kernel/uid16.c:__arm64_sys_getresuid16
  - kernel/uid16.c:__arm64_sys_getresuid16
  - kernel/uid16.c:__arm64_sys_getresuid16
  - kernel/uid16.c:__arm64_sys_getresuid16
  - kernel/uid16.c:__arm64_sys_getresuid16
```
```
In kernel/module.c (ffff8000101c13ec)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/module.c:copy_chunked_from_user
```
```
In kernel/kexec_core.c (ffff8000101c8c70)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/kexec_core.c:_copy_from_user
```
```
In kernel/kexec.c (ffff8000101ca5cc)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/kexec.c:__arm64_compat_sys_kexec_load
  - kernel/kexec.c:__arm64_compat_sys_kexec_load
  - kernel/kexec.c:_copy_from_user
  - kernel/kexec.c:_copy_from_user
```
```
In kernel/compat.c (ffff8000101cc4ec)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/compat.c:get_compat_sigset
  - kernel/compat.c:get_compat_sigset
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:get_compat_sigevent
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:__arm64_compat_sys_sigprocmask
  - kernel/compat.c:__arm64_compat_sys_sigprocmask
  - kernel/compat.c:__arm64_compat_sys_sigprocmask
  - kernel/compat.c:__arm64_compat_sys_sigprocmask
  - kernel/compat.c:put_compat_itimerval
  - kernel/compat.c:put_compat_itimerval
  - kernel/compat.c:get_compat_itimerval
  - kernel/compat.c:get_compat_itimerval
  - kernel/compat.c:compat_put_timespec
  - kernel/compat.c:compat_put_timespec
  - kernel/compat.c:compat_put_timespec
  - kernel/compat.c:compat_put_timespec
  - kernel/compat.c:compat_get_timespec
  - kernel/compat.c:compat_get_timespec
  - kernel/compat.c:compat_get_timespec
  - kernel/compat.c:compat_get_timespec
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_get_timeval
  - kernel/compat.c:compat_get_timeval
  - kernel/compat.c:compat_get_timeval
  - kernel/compat.c:compat_get_timeval
```
```
In kernel/user_namespace.c (ffff8000101e6e08)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_setgroups_write
```
```
In kernel/kprobes.c (ffff8000101f81b0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
```
```
In kernel/seccomp.c (ffff80001020a684)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:_copy_from_user
  - kernel/seccomp.c:_copy_from_user
```
```
In kernel/relay.c (ffff80001020c41c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/trace/trace.c (ffff800010221ee4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:trace_get_user
  - kernel/trace/trace.c:_copy_from_user
  - kernel/trace/trace.c:_copy_from_user
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_read
```
```
In kernel/trace/blktrace.c (ffff800010236ae8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
```
In kernel/trace/bpf_trace.c (ffff80001024ea34)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:_copy_to_user
  - kernel/trace/bpf_trace.c:_copy_to_user
```
```
In kernel/trace/trace_uprobe.c (ffff800010259708)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:_copy_from_user
```
```
In kernel/bpf/core.c (ffff80001025f22c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
```
```
In kernel/bpf/syscall.c (ffff800010264f18)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/verifier.c (ffff8000102695c0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - kernel/bpf/verifier.c:bpf_verifier_vlog
```
```
In kernel/bpf/btf.c (ffff800010285e98)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:_copy_from_user
  - kernel/bpf/btf.c:_copy_from_user
```
```
In kernel/bpf/offload.c (ffff80001028af7c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/bpf/cgroup.c (ffff80001028e4a0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:_copy_from_user
  - kernel/bpf/cgroup.c:_copy_from_user
```
```
In kernel/events/core.c (ffff800010298840)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:_copy_from_user
  - kernel/events/core.c:_copy_from_user
Direct callers:
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:_perf_ioctl
```
```
In kernel/events/uprobes.c (ffff8000102a5a90)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/events/uprobes.c:is_trap_at_addr
```
```
In kernel/rseq.c (ffff8000102ac424)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - kernel/rseq.c:__arm64_sys_rseq
  - kernel/rseq.c:__arm64_sys_rseq
  - kernel/rseq.c:__arm64_sys_rseq
  - kernel/rseq.c:__arm64_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
Direct callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/maccess.c (ffff8000102b9d70)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:strncpy_from_unsafe
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_kernel_write
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/maccess.c:__probe_kernel_read
```
```
In mm/shmem.c (ffff8000102d34f4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/util.c (ffff8000102d8588)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - mm/util.c:_copy_from_user
```
```
In mm/memory.c (ffff8000102fc294)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffff8000102fd38c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mempolicy.c (ffff80001033819c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_compat_sys_mbind
  - mm/mempolicy.c:__arm64_compat_sys_mbind
  - mm/mempolicy.c:__arm64_compat_sys_set_mempolicy
  - mm/mempolicy.c:__arm64_compat_sys_set_mempolicy
  - mm/mempolicy.c:__arm64_compat_sys_get_mempolicy
  - mm/mempolicy.c:__arm64_compat_sys_get_mempolicy
  - mm/mempolicy.c:__arm64_compat_sys_get_mempolicy
  - mm/mempolicy.c:__arm64_compat_sys_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:get_nodes
```
```
In mm/migrate.c (ffff8000103528d4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - mm/migrate.c:__arm64_compat_sys_move_pages
  - mm/migrate.c:__arm64_compat_sys_move_pages
  - mm/migrate.c:__arm64_compat_sys_move_pages
  - mm/migrate.c:__arm64_compat_sys_move_pages
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:store_status
  - mm/migrate.c:store_status
```
```
In mm/userfaultfd.c (ffff800010377f24)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
```
```
In mm/memfd.c (ffff80001037c2b8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - mm/memfd.c:__arm64_sys_memfd_create
```
```
In fs/read_write.c (ffff800010383c78)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_compat_sys_sendfile64
  - fs/read_write.c:__arm64_compat_sys_sendfile64
  - fs/read_write.c:__arm64_compat_sys_sendfile64
  - fs/read_write.c:__arm64_compat_sys_sendfile64
  - fs/read_write.c:__arm64_compat_sys_sendfile
  - fs/read_write.c:__arm64_compat_sys_sendfile
  - fs/read_write.c:__arm64_compat_sys_sendfile
  - fs/read_write.c:__arm64_compat_sys_sendfile
  - fs/read_write.c:__arm64_sys_sendfile64
  - fs/read_write.c:__arm64_sys_sendfile64
  - fs/read_write.c:__arm64_sys_sendfile64
  - fs/read_write.c:__arm64_sys_sendfile64
  - fs/read_write.c:__arm64_sys_sendfile
  - fs/read_write.c:__arm64_sys_sendfile
  - fs/read_write.c:__arm64_sys_sendfile
  - fs/read_write.c:__arm64_sys_sendfile
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:compat_rw_copy_check_uvector
  - fs/read_write.c:__arm64_sys_llseek
  - fs/read_write.c:__arm64_sys_llseek
```
```
In fs/stat.c (ffff80001038ab94)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
```
```
In fs/exec.c (ffff80001038d674)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
```
```
In fs/pipe.c (ffff800010391594)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:pipe_ioctl
  - fs/pipe.c:pipe_ioctl
```
```
In fs/namei.c (ffff80001039ae00)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/namei.c:readlink_copy
```
```
In fs/fcntl.c (ffff80001039c81c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:_copy_from_user
  - fs/fcntl.c:_copy_from_user
```
```
In fs/ioctl.c (ffff80001039e584)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:ioctl_preallocate
  - fs/ioctl.c:ioctl_preallocate
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/ioctl.c:fiemap_fill_next_extent
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/readdir.c (ffff80001039fce0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/readdir.c:__arm64_compat_sys_getdents
  - fs/readdir.c:__arm64_compat_sys_getdents
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:ksys_getdents64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir64
  - fs/readdir.c:__arm64_sys_getdents
  - fs/readdir.c:__arm64_sys_getdents
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir
```
```
In fs/select.c (ffff8000103a4184)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/select.c:__arm64_compat_sys_pselect6_time32
  - fs/select.c:__arm64_compat_sys_pselect6_time32
  - fs/select.c:__arm64_compat_sys_pselect6_time32
  - fs/select.c:__arm64_compat_sys_pselect6_time32
  - fs/select.c:__arm64_compat_sys_pselect6_time64
  - fs/select.c:__arm64_compat_sys_pselect6_time64
  - fs/select.c:__arm64_compat_sys_pselect6_time64
  - fs/select.c:__arm64_compat_sys_pselect6_time64
  - fs/select.c:__arm64_compat_sys_old_select
  - fs/select.c:__arm64_compat_sys_old_select
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:do_sys_poll
  - fs/select.c:__arm64_sys_pselect6
  - fs/select.c:__arm64_sys_pselect6
  - fs/select.c:__arm64_sys_pselect6
  - fs/select.c:__arm64_sys_pselect6
  - fs/select.c:__arm64_sys_select
  - fs/select.c:__arm64_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:poll_select_finish
  - fs/select.c:poll_select_finish
  - fs/select.c:poll_select_finish
```
```
In fs/filesystems.c (ffff8000103b351c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/filesystems.c:fs_name
```
```
In fs/namespace.c (ffff8000103b47c8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/namespace.c:exact_copy_from_user
```
```
In fs/seq_file.c (ffff8000103bce48)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (ffff8000103bf09c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/xattr.c:setxattr
  - fs/xattr.c:setxattr
```
```
In fs/libfs.c (ffff8000103c1c04)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/libfs.c:simple_read_from_buffer
  - fs/libfs.c:simple_read_from_buffer
  - fs/libfs.c:_copy_from_user
  - fs/libfs.c:_copy_from_user
```
```
In fs/splice.c (ffff8000103cea10)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
```
```
In fs/utimes.c (ffff8000103d1024)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:do_compat_futimesat
  - fs/utimes.c:__arm64_sys_utime32
  - fs/utimes.c:__arm64_sys_utime32
  - fs/utimes.c:__arm64_sys_utime32
  - fs/utimes.c:__arm64_sys_utime32
```
```
In fs/d_path.c (ffff8000103d1ff8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/d_path.c:__arm64_sys_getcwd
```
```
In fs/statfs.c (ffff8000103d317c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
```
```
In fs/nsfs.c (ffff8000103d4a04)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/nsfs.c:ns_ioctl
```
```
In fs/fsopen.c (ffff8000103d745c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/fsopen.c:fscontext_read
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ecca8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_ioctl
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103ef568)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_ioctl
  - fs/notify/fanotify/fanotify_user.c:fanotify_ioctl
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
```
```
In fs/eventpoll.c (ffff8000103f1dbc)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
```
```
In fs/signalfd.c (ffff8000103f3dac)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
```
```
In fs/timerfd.c (ffff8000103f5360)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffff8000103f6398)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffff8000103f8a00)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:_copy_from_user
  - fs/userfaultfd.c:_copy_from_user
```
```
In fs/aio.c (ffff8000103fcd24)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/aio.c:__arm64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__arm64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__arm64_compat_sys_io_pgetevents
  - fs/aio.c:__arm64_compat_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_cancel
  - fs/aio.c:__arm64_sys_io_cancel
  - fs/aio.c:__arm64_compat_sys_io_submit
  - fs/aio.c:__arm64_compat_sys_io_submit
  - fs/aio.c:__arm64_sys_io_submit
  - fs/aio.c:__arm64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:__arm64_compat_sys_io_setup
  - fs/aio.c:__arm64_compat_sys_io_setup
  - fs/aio.c:__arm64_compat_sys_io_setup
  - fs/aio.c:__arm64_compat_sys_io_setup
  - fs/aio.c:__arm64_sys_io_setup
  - fs/aio.c:__arm64_sys_io_setup
  - fs/aio.c:__arm64_sys_io_setup
  - fs/aio.c:__arm64_sys_io_setup
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:lookup_ioctx
```
```
In fs/io_uring.c (ffff80001040403c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_setup
  - fs/io_uring.c:io_uring_setup
  - fs/io_uring.c:_copy_from_user
  - fs/io_uring.c:_copy_from_user
```
```
In fs/crypto/keyring.c (ffff80001040e380)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:_copy_from_user
  - fs/crypto/keyring.c:_copy_from_user
```
```
In fs/crypto/policy.c (ffff8000104109a4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/crypto/policy.c:_copy_from_user
  - fs/crypto/policy.c:_copy_from_user
```
```
In fs/verity/enable.c (ffff800010411500)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/verity/enable.c:_copy_from_user
```
```
In fs/verity/measure.c (ffff800010412634)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
```
```
In fs/compat_ioctl.c (ffff80001041d63c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans
  - fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans
  - fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans
  - fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans
  - fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans
  - fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans
  - fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans
  - fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_build_iovec
  - fs/compat_ioctl.c:sg_build_iovec
  - fs/compat_ioctl.c:sg_build_iovec
  - fs/compat_ioctl.c:sg_build_iovec
  - fs/compat_ioctl.c:sg_build_iovec
  - fs/compat_ioctl.c:sg_build_iovec
  - fs/compat_ioctl.c:sg_build_iovec
  - fs/compat_ioctl.c:sg_build_iovec
  - fs/compat_ioctl.c:sg_build_iovec
  - fs/compat_ioctl.c:sg_build_iovec
Direct callers:
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
```
```
In fs/binfmt_elf.c (ffff800010420998)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
Direct callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffff800010421a7c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
Direct callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/fhandle.c (ffff8000104299d0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/fhandle.c:__arm64_sys_name_to_handle_at
  - fs/fhandle.c:__arm64_sys_name_to_handle_at
  - fs/fhandle.c:__arm64_sys_name_to_handle_at
  - fs/fhandle.c:__arm64_sys_name_to_handle_at
  - fs/fhandle.c:_copy_from_user
  - fs/fhandle.c:_copy_from_user
```
```
In fs/quota/quota.c (ffff8000104359a0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/quota/quota.c:_copy_from_user
  - fs/quota/quota.c:_copy_from_user
```
```
In fs/proc/task_mmu.c (ffff80001043a8a4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffff80001043f3f8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/proc/base.c:_copy_from_user
  - fs/proc/base.c:_copy_from_user
```
```
In fs/proc/kcore.c (ffff80001044de54)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/proc/kcore.c:_copy_to_user
  - fs/proc/kcore.c:_copy_to_user
```
```
In fs/proc/vmcore.c (ffff80001044ebf8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
```
```
In fs/proc/page.c (ffff80001044fb8c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
  - fs/proc/page.c:kpagecount_read
```
```
In fs/kernfs/file.c (ffff80001045557c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_read
```
```
In fs/configfs/file.c (ffff8000104596a4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_write_file
```
```
In fs/dcookies.c (ffff80001045f5c8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/dcookies.c:do_lookup_dcookie
```
```
In fs/ext4/ioctl.c (ffff80001048d694)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:_copy_from_user
  - fs/ext4/ioctl.c:_copy_from_user
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/fat/dir.c (ffff8000104e69b0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_compat_dir_ioctl
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_dir_ioctl
  - fs/fat/dir.c:fat_dir_ioctl
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
Direct callers:
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
```
```
In fs/fat/file.c (ffff8000104eb2dc)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/miscdev.c (ffff8000104fe0f4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/fuse/dev.c (ffff800010501b90)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
```
```
In fs/efivarfs/file.c (ffff80001051bba4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
```
```
In ipc/compat.c (ffff80001051c800)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - ipc/compat.c:_copy_from_user
```
```
In ipc/msgutil.c (ffff80001051e364)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - ipc/msgutil.c:_copy_to_user
  - ipc/msgutil.c:_copy_to_user
  - ipc/msgutil.c:_copy_from_user
  - ipc/msgutil.c:_copy_from_user
```
```
In ipc/msg.c (ffff80001051f0ec)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:compat_do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/msg.c:do_msg_fill
  - ipc/msg.c:compat_ksys_msgsnd
  - ipc/msg.c:compat_ksys_msgsnd
  - ipc/msg.c:ksys_msgsnd
  - ipc/msg.c:ksys_msgsnd
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
```
```
In ipc/sem.c (ffff8000105224c0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - ipc/sem.c:_copy_from_user
  - ipc/sem.c:_copy_from_user
```
```
In ipc/shm.c (ffff800010526ce0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - ipc/shm.c:_copy_from_user
  - ipc/shm.c:_copy_from_user
```
```
In ipc/mqueue.c (ffff80001052adf4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:_copy_from_user
  - ipc/mqueue.c:_copy_from_user
```
```
In security/keys/keyring.c (ffff800010530490)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_read_iterator
```
```
In security/keys/keyctl.c (ffff800010532034)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - security/keys/keyctl.c:_copy_to_user
  - security/keys/keyctl.c:_copy_to_user
  - security/keys/keyctl.c:_copy_from_user
  - security/keys/keyctl.c:_copy_from_user
```
```
In security/keys/request_key_auth.c (ffff80001053651c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_read
```
```
In security/keys/user_defined.c (ffff800010536d48)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_read
```
```
In security/keys/compat_dh.c (ffff800010537174)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In security/keys/dh.c (ffff800010538120)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - security/keys/dh.c:_copy_from_user
  - security/keys/dh.c:_copy_from_user
```
```
In security/keys/keyctl_pkey.c (ffff80001053951c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
```
```
In security/keys/big_key.c (ffff80001053a188)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_read
```
```
In security/keys/trusted.c (ffff80001053b5d4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053d3fc)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:_copy_to_user
```
```
In security/selinux/hooks.c (ffff80001054fb74)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
```
```
In security/selinux/selinuxfs.c (ffff800010556b58)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
```
In security/smack/smack_lsm.c (ffff8000105711d4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
```
```
In security/smack/smackfs.c (ffff800010576440)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - security/smack/smackfs.c:_copy_from_user
```
```
In security/tomoyo/common.c (ffff80001057d2d0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
```
```
In security/tomoyo/securityfs_if.c (ffff800010586928)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
```
```
In security/apparmor/apparmorfs.c (ffff80001058af60)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:_copy_from_user
```
```
In security/apparmor/lsm.c (ffff80001059e6d4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
```
In block/ioctl.c (ffff8000105f85fc)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:put_uint
  - block/ioctl.c:put_uint
  - block/ioctl.c:put_int
  - block/ioctl.c:put_int
  - block/ioctl.c:put_ushort
  - block/ioctl.c:put_ushort
  - block/ioctl.c:_copy_from_user
  - block/ioctl.c:_copy_from_user
Direct callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/scsi_ioctl.c (ffff8000106094cc)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/scsi_ioctl.c:sg_io
  - block/scsi_ioctl.c:_copy_from_user
  - block/scsi_ioctl.c:_copy_from_user
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
```
```
In block/bsg.c (ffff80001060a3a8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_scsi_complete_rq
  - block/bsg.c:bsg_scsi_complete_rq
  - block/bsg.c:bsg_scsi_fill_hdr
  - block/bsg.c:bsg_scsi_fill_hdr
```
```
In block/bsg-lib.c (ffff80001060b3c4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_transport_complete_rq
```
```
In block/compat_ioctl.c (ffff80001061c7d4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_put_uint
  - block/compat_ioctl.c:compat_put_uint
  - block/compat_ioctl.c:compat_put_int
  - block/compat_ioctl.c:compat_put_int
  - block/compat_ioctl.c:compat_put_ushort
  - block/compat_ioctl.c:compat_put_ushort
Direct callers:
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - block/compat_ioctl.c:compat_cdrom_generic_command
```
```
In block/blk-zoned.c (ffff80001061fc5c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - block/blk-zoned.c:_copy_to_user
  - block/blk-zoned.c:_copy_to_user
```
```
In block/blk-mq-debugfs.c (ffff800010623c50)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In block/sed-opal.c (ffff80001062872c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - block/sed-opal.c:write_shadow_mbr
```
```
In lib/bitmap.c (ffff80001062b7b0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffff800010632a5c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
  - lib/iov_iter.c:copyout
  - lib/iov_iter.c:fault_in_pages_readable
  - lib/iov_iter.c:fault_in_pages_readable
  - lib/iov_iter.c:fault_in_pages_readable
  - lib/iov_iter.c:fault_in_pages_readable
```
```
In lib/kfifo.c (ffff800010634ac0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:_copy_from_user
  - lib/kfifo.c:_copy_from_user
```
```
In lib/usercopy.c (ffff800010637f40)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/kstrtox.c (ffff800010639c28)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - lib/kstrtox.c:_copy_from_user
```
```
In lib/checksum.c (ffff8000106623d4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - lib/checksum.c:csum_partial_copy_from_user
```
```
In lib/strncpy_from_user.c (ffff800010666b4c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:do_strncpy_from_user
  - lib/strncpy_from_user.c:do_strncpy_from_user
  - lib/strncpy_from_user.c:do_strncpy_from_user
  - lib/strncpy_from_user.c:do_strncpy_from_user
```
```
In lib/strnlen_user.c (ffff800010666e28)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - lib/strnlen_user.c:do_strnlen_user
  - lib/strnlen_user.c:do_strnlen_user
  - lib/strnlen_user.c:do_strnlen_user
  - lib/strnlen_user.c:do_strnlen_user
```
```
In drivers/gpio/gpiolib.c (ffff8000106c33ec)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/gpio/gpiolib.c:_copy_from_user
  - drivers/gpio/gpiolib.c:_copy_from_user
```
```
In drivers/pci/proc.c (ffff8000106f6780)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/pci/syscall.c (ffff800010718f4c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_write
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_write
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_write
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_write
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_write
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_write
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_read
```
```
In drivers/video/fbdev/core/fbmem.c (ffff80001074516c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbmem.c:fb_read
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
```
```
In drivers/video/fbdev/core/fbcmap.c (ffff800010748edc)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:_copy_to_user
  - drivers/video/fbdev/core/fbcmap.c:_copy_to_user
  - drivers/video/fbdev/core/fbcmap.c:_copy_from_user
  - drivers/video/fbdev/core/fbcmap.c:_copy_from_user
```
```
In drivers/video/fbdev/core/fbcon.c (ffff80001075318c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
```
```
In drivers/video/fbdev/imsttfb.c (ffff80001075a148)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:_copy_from_user
  - drivers/video/fbdev/imsttfb.c:_copy_from_user
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffff80001083a974)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
```
```
In drivers/tty/tty_io.c (ffff800010851f0c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_write
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/tty/n_tty.c (ffff800010855d58)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:copy_from_read_buf
```
```
In drivers/tty/tty_ioctl.c (ffff80001085b534)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
```
```
In drivers/tty/tty_jobctrl.c (ffff800010860a6c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
```
In drivers/tty/pty.c (ffff800010861edc)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_get_pktmode
  - drivers/tty/pty.c:pty_get_pktmode
  - drivers/tty/pty.c:pty_set_pktmode
  - drivers/tty/pty.c:pty_set_pktmode
  - drivers/tty/pty.c:pty_get_lock
  - drivers/tty/pty.c:pty_get_lock
  - drivers/tty/pty.c:pty_set_lock
  - drivers/tty/pty.c:pty_set_lock
```
```
In drivers/tty/sysrq.c (ffff800010864bf8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:write_sysrq_trigger
```
```
In drivers/tty/vt/vt_ioctl.c (ffff800010867398)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt_ioctl.c:_copy_from_user
  - drivers/tty/vt/vt_ioctl.c:_copy_from_user
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/vc_screen.c (ffff800010867d64)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
```
```
In drivers/tty/vt/selection.c (ffff8000108694d8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:_copy_from_user
```
```
In drivers/tty/vt/keyboard.c (ffff80001086eb04)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kbkeycode_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kbkeycode_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kbkeycode_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kbkeycode_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
```
```
In drivers/tty/vt/consolemap.c (ffff800010870270)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/consolemap.c:_copy_from_user
  - drivers/tty/vt/consolemap.c:_copy_from_user
```
```
In drivers/tty/vt/vt.c (ffff800010879340)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:tioclinux
Direct callers:
  - drivers/tty/vt/vt.c:tioclinux
```
```
In drivers/tty/serial/serial_core.c (ffff800010882c34)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:_copy_from_user
  - drivers/tty/serial/serial_core.c:_copy_from_user
```
```
In drivers/char/mem.c (ffff8000108ab05c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:read_port
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/mem.c:read_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffff8000108b1110)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/virtio_console.c (ffff8000108b5cc0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
```
```
In drivers/char/hw_random/core.c (ffff8000108b79cc)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/char/tpm/tpm-dev-common.c (ffff8000108b8d74)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
```
```
In drivers/lightnvm/core.c (ffff8000108e00e0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:_copy_from_user
  - drivers/lightnvm/core.c:_copy_from_user
```
```
In drivers/base/regmap/regmap-debugfs.c (ffff80001091ac5c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
```
```
In drivers/block/loop.c (ffff800010924304)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/block/loop.c:loop_get_status_old
  - drivers/block/loop.c:_copy_from_user
  - drivers/block/loop.c:_copy_from_user
```
```
In drivers/block/xen-blkfront.c (ffff80001092a194)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_ioctl
```
```
In drivers/mfd/ab3100-core.c (ffff80001094a6a4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
```
```
In drivers/mfd/aat2870-core.c (ffff80001094c894)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/nvdimm/bus.c (ffff8000109519b4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:_copy_to_user
  - drivers/nvdimm/bus.c:_copy_to_user
  - drivers/nvdimm/bus.c:_copy_from_user
  - drivers/nvdimm/bus.c:_copy_from_user
```
```
In drivers/dma-buf/dma-buf.c (ffff8000109661c4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
```
In drivers/dma-buf/sync_file.c (ffff80001096a74c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:_copy_to_user
  - drivers/dma-buf/sync_file.c:_copy_to_user
  - drivers/dma-buf/sync_file.c:_copy_from_user
  - drivers/dma-buf/sync_file.c:_copy_from_user
```
```
In drivers/dma-buf/sw_sync.c (ffff80001096b930)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:_copy_from_user
  - drivers/dma-buf/sw_sync.c:_copy_from_user
```
```
In drivers/dma-buf/udmabuf.c (ffff80001096ce98)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:_copy_from_user
```
```
In drivers/scsi/scsi_ioctl.c (ffff8000109708dc)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/scsi_error.c (ffff800010974d84)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
```
```
In drivers/scsi/scsi_devinfo.c (ffff800010980cf0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
```
```
In drivers/scsi/scsi_proc.c (ffff8000109815d0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:_copy_from_user
```
```
In drivers/scsi/sg.c (ffff800010993180)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In drivers/ata/libata-scsi.c (ffff8000109a5554)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:_copy_to_user
  - drivers/ata/libata-scsi.c:_copy_to_user
```
```
In drivers/gpu/vga/vgaarb.c (ffff8000109c0644)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/net/tun.c (ffff8000109df918)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:_copy_to_user
  - drivers/net/tun.c:_copy_to_user
  - drivers/net/tun.c:_copy_from_user
  - drivers/net/tun.c:_copy_from_user
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (ffff8000109ed208)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_get
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_get
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a00cec)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/ppp/ppp_generic.c:ppp_write
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/cdrom/cdrom.c (ffff800010a0d730)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:_copy_from_user
  - drivers/cdrom/cdrom.c:_copy_from_user
```
```
In drivers/usb/core/devio.c (ffff800010a308d0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
Direct callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:processcompl_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:proc_bulk_compat
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffff800010a34aac)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8fe2c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
```
```
In drivers/input/input-compat.c (ffff800010a99418)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/input/input-compat.c:_copy_from_user
  - drivers/input/input-compat.c:_copy_from_user
```
```
In drivers/input/mousedev.c (ffff800010a9c9b0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_write
```
```
In drivers/input/evdev.c (ffff800010a9fff4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_set_keycode_v2
  - drivers/input/evdev.c:evdev_handle_set_keycode_v2
  - drivers/input/evdev.c:evdev_handle_set_keycode
  - drivers/input/evdev.c:evdev_handle_set_keycode
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:evdev_handle_get_keycode
  - drivers/input/evdev.c:evdev_handle_get_keycode
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/evdev.c:bits_to_user
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
```
```
In drivers/input/misc/uinput.c (ffff800010aa5220)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_str_to_user
  - drivers/input/misc/uinput.c:uinput_str_to_user
  - drivers/input/misc/uinput.c:uinput_str_to_user
  - drivers/input/misc/uinput.c:uinput_str_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:_copy_from_user
  - drivers/input/misc/uinput.c:_copy_from_user
```
```
In drivers/rtc/dev.c (ffff800010aaaeb0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:_copy_from_user
  - drivers/rtc/dev.c:_copy_from_user
```
```
In drivers/i2c/i2c-dev.c (ffff800010ab88dc)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:compat_i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/i2c/i2c-dev.c:_copy_from_user
  - drivers/i2c/i2c-dev.c:_copy_from_user
```
```
In drivers/media/cec/cec-api.c (ffff800010ac27e8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:_copy_from_user
  - drivers/media/cec/cec-api.c:_copy_from_user
```
```
In drivers/pps/pps.c (ffff800010ac5f34)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:_copy_to_user
  - drivers/pps/pps.c:_copy_to_user
  - drivers/pps/pps.c:_copy_from_user
  - drivers/pps/pps.c:_copy_from_user
```
```
In drivers/ptp/ptp_chardev.c (ffff800010ac7a1c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:_copy_to_user
  - drivers/ptp/ptp_chardev.c:_copy_to_user
  - drivers/ptp/ptp_chardev.c:_copy_from_user
  - drivers/ptp/ptp_chardev.c:_copy_from_user
```
```
In drivers/watchdog/watchdog_dev.c (ffff800010ae07f4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_write
  - drivers/watchdog/watchdog_dev.c:watchdog_write
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
```
In drivers/md/md.c (ffff800010af3650)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:_copy_from_user
  - drivers/md/md.c:_copy_from_user
Direct callers:
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (ffff800010b092b8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:_copy_from_user
  - drivers/md/dm-ioctl.c:_copy_from_user
```
```
In drivers/edac/altera_edac.c (ffff800010b1793c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig
  - drivers/edac/altera_edac.c:altr_edac_device_trig
  - drivers/edac/altera_edac.c:altr_edac_device_trig
```
```
In drivers/mmc/core/block.c (ffff800010b42224)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_ioctl_copy_from_user
  - drivers/mmc/core/block.c:mmc_blk_ioctl_copy_from_user
```
```
In drivers/remoteproc/remoteproc_debugfs.c (ffff800010b827e8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
```
```
In net/socket.c (ffff800010ba41d8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_user
Direct callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:routing_ioctl
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__arm64_sys_getsockopt
  - net/socket.c:__sys_socketpair
  - net/socket.c:__sys_socketpair
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_user
```
```
In net/core/sock.c (ffff800010baf0bc)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:groups_to_user
  - net/core/sock.c:groups_to_user
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:_copy_from_user
  - net/core/sock.c:_copy_from_user
Direct callers:
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/scm.c (ffff800010bbe568)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
```
```
In net/core/flow_dissector.c (ffff800010bc32ec)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
```
```
In net/core/sysctl_net_core.c (ffff800010bc5cf0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (ffff800010bdba60)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_features
  - net/core/ethtool.c:ethtool_get_features
  - net/core/ethtool.c:_copy_from_user
  - net/core/ethtool.c:_copy_from_user
```
```
In net/core/filter.c (ffff800010c0311c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
  - net/core/filter.c:sk_get_filter
  - net/core/filter.c:_copy_from_user
  - net/core/filter.c:_copy_from_user
```
```
In net/core/dev_ioctl.c (ffff800010c03ff0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
```
```
In net/compat.c (ffff800010c32f8c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:scm_detach_fds_compat
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:get_compat_msghdr
  - net/compat.c:get_compat_msghdr
Direct callers:
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
```
In net/netlink/af_netlink.c (ffff800010c4d85c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
Direct callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
```
```
In net/bpf/test_run.c (ffff800010c52ca8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/bpf/test_run.c:_copy_from_user
  - net/bpf/test_run.c:_copy_from_user
```
```
In net/ipv4/ip_options.c (ffff800010c617f8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_get_from_user
```
```
In net/ipv4/ip_sockglue.c (ffff800010c676b0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:_copy_from_user
  - net/ipv4/ip_sockglue.c:_copy_from_user
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffff800010c70044)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_repair_options_est
  - net/ipv4/tcp.c:tcp_repair_options_est
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8b760)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
```
```
In net/ipv4/raw.c (ffff800010c974d0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/raw.c:raw_seticmpfilter
  - net/ipv4/raw.c:raw_seticmpfilter
```
```
In net/ipv4/udp.c (ffff800010c9a5e4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_ioctl
  - net/ipv4/udp.c:udp_ioctl
  - net/ipv4/udp.c:udp_ioctl
```
```
In net/ipv4/arp.c (ffff800010ca30bc)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
```
```
In net/ipv4/devinet.c (ffff800010ca68c4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_gifconf
```
```
In net/ipv4/af_inet.c (ffff800010cabe58)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:_copy_from_user
  - net/ipv4/af_inet.c:_copy_from_user
```
```
In net/ipv4/igmp.c (ffff800010cb293c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
```
```
In net/ipv4/fib_frontend.c (ffff800010cb4154)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (ffff800010cc63cc)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
```
```
In net/ipv4/ipmr.c (ffff800010ccf784)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:_copy_from_user
  - net/ipv4/ipmr.c:_copy_from_user
```
```
In net/unix/af_unix.c (ffff800010cf011c)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/addrconf.c (ffff800010d00254)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
```
```
In net/ipv6/route.c (ffff800010d16b10)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1c520)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:_copy_from_user
  - net/ipv6/ipv6_sockglue.c:_copy_from_user
```
```
In net/ipv6/raw.c (ffff800010d29490)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/mcast.c (ffff800010d32054)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:_copy_to_user
  - net/ipv6/mcast.c:_copy_to_user
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d36e08)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3eae8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:_copy_from_user
  - net/ipv6/ip6_flowlabel.c:_copy_from_user
```
```
In net/ipv6/ip6mr.c (ffff800010d47a98)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:_copy_from_user
  - net/ipv6/ip6mr.c:_copy_from_user
```
```
In net/packet/af_packet.c (ffff800010d5b0d0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:_copy_from_user
  - net/packet/af_packet.c:_copy_from_user
```
```
In net/wireless/wext-core.c (ffff800010d612c8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/wireless/wext-core.c:_copy_from_user
  - net/wireless/wext-core.c:_copy_from_user
```
```
In net/wireless/wext-priv.c (ffff800010d627f8)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:_copy_from_user
  - net/wireless/wext-priv.c:_copy_from_user
```
```
In net/rfkill/core.c (ffff800010d6cfe0)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_read
  - net/rfkill/core.c:rfkill_fop_read
```
```
In net/xdp/xsk.c (ffff800010d7fabc)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:_copy_from_user
  - net/xdp/xsk.c:_copy_from_user
```
```
In arch/arm64/lib/uaccess_flushcache.c (ffff800010d83660)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - arch/arm64/lib/uaccess_flushcache.c:__copy_user_flushcache
```
```
In lib/seq_buf.c (ffff800010d900b4)
Location: arch/arm64/include/asm/uaccess.h:215
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_to_user
```
**Symbols:**

```
ffff80001008a758-ffff80001008a7b8: uaccess_disable_not_uao (STB_LOCAL)
ffff80001008f928-ffff80001008f988: uaccess_disable_not_uao (STB_LOCAL)
ffff80001009df50-ffff80001009dfb0: uaccess_disable_not_uao (STB_LOCAL)
ffff80001010bab8-ffff80001010bb28: uaccess_disable_not_uao (STB_LOCAL)
ffff800010114c58-ffff800010114cb8: uaccess_disable_not_uao (STB_LOCAL)
ffff8000101b6d28-ffff8000101b6d88: uaccess_disable_not_uao (STB_LOCAL)
ffff800010221790-ffff8000102217f0: uaccess_disable_not_uao (STB_LOCAL)
ffff80001025fd80-ffff80001025fde0: uaccess_disable_not_uao (STB_LOCAL)
ffff8000102986e8-ffff800010298750: uaccess_disable_not_uao (STB_LOCAL)
ffff8000102ac010-ffff8000102ac070: uaccess_disable_not_uao (STB_LOCAL)
ffff80001039d8a0-ffff80001039d900: uaccess_disable_not_uao (STB_LOCAL)
ffff80001041a0e0-ffff80001041a140: uaccess_disable_not_uao (STB_LOCAL)
ffff80001041e0e0-ffff80001041e140: uaccess_disable_not_uao (STB_LOCAL)
ffff8000104218d8-ffff800010421938: uaccess_disable_not_uao (STB_LOCAL)
ffff80001048a4c0-ffff80001048a520: uaccess_disable_not_uao (STB_LOCAL)
ffff8000104e4308-ffff8000104e4368: uaccess_disable_not_uao (STB_LOCAL)
ffff8000105f77b0-ffff8000105f7810: uaccess_disable_not_uao (STB_LOCAL)
ffff800010607b50-ffff800010607bb0: uaccess_disable_not_uao (STB_LOCAL)
ffff800010619ef0-ffff800010619f50: uaccess_disable_not_uao (STB_LOCAL)
ffff800010743bc0-ffff800010743c20: uaccess_disable_not_uao (STB_LOCAL)
ffff800010850368-ffff8000108503c8: uaccess_disable_not_uao (STB_LOCAL)
ffff8000108651a8-ffff800010865208: uaccess_disable_not_uao (STB_LOCAL)
ffff80001086aae0-ffff80001086ab40: uaccess_disable_not_uao (STB_LOCAL)
ffff800010872900-ffff800010872960: uaccess_disable_not_uao (STB_LOCAL)
ffff80001098ff30-ffff80001098ff90: uaccess_disable_not_uao (STB_LOCAL)
ffff8000109fe6a8-ffff8000109fe708: uaccess_disable_not_uao (STB_LOCAL)
ffff800010a2cee0-ffff800010a2cf40: uaccess_disable_not_uao (STB_LOCAL)
ffff800010a9de00-ffff800010a9de60: uaccess_disable_not_uao (STB_LOCAL)
ffff800010adf340-ffff800010adf3a0: uaccess_disable_not_uao (STB_LOCAL)
ffff800010ae5b08-ffff800010ae5b68: uaccess_disable_not_uao (STB_LOCAL)
ffff800010ba2658-ffff800010ba26b8: uaccess_disable_not_uao (STB_LOCAL)
ffff800010bab208-ffff800010bab268: uaccess_disable_not_uao (STB_LOCAL)
ffff800010c32928-ffff800010c32988: uaccess_disable_not_uao (STB_LOCAL)
ffff800010c4b870-ffff800010c4b8d0: uaccess_disable_not_uao (STB_LOCAL)
ffff800010c66078-ffff800010c660d8: uaccess_disable_not_uao (STB_LOCAL)
ffff800010c6fd70-ffff800010c6fdd0: uaccess_disable_not_uao (STB_LOCAL)
ffff800010d1c348-ffff800010d1c3a8: uaccess_disable_not_uao (STB_LOCAL)
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
