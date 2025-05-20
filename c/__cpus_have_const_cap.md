# Function: <code>__cpus_have_const_cap</code>

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
In arch/arm64/kernel/debug-monitors.c (ffff800010086590)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/debug-monitors.c:aarch32_break_handler
  - arch/arm64/kernel/debug-monitors.c:aarch32_break_handler
  - arch/arm64/kernel/debug-monitors.c:aarch32_break_handler
  - arch/arm64/kernel/debug-monitors.c:aarch32_break_handler
  - arch/arm64/kernel/debug-monitors.c:aarch32_break_handler
  - arch/arm64/kernel/debug-monitors.c:aarch32_break_handler
  - arch/arm64/kernel/debug-monitors.c:send_user_sigtrap
  - arch/arm64/kernel/debug-monitors.c:mdscr_write
  - arch/arm64/kernel/debug-monitors.c:mdscr_write
  - arch/arm64/kernel/debug-monitors.c:mdscr_write
  - arch/arm64/kernel/debug-monitors.c:mdscr_write
```
```
In arch/arm64/kernel/irq.c (ffff800011433730)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/irq.c:init_IRQ
  - arch/arm64/kernel/irq.c:init_IRQ
  - arch/arm64/kernel/irq.c:system_uses_irq_prio_masking
```
```
In arch/arm64/kernel/fpsimd.c (ffff8000100887dc)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_end
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_end
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_begin
  - arch/arm64/kernel/fpsimd.c:__efi_fpsimd_begin
  - arch/arm64/kernel/fpsimd.c:kernel_neon_end
  - arch/arm64/kernel/fpsimd.c:fpsimd_flush_cpu_state
  - arch/arm64/kernel/fpsimd.c:fpsimd_update_current_state
  - arch/arm64/kernel/fpsimd.c:fpsimd_update_current_state
  - arch/arm64/kernel/fpsimd.c:fpsimd_restore_current_state
  - arch/arm64/kernel/fpsimd.c:fpsimd_bind_state_to_cpu
  - arch/arm64/kernel/fpsimd.c:fpsimd_bind_task_to_cpu
  - arch/arm64/kernel/fpsimd.c:fpsimd_bind_task_to_cpu
  - arch/arm64/kernel/fpsimd.c:fpsimd_signal_preserve_current_state
  - arch/arm64/kernel/fpsimd.c:fpsimd_signal_preserve_current_state
  - arch/arm64/kernel/fpsimd.c:fpsimd_flush_thread
  - arch/arm64/kernel/fpsimd.c:fpsimd_flush_thread
  - arch/arm64/kernel/fpsimd.c:fpsimd_thread_switch
  - arch/arm64/kernel/fpsimd.c:do_sve_acc
  - arch/arm64/kernel/fpsimd.c:sve_get_current_vl
  - arch/arm64/kernel/fpsimd.c:sve_set_current_vl
  - arch/arm64/kernel/fpsimd.c:sve_to_fpsimd
  - arch/arm64/kernel/fpsimd.c:fpsimd_to_sve
  - arch/arm64/kernel/fpsimd.c:fpsimd_save
  - arch/arm64/kernel/fpsimd.c:fpsimd_save
  - arch/arm64/kernel/fpsimd.c:task_fpsimd_load
  - arch/arm64/kernel/fpsimd.c:task_fpsimd_load
```
```
In arch/arm64/kernel/process.c (ffff800010089738)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:arch_setup_new_exec
  - arch/arm64/kernel/process.c:arch_setup_new_exec
  - arch/arm64/kernel/process.c:arch_setup_new_exec
  - arch/arm64/kernel/process.c:arch_setup_new_exec
  - arch/arm64/kernel/process.c:__switch_to
  - arch/arm64/kernel/process.c:copy_thread_tls
  - arch/arm64/kernel/process.c:copy_thread_tls
  - arch/arm64/kernel/process.c:cpu_do_idle
```
```
In arch/arm64/kernel/ptrace.c (ffff80001008bc84)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:compat_tls_set
  - arch/arm64/kernel/ptrace.c:compat_tls_set
  - arch/arm64/kernel/ptrace.c:compat_tls_get
  - arch/arm64/kernel/ptrace.c:compat_tls_get
  - arch/arm64/kernel/ptrace.c:compat_vfp_set
  - arch/arm64/kernel/ptrace.c:compat_vfp_set
  - arch/arm64/kernel/ptrace.c:compat_vfp_set
  - arch/arm64/kernel/ptrace.c:compat_vfp_get
  - arch/arm64/kernel/ptrace.c:compat_vfp_get
  - arch/arm64/kernel/ptrace.c:compat_vfp_get
  - arch/arm64/kernel/ptrace.c:compat_gpr_set
  - arch/arm64/kernel/ptrace.c:compat_gpr_set
  - arch/arm64/kernel/ptrace.c:compat_gpr_get
  - arch/arm64/kernel/ptrace.c:compat_gpr_get
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_set
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_set
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_set
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_set
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_get
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_get
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_get
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_get
  - arch/arm64/kernel/ptrace.c:pac_address_keys_set
  - arch/arm64/kernel/ptrace.c:pac_address_keys_set
  - arch/arm64/kernel/ptrace.c:pac_address_keys_set
  - arch/arm64/kernel/ptrace.c:pac_address_keys_set
  - arch/arm64/kernel/ptrace.c:pac_address_keys_get
  - arch/arm64/kernel/ptrace.c:pac_address_keys_get
  - arch/arm64/kernel/ptrace.c:pac_address_keys_get
  - arch/arm64/kernel/ptrace.c:pac_address_keys_get
  - arch/arm64/kernel/ptrace.c:pac_mask_get
  - arch/arm64/kernel/ptrace.c:pac_mask_get
  - arch/arm64/kernel/ptrace.c:pac_mask_get
  - arch/arm64/kernel/ptrace.c:pac_mask_get
  - arch/arm64/kernel/ptrace.c:sve_set
  - arch/arm64/kernel/ptrace.c:sve_get
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
  - arch/arm64/kernel/ptrace.c:fpr_get
  - arch/arm64/kernel/ptrace.c:fpr_active
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
```
```
In arch/arm64/kernel/setup.c (ffff800011434200)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:setup_arch
  - arch/arm64/kernel/setup.c:arm64_kernel_unmapped_at_el0
  - arch/arm64/kernel/setup.c:system_uses_irq_prio_masking
```
```
In arch/arm64/kernel/signal.c (ffff8000100932b0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
  - arch/arm64/kernel/signal.c:do_notify_resume
  - arch/arm64/kernel/signal.c:do_notify_resume
  - arch/arm64/kernel/signal.c:setup_sigframe
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
```
```
In arch/arm64/kernel/sys.c (ffff8000100937b4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/sys.c:__arm64_sys_arm64_personality
```
```
In arch/arm64/kernel/traps.c (ffff8000100959a8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:bad_mode
  - arch/arm64/kernel/traps.c:user_cache_maint_handler
  - arch/arm64/kernel/traps.c:user_cache_maint_handler
  - arch/arm64/kernel/traps.c:user_cache_maint_handler
  - arch/arm64/kernel/traps.c:user_cache_maint_handler
  - arch/arm64/kernel/traps.c:user_cache_maint_handler
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/traps.c:call_undef_hook
```
```
In arch/arm64/kernel/insn.c (ffff800010da7660)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:__aarch64_insn_write
  - arch/arm64/kernel/insn.c:__aarch64_insn_write
```
```
In arch/arm64/kernel/cpufeature.c (ffff80001009b150)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:cpu_show_meltdown
  - arch/arm64/kernel/cpufeature.c:cpu_enable_cnp
  - arch/arm64/kernel/cpufeature.c:cpu_enable_cnp
  - arch/arm64/kernel/cpufeature.c:cpufeature_pan_not_uao
  - arch/arm64/kernel/cpufeature.c:cpufeature_pan_not_uao
  - arch/arm64/kernel/cpufeature.c:check_local_cpu_capabilities
  - arch/arm64/kernel/cpufeature.c:check_local_cpu_capabilities
  - arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings
  - arch/arm64/kernel/cpufeature.c:unmap_kernel_at_el0
  - arch/arm64/kernel/cpufeature.c:setup_cpu_features
  - arch/arm64/kernel/cpufeature.c:setup_cpu_features
```
```
In arch/arm64/kernel/alternative.c (ffff80001009b594)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/alternative.c:__apply_alternatives
```
```
In arch/arm64/kernel/smp.c (ffff80001009c2c0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:secondary_start_kernel
  - arch/arm64/kernel/smp.c:secondary_start_kernel
```
```
In arch/arm64/kernel/syscall.c (ffff80001009daf4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/syscall.c:el0_svc_handler
```
```
In arch/arm64/kernel/signal32.c (ffff8000100a1460)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In arch/arm64/kernel/module.c (ffff8000100a2774)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/module.c:apply_relocate_add
  - arch/arm64/kernel/module.c:module_alloc
  - arch/arm64/kernel/module.c:module_alloc
  - arch/arm64/kernel/module.c:module_alloc
  - arch/arm64/kernel/module.c:module_alloc
```
```
In arch/arm64/kernel/module-plts.c (ffff8000100a2ec8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/module-plts.c:module_emit_veneer_for_adrp
  - arch/arm64/kernel/module-plts.c:module_emit_plt_entry
```
```
In arch/arm64/kernel/perf_callchain.c (ffff8000100a3574)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
```
```
In arch/arm64/kernel/perf_event.c (ffff8000100a4af0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/perf_event.c:armv8pmu_disable_event
  - arch/arm64/kernel/perf_event.c:armv8pmu_enable_event
  - arch/arm64/kernel/perf_event.c:armv8pmu_enable_event
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a6da0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:cpu_suspend
  - arch/arm64/kernel/suspend.c:cpu_suspend
  - arch/arm64/kernel/suspend.c:cpu_suspend
  - arch/arm64/kernel/suspend.c:cpu_suspend
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
```
```
In arch/arm64/kernel/efi.c (ffff8000100a7880)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/efi.c:arm64_kernel_unmapped_at_el0
```
```
In arch/arm64/kernel/armv8_deprecated.c (ffff8000100a8924)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/armv8_deprecated.c:emulate_swpX
  - arch/arm64/kernel/armv8_deprecated.c:emulate_swpX
  - arch/arm64/kernel/armv8_deprecated.c:emulate_swpX
```
```
In arch/arm64/kernel/acpi.c (ffff8000100a9420)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi.c:apei_claim_sea
  - arch/arm64/kernel/acpi.c:apei_claim_sea
  - arch/arm64/kernel/acpi.c:apei_claim_sea
  - arch/arm64/kernel/acpi.c:apei_claim_sea
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
  - arch/arm64/kernel/acpi.c:__acpi_get_mem_attribute
```
```
In arch/arm64/kernel/acpi_parking_protocol.c (ffff8000100a9660)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi_parking_protocol.c:acpi_parking_protocol_cpu_boot
  - arch/arm64/kernel/acpi_parking_protocol.c:acpi_parking_protocol_cpu_boot
```
```
In arch/arm64/kernel/kaslr.c (ffff800011436d0c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/kaslr.c:kaslr_early_init
  - arch/arm64/kernel/kaslr.c:kaslr_early_init
```
```
In arch/arm64/kernel/machine_kexec.c (ffff8000100a9d00)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/machine_kexec.c:machine_kexec
```
```
In arch/arm64/kernel/crash_dump.c (ffff8000100ab978)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/crash_dump.c:copy_oldmem_page
  - arch/arm64/kernel/crash_dump.c:copy_oldmem_page
```
```
In arch/arm64/kernel/sdei.c (ffff800010da7d54)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/sdei.c:__sdei_handler
  - arch/arm64/kernel/sdei.c:__sdei_handler
  - arch/arm64/kernel/sdei.c:sdei_arch_get_entry_point
  - arch/arm64/kernel/sdei.c:_init_sdei_stack
  - arch/arm64/kernel/sdei.c:_init_sdei_stack
```
```
In arch/arm64/kernel/pointer_auth.c (ffff8000100ac340)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
  - arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys
```
```
In arch/arm64/mm/fault.c (ffff800010081314)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:do_debug_exception
  - arch/arm64/mm/fault.c:debug_exception_exit
  - arch/arm64/mm/fault.c:debug_exception_enter
  - arch/arm64/mm/fault.c:do_sp_pc_abort
  - arch/arm64/mm/fault.c:do_sp_pc_abort
  - arch/arm64/mm/fault.c:do_el0_ia_bp_hardening
  - arch/arm64/mm/fault.c:do_el0_ia_bp_hardening
  - arch/arm64/mm/fault.c:do_el0_irq_bp_hardening
  - arch/arm64/mm/fault.c:do_page_fault
  - arch/arm64/mm/fault.c:ptep_set_access_flags
```
```
In arch/arm64/mm/flush.c (ffff8000100adc40)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/mm/flush.c:sync_icache_aliases
```
```
In arch/arm64/mm/ioremap.c (ffff8000100adfa8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In arch/arm64/mm/mmu.c (ffff8000100af604)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:arch_add_memory
  - arch/arm64/mm/mmu.c:arch_add_memory
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:mark_rodata_ro
  - arch/arm64/mm/mmu.c:mark_rodata_ro
  - arch/arm64/mm/mmu.c:alloc_init_pud
  - arch/arm64/mm/mmu.c:alloc_init_pud
  - arch/arm64/mm/mmu.c:init_pmd
  - arch/arm64/mm/mmu.c:init_pmd
  - arch/arm64/mm/mmu.c:init_pmd
  - arch/arm64/mm/mmu.c:init_pmd
  - arch/arm64/mm/mmu.c:set_swapper_pgd
  - arch/arm64/mm/mmu.c:set_swapper_pgd
```
```
In arch/arm64/mm/context.c (ffff8000100afa80)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
  - arch/arm64/mm/context.c:check_and_switch_context
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In arch/arm64/mm/hugetlbpage.c (ffff8000100b1820)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_clear_flush
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_clear_flush
  - arch/arm64/mm/hugetlbpage.c:set_huge_pte_at
  - arch/arm64/mm/hugetlbpage.c:set_huge_pte_at
  - arch/arm64/mm/hugetlbpage.c:get_clear_flush
  - arch/arm64/mm/hugetlbpage.c:get_clear_flush
```
```
In arch/arm64/net/bpf_jit_comp.c (ffff8000100b4e84)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/net/bpf_jit_comp.c:bpf_jit_alloc_exec
  - arch/arm64/net/bpf_jit_comp.c:bpf_jit_alloc_exec
```
```
In virt/kvm/kvm_main.c (ffff8000100bdad8)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In virt/kvm/vfio.c (ffff8000100c20d8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - virt/kvm/vfio.c:kvm_vfio_set_group
  - virt/kvm/vfio.c:kvm_vfio_set_group
  - virt/kvm/vfio.c:kvm_vfio_set_group
  - virt/kvm/vfio.c:kvm_vfio_set_group
```
```
In virt/kvm/arm/arm.c (ffff8000100c7edc)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_init
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:cpu_hyp_reinit
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_vcpu_init
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_vcpu_init
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_vcpu_init
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_load
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_load
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_load
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_load
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_load
  - virt/kvm/arm/arm.c:kvm_arch_free_vm
  - virt/kvm/arm/arm.c:kvm_arch_alloc_vm
  - virt/kvm/arm/arm.c:_copy_to_user
  - virt/kvm/arm/arm.c:_copy_to_user
  - virt/kvm/arm/arm.c:_copy_from_user
  - virt/kvm/arm/arm.c:_copy_from_user
```
```
In virt/kvm/arm/mmu.c (ffff8000100cc784)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:kvm_set_spte_hva
  - virt/kvm/arm/mmu.c:kvm_set_spte_hva
  - virt/kvm/arm/mmu.c:kvm_set_spte_hva
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:kvm_phys_addr_ioremap
  - virt/kvm/arm/mmu.c:create_hyp_io_mappings
  - virt/kvm/arm/mmu.c:create_hyp_io_mappings
  - virt/kvm/arm/mmu.c:create_hyp_io_mappings
  - virt/kvm/arm/mmu.c:create_hyp_io_mappings
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
```
```
In virt/kvm/arm/psci.c (ffff8000100ced98)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In arch/arm64/kvm/va_layout.c (ffff8000100cf960)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kvm/va_layout.c:kvm_patch_vector_branch
  - arch/arm64/kvm/va_layout.c:kvm_patch_vector_branch
  - arch/arm64/kvm/va_layout.c:kvm_patch_vector_branch
```
```
In arch/arm64/kvm/handle_exit.c (ffff8000100d164c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In arch/arm64/kvm/guest.c (ffff8000100d39bc)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kvm/guest.c:__kvm_arm_vcpu_set_events
  - arch/arm64/kvm/guest.c:__kvm_arm_vcpu_get_events
  - arch/arm64/kvm/guest.c:kvm_arm_set_reg
  - arch/arm64/kvm/guest.c:kvm_arm_set_reg
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
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices
  - arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices
  - arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices
  - arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices
  - arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices
  - arch/arm64/kvm/guest.c:kvm_arm_copy_reg_indices
  - arch/arm64/kvm/guest.c:kvm_arm_num_regs
  - arch/arm64/kvm/guest.c:copy_core_reg_indices
  - arch/arm64/kvm/guest.c:copy_core_reg_indices
  - arch/arm64/kvm/guest.c:_copy_from_user
  - arch/arm64/kvm/guest.c:_copy_from_user
```
```
In arch/arm64/kvm/debug.c (ffff8000100d3f20)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kvm/debug.c:kvm_arm_setup_debug
  - arch/arm64/kvm/debug.c:kvm_arm_init_debug
```
```
In arch/arm64/kvm/reset.c (ffff8000100d4b94)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kvm/reset.c:kvm_reset_vcpu
  - arch/arm64/kvm/reset.c:kvm_reset_vcpu
  - arch/arm64/kvm/reset.c:kvm_reset_vcpu
  - arch/arm64/kvm/reset.c:kvm_reset_vcpu
  - arch/arm64/kvm/reset.c:kvm_reset_vcpu
  - arch/arm64/kvm/reset.c:kvm_reset_vcpu
  - arch/arm64/kvm/reset.c:kvm_reset_vcpu
  - arch/arm64/kvm/reset.c:kvm_reset_vcpu
  - arch/arm64/kvm/reset.c:kvm_arm_vcpu_is_finalized
  - arch/arm64/kvm/reset.c:kvm_arm_vcpu_finalize
  - arch/arm64/kvm/reset.c:kvm_arm_init_sve
  - arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension
  - arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension
  - arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension
  - arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension
  - arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension
  - arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension
  - arch/arm64/kvm/reset.c:kvm_arch_vm_ioctl_check_extension
```
```
In arch/arm64/kvm/sys_regs.c (ffff8000100d9e14)
Location: arch/arm64/include/asm/cpufeature.h:394
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
  - arch/arm64/kvm/sys_regs.c:set_id_aa64zfr0_el1
  - arch/arm64/kvm/sys_regs.c:get_id_aa64zfr0_el1
  - arch/arm64/kvm/sys_regs.c:ptrauth_visibility
  - arch/arm64/kvm/sys_regs.c:ptrauth_visibility
  - arch/arm64/kvm/sys_regs.c:ptrauth_visibility
  - arch/arm64/kvm/sys_regs.c:ptrauth_visibility
  - arch/arm64/kvm/sys_regs.c:reset_pmcr
  - arch/arm64/kvm/sys_regs.c:get_wcr
  - arch/arm64/kvm/sys_regs.c:get_wcr
  - arch/arm64/kvm/sys_regs.c:get_wvr
  - arch/arm64/kvm/sys_regs.c:get_wvr
  - arch/arm64/kvm/sys_regs.c:get_bcr
  - arch/arm64/kvm/sys_regs.c:get_bcr
  - arch/arm64/kvm/sys_regs.c:get_bvr
  - arch/arm64/kvm/sys_regs.c:get_bvr
  - arch/arm64/kvm/sys_regs.c:access_dcsw
  - arch/arm64/kvm/sys_regs.c:_copy_from_user
  - arch/arm64/kvm/sys_regs.c:_copy_from_user
```
```
In arch/arm64/kvm/fpsimd.c (ffff8000100dad48)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_put_fp
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_put_fp
  - arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_ctxsync_fp
```
```
In arch/arm64/kvm/pmu.c (ffff8000100db3b4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kvm/pmu.c:kvm_vcpu_pmu_restore_host
  - arch/arm64/kvm/pmu.c:kvm_vcpu_pmu_restore_guest
  - arch/arm64/kvm/pmu.c:kvm_set_pmu_events
```
```
In virt/kvm/arm/vgic/vgic.c (ffff8000100dd144)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_flush_hwstate
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_sync_hwstate
```
```
In virt/kvm/arm/vgic/vgic-init.c (ffff8000100de324)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_init_cpu_hardware
```
```
In virt/kvm/arm/vgic/vgic-v3.c (ffff8000100e0684)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_put
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_put
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_vmcr_sync
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_load
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_load
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_load
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_probe
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_probe
```
```
In virt/kvm/arm/vgic/vgic-kvm-device.c (ffff8000100e6234)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-kvm-device.c:vgic_v2_get_attr
  - virt/kvm/arm/vgic/vgic-kvm-device.c:vgic_v2_get_attr
  - virt/kvm/arm/vgic/vgic-kvm-device.c:vgic_v2_set_attr
  - virt/kvm/arm/vgic/vgic-kvm-device.c:vgic_v2_set_attr
```
```
In virt/kvm/arm/vgic/vgic-its.c (ffff8000100e97f4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_set_attr
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_set_attr
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_set_attr
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_set_attr
```
```
In virt/kvm/arm/arch_timer.c (ffff8000100ee1c4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - virt/kvm/arm/arch_timer.c:kvm_arm_timer_get_attr
  - virt/kvm/arm/arch_timer.c:kvm_arm_timer_get_attr
  - virt/kvm/arm/arch_timer.c:kvm_arm_timer_set_attr
  - virt/kvm/arm/arch_timer.c:kvm_arm_timer_set_attr
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
  - virt/kvm/arm/arch_timer.c:set_cntvoff
  - virt/kvm/arm/arch_timer.c:get_timer_map
```
```
In virt/kvm/arm/pmu.c (ffff8000100ef758)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - virt/kvm/arm/pmu.c:kvm_arm_pmu_v3_get_attr
  - virt/kvm/arm/pmu.c:kvm_arm_pmu_v3_get_attr
  - virt/kvm/arm/pmu.c:kvm_arm_pmu_v3_set_attr
  - virt/kvm/arm/pmu.c:kvm_arm_pmu_v3_set_attr
```
```
In virt/kvm/arm/hyp/vgic-v3-sr.c (ffff800010dac90c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_activate_traps
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_restore_state
  - virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_save_state
```
```
In arch/arm64/kvm/hyp/sysreg-sr.c (ffff8000100efaac)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/sysreg-sr.c:kvm_vcpu_put_sysregs
  - arch/arm64/kvm/hyp/sysreg-sr.c:kvm_vcpu_load_sysregs
  - arch/arm64/kvm/hyp/sysreg-sr.c:__sysreg32_restore_state
  - arch/arm64/kvm/hyp/sysreg-sr.c:__sysreg32_save_state
  - arch/arm64/kvm/hyp/sysreg-sr.c:__sysreg_restore_el2_return_state
  - arch/arm64/kvm/hyp/sysreg-sr.c:__sysreg_save_el2_return_state
```
```
In arch/arm64/kvm/hyp/debug-sr.c (ffff800010dae02c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/debug-sr.c:__debug_switch_to_host
  - arch/arm64/kvm/hyp/debug-sr.c:__debug_switch_to_guest
```
```
In arch/arm64/kvm/hyp/switch.c (ffff800010daeb88)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/switch.c:__kvm_vcpu_run_nvhe
  - arch/arm64/kvm/hyp/switch.c:__kvm_vcpu_run_nvhe
  - arch/arm64/kvm/hyp/switch.c:__set_host_arch_workaround_state
  - arch/arm64/kvm/hyp/switch.c:__set_guest_arch_workaround_state
  - arch/arm64/kvm/hyp/switch.c:fixup_guest_exit
  - arch/arm64/kvm/hyp/switch.c:fixup_guest_exit
  - arch/arm64/kvm/hyp/switch.c:fixup_guest_exit
  - arch/arm64/kvm/hyp/switch.c:fixup_guest_exit
  - arch/arm64/kvm/hyp/switch.c:fixup_guest_exit
  - arch/arm64/kvm/hyp/switch.c:fixup_guest_exit
  - arch/arm64/kvm/hyp/switch.c:__activate_vm
  - arch/arm64/kvm/hyp/switch.c:__activate_traps
  - arch/arm64/kvm/hyp/switch.c:__activate_traps
  - arch/arm64/kvm/hyp/switch.c:__activate_traps
  - arch/arm64/kvm/hyp/switch.c:__activate_traps
  - arch/arm64/kvm/hyp/switch.c:activate_traps_vhe
  - arch/arm64/kvm/hyp/switch.c:activate_traps_vhe
  - arch/arm64/kvm/hyp/switch.c:activate_traps_vhe
  - arch/arm64/kvm/hyp/switch.c:activate_traps_vhe
  - arch/arm64/kvm/hyp/switch.c:__activate_traps_fpsimd32
```
```
In arch/arm64/kvm/hyp/tlb.c (ffff800010daf0c4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/kvm/hyp/tlb.c:__kvm_tlb_flush_vmid_ipa
  - arch/arm64/kvm/hyp/tlb.c:__kvm_tlb_flush_vmid_ipa
  - arch/arm64/kvm/hyp/tlb.c:__tlb_switch_to_guest
  - arch/arm64/kvm/hyp/tlb.c:__tlb_switch_to_guest
  - arch/arm64/kvm/hyp/tlb.c:__tlb_switch_to_guest_vhe
  - arch/arm64/kvm/hyp/tlb.c:__tlb_switch_to_guest_vhe
```
```
In kernel/fork.c (ffff8000100f2088)
Location: arch/arm64/include/asm/cpufeature.h:394
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
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_mmap
```
```
In kernel/exit.c (ffff8000100fc7c0)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In kernel/sysctl.c (ffff800010102ce8)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In kernel/sysctl_binary.c (ffff800010105580)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In kernel/capability.c (ffff8000101063a4)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In kernel/ptrace.c (ffff800010109c10)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In kernel/signal.c (ffff80001010e59c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_rt_sigsuspend
  - kernel/signal.c:__arm64_sys_rt_sigsuspend
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__arm64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__arm64_sys_rt_sigtimedwait
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
```
```
In kernel/sys.c (ffff800010117668)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In kernel/groups.c (ffff800010130fcc)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/groups.c:groups_from_user
  - kernel/groups.c:groups_from_user
  - kernel/groups.c:groups_to_user
  - kernel/groups.c:groups_to_user
  - kernel/groups.c:groups_alloc
  - kernel/groups.c:groups_alloc
```
```
In kernel/sched/core.c (ffff80001013d0e4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
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
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/core.c:schedule_tail
  - kernel/sched/core.c:_copy_from_user
  - kernel/sched/core.c:_copy_from_user
```
```
In kernel/sched/debug.c (ffff800010160c08)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_feat_write
  - kernel/sched/debug.c:sched_feat_write
```
```
In kernel/sched/psi.c (ffff800010168120)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In kernel/power/qos.c (ffff80001016d7f4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_write
  - kernel/power/qos.c:pm_qos_power_write
```
```
In kernel/printk/printk.c (ffff8000101736cc)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/dma/remap.c (ffff8000101976a4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/dma/remap.c:arch_dma_alloc
  - kernel/dma/remap.c:arch_dma_alloc
```
```
In kernel/kcmp.c (ffff800010197998)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/profile.c (ffff800010199464)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In kernel/time/time.c (ffff80001019b3cc)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In kernel/time/posix-timers.c (ffff8000101acca8)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In kernel/time/itimer.c (ffff8000101b007c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/time/itimer.c:__arm64_sys_setitimer
  - kernel/time/itimer.c:__arm64_sys_setitimer
```
```
In kernel/futex.c (ffff8000101b7304)
Location: arch/arm64/include/asm/cpufeature.h:394
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
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:get_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:cmpxchg_futex_value_locked
```
```
In kernel/uid16.c (ffff8000101be1c0)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In kernel/module.c (ffff8000101c5928)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:__do_sys_init_module
  - kernel/module.c:copy_chunked_from_user
  - kernel/module.c:copy_chunked_from_user
```
```
In kernel/kexec_core.c (ffff8000101c9304)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/kexec_core.c:kimage_crash_copy_vmcoreinfo
  - kernel/kexec_core.c:_copy_from_user
  - kernel/kexec_core.c:_copy_from_user
```
```
In kernel/kexec.c (ffff8000101ca570)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/kexec.c:__arm64_compat_sys_kexec_load
  - kernel/kexec.c:__arm64_compat_sys_kexec_load
  - kernel/kexec.c:_copy_from_user
  - kernel/kexec.c:_copy_from_user
```
```
In kernel/compat.c (ffff8000101cc460)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In kernel/user_namespace.c (ffff8000101e6d78)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/user_namespace.c:proc_setgroups_write
  - kernel/user_namespace.c:proc_setgroups_write
```
```
In kernel/kprobes.c (ffff8000101f80b4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:write_enabled_file_bool
```
```
In kernel/seccomp.c (ffff80001020a608)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In kernel/relay.c (ffff80001020c3b8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
  - kernel/relay.c:relay_file_read
```
```
In kernel/trace/trace.c (ffff800010221e4c)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In kernel/trace/blktrace.c (ffff800010236a3c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
```
In kernel/trace/bpf_trace.c (ffff80001024e9a4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:_copy_to_user
  - kernel/trace/bpf_trace.c:_copy_to_user
```
```
In kernel/trace/trace_uprobe.c (ffff800010259648)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:_copy_from_user
  - kernel/trace/trace_uprobe.c:_copy_from_user
```
```
In kernel/bpf/core.c (ffff80001025f1a4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_realloc
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In kernel/bpf/syscall.c (ffff800010264ee0)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In kernel/bpf/verifier.c (ffff800010269558)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In kernel/bpf/btf.c (ffff800010285dbc)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In kernel/bpf/offload.c (ffff80001028aeec)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/bpf/cgroup.c (ffff80001028e45c)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In kernel/events/core.c (ffff800010298804)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In kernel/events/uprobes.c (ffff8000102a5a34)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:is_trap_at_addr
```
```
In kernel/iomem.c (ffff8000102abba8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - kernel/iomem.c:memremap
  - kernel/iomem.c:ioremap_cache
  - kernel/iomem.c:ioremap_cache
```
```
In kernel/rseq.c (ffff8000102ac3e0)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In mm/maccess.c (ffff8000102b9d30)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In mm/shmem.c (ffff8000102d33e8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/util.c (ffff8000102d84c8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - mm/util.c:_copy_from_user
  - mm/util.c:_copy_from_user
```
```
In mm/mmu_context.c (ffff8000102dfea4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/percpu.c (ffff8000102e1cf4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/memory.c (ffff8000102fc230)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
```
```
In mm/mincore.c (ffff8000102fd328)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mmu_gather.c (ffff8000103049bc)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In mm/mprotect.c (ffff800010305650)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff800010306370)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffff8000103084d8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_clear_flush_young
  - mm/pgtable-generic.c:pmdp_clear_flush_young
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (ffff80001030a140)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
```
In mm/vmalloc.c (ffff8000103108ec)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_32
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vmalloc_exec
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vzalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_node
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vzalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:vmalloc
  - mm/vmalloc.c:__vmalloc_node_flags_caller
  - mm/vmalloc.c:__vmalloc_node_flags_caller
```
```
In mm/page_alloc.c (ffff8000114581f8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/madvise.c (ffff80001031dae4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - mm/madvise.c:tlb_flush_mmu_tlbonly
  - mm/madvise.c:tlb_flush_mmu_tlbonly
  - mm/madvise.c:tlb_flush_mmu_tlbonly
  - mm/madvise.c:tlb_flush_mmu_tlbonly
```
```
In mm/hugetlb.c (ffff800010335a48)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/mempolicy.c (ffff800010338138)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In mm/sparse-vmemmap.c (ffff800010da0d64)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/migrate.c (ffff800010352894)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In mm/huge_memory.c (ffff800010358040)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/zsmalloc.c (ffff80001037542c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/early_ioremap.c (ffff8000103768a0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - mm/early_ioremap.c:arm64_kernel_unmapped_at_el0
```
```
In mm/userfaultfd.c (ffff800010377e60)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In mm/memfd.c (ffff80001037c218)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - mm/memfd.c:__arm64_sys_memfd_create
  - mm/memfd.c:__arm64_sys_memfd_create
```
```
In fs/read_write.c (ffff800010383a4c)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In fs/stat.c (ffff80001038ab20)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In fs/exec.c (ffff80001038d630)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In fs/pipe.c (ffff800010391518)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:do_pipe2
  - fs/pipe.c:pipe_ioctl
  - fs/pipe.c:pipe_ioctl
```
```
In fs/namei.c (ffff80001039ad80)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/namei.c:readlink_copy
  - fs/namei.c:readlink_copy
```
```
In fs/fcntl.c (ffff80001039c7c0)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In fs/ioctl.c (ffff80001039e520)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In fs/readdir.c (ffff80001039fc9c)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In fs/select.c (ffff8000103a4100)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In fs/filesystems.c (ffff8000103b349c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/filesystems.c:fs_name
  - fs/filesystems.c:fs_name
```
```
In fs/namespace.c (ffff8000103b486c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/namespace.c:exact_copy_from_user
  - fs/namespace.c:exact_copy_from_user
```
```
In fs/seq_file.c (ffff8000103bcde4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (ffff8000103bef78)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/xattr.c:setxattr
  - fs/xattr.c:setxattr
```
```
In fs/libfs.c (ffff8000103c1ba0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/libfs.c:simple_read_from_buffer
  - fs/libfs.c:simple_read_from_buffer
  - fs/libfs.c:_copy_from_user
  - fs/libfs.c:_copy_from_user
```
```
In fs/splice.c (ffff8000103ce998)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In fs/utimes.c (ffff8000103d0fe0)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In fs/d_path.c (ffff8000103d1f78)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/d_path.c:__arm64_sys_getcwd
  - fs/d_path.c:__arm64_sys_getcwd
```
```
In fs/statfs.c (ffff8000103d3108)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In fs/nsfs.c (ffff8000103d4950)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/nsfs.c:ns_ioctl
  - fs/nsfs.c:ns_ioctl
```
```
In fs/fsopen.c (ffff8000103d73f4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/fsopen.c:fscontext_read
  - fs/fsopen.c:fscontext_read
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ecbec)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In fs/notify/fanotify/fanotify_user.c (ffff8000103ef4f8)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In fs/eventpoll.c (ffff8000103f1d58)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In fs/signalfd.c (ffff8000103f3d2c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_copyinfo
  - fs/signalfd.c:signalfd_copyinfo
```
```
In fs/timerfd.c (ffff8000103f52fc)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_read
```
```
In fs/eventfd.c (ffff8000103f6308)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_write
  - fs/eventfd.c:eventfd_read
  - fs/eventfd.c:eventfd_read
```
```
In fs/userfaultfd.c (ffff8000103f89bc)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In fs/aio.c (ffff8000103fcca8)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In fs/io_uring.c (ffff800010403fd8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_setup
  - fs/io_uring.c:io_uring_setup
  - fs/io_uring.c:_copy_from_user
  - fs/io_uring.c:_copy_from_user
```
```
In fs/crypto/keyring.c (ffff80001040e2ec)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In fs/crypto/policy.c (ffff800010410940)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In fs/verity/enable.c (ffff800010411444)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/verity/enable.c:_copy_from_user
  - fs/verity/enable.c:_copy_from_user
```
```
In fs/verity/measure.c (ffff800010412400)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In fs/compat_ioctl.c (ffff80001041d5f8)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In fs/binfmt_elf.c (ffff80001042093c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
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
```
```
In fs/compat_binfmt_elf.c (ffff8000104219f0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
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
```
```
In fs/fhandle.c (ffff800010429974)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In fs/quota/quota.c (ffff8000104358e4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/quota/quota.c:_copy_from_user
  - fs/quota/quota.c:_copy_from_user
```
```
In fs/proc/task_mmu.c (ffff80001043a838)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
```
```
In fs/proc/base.c (ffff80001043f338)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/proc/base.c:_copy_from_user
  - fs/proc/base.c:_copy_from_user
```
```
In fs/proc/kcore.c (ffff80001044ddd8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/proc/kcore.c:_copy_to_user
  - fs/proc/kcore.c:_copy_to_user
```
```
In fs/proc/vmcore.c (ffff80001044eb78)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In fs/proc/page.c (ffff80001044fb48)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In fs/kernfs/file.c (ffff8000104554ec)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/kernfs/file.c:kernfs_fop_read
```
```
In fs/configfs/file.c (ffff800010459610)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_write_file
  - fs/configfs/file.c:configfs_write_file
```
```
In fs/dcookies.c (ffff80001045f548)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/dcookies.c:do_lookup_dcookie
  - fs/dcookies.c:do_lookup_dcookie
```
```
In fs/ext4/ioctl.c (ffff80001048d650)
Location: arch/arm64/include/asm/cpufeature.h:394
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
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:_copy_from_user
  - fs/ext4/ioctl.c:_copy_from_user
```
```
In fs/ext4/super.c (ffff8000104b878c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_kvzalloc
  - fs/ext4/super.c:ext4_kvzalloc
```
```
In fs/fat/dir.c (ffff8000104e6968)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In fs/fat/file.c (ffff8000104eb298)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In fs/ecryptfs/miscdev.c (ffff8000104fe0b0)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In fs/fuse/dev.c (ffff800010501b30)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_ioctl
  - fs/fuse/dev.c:fuse_dev_ioctl
```
```
In fs/efivarfs/file.c (ffff80001051bae0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In ipc/compat.c (ffff80001051c744)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - ipc/compat.c:_copy_from_user
  - ipc/compat.c:_copy_from_user
```
```
In ipc/msgutil.c (ffff80001051e2e8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - ipc/msgutil.c:_copy_to_user
  - ipc/msgutil.c:_copy_to_user
  - ipc/msgutil.c:_copy_from_user
  - ipc/msgutil.c:_copy_from_user
```
```
In ipc/msg.c (ffff80001051f0d8)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In ipc/sem.c (ffff800010522400)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - ipc/sem.c:_copy_from_user
  - ipc/sem.c:_copy_from_user
```
```
In ipc/shm.c (ffff800010526c24)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - ipc/shm.c:_copy_from_user
  - ipc/shm.c:_copy_from_user
```
```
In ipc/mqueue.c (ffff80001052ad90)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In security/keys/keyring.c (ffff800010530428)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_read_iterator
  - security/keys/keyring.c:keyring_read_iterator
```
```
In security/keys/keyctl.c (ffff800010531fb8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - security/keys/keyctl.c:_copy_to_user
  - security/keys/keyctl.c:_copy_to_user
  - security/keys/keyctl.c:_copy_from_user
  - security/keys/keyctl.c:_copy_from_user
```
```
In security/keys/request_key_auth.c (ffff8000105364b4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_read
  - security/keys/request_key_auth.c:request_key_auth_read
```
```
In security/keys/user_defined.c (ffff800010536ce0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_read
  - security/keys/user_defined.c:user_read
```
```
In security/keys/compat_dh.c (ffff8000105370e4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
```
```
In security/keys/dh.c (ffff800010538060)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - security/keys/dh.c:_copy_from_user
  - security/keys/dh.c:_copy_from_user
```
```
In security/keys/keyctl_pkey.c (ffff8000105394b8)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In security/keys/big_key.c (ffff80001053a120)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_alloc_buffer
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/keys/trusted.c (ffff80001053b554)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053d380)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:_copy_to_user
  - security/keys/encrypted-keys/encrypted.c:_copy_to_user
```
```
In security/selinux/hooks.c (ffff80001054fb30)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
```
```
In security/selinux/selinuxfs.c (ffff800010556af4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
```
```
In security/smack/smack_lsm.c (ffff80001057116c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
```
```
In security/smack/smackfs.c (ffff800010576380)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - security/smack/smackfs.c:_copy_from_user
  - security/smack/smackfs.c:_copy_from_user
```
```
In security/tomoyo/common.c (ffff80001057d28c)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In security/tomoyo/securityfs_if.c (ffff8000105868c4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
```
```
In security/apparmor/apparmorfs.c (ffff80001058aea0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:_copy_from_user
  - security/apparmor/apparmorfs.c:_copy_from_user
```
```
In security/apparmor/lsm.c (ffff80001059e690)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
```
In block/ioctl.c (ffff8000105f85b4)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In block/scsi_ioctl.c (ffff800010609468)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In block/bsg.c (ffff80001060a364)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In block/bsg-lib.c (ffff80001060b300)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_transport_complete_rq
  - block/bsg-lib.c:bsg_transport_complete_rq
```
```
In block/compat_ioctl.c (ffff80001061c778)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In block/blk-zoned.c (ffff80001061fbe0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - block/blk-zoned.c:_copy_to_user
  - block/blk-zoned.c:_copy_to_user
```
```
In block/blk-mq-debugfs.c (ffff800010623bc0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - block/blk-mq-debugfs.c:queue_state_write
```
```
In block/sed-opal.c (ffff8000106286c8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
```
```
In lib/bitmap.c (ffff80001062b76c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parse
  - lib/bitmap.c:__bitmap_parse
```
```
In lib/iov_iter.c (ffff8000106329ec)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In lib/kfifo.c (ffff8000106349d8)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In lib/usercopy.c (ffff800010637ee4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:check_zeroed_user
```
```
In lib/kstrtox.c (ffff800010639b68)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - lib/kstrtox.c:_copy_from_user
  - lib/kstrtox.c:_copy_from_user
```
```
In lib/pci_iomap.c (ffff80001063d6dc)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/pci_iomap.c:pci_iomap_wc_range
  - lib/pci_iomap.c:pci_iomap_range
  - lib/pci_iomap.c:pci_iomap_range
```
```
In lib/devres.c (ffff80001063dd60)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap
  - lib/devres.c:__devm_ioremap
  - lib/devres.c:__devm_ioremap
  - lib/devres.c:__devm_ioremap
  - lib/devres.c:__devm_ioremap
```
```
In lib/checksum.c (ffff800010662358)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - lib/checksum.c:csum_partial_copy_from_user
  - lib/checksum.c:csum_partial_copy_from_user
```
```
In lib/strncpy_from_user.c (ffff800010666b0c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:do_strncpy_from_user
  - lib/strncpy_from_user.c:do_strncpy_from_user
  - lib/strncpy_from_user.c:do_strncpy_from_user
  - lib/strncpy_from_user.c:do_strncpy_from_user
```
```
In lib/strnlen_user.c (ffff800010666dcc)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - lib/strnlen_user.c:do_strnlen_user
  - lib/strnlen_user.c:do_strnlen_user
  - lib/strnlen_user.c:do_strnlen_user
  - lib/strnlen_user.c:do_strnlen_user
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (ffff800011470c48)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
```
```
In drivers/irqchip/irq-gic.c (ffff80001066ccd4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:arm64_kernel_unmapped_at_el0
```
```
In drivers/irqchip/irq-gic-v2m.c (ffff800011471f30)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_init_one
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_init_one
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066f39c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_cpu_sys_reg_init
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
  - drivers/irqchip/irq-gic-v3.c:arm64_kernel_unmapped_at_el0
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800011473a90)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff8000114752f0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init
```
```
In drivers/irqchip/irq-sni-exiu.c (ffff80001067c118)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/irqchip/irq-sni-exiu.c:exiu_init
  - drivers/irqchip/irq-sni-exiu.c:exiu_init
```
```
In drivers/bus/arm-cci.c (ffff80001067eec0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In drivers/gpio/gpiolib.c (ffff8000106c31ac)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/pci/pci.c (ffff8000106e5a80)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:devm_pci_remap_cfgspace
  - drivers/pci/pci.c:pci_remap_iospace
  - drivers/pci/pci.c:pci_remap_iospace
  - drivers/pci/pci.c:pci_ioremap_bar
  - drivers/pci/pci.c:pci_ioremap_bar
```
```
In drivers/pci/rom.c (ffff8000106ef744)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
  - drivers/pci/rom.c:pci_map_rom
```
```
In drivers/pci/proc.c (ffff8000106f673c)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/pci/quirks.c (ffff8000106feed8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_e100_interrupt
  - drivers/pci/quirks.c:quirk_e100_interrupt
```
```
In drivers/pci/hotplug/shpchp_hpc.c (ffff800010710e58)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
```
In drivers/pci/msi.c (ffff800010714f48)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In drivers/pci/syscall.c (ffff800010718d8c)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/pci/ecam.c (ffff8000107199e0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/pci/ecam.c:pci_ecam_create
  - drivers/pci/ecam.c:pci_ecam_create
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffff80001071cd34)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff80001072ff3c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_raise_msix_irq
```
```
In drivers/video/fbdev/core/fbmem.c (ffff800010745170)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In drivers/video/fbdev/core/fbcmap.c (ffff800010748e60)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:_copy_to_user
  - drivers/video/fbdev/core/fbcmap.c:_copy_to_user
  - drivers/video/fbdev/core/fbcmap.c:_copy_from_user
  - drivers/video/fbdev/core/fbcmap.c:_copy_from_user
```
```
In drivers/video/fbdev/core/fbcon.c (ffff800010753110)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
```
```
In drivers/video/fbdev/imsttfb.c (ffff80001075a08c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:_copy_from_user
  - drivers/video/fbdev/imsttfb.c:_copy_from_user
  - drivers/video/fbdev/imsttfb.c:arm64_kernel_unmapped_at_el0
```
```
In drivers/video/fbdev/amba-clcd.c (ffff80001075c7dc)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_register
  - drivers/video/fbdev/amba-clcd.c:clcdfb_register
```
```
In drivers/video/fbdev/asiliantfb.c (ffff80001075d4d4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/efifb.c (ffff80001075e354)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:arm64_kernel_unmapped_at_el0
```
```
In drivers/video/fbdev/mx3fb.c (ffff8000107606c4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
```
```
In drivers/video/fbdev/simplefb.c (ffff800010761228)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a93a0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/acpi/apei/erst.c (ffff8000107adaac)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
  - drivers/acpi/apei/erst.c:erst_exec_move_data
```
```
In drivers/amba/bus.c (ffff8000107b96c8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
```
```
In drivers/clk/clk-qoriq.c (ffff800011483dbc)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/clk/clk-qoriq.c:clockgen_init
  - drivers/clk/clk-qoriq.c:clockgen_init
```
```
In drivers/dma/amba-pl08x.c (ffff800010802668)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080d830)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:arm64_kernel_unmapped_at_el0
```
```
In drivers/soc/fsl/qbman/bman_portal.c (ffff800010810ec0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe
```
```
In drivers/soc/fsl/qbman/qman_portal.c (ffff800010811498)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
```
```
In drivers/soc/renesas/renesas-soc.c (ffff800011490c98)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
```
```
In drivers/xen/events/events_2l.c (ffff800010833220)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
```
```
In drivers/xen/xenbus/xenbus_client.c (ffff8000108353fc)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffff80001083a888)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
```
```
In drivers/xen/xlate_mmu.c (ffff8000114923c0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
```
In drivers/reset/reset-sunxi.c (ffff800011492964)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/reset/reset-sunxi.c:sun6i_reset_init
  - drivers/reset/reset-sunxi.c:sun6i_reset_init
```
```
In drivers/tty/tty_io.c (ffff800010851e90)
Location: arch/arm64/include/asm/cpufeature.h:394
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
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_write
```
```
In drivers/tty/n_tty.c (ffff800010855c08)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/tty/tty_ioctl.c (ffff80001085b4d0)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/tty/tty_jobctrl.c (ffff800010860a28)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/tty/pty.c (ffff800010861e74)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/tty/sysrq.c (ffff800010864b88)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:write_sysrq_trigger
  - drivers/tty/sysrq.c:write_sysrq_trigger
```
```
In drivers/tty/vt/vt_ioctl.c (ffff8000108672f8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt_ioctl.c:_copy_from_user
  - drivers/tty/vt/vt_ioctl.c:_copy_from_user
```
```
In drivers/tty/vt/vc_screen.c (ffff800010867cfc)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_read
```
```
In drivers/tty/vt/selection.c (ffff80001086941c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:_copy_from_user
  - drivers/tty/vt/selection.c:_copy_from_user
```
```
In drivers/tty/vt/keyboard.c (ffff80001086eac0)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In drivers/tty/vt/consolemap.c (ffff80001087019c)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/tty/vt/vt.c (ffff8000108792d4)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In drivers/tty/serial/serial_core.c (ffff800010882bd0)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/tty/serial/earlycon.c (ffff800011493c50)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffff800010886e84)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_std_resource
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088fbb4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
  - drivers/tty/serial/8250/8250_pci.c:pci_plx9050_init
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a1824)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_request_port
  - drivers/tty/serial/msm_serial.c:msm_request_port
```
```
In drivers/char/mem.c (ffff8000108ab114)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/char/random.c (ffff8000108b10cc)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/char/virtio_console.c (ffff8000108b5c5c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In drivers/char/hw_random/core.c (ffff8000108b7930)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/char/tpm/tpm-dev-common.c (ffff8000108b8cb8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffff8000108ca3c4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
```
```
In drivers/lightnvm/core.c (ffff8000108e0024)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:_copy_from_user
  - drivers/lightnvm/core.c:_copy_from_user
```
```
In drivers/base/firmware_loader/main.c (ffff80001090cfa4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (ffff80001091aba4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
```
```
In drivers/block/loop.c (ffff800010924260)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/block/xen-blkfront.c (ffff80001092a154)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_ioctl
  - drivers/block/xen-blkfront.c:blkif_ioctl
```
```
In drivers/mfd/ab3100-core.c (ffff80001094a518)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
```
```
In drivers/mfd/aat2870-core.c (ffff80001094c738)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
```
```
In drivers/mfd/syscon.c (ffff80001094e7b0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:of_syscon_register
  - drivers/mfd/syscon.c:of_syscon_register
```
```
In drivers/nvdimm/core.c (ffff80001094ff20)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/bus.c (ffff800010951938)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:_copy_to_user
  - drivers/nvdimm/bus.c:_copy_to_user
  - drivers/nvdimm/bus.c:_copy_from_user
  - drivers/nvdimm/bus.c:_copy_from_user
```
```
In drivers/dma-buf/dma-buf.c (ffff800010966134)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
```
```
In drivers/dma-buf/sync_file.c (ffff80001096a6d0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:_copy_to_user
  - drivers/dma-buf/sync_file.c:_copy_to_user
  - drivers/dma-buf/sync_file.c:_copy_from_user
  - drivers/dma-buf/sync_file.c:_copy_from_user
```
```
In drivers/dma-buf/sw_sync.c (ffff80001096b8cc)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:_copy_from_user
  - drivers/dma-buf/sw_sync.c:_copy_from_user
```
```
In drivers/dma-buf/udmabuf.c (ffff80001096cddc)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:_copy_from_user
  - drivers/dma-buf/udmabuf.c:_copy_from_user
```
```
In drivers/scsi/scsi_ioctl.c (ffff800010970898)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/scsi/scsi_error.c (ffff800010974d3c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
```
```
In drivers/scsi/scsi_devinfo.c (ffff800010980c60)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
```
```
In drivers/scsi/scsi_proc.c (ffff800010981510)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:_copy_from_user
  - drivers/scsi/scsi_proc.c:_copy_from_user
```
```
In drivers/scsi/sg.c (ffff80001099311c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
```
```
In drivers/ata/libata-scsi.c (ffff8000109a5510)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/gpu/vga/vgaarb.c (ffff8000109c05b4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/net/tun.c (ffff8000109df8d0)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/net/ethernet/freescale/fec_ptp.c (ffff8000109ed18c)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/net/ethernet/freescale/fman/fman_muram.c (ffff8000109edcc4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_muram.c:fman_muram_init
  - drivers/net/ethernet/freescale/fman/fman_muram.c:fman_muram_init
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fc350)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable_device
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable_device
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a00c48)
Location: arch/arm64/include/asm/cpufeature.h:394
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
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/ppp/ppp_generic.c:ppp_write
```
```
In drivers/cdrom/cdrom.c (ffff800010a0d674)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:_copy_from_user
  - drivers/cdrom/cdrom.c:_copy_from_user
```
```
In drivers/usb/core/devio.c (ffff800010a3082c)
Location: arch/arm64/include/asm/cpufeature.h:394
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
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:parse_usbdevfs_streams
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
```
```
In drivers/usb/core/devices.c (ffff800010a34a40)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/usb/host/pci-quirks.c (ffff800010a50d70)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8fd40)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
```
```
In drivers/input/input-compat.c (ffff800010a9935c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/input/input-compat.c:_copy_from_user
  - drivers/input/input-compat.c:_copy_from_user
```
```
In drivers/input/mousedev.c (ffff800010a9c934)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_write
```
```
In drivers/input/evdev.c (ffff800010a9ffb0)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In drivers/input/misc/uinput.c (ffff800010aa513c)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/rtc/dev.c (ffff800010aaae6c)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/i2c/i2c-dev.c (ffff800010ab8834)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/media/cec/cec-api.c (ffff800010ac272c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:_copy_from_user
  - drivers/media/cec/cec-api.c:_copy_from_user
```
```
In drivers/pps/pps.c (ffff800010ac5ef0)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/ptp/ptp_chardev.c (ffff800010ac79a0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:_copy_to_user
  - drivers/ptp/ptp_chardev.c:_copy_to_user
  - drivers/ptp/ptp_chardev.c:_copy_from_user
  - drivers/ptp/ptp_chardev.c:_copy_from_user
```
```
In drivers/watchdog/watchdog_dev.c (ffff800010ae07b0)
Location: arch/arm64/include/asm/cpufeature.h:394
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
  - drivers/watchdog/watchdog_dev.c:watchdog_write
  - drivers/watchdog/watchdog_dev.c:watchdog_write
```
```
In drivers/md/md.c (ffff800010af35ec)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In drivers/md/dm-ioctl.c (ffff800010b09238)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In drivers/edac/altera_edac.c (ffff800010b178cc)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig2
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig
  - drivers/edac/altera_edac.c:altr_edac_a10_device_trig
  - drivers/edac/altera_edac.c:altr_edac_device_trig
  - drivers/edac/altera_edac.c:altr_edac_device_trig
  - drivers/edac/altera_edac.c:altr_sdram_probe
  - drivers/edac/altera_edac.c:altr_sdram_probe
```
```
In drivers/mmc/core/block.c (ffff800010b42194)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_ioctl_copy_from_user
  - drivers/mmc/core/block.c:mmc_blk_ioctl_copy_from_user
```
```
In drivers/firmware/efi/arm-runtime.c (ffff800010b60fd8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In drivers/firmware/efi/earlycon.c (ffff800010d9f670)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
  - drivers/firmware/efi/earlycon.c:efi_earlycon_map
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b642fc)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b655d0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
```
In drivers/clocksource/arm_arch_timer.c (ffff800010b67e8c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/clocksource/arm_arch_timer.c:arm64_kernel_unmapped_at_el0
```
```
In drivers/of/address.c (ffff800010b73e60)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_io_request_and_map
  - drivers/of/address.c:of_iomap
  - drivers/of/address.c:of_iomap
```
```
In drivers/mailbox/pl320-ipc.c (ffff800010b7acac)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/mailbox/pl320-ipc.c:pl320_probe
  - drivers/mailbox/pl320-ipc.c:pl320_probe
```
```
In drivers/remoteproc/remoteproc_debugfs.c (ffff800010b82754)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
```
```
In net/socket.c (ffff800010ba4194)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In net/core/sock.c (ffff800010baf0a4)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In net/core/scm.c (ffff800010bbe524)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In net/core/flow_dissector.c (ffff800010bc3274)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In net/core/sysctl_net_core.c (ffff800010bc5c8c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (ffff800010bdba48)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_features
  - net/core/ethtool.c:ethtool_get_features
  - net/core/ethtool.c:_copy_from_user
  - net/core/ethtool.c:_copy_from_user
```
```
In net/core/filter.c (ffff800010c030b4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
  - net/core/filter.c:sk_get_filter
  - net/core/filter.c:_copy_from_user
  - net/core/filter.c:_copy_from_user
```
```
In net/core/dev_ioctl.c (ffff800010c03f4c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In net/compat.c (ffff800010c32f0c)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In net/netlink/af_netlink.c (ffff800010c4d7e8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/bpf/test_run.c (ffff800010c52be8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/bpf/test_run.c:_copy_from_user
  - net/bpf/test_run.c:_copy_from_user
```
```
In net/ipv4/ip_options.c (ffff800010c61794)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_get_from_user
  - net/ipv4/ip_options.c:ip_options_get_from_user
```
```
In net/ipv4/ip_sockglue.c (ffff800010c6761c)
Location: arch/arm64/include/asm/cpufeature.h:394
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
```
```
In net/ipv4/tcp.c (ffff800010c6ffe4)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_repair_options_est
  - net/ipv4/tcp.c:tcp_repair_options_est
  - net/ipv4/tcp.c:tcp_ioctl
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8b6d0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
```
```
In net/ipv4/raw.c (ffff800010c972d0)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In net/ipv4/udp.c (ffff800010c9a5d0)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In net/ipv4/arp.c (ffff800010ca3050)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_ioctl
```
```
In net/ipv4/devinet.c (ffff800010ca6860)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_gifconf
  - net/ipv4/devinet.c:inet_gifconf
```
```
In net/ipv4/af_inet.c (ffff800010cabd9c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:_copy_from_user
  - net/ipv4/af_inet.c:_copy_from_user
```
```
In net/ipv4/igmp.c (ffff800010cb2888)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In net/ipv4/fib_frontend.c (ffff800010cb4090)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In net/ipv4/bpfilter/sockopt.c (ffff800010cc63b8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
```
```
In net/ipv4/ipmr.c (ffff800010ccf720)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In net/unix/af_unix.c (ffff800010cf00d8)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_ioctl
```
```
In net/ipv6/addrconf.c (ffff800010d00190)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In net/ipv6/route.c (ffff800010d16a78)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/route.c:ipv6_route_ioctl
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1c464)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:_copy_from_user
  - net/ipv6/ipv6_sockglue.c:_copy_from_user
```
```
In net/ipv6/raw.c (ffff800010d29290)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_ioctl
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/mcast.c (ffff800010d32010)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:_copy_to_user
  - net/ipv6/mcast.c:_copy_to_user
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d36d78)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3ea2c)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:_copy_from_user
  - net/ipv6/ip6_flowlabel.c:_copy_from_user
```
```
In net/ipv6/ip6mr.c (ffff800010d47a1c)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In net/packet/af_packet.c (ffff800010d5b08c)
Location: arch/arm64/include/asm/cpufeature.h:394
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
In net/wireless/wext-core.c (ffff800010d61208)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/wireless/wext-core.c:_copy_from_user
  - net/wireless/wext-core.c:_copy_from_user
```
```
In net/wireless/wext-priv.c (ffff800010d62738)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:_copy_from_user
  - net/wireless/wext-priv.c:_copy_from_user
```
```
In net/rfkill/core.c (ffff800010d6cf50)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_read
  - net/rfkill/core.c:rfkill_fop_read
```
```
In net/xdp/xsk.c (ffff800010d7fa4c)
Location: arch/arm64/include/asm/cpufeature.h:394
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
  - net/xdp/xsk.c:_copy_from_user
  - net/xdp/xsk.c:_copy_from_user
```
```
In net/xdp/xdp_umem.c (0)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
```
```
In arch/arm64/lib/uaccess_flushcache.c (ffff800010d83610)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - arch/arm64/lib/uaccess_flushcache.c:__copy_user_flushcache
  - arch/arm64/lib/uaccess_flushcache.c:__copy_user_flushcache
```
```
In lib/seq_buf.c (ffff800010d90050)
Location: arch/arm64/include/asm/cpufeature.h:394
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_to_user
  - lib/seq_buf.c:seq_buf_to_user
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
